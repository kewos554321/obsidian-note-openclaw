---
date: 2026-07-20
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-07-20

**今日涵蓋 Sections：**
- 💻 Tech & AI
- 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
- 🔵 Google 動態
- 📈 Markets Overview
- 🏠 台灣房市
- 📊 Watchlist
- 🌍 World News
- 📷 Camera Deals
- 🤿 Dive Gear Deals
- ✈️ Flight Tips
- 📚 Learning — Finance
- 🧩 LeetCode Blind 100
- 📷 Learning — Photography
- 📚 Learning — Tech
- 🎬 Learning — YouTube

---

Here is your daily briefing for today.

## 🔥 今日重點 Top Highlights

1.  **GPT-5.6 用提示解決了30年未解的凸優化難題** — 這不僅是程式碼生成，而是AI達到研究級推理能力的里程碑。 [Link](https://old.reddit.com/r/math/comments/1uxj3cy/after_openais_cdc_proof_announcement_gpt56_used_a/)
2.  **Claude Code 改用 Rust 寫的 Bun** — 從 Node.js 遷移，架構大改，對所有開發AI輔助工具的工程師來說是重要信號。 [Link](https://simonwillison.net/2026/Jul/19/claude-code-in-bun-in-rust/)
3.  **全球市場風險急升：日經暴跌4%，S&P 500 跌1.5%** — 台股加權指數持平，但外部壓力巨大，需留意資金流向。 (See Markets section)
4.  **AI 建議讓人「準確度降3倍，但信心增2倍」** — 關鍵UX發現：設計AI工具時，必須鼓勵驗證，而非盲目信任。 [Link](https://thenextweb.com/news/ai-advice-suppresses-critical-thinking-wrong-answers-study)
5.  **Google 推出 LiteRT.js：瀏覽器內高效能 AI 推理** — 對開發客戶端AI功能、追求低延遲的工程師是重大更新。 [Link](https://developers.googleblog.com/litertjs-googles-high-performance-web-ai-inference/)

---

- 💻 **Tech:** Claude Code 改用 Rust 寫的 Bun；GPT-5.6 解決數學難題；OpenAI Codex 上下文砍10萬 tokens；ESP32 廣告阻擋器只用50KB RAM；AI建議降低批判性思維。
- 🤖 **AI 公司動態:** 今日重點在 Tesla 7/22 財報與自駕進展，OpenAI/Anthropic 無重大更新。
- 🔵 **Google 動態:** Gemini API 代理功能擴展、LiteRT.js 瀏覽器推理、Conductor 支援 Antigravity、Qwen 3.5-397B MoE 在 TPUv7 上加速4.7倍。
- 📈 **Markets:** 全球風險趨避，日經暴跌4%，S&P 500 跌1.5%，台股持平。
- 🏠 **台灣房市:** 高總價去化放緩，中低總價剛需撐盤；建議鎖定捷運末端或新興重劃區。
- 📊 **Watchlist:** AI 硬體股全面重挫，SMCI 跌10%、AVGO 跌6%，NVDA/GOOGL 跌逾2%。
- 🌍 **World News:** 美軍在伊拉克遭伊朗攻擊陣亡；Tate兄弟在美被捕，英國要求引渡；俄羅斯對烏克蘭發動大規模飛彈攻擊；歐盟新邊境系統將使護照檢查時間倍增；蓋亞那渡輪沉沒，數十人失蹤。
- 📷 **Camera Deals:** 7月父親節前哨戰與暑假學生方案開跑，Sony A7C II 或 Fujifilm X-T5 可等7月底價格調整。
- 🤿 **Dive Gear Deals:** 7月台灣潛水旺季，店家出清3mm防寒衣與面鏡組；去年款調節器與BCD可望有20-30% off。
- ✈️ **Flight Tips:** 7月日本/歐洲/美國皆為旺季，票價高；泰國雨季有便宜機票；澳洲冬季為淡季，可留意 Jetstar 週五特價。
- 📚 **Learning — Finance:** 營收 vs. 淨利潤：營收成長但淨利潤停滯，是成本失控的危險信號。
- 🧩 **LeetCode Blind 100:** 49. Group Anagrams — 核心模式：用排序後的字串作為 hashmap 鍵值。
- 📷 **Learning — Photography:** Sony A7C IBIS 防手震技巧：手持快門可放慢至1/15s，錄影用 Active 模式，廣角鏡頭效果最佳。
- 📚 **Learning — Tech:** Token Bucket vs. Leaky Bucket 演算法：前者允許突發流量，後者平滑輸出。
- 🎬 **Learning — YouTube:** 攝影Vlog要避免幻燈片

---

## 💻 Tech

### 💻 Tech & AI
> `2026-07-20 09:02:51`

#### Hacker News
- [AI advice made people 3x less accurate but 2x confident, researchers found](https://thenextweb.com/news/ai-advice-suppresses-critical-thinking-wrong-answers-study) ⭐262
- [Talk: The Art of Braiding Algorithms](https://pgadey.ca/notes/talk-relatorium-2026/) ⭐20
- [Claude Code uses Bun written in Rust now](https://simonwillison.net/2026/Jul/19/claude-code-in-bun-in-rust/) ⭐382
- [Ask HN: What are your favorite blogs not about AI?](https://news.ycombinator.com/item?id=48972858) ⭐29
- [OpenAI reduces Codex Model Context Size from 372k to 272k](https://github.com/openai/codex/pull/33972/files) ⭐304
- [Moonshot AI suspends new subscriptions due to Kimi K3 demand](https://twitter.com/kimi_moonshot/status/2078855608565207130) ⭐213
- [Compiled List of over $1000 in AI/GPU/LLM Credits (100% Free)](https://sairc.vercel.app/resources) ⭐3
- [Clever hacker fits 537,000 domains in a $5 ESP32 ad-blocking dongle](https://www.tomshardware.com/networking/clever-hacker-fits-537-000-domains-in-a-tiny-usd5-esp32-ad-blocking-dongle-firmware-uses-only-around-50kb-of-ram-and-can-answer-blocked-lookups-in-10-milliseconds) ⭐74
- [Heavy TV watching associated with smaller brain structures, study finds](https://dornsife.usc.edu/news/stories/heavy-tv-watching-associated-with-smaller-brain-structures/) ⭐88
- [GPT-5.6 used a prompt to close a 30-year gap in convex optimization](https://old.reddit.com/r/math/comments/1uxj3cy/after_openais_cdc_proof_announcement_gpt56_used_a/) ⭐584

#### HuggingFace
- [On Locality and Length Generalization in Visual Reasoning](https://huggingface.co/papers/2607.09061)
- [Rethinking the Evaluation of Harness Evolution for Agents](https://huggingface.co/papers/2607.12227)
- [Chat2Scenic: An Iterative RAG-Based Framework for Scenario Generation in Autonomous Driving](https://huggingface.co/papers/2607.14387)
- [Hierarchical Denoising For Multi-Step Visual Reasoning](https://huggingface.co/papers/2607.15278)
- [RxBrain: Embodied Cognition Foundation Model with Joint Language-Visual Reasoning and Imagination](https://huggingface.co/papers/2607.14187)
- [Token Time Continuous Diffusion for Language Modeling](https://huggingface.co/papers/2607.14106)

#### ArXiv
- [Partition, Prompt, Aggregate: Statistical Self-Consistency in Language Models](http://arxiv.org/abs/2607.15277v1)
- [RoboTTT: Context Scaling for Robot Policies](http://arxiv.org/abs/2607.15275v1)
- [MeanFlowNFT: Bringing Forward-Process RL to Average-Velocity Generators](http://arxiv.org/abs/2607.15273v1)
- [SciDiagramEdit: Learning to Edit Scientific Diagrams from Paper Revisions](http://arxiv.org/abs/2607.15272v1)
- [Online Neural Space Time Memory for Dynamic Novel View Synthesis](http://arxiv.org/abs/2607.15271v1)
- [Pretraining Data Can Be Poisoned through Computational Propaganda](http://arxiv.org/abs/2607.15267v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-07-20 09:03:02`

#### Tesla
- [Dow Jones Futures: Oil Prices Rise As U.S.-Iran Attacks Escalate; Google, Tesla Ahead](https://finance.yahoo.com/m/6c8dacfc-1037-32fc-a343-353600ff0076/dow-jones-futures%3A-oil-prices.html)
- [Tesla, Alphabet, Intel, GM: Earnings to watch this week](https://finance.yahoo.com/video/tesla-alphabet-intel-gm-earnings-000000527.html)
- [Mercedes Benz (XTRA:MBG) Unveils CLA 250 Plus To Take On Tesla Model 3](https://finance.yahoo.com/markets/stocks/articles/mercedes-benz-xtra-mbg-unveils-210728470.html)
- [Elon Musk's Tesla Remains One of the Last Great Founder-Led Tech Giants. Is the Stock a Buy Before July 22?](https://finance.yahoo.com/m/52e16a02-d182-306f-85d6-48a8b10b122f/elon-musk%27s-tesla-remains-one.html)

### 🔵 Google 動態
> `2026-07-20 09:02:57`

#### Google AI Blog
- [Connect more of your apps to Search](https://blog.google/products-and-platforms/products/search/connected-apps/)
- [Create, edit and star in videos with two Google Vids updates](https://blog.google/products-and-platforms/products/workspace/gemini-omni-personal-avatars/)
- [Celebrating 25 years of visual search innovation](https://blog.google/products-and-platforms/products/search/google-images-25th-anniversary/)
- [Expanding Managed Agents in Gemini API:  background tasks, remote MCP and more](https://blog.google/innovation-and-ai/technology/developers-tools/expanding-managed-agents-gemini-api/)
- [The latest AI news we announced in June 2026](https://blog.google/innovation-and-ai/technology/ai/google-ai-updates-june-2026/)
#### Google Blog
- [Designing emoji for the way we communicate today](https://blog.google/products-and-platforms/platforms/android/world-emoji-day-noto-3d/)
- [Experience the legacy of Estadio Azteca on Google Earth.](https://blog.google/products-and-platforms/products/earth/estadio-azteca/)
- [Beach vibes and temporary wallpaper are trending for back-to-school season.](https://blog.google/products-and-platforms/products/shopping/back-to-school-trends/)
- [6 back-to-school shopping tricks every student should know](https://blog.google/products-and-platforms/products/shopping/6-back-to-school-shopping-tricks-every-student-should-know/)
- [Reimagining higher education with the Waterloo Futures Lab](https://blog.google/products-and-platforms/products/education/university-of-waterloo-futures-lab/)
#### Google Developers
- [Evolving Spec-Driven Development: Conductor Now Supports Antigravity](https://developers.googleblog.com/evolving-spec-driven-development-conductor-now-supports-antigravity/)
- [Expanding Choice in Gemini Enterprise Agent Platform: Introducing Grounding with Parallel Web Search](https://developers.googleblog.com/expanding-choice-in-gemini-enterprise-agent-platform-introducing-grounding-with-parallel-web-search/)
- [Building scalable AI agents with modular prompt transpilation](https://developers.googleblog.com/building-scalable-ai-agents-with-modular-prompt-transpilation/)
- [Systems Engineering Playbook: Optimizing Qwen 3.5-397B MoE on Ironwood (TPU7x)](https://developers.googleblog.com/systems-engineering-playbook-optimizing-qwen-35-397b-moe-on-ironwood-tpu7x/)
- [LiteRT.js, Google's high performance Web AI Inference](https://developers.googleblog.com/litertjs-googles-high-performance-web-ai-inference/)

## 📈 Finance

### 📈 Markets Overview
> `2026-07-20 09:03:06`

#### Indices
- S&P 500: 7,457.69 ▼1.51%
- 台股加權: 42,671.27 ▲0.00%
- 日經 225: 64,141.12 ▼4.03%

### 🏠 台灣房市
> `2026-07-20 09:04:09`

#### AI 分析
#### 台灣房市分析 (截至 2026-07-20)

1. **整體趨勢**：市場呈現「高總價去化放緩，中低總價剛需撐盤」格局。高總價豪宅交易零星，但單價仍維持高檔；一般住宅則受惠於自住需求與通膨預期，價格持穩，惟成交量因貸款緊縮與觀望氛圍略有收縮。

2. **值得注意的地區與物件**：高總價成交集中於**台北市精華區**（大安、信義等），華廈與大樓單價達每坪50-120萬新台幣，顯示頂級地段抗跌性強。**新北、桃園**則以總價2000-4000萬的換屋型產品較為活躍，具備捷運或重劃區題材的物件去化較快。

3. **對自住者建議**：可優先鎖定**捷運末端或新興重劃區**（如新北塭仔圳、桃園青埔周邊），避開高總價物件；利用當前買方議價空間略增的時機，多看多比較，並注意銀行貸款成數與利率變動。

4. **對投資者建議**：短期避開豪宅與高總價產品（流動性風險高），可關注**低總價小宅**（20-30坪）或**具都更潛力的老華廈**，租金報酬率穩定且轉手較易。長期則留意央行利率政策與《平均地權條例》修法後續影響。

5. **風險提示**：2026年下半年需關注**美國大選後全球資金流向**及**台灣央行是否進一步緊縮信用**，若升息或選擇性信用管制加嚴，可能壓抑房價漲勢，建議保留充足現金流。

#### 591 最新


#### 實價登錄 (115S2) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 華廈(10層含以下有電梯) | 342.6㎡ | 17800萬 | 519496元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 675.5㎡ | 17000萬 | 279512元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 294.7㎡ | 10848萬 | 368078元/㎡ |
|  | 其他 | 0.0㎡ | 9369萬 | 36623元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 261.6㎡ | 8350萬 | 357414元/㎡ |

### 📊 Watchlist
> `2026-07-20 09:03:36`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 202.81 ▼2.21% |
| Market Cap | $4.91T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.1% / 64.0% / 63.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 25.20 |
| Beta | 2.21 |
| 52-Week | 164.07 – 236.54 |
| Div. Yield | — |

**Recent News:**
- [Should You Buy $1,000 Worth of SpaceX Stock Before Its First Earnings Report?](https://finance.yahoo.com/m/7af3c13f-fb92-3e49-8233-0ce2705ab1fb/should-you-buy-%241%2C000-worth.html) — Motley Fool
- [Memory Chips Just Fell Into a Bear Market. Micron Is Down 30% From Its High Even as AI Demand Booms.](https://finance.yahoo.com/m/6bb6bfe1-e5d4-3a0e-a30c-a44469963179/memory-chips-just-fell-into-a.html) — Motley Fool
- [Oil Pulls the Market Lower Again](https://finance.yahoo.com/m/b1fae642-1a0a-358f-85d4-70ef23ae17df/oil-pulls-the-market-lower.html) — Motley Fool

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 495.76 ▼1.03% |
| Market Cap | $808.39B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 50.3% / 11.7% / 13.4% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 12.54 |
| Beta | 2.47 |
| 52-Week | 149.22 – 584.73 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures: Oil Prices Rise As U.S.-Iran Attacks Escalate; Google, Tesla Ahead](https://finance.yahoo.com/m/6c8dacfc-1037-32fc-a343-353600ff0076/dow-jones-futures%3A-oil-prices.html) — Investor's Business Daily
- [Advanced Micro Devices vs. Navitas Semiconductor: Here's What The Quarterly Revenue Trends of These Artificial Intelligence Companies Reveal to Investors](https://finance.yahoo.com/m/60b935d7-5b73-3b07-9307-573d07c976c2/advanced-micro-devices-vs..html) — Motley Fool
- [Prediction: Investors Will Be Happy if They Buy AMD Stock Before the Company's Big AI Event on July 22](https://finance.yahoo.com/m/c6c04209-84a9-3a07-9dcf-3d46a21b8018/prediction%3A-investors-will-be.html) — Motley Fool

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 393.82 ▼1.82% |
| Market Cap | $2.93T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 68.3% / 46.8% / 39.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 7.06 |
| Beta | 1.13 |
| 52-Week | 349.20 – 555.45 |
| Div. Yield | — |

**Recent News:**
- [Elon Musk's Tesla Remains One of the Last Great Founder-Led Tech Giants. Is the Stock a Buy Before July 22?](https://finance.yahoo.com/m/52e16a02-d182-306f-85d6-48a8b10b122f/elon-musk%27s-tesla-remains-one.html) — Motley Fool
- [Apple Just Hit an All-Time High. HSBC Thinks It Can Climb Even Higher](https://finance.yahoo.com/m/ecadc5d0-0f0f-3aff-8b18-1ffdfeaf333d/apple-just-hit-an-all-time.html) — 24/7 Wall St.
- [I Can’t Stop Buying Alphabet Because The AI Talent Narrative is Wrong](https://finance.yahoo.com/m/f2c4d76e-3fef-3800-83da-1205825e90b6/i-can%E2%80%99t-stop-buying-alphabet.html) — 24/7 Wall St.

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 346.77 ▼2.17% |
| Market Cap | $4.19T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.4% / 32.7% / 37.9% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 8.76 |
| Beta | 1.25 |
| 52-Week | 186.15 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures: Oil Prices Rise As U.S.-Iran Attacks Escalate; Google, Tesla Ahead](https://finance.yahoo.com/m/6c8dacfc-1037-32fc-a343-353600ff0076/dow-jones-futures%3A-oil-prices.html) — Investor's Business Daily
- [Tesla, Alphabet, Intel, GM: Earnings to watch this week](https://finance.yahoo.com/video/tesla-alphabet-intel-gm-earnings-000000527.html) — Yahoo Finance Video
- [Alphabet's Gemini 3.5 Pro Is Late and the Stock Is Slipping. Is the AI Leader Falling Behind?](https://finance.yahoo.com/m/fa0cb4e7-4b8e-33ae-a630-0fb44d699941/alphabet%27s-gemini-3.5-pro-is.html) — Motley Fool

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 247.23 ▼1.06% |
| Market Cap | $2.66T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 50.6% / 11.5% / 12.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.01 |
| Beta | 1.46 |
| 52-Week | 196.00 – 278.56 |
| Div. Yield | — |

**Recent News:**
- [Anthropic's Potential $1.2 Trillion IPO Could Make This Stock a Major Beneficiary](https://finance.yahoo.com/m/0d7c886f-5c91-3fb8-ac8b-9c8a7d9fcc4f/anthropic%27s-potential-%241.2.html) — Motley Fool
- [AI Expectations Hit a Fever Pitch](https://finance.yahoo.com/m/8a07556a-36e5-3032-8a50-d25413edded4/ai-expectations-hit-a-fever.html) — Motley Fool
- [Amazon closes another major facility, nearly 500 workers affected](https://finance.yahoo.com/m/442b4aa4-2362-34c8-8067-c3c4e5e99138/amazon-closes-another-major.html) — TheStreet

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 646.01 ▼2.79% |
| Market Cap | $1.64T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.9% / 41.2% / 32.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.72 |
| Beta | 1.25 |
| 52-Week | 520.26 – 796.25 |
| Div. Yield | — |

**Recent News:**
- [Meta Makes Big Moves Around AI Models and Chip Production](https://finance.yahoo.com/m/003bf77e-ee1e-392e-a9b1-c950a14978ee/meta-makes-big-moves-around.html) — Motley Fool
- [I Can’t Stop Buying Alphabet Because The AI Talent Narrative is Wrong](https://finance.yahoo.com/m/f2c4d76e-3fef-3800-83da-1205825e90b6/i-can%E2%80%99t-stop-buying-alphabet.html) — 24/7 Wall St.
- [Can Nebius Group Really 10X by 2030? The Math Says Yes](https://finance.yahoo.com/m/ffcfecff-4171-3bcb-9704-b93e2677d563/can-nebius-group-really-10x.html) — 24/7 Wall St.

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 370.82 ▼5.95% |
| Market Cap | N/A |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | N/A / N/A / N/A |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | N/A |
| Beta | N/A |
| 52-Week | N/A – N/A |
| Div. Yield | — |

**Recent News:**
- [Broadcom (AVGO) Lands Standard Chartered Deal To Power Banking Cloud In 54 Markets](https://finance.yahoo.com/markets/stocks/articles/broadcom-avgo-lands-standard-chartered-231157865.html) — Simply Wall St.
- [Wall Street Is Warming to Marvell After Its XConn Acquisition. Here’s The Price Target](https://finance.yahoo.com/m/b261266c-cb7d-3ee5-87bc-4ccdffcbcdb8/wall-street-is-warming-to.html) — 24/7 Wall St.
- [Why the SOXS Semiconductor Bear ETF Is Surging as Chip Stocks Sell Off](https://finance.yahoo.com/m/f8d2dc1a-707a-32bf-b89c-79894d79944d/why-the-soxs-semiconductor.html) — 24/7 Wall St.

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 267.19 ▼3.54% |
| Market Cap | N/A |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | N/A / N/A / N/A |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | N/A |
| Beta | N/A |
| 52-Week | N/A – N/A |
| Div. Yield | — |

**Recent News:**
- [AMD vs. Arm vs. Intel: The Best Stock to Play the Rise of Agentic AI](https://finance.yahoo.com/m/5e096224-90e7-3066-bad8-2391664983af/amd-vs.-arm-vs.-intel%3A-the.html) — Motley Fool
- [Nvidia and AMD Hit by AI Selloff](https://finance.yahoo.com/technology/ai/articles/nvidia-amd-hit-ai-selloff-200109203.html) — GuruFocus.com
- [Arm Holdings chief says AI boom is being hampered by supply constraints](https://finance.yahoo.com/m/286b9f82-e822-3366-a3cb-e1121e5ee4ea/arm-holdings-chief-says-ai.html) — Proactive

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 132.38 ▼1.53% |
| Market Cap | $303.95B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.1% / 38.1% / 43.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 37.50 |
| Beta | 1.56 |
| 52-Week | 106.37 – 207.52 |
| Div. Yield | — |

**Recent News:**
- [If You'd Put $10,000 in Palantir at Its IPO, Here's What You'd Have Now -- Even After a 37% Drop](https://finance.yahoo.com/m/fb52cb4f-e38a-3cd5-a97c-942ed93409cd/if-you%27d-put-%2410%2C000-in.html) — Motley Fool
- [Mira Murati Unveils Open-Weight AI Model as Alex Karp, Satya Nadella Warn Companies Are Giving Away Their IP](https://finance.yahoo.com/m/c114d997-4457-3f81-95c8-636423d9045c/mira-murati-unveils.html) — Benzinga
- [Earnings From Taiwan Semiconductor and ASML Show Soaring Demand, So Why Are AI Stocks Falling? (And Here's What Investors Should Do Next.)](https://finance.yahoo.com/m/33ebac4d-7800-30ab-8d6e-feeaa5d9828e/earnings-from-taiwan.html) — Motley Fool

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 24.18 ▼10.08% |
| Market Cap | N/A |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | N/A / N/A / N/A |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | N/A |
| Beta | N/A |
| 52-Week | N/A – N/A |
| Div. Yield | — |

**Recent News:**
- [Micron, Nvidia, Netflix, SK Hynix, Alphabet, Intuitive Surgical, and More Stocks That Explain Today’s Market](https://finance.yahoo.com/m/7fa796ea-0940-3e76-942a-7ce5e7ba25b7/micron%2C-nvidia%2C-netflix%2C-sk.html) — Barrons.com
- [Can Super Micro Computer's RDHx Expansion Fuel AI Data Center Demand?](https://finance.yahoo.com/technology/ai/articles/super-micro-computers-rdhx-expansion-133800077.html) — Zacks
- [Is Super Micro Computer (SMCI) Fairly Valued On AI Cooling Expansion And Legal Risk?](https://finance.yahoo.com/markets/stocks/articles/super-micro-computer-smci-fairly-131557483.html) — Simply Wall St.

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 380.84 ▼2.61% |
| Market Cap | $1.43T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.1% / 5.0% / 4.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 14.64 |
| Beta | 1.80 |
| 52-Week | 297.82 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures: Oil Prices Rise As U.S.-Iran Attacks Escalate; Google, Tesla Ahead](https://finance.yahoo.com/m/6c8dacfc-1037-32fc-a343-353600ff0076/dow-jones-futures%3A-oil-prices.html) — Investor's Business Daily
- [Tesla, Alphabet, Intel, GM: Earnings to watch this week](https://finance.yahoo.com/video/tesla-alphabet-intel-gm-earnings-000000527.html) — Yahoo Finance Video
- [Mercedes Benz (XTRA:MBG) Unveils CLA 250 Plus To Take On Tesla Model 3](https://finance.yahoo.com/markets/stocks/articles/mercedes-benz-xtra-mbg-unveils-210728470.html) — Simply Wall St.

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 683.17 ▼1.53% |
| Market Cap | N/A |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | N/A / N/A / N/A |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | N/A |
| Beta | N/A |
| 52-Week | N/A – N/A |
| Div. Yield | — |

**Recent News:**
- [DIA’s 10-Year Shortfall: How a 186.7% Return Masks a $128K Hidden Cost](https://finance.yahoo.com/m/e2bdcc35-6fbb-3853-81f9-214340651c3d/dia%E2%80%99s-10-year-shortfall%3A-how.html) — 24/7 Wall St.
- [Go Big or Go Bigger: Is the Vanguard Mega Cap Growth ETF or S&P 500 Growth ETF the Better Buy?](https://finance.yahoo.com/m/4509de58-531d-380a-9003-d685d045cc9a/go-big-or-go-bigger%3A-is-the.html) — Motley Fool
- [This "Hands-Off" ETF Could Be Your Ticket to Becoming a Millionaire](https://finance.yahoo.com/m/5323ca7d-30cf-39ec-9556-4392a5d8e1b9/this-%22hands-off%22-etf-could-be.html) — Motley Fool

## 🌍 News

### 🌍 World News
> `2026-07-20 09:04:13`

- [US soldier killed and one injured after Iranian attack in Iraq](https://www.bbc.co.uk/news/articles/cgk417jp83po?at_medium=RSS&at_campaign=rss)
- [Tate brothers arrested in US as further UK charges take total to 59](https://www.bbc.co.uk/news/articles/cwymly9yd33o?at_medium=RSS&at_campaign=rss)
- [Russia launches major ballistic missile attack on Ukrainian cities](https://www.bbc.co.uk/news/articles/c2el7xpnzrpo?at_medium=RSS&at_campaign=rss)
- [New EU border system tripling time at passport control, airport boss says](https://www.bbc.co.uk/news/articles/ckg5gg6n9x3o?at_medium=RSS&at_campaign=rss)
- [The 1975's Matty Healy marries model Gabbriette Bechtel in Los Angeles](https://www.bbc.co.uk/news/articles/c5ywxp2d826o?at_medium=RSS&at_campaign=rss)
- [Ferry carrying 133 passengers and crew sinks off Guyana coast](https://www.bbc.co.uk/news/articles/cm2gm99nrm7o?at_medium=RSS&at_campaign=rss)
- [Health officials identify source of US explosive diarrhoea outbreak](https://www.bbc.co.uk/news/articles/c4gw9n1kx9do?at_medium=RSS&at_campaign=rss)
- [Neighbours actor Terence Donovan dies aged 90](https://www.bbc.co.uk/news/articles/crmrznw82j4o?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-07-20 09:04:29`

#### AI Tips
Here’s your tailored photography expert advice for **July 20, 2026** in Taiwan.

---

## 【購買優惠】

#### Best places to buy camera gear in Taiwan (July 2026)

| Channel | Best for | Notes |
|---------|----------|-------|
| **PChome 24h** | New gear, fast delivery | Often has **銀行加碼回饋** (bank rebates) on Wednesdays. Check for **限時特賣** on Sony, Canon, Nikon. |
| **momo購物網** | Bundles (kit + memory card + bag) | July has **超級品牌日** for Fujifilm and DJI. Use **momo幣** for extra discount. |
| **光華商場 (Guanghua Digital Plaza)** | Bargaining, used gear, accessories | Go on a weekday afternoon. **Negotiate** on cash deals. Avoid weekends (crowded). |
| **日本代購 (Japan proxy)** | High-end lenses, rare bodies | Yen is weak in 2026. Use **Buyee** or **ZenMarket**. Add 8-10% for shipping + customs. |
| **二手 (Used)** | Budget bodies, vintage lenses | Check **DCView二手市場** or **蝦皮拍賣**. Meet in person at 光華 or 捷運站. |

#### Seasonal sale tips for July

- **7月父親節前哨戰** – Many retailers start Father’s Day promos in late July. Look for **gimbal + camera bundles** (popular for dads).
- **暑假學生方案** – Canon and Sony often have **student discounts** (show student ID). Check **校園專案** on official sites.
- **颱風季清倉** – If a typhoon hits, outdoor gear (waterproof housings, tripods) may go on sale. Watch PChome’s **颱風特賣**.
- **銀行信用卡回饋** – July often has **3%–5% cashback** on 玉山, 台新, 國泰世華 for electronics. Stack with platform coupons.

> **Pro tip:** If you want a **Sony A7C II** or **Fujifilm X-T5**, wait until **late July** – rumors say a price drop before August’s new

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-07-20 09:04:35`

#### AI Tips
Here’s a practical, actionable guide tailored for Taiwan divers in **July 2026**.

---

#### 【購買優惠】Best Places & July Seasonal Tips

**1. Best places to buy in Taiwan (July 2026)**
- **Online (Shopee / 蝦皮商城):** Look for shops with “商城” badge (e.g., **潛水兵工廠**, **海人選品**, **極光潛水**). July often has mid-summer “7.7” or “7.15” shopping festivals with coupons + free shipping.
- **Physical stores (台北/台中/高雄):**  
  - **台北:** 內湖「潛水者之家」, 八德路「東潛」  
  - **台中:** 西屯「海島潛水」  
  - **高雄:** 前鎮「潛水易購」  
  *Tip: Visit on weekdays for better negotiation, especially for fins or BCDs.*
- **Facebook 社團:**  
  - **「台灣潛水裝備二手交流」** (great for used regulators/BCD, but test before buying)  
  - **「潛水裝備新品團購」** (July often has group buys for summer stock clearance)

**2. July seasonal sale tips & diving notes**
- **July = 台灣潛水旺季** (water temp 27–29°C, visibility best in 東北角/小琉球).  
  - **Sale trend:** Many shops clear out **wetsuits (3mm shorty)** and **mask/snorkel sets** to make room for fall gear.  
  - **Watch for:** “夏季出清” (summer clearance) on **regulators** and **BCD** – last year’s model often 20–30% off.  
- **Asia note:** July is **typhoon season** in Taiwan.

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-07-20 09:04:22`

#### AI Flight Tips — July
Here are your actionable flight deal tips from Taiwan for July 2026:

**Japan (Tokyo/Osaka/Sapporo)**  
July is **peak summer** (school holidays + Obon in mid-August), so prices are high. Book **10–12 weeks in advance** for the best rates. Cheapest option: **Peach Aviation** or **Scoot** via Taipei (TPE) to Tokyo (NRT) or Osaka (KIX); for Sapporo, try **Tigerair Taiwan** direct from TPE. Watch for **Peach’s “Happy Peach” flash sales** (usually every Tuesday morning).

**Thailand (Bangkok/Chiang Mai)**  
July is **low season** (rainy), so deals are plentiful. Book **4–6 weeks ahead** for last-minute steals. Cheapest: **Thai Lion Air** or **AirAsia** from TPE to DMK (Bangkok) or CNX (Chiang Mai); often under $150 round trip. Look for **AirAsia’s “Big Sale”** (typically late July) for 20–30% off.

**Europe (any major city)**  
July is **peak summer**, so expect high fares. Book **12–16 weeks in advance** for the best price. Cheapest route: **China Airlines** or **EVA Air** via a stopover (e.g., Taipei → London → Paris) often beats nonstop. Watch for **EVA Air’s “Hello Kitty” promotions** or **Turkish Airlines’ summer sales** (stop in Istanbul) for $600–$800 round trips.

**USA (West Coast / East Coast)**  
July is **peak season** (summer travel). Book **10–14 weeks ahead**. Cheapest to West Coast: **Starlux Airlines** (TPE→LAX/SFO) or **EVA Air** (often $700–$900). For East Coast: **China Airlines** (TPE→JFK) or **Korean Air** via Seoul ($900–$1,200). Check **Starlux’s “Early Bird” deals** (usually 3–4 months out) for 15% off.

**Egypt (Cairo)**  
July is **peak season** (tourist high), but still moderate. Book **8–10 weeks in advance**. Cheapest: **EgyptAir** via Bangkok (BKK→CAI) or **Turkish Airlines** via Istanbul (IST). Look for **Turkish Airlines’ “Stopover in Istanbul” promo** (free hotel) which can save $200–$300 on the total fare.

**Australia (Sydney/Melbourne)**  
July is **winter in Australia** (low season for tourists, but still moderate demand). Book **6–8 weeks ahead**. Cheapest: **Jetstar** (TPE→KIX→SYD/MEL) or **Scoot** via Singapore (SIN). Watch for **Jetstar’s “Friday Fare Frenzy”** (every Friday) for one-way fares as low as $150 AUD from Taipei.

## 📚 Learning

### 📚 Learning — Finance
> `2026-07-20 09:04:39`

#### 📚 Today's Concept: Revenue vs. Net Income

What it is: Revenue is the total money a company brings in from selling its products or services, before any costs are deducted. Net income is what’s left after subtracting all expenses—like cost of goods sold, salaries, taxes, and interest—from revenue.

Why it matters: A company can have soaring revenue but still lose money if its costs are too high. Comparing revenue growth to net income trends helps you spot whether growth is profitable or just burning cash.

Example: Imagine a software firm reports $100M in revenue, but its total expenses are $95M. Net income is $5M (5% profit margin). Next quarter, revenue jumps to $120M, but expenses balloon to $118M—net income drops to $2M (1.7% margin). Revenue grew 20%, but net income fell 60%.

Rule of thumb: If revenue is rising but net income is flat or falling, investigate rising costs—this is often a warning sign of inefficiency or price-cutting to chase sales.

### 🧩 LeetCode Blind 100
> `2026-07-20 09:04:43`

#### 🧩 Blind 100 — 49. Group Anagrams [Arrays & Hashing]
**連結:** https://leetcode.com/problems/group-anagrams/
> 📅 **Today's Daily Challenge:** #1386 Shift 2D Grid [Easy] — Tags: Array, Matrix, Simulation — https://leetcode.com/problems/shift-2d-grid/

**Problem Type:** Arrays & Hashing / Sorting  
**Key Insight:** Anagrams have identical sorted strings or character frequency tuples — use one of these as a hashmap key to group them.

**Approach:**
1. Initialize a defaultdict(list) to store groups.
2. For each string `s` in `strs`:
   - Sort `s` → `sorted_s = ''.join(sorted(s))`
   - Append `s` to `d[sorted_s]`
3. Return `list(d.values())`

**Python3 Solution:**
```python
from collections import defaultdict

class Solution:
    def groupAnagrams(self, strs: List[str]) -> List[List[str]]:
        groups = defaultdict(list)
        for s in strs:
            key = ''.join(sorted(s))
            groups[key].append(s)
        return list(groups.values())
```

**Complexity:** Time O(N * K log K) | Space O(N * K)  
*N = number of strings, K = max length of a string*

**Blind 100 Note:** Core "hashmap with transformed key" pattern. Teaches how to identify equivalence classes. Similar problems: *Valid Anagram*, *Group Shifted Strings*, *Find Duplicate Subtrees*.

**Contest Tips:**
- Sorting is fine for contest speed (K ≤ 100 here). For ultra-optimization, use tuple of 26 char counts as key (O(N*K) time).
- Use `defaultdict(list)` to avoid checking key existence.
- Edge case: empty list → returns `[]` correctly.
- Python trick: `''.join(sorted(s))` is fast enough; don't overcomplicate.

### 📷 Learning — Photography
> `2026-07-20 09:04:52`

#### 📷 Today's Concept: Sony A7C — IBIS In-Body Stabilization Tips and Limits

**What it is:** IBIS uses internal sensor-shift mechanics to counteract camera shake, stabilizing your footage and stills without a gimbal or tripod. On the Sony A7C, it provides up to 5 stops of compensation.

**Why it matters:** It lets you shoot handheld at slower shutter speeds (1/15s for static subjects) and smooth out walking shots for video, reducing the need for bulky support gear in portrait, street, and landscape work.

**How to apply it:**
1. **For stills:** Set shutter speed to 1/(focal length) or slower—e.g., 1/30s with a 35mm lens—and brace your elbows against your body.
2. **For video:** Enable “SteadyShot” (Standard) for walking shots; switch to “Active” for more aggressive smoothing, but expect a slight crop.
3. **Use a wide lens (24-35mm)** to maximize IBIS effectiveness—longer focal lengths (85mm+) still require faster shutter speeds or a tripod.
4. **Pan smoothly:** IBIS can fight intentional pans; for cinematic video, use “SteadyShot” with “Panning” mode to avoid jitter.

**Sony A7C tip:** Go to Menu → Camera Settings 2 → SteadyShot → set to “Standard” for most handheld work. For video, enable “SteadyShot Adjust.” (Auto) to let the camera prioritize stabilization over framing.

**Common mistake:** Relying on IBIS at very slow shutter speeds (1/8s or slower) for portraits—subject motion blur will ruin sharpness. Always match shutter speed to your subject’s stillness, not just your hand stability.

### 📚 Learning — Tech
> `2026-07-20 09:04:46`

#### 📚 Today's Concept: Rate Limiting Algorithms (Token Bucket, Leaky Bucket)

**What it is:** Rate limiting algorithms control the frequency of requests to a system. Token Bucket allows bursts by accumulating tokens over time, while Leaky Bucket processes requests at a fixed rate, smoothing out spikes.

**When to use it:** Use Token Bucket for APIs that need to handle sudden traffic spikes (e.g., a social media feed refresh). Use Leaky Bucket for steady, predictable throughput (e.g., a payment gateway processing transactions).

**Example (Token Bucket in Python):**
```python
import time

class TokenBucket:
    def __init__(self, rate, capacity):
        self.rate = rate
        self.capacity = capacity
        self.tokens = capacity
        self.last_refill = time.monotonic()

    def allow(self):
        now = time.monotonic()
        self.tokens = min(self.capacity, self.tokens + (now - self.last_refill) * self.rate)
        self.last_refill = now
        if self.tokens >= 1:
            self.tokens -= 1
            return True
        return False
```

**Gotcha:** A common mistake is using Token Bucket without resetting the token count on refill, causing it to exceed capacity and allow infinite bursts. Always cap tokens to the bucket’s capacity.

### 🎬 Learning — YouTube
> `2026-07-20 09:04:56`

#### 🎬 今日主題：攝影Vlog — 如何展示攝影作品集讓觀眾感興趣
**類別：** 攝影Vlog

**是什麼：**  
攝影Vlog是將你的攝影作品與生活故事結合，透過影片展示創作過程與成品，讓觀眾感受你的視角與熱情。它不是單純放照片，而是用動態敘事引發共鳴。

**為什麼重要：**  
對初學者來說，這能快速建立個人風格與觀眾連結，避免淪為「另一台相機開箱」，讓你的頻道在競爭中脫穎而出。

**怎麼做：**  
1. **選主題**：每次聚焦一個作品系列（如「街頭光影」），用一句話說明靈感來源。  
2. **拍過程**：用Sony A7C錄製拍攝當下的思考與技巧，例如如何構圖、調整參數。  
3. **AI剪輯**：用Descript或剪映自動生成字幕、去蕪存菁，專注在關鍵片段。  
4. **對比展示**：將成品照片與拍攝場景並列，解說你的創作決策。  
5. **結尾呼籲**：問觀眾「你最想學哪個技巧？」引導留言互動。

**新手常犯的錯：**  
只放照片幻燈片，缺乏故事線。避免方法：用「問題→解決→成果」結構，例如「遇到逆光怎麼辦？我這樣調整」。

**延伸 idea：**  
「帶著Sony A7C去老街：用AI快速剪出3種風格作品集」— 結合旅遊與攝影，展示同一場景的日系、黑白、復古調色，適合初學者模仿。
