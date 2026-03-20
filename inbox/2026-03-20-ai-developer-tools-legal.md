---
date: 2026-03-20
tags: [daily-digest, automated]
sections: ["learning_leetcode", "learning_photography", "learning_tech", "learning_youtube", "tech_ai"]
---

# Daily Digest — 2026-03-20

**今日涵蓋 Sections：**
- 🧩 LeetCode Blind 100
- 📷 Learning — Photography
- 📚 Learning — Tech
- 🎬 Learning — YouTube
- 💻 Tech & AI

---

## 🔥 今日重點 Top Highlights
*   **OpenAI 收購 Python 工具開發商 Astral**，標誌著其向開發者工具領域的積極擴張，可能影響未來 AI 輔助編程生態。 [Link](https://astral.sh/blog/openai)
*   **Anthropic 起訴 OpenCode 涉嫌違反授權**，凸顯了開源 AI 模型使用與商業許可之間的持續緊張關係。 [Link](https://github.com/anomalyco/opencode/pull/18186)
*   **Google 詳述 Android 新 24 小時側載流程**，旨在提升 Play Store 外安裝未驗證應用的安全性，開發者與進階用戶需留意新規。 [Link](https://arstechnica.com/gadgets/2026/03/google-details-new-24-hour-process-to-sideload-unverified-android-apps/)
*   **LeetCode 重點題型：Trie 結構的萬用字元搜尋**，掌握 `WordDictionary` 的設計（DFS遞迴處理 `.`）對解系統設計與搜尋題目至關重要。 [Link](https://leetcode.com/problems/design-add-and-search-words-data-structure/)
*   **攝影實用技巧：手動設定白平衡控制畫面情緒**，將 Sony A7C 的白平衡功能設為自訂鍵，可快速在溫暖（>5500K）與冷冽（<4500K）氛圍間切換。

---
今日摘要：
- 💻 Tech & AI: OpenAI 收購 Astral、Anthropic 提起訴訟、Google 公布 Android 側載新規、AI 編碼代理研究與 Meta V-JEPA 2.1 模型。
- 📚 Learning — Tech: 比較 Blue-Green 與 Canary 兩種部署策略的適用場景與注意事項。
- 📷 Learning — Photography: 學習透過手動控制色溫（Kelvin）來營造照片的溫暖或冷冽情緒。
- 🎬 Learning — YouTube: 強調影片標題與縮圖文字必須傳遞一致的核心訊息，以提升點擊率。
- 🧩 Leetcode Blind 100: 練習設計支援萬用字元搜尋的單詞資料結構（Trie + DFS）。

---

## 🧩 LeetCode Blind 100
> `2026-03-20 14:35:28`

Blind 100: 211. Design Add and Search Words Data Structure [Tries]
https://leetcode.com/problems/design-add-and-search-words-data-structure/
> 📅 **Today's Daily Challenge:** #3884 Minimum Absolute Difference in Sliding Submatrix [Medium] — Tags: Array, Sorting, Matrix — https://leetcode.com/problems/minimum-absolute-difference-in-sliding-submatrix/

**Problem Type:** Trie + DFS/Backtracking  
**Key Insight:** Use a trie to store words; for search with wildcard `.`, recursively explore all child nodes at that level.  

**Approach:**  
1. Implement a `TrieNode` with children dict and `is_end` flag.  
2. **addWord:** Traverse trie, creating nodes as needed, mark end.  
3. **search:** For normal letters, go to exact child; for `.`, recursively search all children at that level.  

**Python3 Solution:**
```python
class TrieNode:
    def __init__(self):
        self.children = {}
        self.is_end = False

class WordDictionary:
    def __init__(self):
        self.root = TrieNode()

    def addWord(self, word: str) -> None:
        node = self.root
        for ch in word:
            if ch not in node.children:
                node.children[ch] = TrieNode()
            node = node.children[ch]
        node.is_end = True

    def search(self, word: str) -> bool:
        def dfs(j, node):
            for i in range(j, len(word)):
                ch = word[i]
                if ch == '.':
                    for child in node.children.values():
                        if dfs(i + 1, child):
                            return True
                    return False
                else:
                    if ch not in node.children:
                        return False
                    node = node.children[ch]
            return node.is_end
        
        return dfs(0, self.root)
```

**Complexity:**  
- **addWord:** O(L) time, O(L) space for new nodes.  
- **search:** Without `.` → O(L); with `.` → O(N * 26^D) worst case, where D = number of `.`.  
- **Space:** O(T) total, T = total characters in all words.

**Blind 100 Note:**  
This is the **wildcard search in trie** pattern. Tests understanding of prefix trees + backtracking. Similar:  
- 208. Implement Trie  
- 212. Word Search II  
- 745. Prefix and Suffix Search

**Contest Tips:**  
- Use `defaultdict` or dict for children; list of size 26 is slower in Python.  
- Edge cases: `.` at last char, empty word (not in constraints).  
- Optimize: store word length in separate set to early reject mismatched lengths (optional).  
- Common mistake: forgetting to mark `is_end` and handle multiple `.` recursively.

---

## 📷 Learning — Photography
> `2026-03-20 17:20:17`

Today's concept: Color — Warm vs Cool Color Temperature Mood
**What it is:** Color temperature is the warmth (yellow/red) or coolness (blue) of light, measured in Kelvin. It’s a foundational tool for establishing mood in your images and videos.

**Why it matters:** Warm light feels intimate, nostalgic, or joyful; cool light evokes solitude, tension, or serenity. Controlling it directs your viewer’s emotional response.

**How to apply it:**
1.  **Set your White Balance manually.** Don’t use Auto WB for deliberate color mood.
2.  **For warmth (e.g., golden hour portraits),** set your WB to 5500K or higher, or use the "Shade" or "Cloudy" preset.
3.  **For coolness (e.g., a stark street scene),** set your WB to 4500K or lower, or use the "Fluorescent" or "Incandescent" preset.
4.  **In video,** shoot in S-Log3 or a Creative Look with your desired WB baked in for a consistent cinematic grade.

**Sony A7C tip:** Assign **White Balance** to a custom button (like the left of the D-pad) for rapid adjustment without entering menus.

**Common mistake:** Mixing color temperatures in a single scene, like warm indoor lighting with cool window light, creating a muddy conflict. Choose one dominant temperature for cohesion.

---

## 📚 Learning — Tech
> `2026-03-20 17:13:47`

Today's concept: Blue-Green vs Canary Deployments
**What it is:** Blue-green deployments maintain two identical environments (blue = current, green = new). You deploy to the idle environment and switch all traffic at once. Canary deployments route a small percentage of traffic to the new version, gradually increasing it.

**When to use it:** Use blue-green for simple, fast rollbacks (e.g., major API version change). Use canary for testing new features in production with real users (e.g., a new recommendation algorithm).

**Example:** A Kubernetes Ingress canary might route via annotation:
```yaml
nginx.ingress.kubernetes.io/canary: "true"
nginx.ingress.kubernetes.io/canary-weight: "10"
```

**Gotcha:** Blue-green requires double infrastructure cost during cutover. Canary's mistake is not having robust metrics to decide if the canary is healthy before proceeding.

---

## 🎬 Learning — YouTube
> `2026-03-20 17:25:11`

今日主題：Script — 撰寫標題與縮圖文字的一致性邏輯
**是什麼：** 標題與縮圖文字是觀眾第一眼看到的「組合廣告」。它們必須傳遞一致的訊息，共同強化一個核心看點或情緒，引導觀眾點擊。

**為什麼重要：** 不一致會混淆觀眾，大幅降低點擊意願。保持一致性，能精準篩選目標觀眾，提升影片點擊率（CTR）。

**怎麼做：**
1.  **先定核心**：用一句話總結影片最大亮點（例如：「A7C 拍 Vlog 最被低估的功能」）。
2.  **標題下錨**：將核心亮點融入標題，使用關鍵字（如：Sony A7C、旅拍秘訣）。
3.  **縮圖強化**：縮圖上的大字只提煉標題中最吸引人的「一個」關鍵詞或結果（如：「一鍵搞定調色」、「台北隱藏景點」）。
4.  **視覺呼應**：縮圖畫面必須直接展現標題所承諾的內容（如標題談「科技開箱」，縮圖就特寫產品）。
5.  **測試檢查**：完成後自問：只看標題+縮圖，我能立即知道影片在講什麼嗎？

**新手常犯的錯：** 縮圖文字重複完整標題，顯得雜亂。應避免：縮圖是「標題的摘要」，而非複製貼上。

**延伸 idea：** 「我的 Sony A7C 旅行輕量化設定：一機兩鏡的背包開箱與實拍」。標題點明設備與用途，縮圖可放背包裝備全景圖，加上「減重 3 公斤」等大字。

---

## 💻 Tech & AI
> `2026-03-20 07:50:24`

- **Astral (makers of Ruff) joins OpenAI** – The popular Python tooling company is being acquired, signaling OpenAI's expansion into developer tools. [Link](https://astral.sh/blog/openai)
- **Anthropic sues OpenCode for alleged license violation** – Legal action highlights ongoing tensions around open-source AI model use and licensing. [Link](https://github.com/anomalyco/opencode/pull/18186)
- **Google details new 24-hour sideloading process for Android** – Aims to improve security for installing unverified apps outside the Play Store. [Link](https://arstechnica.com/gadgets/2026/03/google-details-new-24-hour-process-to-sideload-unverified-android-apps/)
- **Research: Improving AI coding agents to reduce regressions** – TDAD framework uses graph-based impact analysis for test-driven agentic development. [Link](http://arxiv.org/abs/2603.17973v1)
- **V-JEPA 2.1 advances self-supervised video learning** – New model from Meta learns dense visual features for both images and videos. [Link](https://huggingface.co/papers/2603.14482)

---

## 📋 Raw Sources

### 🧩 LeetCode Blind 100

#### 🧩 Blind 100 — 211. Design Add and Search Words Data Structure [Tries]
**連結:** https://leetcode.com/problems/design-add-and-search-words-data-structure/
> 📅 **Today's Daily Challenge:** #3884 Minimum Absolute Difference in Sliding Submatrix [Medium] — Tags: Array, Sorting, Matrix — https://leetcode.com/problems/minimum-absolute-difference-in-sliding-submatrix/

**Problem Type:** Trie + DFS/Backtracking  
**Key Insight:** Use a trie to store words; for search with wildcard `.`, recursively explore all child nodes at that level.  

**Approach:**  
1. Implement a `TrieNode` with children dict and `is_end` flag.  
2. **addWord:** Traverse trie, creating nodes as needed, mark end.  
3. **search:** For normal letters, go to exact child; for `.`, recursively search all children at that level.  

**Python3 Solution:**
```python
class TrieNode:
    def __init__(self):
        self.children = {}
        self.is_end = False

class WordDictionary:
    def __init__(self):
        self.root = TrieNode()

    def addWord(self, word: str) -> None:
        node = self.root
        for ch in word:
            if ch not in node.children:
                node.children[ch] = TrieNode()
            node = node.children[ch]
        node.is_end = True

    def search(self, word: str) -> bool:
        def dfs(j, node):
            for i in range(j, len(word)):
                ch = word[i]
                if ch == '.':
                    for child in node.children.values():
                        if dfs(i + 1, child):
                            return True
                    return False
                else:
                    if ch not in node.children:
                        return False
                    node = node.children[ch]
            return node.is_end
        
        return dfs(0, self.root)
```

**Complexity:**  
- **addWord:** O(L) time, O(L) space for new nodes.  
- **search:** Without `.` → O(L); with `.` → O(N * 26^D) worst case, where D = number of `.`.  
- **Space:** O(T) total, T = total characters in all words.

**Blind 100 Note:**  
This is the **wildcard search in trie** pattern. Tests understanding of prefix trees + backtracking. Similar:  
- 208. Implement Trie  
- 212. Word Search II  
- 745. Prefix and Suffix Search

**Contest Tips:**  
- Use `defaultdict` or dict for children; list of size 26 is slower in Python.  
- Edge cases: `.` at last char, empty word (not in constraints).  
- Optimize: store word length in separate set to early reject mismatched lengths (optional).  
- Common mistake: forgetting to mark `is_end` and handle multiple `.` recursively.

---

### 📷 Learning — Photography

#### 📷 Today's Concept: Color — Warm vs Cool Color Temperature Mood

**What it is:** Color temperature is the warmth (yellow/red) or coolness (blue) of light, measured in Kelvin. It’s a foundational tool for establishing mood in your images and videos.

**Why it matters:** Warm light feels intimate, nostalgic, or joyful; cool light evokes solitude, tension, or serenity. Controlling it directs your viewer’s emotional response.

**How to apply it:**
1.  **Set your White Balance manually.** Don’t use Auto WB for deliberate color mood.
2.  **For warmth (e.g., golden hour portraits),** set your WB to 5500K or higher, or use the "Shade" or "Cloudy" preset.
3.  **For coolness (e.g., a stark street scene),** set your WB to 4500K or lower, or use the "Fluorescent" or "Incandescent" preset.
4.  **In video,** shoot in S-Log3 or a Creative Look with your desired WB baked in for a consistent cinematic grade.

**Sony A7C tip:** Assign **White Balance** to a custom button (like the left of the D-pad) for rapid adjustment without entering menus.

**Common mistake:** Mixing color temperatures in a single scene, like warm indoor lighting with cool window light, creating a muddy conflict. Choose one dominant temperature for cohesion.

---

### 📚 Learning — Tech

#### 📚 Today's Concept: Blue-Green vs Canary Deployments

**What it is:** Blue-green deployments maintain two identical environments (blue = current, green = new). You deploy to the idle environment and switch all traffic at once. Canary deployments route a small percentage of traffic to the new version, gradually increasing it.

**When to use it:** Use blue-green for simple, fast rollbacks (e.g., major API version change). Use canary for testing new features in production with real users (e.g., a new recommendation algorithm).

**Example:** A Kubernetes Ingress canary might route via annotation:
```yaml
nginx.ingress.kubernetes.io/canary: "true"
nginx.ingress.kubernetes.io/canary-weight: "10"
```

**Gotcha:** Blue-green requires double infrastructure cost during cutover. Canary's mistake is not having robust metrics to decide if the canary is healthy before proceeding.

---

### 🎬 Learning — YouTube

#### 🎬 今日主題：Script — 撰寫標題與縮圖文字的一致性邏輯
**類別：** 腳本

**是什麼：** 標題與縮圖文字是觀眾第一眼看到的「組合廣告」。它們必須傳遞一致的訊息，共同強化一個核心看點或情緒，引導觀眾點擊。

**為什麼重要：** 不一致會混淆觀眾，大幅降低點擊意願。保持一致性，能精準篩選目標觀眾，提升影片點擊率（CTR）。

**怎麼做：**
1.  **先定核心**：用一句話總結影片最大亮點（例如：「A7C 拍 Vlog 最被低估的功能」）。
2.  **標題下錨**：將核心亮點融入標題，使用關鍵字（如：Sony A7C、旅拍秘訣）。
3.  **縮圖強化**：縮圖上的大字只提煉標題中最吸引人的「一個」關鍵詞或結果（如：「一鍵搞定調色」、「台北隱藏景點」）。
4.  **視覺呼應**：縮圖畫面必須直接展現標題所承諾的內容（如標題談「科技開箱」，縮圖就特寫產品）。
5.  **測試檢查**：完成後自問：只看標題+縮圖，我能立即知道影片在講什麼嗎？

**新手常犯的錯：** 縮圖文字重複完整標題，顯得雜亂。應避免：縮圖是「標題的摘要」，而非複製貼上。

**延伸 idea：** 「我的 Sony A7C 旅行輕量化設定：一機兩鏡的背包開箱與實拍」。標題點明設備與用途，縮圖可放背包裝備全景圖，加上「減重 3 公斤」等大字。

---

### 💻 Tech & AI

#### Hacker News
- [Astral to Join OpenAI](https://astral.sh/blog/openai) ⭐1173
- [Google details new 24-hour process to sideload unverified Android apps](https://arstechnica.com/gadgets/2026/03/google-details-new-24-hour-process-to-sideload-unverified-android-apps/) ⭐416
- [EsoLang-Bench: Evaluating Genuine Reasoning in LLMs via Esoteric Languages](https://esolang-bench.vercel.app/) ⭐49
- [Be intentional about how AI changes your codebase](https://aicode.swerdlow.dev) ⭐45
- [NanoGPT Slowrun: 10x Data Efficiency with Infinite Compute](https://qlabs.sh/10x) ⭐83
- [Launch HN: Voltair (YC W26) – Drone and charging network for power utilities](https://news.ycombinator.com/item?id=47442452) ⭐44
- [Scaling Karpathy's Autoresearch: What Happens When the Agent Gets a GPU Cluster](https://blog.skypilot.co/scaling-autoresearch/) ⭐110
- [Tesla: Failure of the FSD's degradation detection system [pdf]](https://static.nhtsa.gov/odi/inv/2026/INOA-EA26002-10023.pdf) ⭐146
- [The Need for an Independent AI Grid](https://amppublic.com/) ⭐12
- [Anthropic takes legal action against OpenCode](https://github.com/anomalyco/opencode/pull/18186) ⭐352

#### HuggingFace
- [From Prior to Pro: Efficient Skill Mastery via Distribution Contractive RL Finetuning](https://huggingface.co/papers/2603.10263)
- [V-JEPA 2.1: Unlocking Dense Features in Video Self-Supervised Learning](https://huggingface.co/papers/2603.14482)
- [Expert Threshold Routing for Autoregressive Language Modeling with Dynamic Computation Allocation and Load Balancing](https://huggingface.co/papers/2603.11535)
- [Coherent Human-Scene Reconstruction from Multi-Person Multi-View Video in a Single Pass](https://huggingface.co/papers/2603.12789)
- [Fanar-Sadiq: A Multi-Agent Architecture for Grounded Islamic QA](https://huggingface.co/papers/2603.08501)
- [HeBA: Heterogeneous Bottleneck Adapters for Robust Vision-Language Models](https://huggingface.co/papers/2603.16653)

#### ArXiv
- [Unified Spatio-Temporal Token Scoring for Efficient Video VLMs](http://arxiv.org/abs/2603.18004v1)
- [Loc3R-VLM: Language-based Localization and 3D Reasoning with Vision-Language Models](http://arxiv.org/abs/2603.18002v1)
- [AgentFactory: A Self-Evolving Framework Through Executable Subagent Accumulation and Reuse](http://arxiv.org/abs/2603.18000v1)
- [LoST: Level of Semantics Tokenization for 3D Shapes](http://arxiv.org/abs/2603.17995v1)
- [Toward Scalable Automated Repository-Level Datasets for Software Vulnerability Detection](http://arxiv.org/abs/2603.17974v1)
- [TDAD: Test-Driven Agentic Development - Reducing Code Regressions in AI Coding Agents via Graph-Based Impact Analysis](http://arxiv.org/abs/2603.17973v1)
