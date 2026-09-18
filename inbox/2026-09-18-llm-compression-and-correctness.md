---
date: 2026-09-18
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "savings_travel", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube", "immigration_au"]
---

# Daily Digest — 2026-09-18

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
- 🗺️ Travel Deals
- 📚 Learning — Finance
- 🧩 LeetCode Blind 100
- 📷 Learning — Photography
- 📚 Learning — Tech
- 🎬 Learning — YouTube
- 🇦🇺 Australia Immigration

---

## 🔥 今日重點 Top Highlights

- **AI 硬體全面大漲，台股同步走強** — SMCI +13.22%、ARM +9.54%、AMD +6.36%，TAIEX 漲 1.36% 領先美日。對台灣供應鏈（TSMC、伺服器 ODM、ABF 載板）是正面訊號，值得留意是否為短線過熱。
- **澳洲移民制度傳出重大改革** — Labor 政府預告將重整移民系統，189/190/491 的職業清單與資格條件可能變動。若你正在規劃 EOI，建議先觀望再遞交。 [公告討論](https://www.reddit.com/r/AusVisa/comments/1wiin5c/just_announced_labors_planned_changes_on_migration/) · [改革更新](https://www.reddit.com/r/AusVisa/comments/1wii55w/update_on_migration_overhaul/)
- **Google ADK for Kotlin 1.0 發布** — 與 Python/Java 核心功能對等，可在 Android 上開發 production-ready 多代理 AI 應用。 [Link](https://developers.googleblog.com/announcing-adk-for-kotlin-10-building-production-ready-ai-agents-in-kotlin-android-and-beyond/)
- **Bonsai 2 27B：27B 模型壓縮至 1/9 體積** — 若你在邊緣裝置或受限硬體上部署 LLM，這是今天最值得實測的一條。 [Link](https://prismml.com/news/bonsai-2-27b)
- **Uber 的 retry storm 防護實戰文** — 分散式系統必讀，避免重試放大導致連鎖故障。 [Link](https://www.uber.com/us/en/blog/protecting-against-retry-storms/)

---

- 💻 **Tech**: Bonsai 2 27B 壓縮、Bend 語言（proof-based AI 防錯）、Infinite-Parameter LLMs、Uber retry storm 防護、Fathom 稀疏解碼。
- 🤖 **AI 公司動態**: 無 OpenAI/Anthropic 消息；Tesla FCF -$1.1B 但現金 $43.5B 撐得住，Crusoe 募 $3.9B 建 AI 資料中心。
- 🔵 **Google**: ADK for Kotlin 1.0、開源 SDK 生成（AGPLv3）、Agent Anomaly Detection 私測、TPU 自動化 LLM 後訓練、UN Data Commons。
- 📈 **Markets**: 美股 S&P +0.69%、台股 +1.36% 領漲、日經 +0.86%，全面 risk-on。
- 🏠 **台灣房市**: Q2 高總價量縮價穩、個案表現；自住避開高單價重劃區，投資留意流動性風險。
- 📊 **Watchlist**: 12 檔全紅，SMCI/ARM/AMD 領漲；估值欄位全 N/A，純價格動能解讀。
- 🌍 **World News**: 加拿大挺歐盟「準會員」、南非連環命案、UN 稱美在伊朗涉戰爭罪、伊朗代表團獲准赴 UN、在華被囚美學者家屬求助。
- 📷 **Camera Deals**: 台灣各通路優缺點比較；9 月中秋＋開學季是機身+鏡頭組合入手時機。
- 🤿 **Dive Gear**: 台灣實體/線上/二手管道整理；9 月潛季交界，防寒衣與輕裝折扣多。
- ✈️ **Flight Tips**: 9 月飛日本/泰國/歐洲/美國/埃及/澳洲的廉航與促銷整理；澳洲避開 9/25–10/5 學校假期。
- 🗺️ **Travel Deals**: 日本節奏重於天數、歐洲 7 天 3 城太趕、隨機廉航風險高。
- 📚 **Learning — Finance**: Gross vs Operating Margin — 差距大代表 overhead 重，operating margin 負但 gross 高可能永遠無法規模化獲利。
- 🧩 **LeetCode Blind 100**: #973 K Closest Points — max-heap of size K，O(n log k)；今日挑戰 #1644 Hard。
- 📷 **Learning — Photography**: 長

---

## 💻 Tech

### 💻 Tech & AI
> `2026-09-18 09:21:46`

#### Hacker News
- [Bonsai 2 27B: Near-Lossless Compression in a 9x Smaller Footprint](https://prismml.com/news/bonsai-2-27b) ⭐200
- [Bend – A language that blocks AI mistakes via proof, on CPU and GPU](https://bend-lang.com/) ⭐271
- [Diplodocus, Long Thought Exclusively American, Turns Up in Spain](https://www.sci.news/paleontology/spanish-diplodocus-15064.html) ⭐26
- [Infinite-Parameter LLMs: Generating and Adapting Weights from Live Data](https://arxiv.org/abs/2609.18842) ⭐107
- [How Uber Protects Against Retry Storms](https://www.uber.com/us/en/blog/protecting-against-retry-storms/) ⭐33
- [The American Religion of Self-Storage Facilities](https://www.newyorker.com/magazine/2026/09/21/the-american-religion-of-self-storage-facilities) ⭐188
- [TSMC revealing details about next gen A14 node](https://iedm26.mapyourshow.com/8_0/sessions/session-details.cfm?scheduleid=331) ⭐87
- [Show HN: Share your AI Setup, Learn from others](https://mysetup.ai/) ⭐182
- [Launch HN: Skillsync (YC W26) – AI chat sessions made portable across agents](https://news.ycombinator.com/item?id=49743049) ⭐47
- [Sex, AI, and the Apocalypse](https://www.iankduncan.com/personal/2026-09-16-sex-ai-and-the-apocalypse/) ⭐157

#### HuggingFace
- [Fingers as Legs: Learning Self-Supported Locomotion and Manipulation with an Anthropomorphic Hand](https://huggingface.co/papers/2609.17172)
- [CERA-MoA: Co-Evolving Routing Mechanisms with Continually Learning LLM Agents](https://huggingface.co/papers/2609.18779)
- [Fathom: Per-Query Read Depth for Sparse Decoding over Offloaded KV Caches](https://huggingface.co/papers/2609.17652)
- [In-Context Robot Learning with VLM Agents](https://huggingface.co/papers/2609.19138)
- [Assessing nnU-Net Generalization across Brain Tumor Populations in BraTS-GoAT 2026](https://huggingface.co/papers/2609.15524)
- [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063)

#### ArXiv
- [Objective vs. Search: Decomposing What Makes a Good Tokeniser](http://arxiv.org/abs/2609.19145v1)
- [A Zeroth-Order Paradigm for LLM Preference Alignment](http://arxiv.org/abs/2609.19144v1)
- [PANORAMA: Panoptic Grounded Captioning via Mask Proposal Selection](http://arxiv.org/abs/2609.19143v1)
- [Dreaming the Sound of Contact: Leveraging Video and Audio Generation for Zero-Shot Force-Aware Manipulation and Data Generation](http://arxiv.org/abs/2609.19137v1)
- [Exponential Hardness of Off-Policy Evaluation under History-Dependent Logging](http://arxiv.org/abs/2609.19135v1)
- [ScienceIDE: Turning World's Scientific Codebase into Agent Learnable Environments](http://arxiv.org/abs/2609.19134v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-09-18 09:21:53`

#### Tesla
- [The Under-the-Radar Stock Big Money Is Quietly Buying Up](https://finance.yahoo.com/markets/stocks/articles/under-radar-stock-big-money-002500496.html)
- [Crusoe raises $3.9B to build massive data centers and small modular ‘AI factories’](https://finance.yahoo.com/technology/ai/articles/crusoe-raises-3-9b-build-232552504.html)
- [Tesla Posted Negative $1.1 Billion in Free Cash Flow Last Quarter as Elon Musk Ramps Up Spending on Robotaxis and Optimus. Here's Why the Company's $43.5 Billion Cash Cushion Still Matters.](https://finance.yahoo.com/markets/stocks/articles/tesla-posted-negative-1-1-225900533.html)
- [Elon Musk Predicts Solar Will Crush All Other Energy Sources to Below 0.1% Amid Texas Boom: ‘So Obviously the Future’](https://finance.yahoo.com/energy/articles/elon-musk-predicts-solar-crush-220019461.html)

### 🔵 Google 動態
> `2026-09-18 09:21:50`

#### Google AI Blog
- [Making global data easier to explore](https://blog.google/innovation-and-ai/technology/ai/google-un-data-commons-platform/)
- [AI for Societal Impact](https://blog.google/innovation-and-ai/technology/ai/ai-for-societal-impact/)
- [Building AI to accelerate science and improve lives](https://blog.google/innovation-and-ai/technology/ai/ai-applications-science-people/)
- [AI for everyone in every language](https://blog.google/innovation-and-ai/technology/ai/ai-for-every-language/)
- [New insights from Google’s AI & Economy ATLAS](https://blog.google/innovation-and-ai/technology/ai/ai-economy-atlas-september-2026/)
#### Google Blog
- [Making global data easier to explore](https://blog.google/innovation-and-ai/technology/ai/google-un-data-commons-platform/)
- [The new CC, an AI agent built for families](https://blog.google/innovation-and-ai/models-and-research/google-labs/cc-expanding-to-groups/)
- [Drive with “Forgotten Island” on Waze.](https://blog.google/waze/waze-forgotten-island/)
- [Helping bring the world’s first large-scale, near-zero emissions steel plant online](https://blog.google/company-news/outreach-and-initiatives/sustainability/google-stegra-green-steel/)
- [3 new ways we're improving Search profiles for publishers](https://blog.google/products-and-platforms/products/search/3-new-ways-were-improving-search-profiles-for-publishers/)
#### Google Developers
- [Why client SDK generation belongs in the open](https://developers.googleblog.com/why-client-sdk-generation-belongs-in-the-open/)
- [Agent Anomaly Detection, now in Private Preview on the Gemini Enterprise Agent Platform](https://developers.googleblog.com/agent-anomaly-detection-now-in-private-preview-on-the-gemini-enterprise-agent-platform/)
- [Build zero-trust AI agents that judge intent, not just syntax](https://developers.googleblog.com/build-zero-trust-ai-agents-that-judge-intent-not-just-syntax/)
- [Autonomous LLM post-training with Tunix on TPUs](https://developers.googleblog.com/autonomous-llm-post-training-with-tunix-on-tpus/)
- [Announcing ADK for Kotlin 1.0: Building Production-Ready AI Agents in Kotlin, Android, and Beyond](https://developers.googleblog.com/announcing-adk-for-kotlin-10-building-production-ready-ai-agents-in-kotlin-android-and-beyond/)

## 📈 Finance

### 📈 Markets Overview
> `2026-09-18 09:21:55`

#### Indices
- S&P 500: 7,637.76 ▲0.69%
- 台股加權: 46,917.84 ▲1.36%
- 日經 225: 64,685.48 ▲0.86%

### 🏠 台灣房市
> `2026-09-18 09:22:44`

#### AI 分析
1. **整體趨勢**：2026年Q2高總價市場仍見成交，但單價落差極大（27.9萬～51.9萬/㎡），顯示資金集中於精華地段，非全面性上漲；政策調控與高利率環境下，買方追價意願保守，市場呈「量縮價穩、個案表現」格局。

2. **值得注意的地區／物件**：高總價成交集中於住宅大樓（11層以上）與低樓層華廈，坪數多為260～675㎡大戶型，單價27.9萬者可能位於新興重劃區或非核心地段，51.9萬者則屬市中心精華區；「其他」類型（0㎡、單價3.6萬）多為特殊交易（如土地、持分或親友間移轉），不宜視為行情參考。

3. **自住建議**：優先鎖定生活機能成熟、學區與交通建設明確的區域，避開單價過高且供給量大的重劃區；善用實價登錄比對同社區近期成交，議價空間約5～10%，勿因個案高價而恐慌追價。

4. **投資建議**：高總價產品流動性低，除非長期持有或具都更、危老題材，否則不建議短線進場；可關注總價2,000～4,000萬、單價合理的中小坪數電梯大樓，租金投報率較穩定，且轉手性較佳。

5. **風險提醒**：2026年下半若央行維持選擇性信用管制，高總價貸款成數受限，買方自備款壓力大；建議預留至少3成自備款及2年房貸緩衝金，並緊盯Q3實價登錄是否出現單價鬆動訊號。

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
> `2026-09-18 09:22:19`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 219.34 ▲2.54% |
| Market Cap | $5.31T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.7% / 65.2% / 63.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 23.17 |
| Beta | 2.22 |
| 52-Week | 164.27 – 236.54 |
| Div. Yield | — |

**Recent News:**
- [1 Tech Stock That's Too Good to Pass On as We Approach the Fourth Quarter](https://finance.yahoo.com/markets/stocks/articles/1-tech-stock-thats-too-005300469.html) — Motley Fool
- [Prediction: The Invesco QQQ Trust Beats the S&P 500 Again Over the Next 5 Years](https://finance.yahoo.com/markets/stocks/articles/prediction-invesco-qqq-trust-beats-004301148.html) — Motley Fool
- [Why GE Vernova Stock Bumped Higher Today](https://finance.yahoo.com/markets/stocks/articles/why-ge-vernova-stock-bumped-002448626.html) — Motley Fool

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 545.09 ▲6.36% |
| Market Cap | $888.82B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.2% / 15.7% / 15.6% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.23 |
| Beta | 2.48 |
| 52-Week | 149.85 – 584.73 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures Fall After S&P 500, Nasdaq Rebound Above Key Level; Moderna, AMD, SpaceX Flash Buy Signals](https://finance.yahoo.com/m/1921e6e5-7c6c-3cc6-ae73-750d397323c3/dow-jones-futures-fall-after.html) — Investor's Business Daily
- [Why AMD Stock Jumped Today](https://finance.yahoo.com/markets/stocks/articles/why-amd-stock-jumped-today-233549219.html) — Motley Fool
- [Nebius Group (NBIS) Raises AI Cloud Prices As Compute Demand Tests Customer Costs](https://finance.yahoo.com/technology/ai/articles/nebius-group-nbis-raises-ai-232109046.html) — Simply Wall St.

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 497.75 ▲1.52% |
| Market Cap | $3.70T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.9% / 46.8% / 40.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 8.36 |
| Beta | 1.11 |
| 52-Week | 349.20 – 553.72 |
| Div. Yield | — |

**Recent News:**
- [Microsoft (MSFT) Puts a Clock on Free Xbox Cloud Gaming](https://finance.yahoo.com/technology/articles/microsoft-msft-puts-clock-free-235334777.html) — Insider Monkey
- [Tech Companies’ Staff Knew Their AI Tools Posed ‘Existential Threat’ to Publishers](https://finance.yahoo.com/m/33a3e37c-c02a-365d-96e9-7ba03d9d33e9/tech-companies%E2%80%99-staff-knew.html) — The Wall Street Journal
- [$500,000 Split Between VOO and QQQ Owns the Same Seven Stocks Twice, and Nobody Adds Up the Overlap](https://finance.yahoo.com/markets/stocks/articles/500-000-split-between-voo-221509822.html) — 24/7 Wall St.

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 347.33 ▲1.30% |
| Market Cap | $4.20T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.1% / 54.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.52 |
| Beta | 1.23 |
| 52-Week | 235.84 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [1 Tech Stock That's Too Good to Pass On as We Approach the Fourth Quarter](https://finance.yahoo.com/markets/stocks/articles/1-tech-stock-thats-too-005300469.html) — Motley Fool
- [Mark Cuban exposes a problem with how Meta and Google fund AI](https://finance.yahoo.com/technology/ai/articles/mark-cuban-exposes-problem-meta-003700561.html) — TheStreet
- [Why Banks Suddenly Want Stablecoins, and Why It May Matter for You](https://finance.yahoo.com/markets/crypto/articles/why-banks-suddenly-want-stablecoins-001112202.html) — BeInCrypto

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 251.19 ▲2.13% |
| Market Cap | $2.70T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 50.8% / 12.1% / 17.4% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.90 |
| Beta | 1.44 |
| 52-Week | 196.00 – 287.20 |
| Div. Yield | — |

**Recent News:**
- [Why Generac Stock Soared Today](https://finance.yahoo.com/markets/stocks/articles/why-generac-stock-soared-today-234107343.html) — Motley Fool
- [AI Security Debate — Amazon Says AI Models To Be Released Only When 'Ready And Safe'](https://finance.yahoo.com/technology/ai/articles/ai-security-debate-amazon-says-234035124.html) — Stocktwits
- [S&P 500, Nasdaq, Dow End Higher As Drop In Oil Prices Allays Inflationary Concerns — NVDA, MCD, CRWV, LMT, AMZN In Focus](https://finance.yahoo.com/markets/stocks/articles/p-500-nasdaq-dow-end-222214421.html) — Stocktwits

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 682.31 ▲1.34% |
| Market Cap | $1.74T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.7% / 38.1% / 29.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.64 |
| Beta | 1.24 |
| 52-Week | 520.26 – 790.80 |
| Div. Yield | — |

**Recent News:**
- [Mark Cuban exposes a problem with how Meta and Google fund AI](https://finance.yahoo.com/technology/ai/articles/mark-cuban-exposes-problem-meta-003700561.html) — TheStreet
- [Non-Tech Stocks Can Still Deliver Huge Gains](https://finance.yahoo.com/markets/stocks/articles/non-tech-stocks-still-deliver-000800931.html) — Zacks
- [Meta (META) Hands its New AI Agent the Keys to Your Inbox and Wallet](https://finance.yahoo.com/technology/ai/articles/meta-meta-hands-ai-agent-234026981.html) — Insider Monkey

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 347.30 ▲2.37% |
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
- [Salesforce CEO warns AI companies not to repeat this costly mistake](https://finance.yahoo.com/technology/ai/articles/salesforce-ceo-warns-ai-companies-221700236.html) — TheStreet
- [$500,000 Split Between VOO and QQQ Owns the Same Seven Stocks Twice, and Nobody Adds Up the Overlap](https://finance.yahoo.com/markets/stocks/articles/500-000-split-between-voo-221509822.html) — 24/7 Wall St.
- [Jim Cramer on Broadcom (AVGO): “The Stock May Be Too Cheap to Ignore”](https://finance.yahoo.com/markets/stocks/articles/jim-cramer-broadcom-avgo-stock-214237143.html) — Insider Monkey

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 264.90 ▲9.54% |
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
- [Update: US Equity Indexes Rise, Big Tech Perks Up After Fed's Commitment to Controlling Inflation Sinks Treasury Yields](https://finance.yahoo.com/markets/stocks/articles/us-equity-indexes-rise-big-213219728.html) — MT Newswires
- [AMD Leads Chip Stocks Higher Amid Sector Rebound](https://finance.yahoo.com/m/c04c7815-41c6-3fb6-9a52-2b9916a1105e/amd-leads-chip-stocks-higher.html) — Investor's Business Daily
- [Arm CEO Rene Haas more confident on $2 billion AI chip revenue target](https://finance.yahoo.com/technology/ai/articles/arm-ceo-rene-haas-more-175603204.html) — Quartz

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 176.24 ▲1.09% |
| Market Cap | $404.66B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.8% / 42.8% / 49.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 43.22 |
| Beta | 1.62 |
| 52-Week | 106.37 – 207.52 |
| Div. Yield | — |

**Recent News:**
- [Palantir Technologies (PLTR) AI Deal Rush Meets A Fair Value Debate](https://finance.yahoo.com/markets/stocks/articles/palantir-technologies-pltr-ai-deal-001448200.html) — Simply Wall St.
- [Palantir, Rocket Lab among biggest climbers in power ranking](https://finance.yahoo.com/markets/stocks/articles/palantir-rocket-lab-among-biggest-221047961.html) — TheStreet
- [Michael Burry returns to a difficult corner of Wall Street](https://finance.yahoo.com/markets/stocks/articles/michael-burry-returns-difficult-corner-220700698.html) — TheStreet

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 40.35 ▲13.22% |
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
- [Will 2026 Doom and Gloom Lead to Opportunity?](https://finance.yahoo.com/markets/stocks/articles/2026-doom-gloom-lead-opportunity-195200609.html) — Zacks
- [Super Micro Computer Stock Soars -- $1.3 Trillion AI Server Boom Lifts Shares](https://finance.yahoo.com/markets/stocks/articles/super-micro-computer-stock-soars-182328823.html) — GuruFocus.com
- [Dell’s AI Backlog Surge Positions Stock for $600+ as Server Revenue Doubles](https://finance.yahoo.com/markets/stocks/articles/dell-ai-backlog-surge-positions-170011018.html) — 24/7 Wall St.

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 366.20 ▲2.27% |
| Market Cap | $1.45T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 18.9% / 4.2% / 3.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.65 |
| Beta | 1.84 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [The Under-the-Radar Stock Big Money Is Quietly Buying Up](https://finance.yahoo.com/markets/stocks/articles/under-radar-stock-big-money-002500496.html) — Motley Fool
- [Crusoe raises $3.9B to build massive data centers and small modular ‘AI factories’](https://finance.yahoo.com/technology/ai/articles/crusoe-raises-3-9b-build-232552504.html) — TechCrunch
- [Tesla Posted Negative $1.1 Billion in Free Cash Flow Last Quarter as Elon Musk Ramps Up Spending on Robotaxis and Optimus. Here's Why the Company's $43.5 Billion Cash Cushion Still Matters.](https://finance.yahoo.com/markets/stocks/articles/tesla-posted-negative-1-1-225900533.html) — Motley Fool

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 701.03 ▲0.69% |
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
- [Prediction: The Invesco QQQ Trust Beats the S&P 500 Again Over the Next 5 Years](https://finance.yahoo.com/markets/stocks/articles/prediction-invesco-qqq-trust-beats-004301148.html) — Motley Fool
- [ETF Oasis at Future Proof: Tuesday Highlights](https://finance.yahoo.com/markets/options/articles/etf-oasis-future-proof-tuesday-223819508.html) — etf.com
- [$500,000 Split Between VOO and QQQ Owns the Same Seven Stocks Twice, and Nobody Adds Up the Overlap](https://finance.yahoo.com/markets/stocks/articles/500-000-split-between-voo-221509822.html) — 24/7 Wall St.

## 🌍 News

### 🌍 World News
> `2026-09-18 09:22:46`

- [Canada welcomes EU proposal to become 'associate member'](https://www.bbc.co.uk/news/articles/cwly7vkke4jxo?at_medium=RSS&at_campaign=rss)
- [Ninth woman's body found as South African police investigate string of deaths](https://www.bbc.co.uk/news/articles/cqx2zgk8k8xvo?at_medium=RSS&at_campaign=rss)
- [UN experts say grounds to believe US committed war crimes in Iran strikes](https://www.bbc.co.uk/news/articles/cm9w4n5nverdo?at_medium=RSS&at_campaign=rss)
- [US to allow Iran delegation to attend UN meetings in New York as war passes half-year mark](https://www.bbc.co.uk/news/articles/c6n8m72r13ngo?at_medium=RSS&at_campaign=rss)
- [Wife of US scholar jailed in China asks Trump to raise arrest at Xi meeting](https://www.bbc.co.uk/news/articles/c9j3d2rr6g24o?at_medium=RSS&at_campaign=rss)
- [Hyrox athlete apologises for continuing race after soiling herself](https://www.bbc.co.uk/news/articles/ck0e35qyqlx0o?at_medium=RSS&at_campaign=rss)
- [Aztec document goes on display in Mexico after 186 years abroad](https://www.bbc.co.uk/news/articles/ck980qyy6d2zo?at_medium=RSS&at_campaign=rss)
- [Assad regime planned US journalist's kidnap for weeks, BBC finds](https://www.bbc.co.uk/news/articles/cv0lrxw6ygl2o?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-09-18 09:22:59`

#### AI Tips
# 📸 台灣攝影採購 & 今日技巧快報（2026/09/18）

## 🛒 購買優惠：台灣買相機鏡頭哪裡最划算？

#### 各通路優缺點速覽

| 通路 | 適合買什麼 | 優點 | 注意事項 |
|------|-----------|------|---------|
| **PChome 24h** | 公司貨機身、配件 | 到貨快、可刷卡分期、常有「品牌日」折價券 | 價格偏硬，比價後再下手 |
| **momo購物** | 組合包（機身+鏡頭+記憶卡） | 常送贈品、mo幣回饋、信用卡回饋疊加 | 贈品價值要自己算，別被話術 |
| **蝦皮商城** | 平行輸入、配件 | 折扣券多、賣家競爭 | 認明「商城」與評價，保固要看清楚 |
| **光華商場 / 相機街** | 機身、二手、議價 | 可現場試機、當面議價、撿展示機 | 週末人潮多，平日去更好談 |
| **日本代購 / Bic Camera** | 日系鏡頭、機身 | 匯率好時便宜 1~2 成 | 保固多為日本國內，維修要寄回 |
| **二手（DCView、旋轉拍賣、M01市集）** | 鏡頭、老機身 | CP值高 | 面交驗快門數、入塵、發霉 |

#### 🗓️ 九月季節性採購時機

1. **開學季尾聲（9月中下旬）**：相機店常有「學生專案」，憑學生證折 500~2000 元，非學生也可問「開學優惠」。
2. **中秋節前後（今年中秋 9/25）**：momo、PChome 常推「中秋家電3C節」，滿萬折千、mo幣加倍，是入手**機身+鏡頭組合**的好時機。
3. **iPhone / 新機發表後（9月）**：手機新機上市會帶動「相機

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-09-18 09:23:03`

#### AI Tips
# 台灣潛水裝備採購 & 9月裝備提醒（2026-09-18）

## 【購買優惠】台灣買潛水裝備的實用管道

**實體店家（可試穿、售後最穩）**
- **台北**：潛水貨倉、海人潛水、Blue Trend 藍色趨勢、IDiver
- **台中**：潛水主義、海洋先生
- **高雄/墾丁**：墾丁在地潛店（如台灣潛水、水世界），旺季常有組合價
- **建議**：輕裝（面鏡、蛙鞋、防寒衣）一定要現場試；重裝（調節器、BCD）可先店內問價再比線上。

**線上 / 社團（撿便宜主戰場）**
- **蝦皮、momo、PChome**：適合買配件、防水袋、燈具，比價快
- **Facebook 社團**：搜「潛水二手買賣」「台灣潛水裝備交流」「潛水裝備 二手 全新」——二手調節器、BCD 常打到 5–7 折
- **露天、旋轉拍賣**：老裝備多，議價空間大
- **國外代購/直送**：Diveinn、Amazon JP、日本樂天，日系品牌（GULL、TUSA）價差可觀，但注意關稅與保固

**9月採購時機提示**
- 9月是**台灣東北角、墾丁、小琉球、綠島的潛季尾聲/旺季交界**，店家常出清夏季庫存 → **防寒衣、輕裝折扣多**
- 雙十、週年慶（10月）前，先卡位 9 月檔期，避免旺季漲價
-

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-09-18 09:22:55`

#### AI Flight Tips — September
# Flight Deals Cheat Sheet — Departing Taiwan (Sep 2026)

**Japan (Tokyo/Osaka/Sapporo)**
- September = off-peak sweet spot (post-summer, pre-autumn); typhoon season risk though. Book 6–8 weeks out.
- Cheapest: LCCs — Peach, Scoot, Tigerair Taiwan to TYO/OSA; Scoot or AirAsia X for CTS. TPE–NRT/TPE–KIX round-trip often NT$5,000–8,000.
- Watch: Peach "Happy Peach" flash sales and Tigerair Taiwan Tuesday promos; avoid Golden Week (early Oct) return dates.

**Thailand (Bangkok/Chiang Mai)**
- September = low season (rainy), cheapest month of the year. Book 4–6 weeks out.
- Cheapest: Thai Vietjet, AirAsia, and Lion Air via TPE–DMK/BKK; Chiang Mai often cheapest on AirAsia via Bangkok.
- Watch: AirAsia "Free Seats" campaigns (usually Mar & Sep); Thai Vietjet 0-baht promos. Round-trips from NT$4,500–7,000.

**Europe (any major city)**
- September = shoulder season, still pricey early month, drops sharply after mid-Sep. Book 10–14 weeks out.
- Cheapest: China Airlines/EVA Air direct to LHR/AMS/CDG/VIE; or one-stop on China Eastern, Turkish, or Emirates for NT$22,000–30,000 round-trip.
- Watch: EVA Air and China Airlines early-bird fares (usually 3–6 months out); Turkish Airlines Istanbul stopover deals.

**USA (West/East Coast)**
- September = post-Labor Day off-peak, one of the cheapest months. Book 8–12 weeks out.
- Cheapest: EVA Air/China Airlines direct to LAX/SFO/SEA/ONT/JFK; Starlux often undercuts on LAX/SFO. Round-trip NT$25,000–35,000.
- Watch: Starlux and EVA "early bird" promos; United/Delta via Tokyo or Seoul can beat directs on East Coast.

**Egypt (Cairo)**
- September = shoulder (still hot, ~35°C); Oct–Apr is peak. Book 10–14 weeks out.
- Cheapest: China Eastern via Shanghai, or Turkish via Istanbul; Emirates/Qatar via Gulf. Round-trip NT$28,000–38,000.
- Watch: Turkish Airlines and Qatar Airways Taiwan promos; EgyptAir via Bangkok sometimes cheapest but long layover.

**Australia (Sydney/Melbourne)**
- September = early spring, shoulder-to-peak transition; school holidays late Sep push prices up. Book 8–10 weeks out.
- Cheapest: China Airlines and EVA Air direct TPE–SYD/BNE/MEL; Scoot via Singapore or AirAsia X via KL for budget. Round-trip NT$20,000–28,000.
- Watch: China Airlines "Down Under" seasonal sales (usually Jun–Aug); avoid departing Sep 25–Oct 5 (NSW school holidays).

**Universal tips:** Tue/Wed departures are cheapest; set Google

### 🗺️ Travel Deals
> `2026-09-18 09:22:49`

#### r/solotravel
- [14 days in Tokyo vs adding 4 days in Beijing: Pushing my limits or setting myself up for burnout? (Need perspective after a failed trip 2 years ago)](https://www.reddit.com/r/solotravel/comments/1wiwfj4/14_days_in_tokyo_vs_adding_4_days_in_beijing/)
- [Krakow, Berlin, London. OH. MY.](https://www.reddit.com/r/solotravel/comments/1wj5bsn/krakow_berlin_london_oh_my/)
- [Has anyone ever travelled by simply taking the cheapest flight every 2 days?](https://www.reddit.com/r/solotravel/comments/1whvlrk/has_anyone_ever_travelled_by_simply_taking_the/)
- [Is Rome, Florence & Venice too much for a 7-day solo trip?](https://www.reddit.com/r/solotravel/comments/1whngx3/is_rome_florence_venice_too_much_for_a_7day_solo/)
- [Rate my Australia Itinerary (2 weeks, possibly cursed) / is Airlie worth it?](https://www.reddit.com/r/solotravel/comments/1wiad7b/rate_my_australia_itinerary_2_weeks_possibly/)
- [8 days in japan as a solo traveller](https://www.reddit.com/r/solotravel/comments/1wi9c8i/8_days_in_japan_as_a_solo_traveller/)

## 📚 Learning

### 📚 Learning — Finance
> `2026-09-18 09:23:05`

#### 📚 Today's Concept: Gross Margin and Operating Margin

What it is: Gross margin is revenue minus cost of goods sold, divided by revenue, showing profit from making and delivering your product. Operating margin subtracts operating expenses like R&D, sales, and admin from that, showing profit from running the whole business.

Why it matters: Comparing the two reveals whether a company's core product is profitable or whether overhead is eating the gains, which tells you if scaling will help or hurt.

Example: A SaaS company has $100M revenue and $30M hosting/support costs, so gross margin is 70%. It spends $40M on sales and $25M on R&D/admin, leaving $5M operating profit, a 5% operating margin. Gross margin looks healthy, but heavy spending leaves little room.

Rule of thumb: A wide gap between gross and operating margin signals bloated overhead; if operating margin is negative while gross margin is high, the business model may never scale profitably.

### 🧩 LeetCode Blind 100
> `2026-09-18 09:23:09`

#### 🧩 Blind 100 — 973. K Closest Points to Origin [Heap]
**連結:** https://leetcode.com/problems/k-closest-points-to-origin/
> 📅 **Today's Daily Challenge:** #1644 Maximum Number of Non-Overlapping Substrings [Hard] — Tags: Hash Table, String, Greedy, Sorting — https://leetcode.com/problems/maximum-number-of-non-overlapping-substrings/

## 973. K Closest Points to Origin

**Problem Type:** Heap / Top-K Selection

**Key Insight:** We only need the K smallest distances, not a full sort. A max-heap of size K lets us evict the farthest point whenever we exceed K — keeping the K closest in O(n log k) instead of O(n log n).

**Approach:**
1. Iterate over each point, compute squared distance `x*x + y*y` (skip sqrt — monotonic, saves time).
2. Push `(-dist, x, y)` onto a max-heap (negate to simulate max-heap with Python's min-heap).
3. If heap size exceeds `k`, pop the largest (farthest) point.
4. Return the `(x, y)` pairs remaining in the heap.

**Python3 Solution:**
```python
class Solution:
    def kClosest(self, points: List[List[int]], k: int) -> List[List[int]]:
        heap = []
        for x, y in points:
            d = x*x + y*y
            heapq.heappush(heap, (-d, x, y))
            if len(heap) > k:
                heapq.heappop(heap)
        return [[x, y] for _, x, y in heap]
```

**Complexity:** Time O(n log k) | Space O(k)

**Blind 100 Note:** Represents the **Top-K with Heap** pattern — the canonical alternative to sorting when k ≪ n. Related: 215 (Kth Largest), 347 (Top K Frequent), 692 (Top K Frequent Words), 1046 (Last Stone Weight). Also solvable via Quickselect (O(n) avg) — worth knowing both.

**Contest Tips:**
- **Skip sqrt** — comparing squared distances is equivalent and faster.
- **Negate for max-heap** — Python's `heapq` is min-only. Alternative: push `(dist, x, y)` and use `heapq.nsmallest(k, ...)`.
- **Edge cases:** k == len(points) (heap never pops — fine), duplicate points, points at origin.
- **Quickselect alternative** if interviewer asks for O(n) average — but heap is safer in contests (no worst-case O(n²) risk).
- **Don't sort** unless k is close to n; `sorted(points, key=...)[:k]` is O(n log n) and often passes but isn't the intended solution.

### 📷 Learning — Photography
> `2026-09-18 09:23:13`

#### 📷 Today's Concept: Landscape — Long Exposure with ND Filters

**What it is:** Long exposure with ND filters means placing a dark glass filter over your lens to block light, letting you use slow shutter speeds (1–30+ seconds) in bright conditions. This turns moving elements—water, clouds, traffic—into smooth, blurred streaks.

**Why it matters:** It transforms chaotic scenes into serene, minimalist images with a dreamy, cinematic quality. Motion becomes a visual texture rather than a frozen instant.

**How to apply it:**
1. Compose on a tripod and lock focus manually—autofocus hunts in the dark.
2. Switch to Manual mode, set ISO 100 and aperture f/8–f/16 for sharpness.
3. Meter without the filter, then calculate your new shutter speed (a 10-stop ND turns 1/125s into ~8 seconds).
4. Screw on the ND filter, set that shutter speed, and shoot in Single or Bulb mode.
5. Use a 2-second self-timer or remote to avoid shake.

**Sony A7C tip:** Enable **SteadyShot OFF** when on a tripod (menu: Shooting > Image Stabilization), and turn on **Live View Display > Setting Effect OFF** so you can actually see to compose through a 10-stop filter. The compact 16–35mm f/4 PZ is ideal for wide landscape work.

**Common mistake:** Forgetting to cover the viewfinder or disable stabilization, causing micro-blur. Also, cheap ND filters cast color shifts—invest in a good 10-stop and fix white balance in post.

### 📚 Learning — Tech
> `2026-09-18 09:23:11`

#### 📚 Today's Concept: Blue-Green vs Canary Deployments

**What it is:** Blue-green runs two identical environments, switching all traffic from old (blue) to new (green) at once. Canary routes a small percentage of traffic to the new version, then gradually increases it.

**When to use it:** Use blue-green when you need instant rollback and can afford double infrastructure. Use canary when you want to limit blast radius and validate with real traffic—e.g., rolling out a new recommendation algorithm to 1% of users before full release.

**Example:**
```yaml
# Canary: 5% to v2
traffic:
  - version: v1
    weight: 95
  - version: v2
    weight: 5
# Blue-green: flip the switch
service: myapp
target: green  # was blue
```

**Gotcha:** Blue-green isn't zero-risk—database schema changes are shared, so a bad migration breaks both environments. Canary isn't free either: you must monitor the right metrics, or you'll promote a broken version because error rates look fine at 1% traffic.

### 🎬 Learning — YouTube
> `2026-09-18 09:23:16`

#### 🎬 今日主題：剪輯 — 字幕設計：字型 / 位置 / 動畫風格
**類別：** 剪輯

**是什麼：** 字幕設計指字型、位置與動畫風格的搭配，讓觀眾在無聲滑手機時也能看懂內容。它是影片節奏與品牌感的一部分，不只是「打字上去」而已。

**為什麼重要：** 多數觀眾靜音觀看，字幕直接影響完看率與追蹤意願；一致的風格會讓你的頻道更快被記住。

**怎麼做：**
1. 字型選 1–2 款無襯線中文字（如思源黑體、Noto Sans），標題與內文分開用。
2. 位置固定在畫面下方 1/3，避開 YouTube 進度條與訂閱按鈕。
3. 動畫用「淡入＋微上移」或「逐字彈出」，時長 0.2–0.3 秒，別用花俏旋轉。
4. 用 AI 工具（CapCut、Vrew、Descript）自動上字幕後，手動修錯字與斷句。
5. 建立一組自己的字幕預設，之後每支片直接套用。

**新手常犯的錯：** 一次用三種字型＋彩虹色＋誇張動畫，看起來像長輩圖。解法：整支片只留一種主字型、兩色以內、一種動畫。

**延伸 idea：** 拍一支「我用 AI 自動上字幕，準確率實測」的科技開箱短片，同時展示你的字幕風格，一魚兩吃。

## 🛂 Immigration

### 🇦🇺 Australia Immigration
> `2026-09-18 09:23:19`

- [September 2026 Partner Visa Mega Thread (Subclasses 820/801, 309/100, 300)](https://www.reddit.com/r/AusVisa/comments/1w4y9nu/september_2026_partner_visa_mega_thread/)
- [Just Announced: Labor's planned changes on migration](https://www.reddit.com/r/AusVisa/comments/1wiin5c/just_announced_labors_planned_changes_on_migration/)
- [I’ve seen so many posts asking whether they can still bring their husband, wife or partner to Australia. It really shows how brutal sudden immigration changes can feel .And if your partner is offshore right now and your country isn’t listed, I’m genuinely sorry , this must be incredibly stressful.](https://www.reddit.com/r/AusVisa/comments/1wisqp1/ive_seen_so_many_posts_asking_whether_they_can/)
- [ETA (Subclass 601) Taking Time](https://www.reddit.com/r/AusVisa/comments/1wj76ig/eta_subclass_601_taking_time/)
- [Update on migration overhaul](https://www.reddit.com/r/AusVisa/comments/1wii55w/update_on_migration_overhaul/)
