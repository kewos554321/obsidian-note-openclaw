---
date: 2026-07-23
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "savings_travel", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube", "immigration_au"]
---

# Daily Digest — 2026-07-23

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

1. **Nvidia DGX Spark 當日常開發機實測** — 一位工程師分享用 $3,000 的 Grace Hopper 超級晶片主機進行日常開發，AI/ML 效能驚人但 Linux 相容性有小問題。適合考慮入手 AI 開發硬體的工程師參考。 [Link](https://daniel.lawrence.lu/blog/2026-07-15-dgx-spark-as-daily-driver/)

2. **台股 TAIEX 強漲 1.34% 領先亞洲市場** — 收在 44,825.78 點，半導體與科技股帶動買氣。同時 Super Micro (SMCI) 單日暴漲 +28.24%，AI 伺服器需求持續火熱。

3. **Google 釋出 Tunix：JAX-native 強化學習訓練庫** — 專為多輪、工具使用的 LLM Agent 設計，消除 TPU 閒置瓶頸。對做 LLM Agent 開發的工程師是重大更新。 [Link](https://developers.googleblog.com/scaling-agentic-rl-high-throughput-agentic-training-with-tunix/)

4. **美國與沙烏地阿拉伯簽署歷史性民用核能協議** — 美國企業將獲得沙國核能計畫的重大參與權，可能影響中東地緣政治與能源市場。 [BBC](https://www.bbc.co.uk/news/articles/cj03r59z73po)

5. **SkewAdam 優化器：MoE 模型記憶體減半** — 新論文提出對 Mixture-of-Experts 模型減少 50%+ 優化器狀態記憶體的方法，對訓練大型 MoE 語言模型至關重要。 [Link](https://huggingface.co/papers/2607.19058)

---

- 💻 Tech: Terrence Tao 用 ChatGPT 探索 Jacobian 猜想、Reddit 限制純 HTML 引發爭議、Nvidia DGX Spark 實測、SkewAdam 優化 MoE 記憶體、CodeRescue 動態升級模型降低成本
- 🤖 AI 公司動態: Tesla Q2 獲利不如預期，股價下跌；Musk 宣布鉅額 AI 基礎設施投資計畫，並獲 Micron 合理價格晶片供應
- 🔵 Google 動態: 釋出 Tunix (Agentic RL 訓練)、Managed Agents 支援背景執行與 MCP、Ray 2.55 正式支援 TPU、Conductor 跨平台化、Gemini Enterprise Agent 整合 Parallel Web Search
- 📈 Markets: 台股 TAIEX +1.34% 領漲、日經 +1.01%、S&P 500 +0.75%，亞洲市場普遍樂觀
- 🏠 台灣房市: 高總價市場量縮價穩，豪宅單價 51.9 萬/坪仍有支撐，建議自住買方鎖定實價登錄中低價位
- 📊 Watchlist: SMCI +28.24% 暴漲、AVGO +4.93%、ARM +5.11% 半導體強勢；PLTR -6.10% 獲利了結
- 🌍 World News: 美沙核能協議、川普威脅伊朗、油輪因胡塞威脅掉頭、烏克蘭無人機襲擊俄羅斯電商倉庫、祕魯火災10死
- 📷 Camera Deals: 7月年中慶優惠進行中，PChome/momo 入門無反相機 10-15% off；光華商場可議價 3-8%
- 🤿 Dive Gear Deals: 7月潛水季水溫 26-29°C，穿 3mm 防寒衣即可；百貨年中慶潛水品牌可能有滿千送百
- ✈️ Flight Tips: 日本旺季需 8-12 週前訂票；泰國雨季 4-6 週前即可；歐洲旺季價格高 40-60%，已偏晚但仍可查 Turkish Airlines 夏季優惠
- 🗺️ Travel Deals: 埃及落地簽 $25 USD、每日預算 $30-50；歐洲申根簽證需 4-6 週前申請；泰國免簽、北京需台胞證
- 📚 Learning — Finance: 今日概念：Enterprise Value (EV) 與 EV/EBITDA — 低於 10x 通常便宜，

---

## 💻 Tech

### 💻 Tech & AI
> `2026-07-23 08:59:09`

#### Hacker News
- [Quality non-fiction books are the antithesis of AI slop](https://resobscura.substack.com/p/quality-non-fiction-books-are-the) ⭐118
- [Are AI Labs Pelicanmaxxing?](https://dylancastillo.co/posts/pelicanmaxxing.html) ⭐373
- [Terrence Tao's ChatGPT Conversation about the Jacobian Conjecture Counterexample](https://chatgpt.com/share/6a5fdc7a-d6f8-83e8-bbea-8deb42cfed56) ⭐558
- [Fairphone 6 wide camera experimental Linux support](https://nondescriptpointer.com/articles/fairphone-6-wide-camera-linux/) ⭐61
- [So Reddit has decided that plain HTML is unsafe](https://www.cole-k.com/2026/07/21/reddit/) ⭐251
- [Anthropomorphism in Children's Interactions with LLM Chatbots](https://arxiv.org/abs/2607.18250) ⭐14
- [Launch HN: Unlayer (YC W22) – Add email and document builders to your app](https://unlayer.com) ⭐45
- [Businesses with ugly AI menu redesigns](https://blog.fiddery.com/businesses-with-ugly-ai-menu-redesigns/) ⭐175
- [Nvidia DGX Spark as a daily driver](https://daniel.lawrence.lu/blog/2026-07-15-dgx-spark-as-daily-driver/) ⭐82
- [Which streaming service was that on again?](https://www.timwehrle.de/blog/which-streaming-service-was-that-on-again/) ⭐43

#### HuggingFace
- [AutoIndex: Learning Representation Programs for Retrieval](https://huggingface.co/papers/2607.18603)
- [Subliminal Clocks: Latent Time Modelling in Diffusion Language Models](https://huggingface.co/papers/2607.01774)
- [Transcription Policy as a Latent Variable: Activating Controllable Verbatim ASR with Word-Level Timing](https://huggingface.co/papers/2607.18934)
- [Computational Humor with Multimodal LLMs: Methods, Datasets, Evaluation, and Challenges](https://huggingface.co/papers/2607.19011)
- [Delineate Anything v2: A Global Foundation Model for Field Delineation](https://huggingface.co/papers/2607.19069)
- [Where Should Optimizer State Live? Tiered State Allocation for Memory-Efficient Mixture-of-Experts Training](https://huggingface.co/papers/2607.19058)

#### ArXiv
- [Copy Less, Ground More: Overcoming Repetitive Copying in Long-Context Reasoning via Evidence-Aware Reinforcement Learning](http://arxiv.org/abs/2607.19345v1)
- [Appearance Pointers -- Multimodal Region Control of Diffusion Transformers](http://arxiv.org/abs/2607.19344v1)
- [CodeRescue: Budget-Calibrated Recovery Routing for Coding Agents](http://arxiv.org/abs/2607.19338v1)
- [Agents in the Wild: Where Research Meets Deployment](http://arxiv.org/abs/2607.19336v1)
- [1-Lipschitz Neural Networks on Hadamard Manifolds](http://arxiv.org/abs/2607.19335v1)
- [Fundamental limits of distributed multiclass classification from simple binary decisions](http://arxiv.org/abs/2607.19334v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-07-23 08:59:23`

#### Tesla
- [Dow Jones Futures Rise; Google, Tesla Fall On Earnings, Capex, But AI Stocks Climb](https://finance.yahoo.com/m/092ff924-f233-311d-95de-ed11a4dabc57/dow-jones-futures-rise%3B.html)
- [Tesla shares fall as Musk touts ambitious -- and costly -- plans](https://finance.yahoo.com/markets/stocks/articles/tesla-shares-dip-profit-misses-210534033.html)
- [Market Chatter: Tesla Received Reasonable-Terms Chip Supply From Micron, Musk Says](https://finance.yahoo.com/markets/stocks/articles/market-chatter-tesla-received-reasonable-000108352.html)
- [Tesla: Q2 Earnings Snapshot](https://finance.yahoo.com/markets/stocks/articles/tesla-q2-earnings-snapshot-233533626.html)

### 🔵 Google 動態
> `2026-07-23 08:59:13`

#### Google AI Blog
- [3 Google updates from Galaxy Unpacked 2026](https://blog.google/products-and-platforms/platforms/android/galaxy-unpacked-2026/)
- [Connect more of your apps to Search](https://blog.google/products-and-platforms/products/search/connected-apps/)
- [Create, edit and star in videos with two Google Vids updates](https://blog.google/products-and-platforms/products/workspace/gemini-omni-personal-avatars/)
- [Celebrating 25 years of visual search innovation](https://blog.google/products-and-platforms/products/search/google-images-25th-anniversary/)
- [Expanding Managed Agents in Gemini API:  background tasks, remote MCP and more](https://blog.google/innovation-and-ai/technology/developers-tools/expanding-managed-agents-gemini-api/)
#### Google Blog
- [Q2 2026 earnings call: Remarks from our CEO](https://blog.google/company-news/inside-google/message-ceo/alphabet-earnings-q2-2026/)
- [Here’s how to ask Gemini Live for help with anything you see.](https://blog.google/products-and-platforms/products/gemini/gemini-live-camera-how-to/)
- [Switch to Android easily — and bring your data with you.](https://blog.google/products-and-platforms/platforms/android/galaxy-unpacked-switch-from-iphone-to-android/)
- [3 Google updates from Galaxy Unpacked 2026](https://blog.google/products-and-platforms/platforms/android/galaxy-unpacked-2026/)
- [13 Google tips for a fun, productive summer off from college](https://blog.google/products-and-platforms/products/education/summer-productivity-tips-google-ai-tools/)
#### Google Developers
- [Scaling Agentic RL: High-Throughput Agentic Training with Tunix](https://developers.googleblog.com/scaling-agentic-rl-high-throughput-agentic-training-with-tunix/)
- [Run Ray on TPU, Part 1: The foundations](https://developers.googleblog.com/run-ray-on-tpu-part-1-the-foundations/)
- [Evolving Spec-Driven Development: Conductor Now Supports Antigravity](https://developers.googleblog.com/evolving-spec-driven-development-conductor-now-supports-antigravity/)
- [Expanding Choice in Gemini Enterprise Agent Platform: Introducing Grounding with Parallel Web Search](https://developers.googleblog.com/expanding-choice-in-gemini-enterprise-agent-platform-introducing-grounding-with-parallel-web-search/)
- [Building scalable AI agents with modular prompt transpilation](https://developers.googleblog.com/building-scalable-ai-agents-with-modular-prompt-transpilation/)

## 📈 Finance

### 📈 Markets Overview
> `2026-07-23 08:59:26`

#### Indices
- S&P 500: 7,498.96 ▲0.75%
- 台股加權: 44,825.78 ▲1.34%
- 日經 225: 66,784.14 ▲1.01%

### 🏠 台灣房市
> `2026-07-23 09:00:17`

#### AI 分析
#### 台灣房市重點分析 (2026-07-23)

1. **整體趨勢：高總價市場量縮價穩**  
   近期高總價成交案例顯示，頂級豪宅（如大安區華廈單價達51.9萬/坪）仍具支撐，但多數高總價住宅大樓單價落在27.9萬至36.8萬/坪，顯示市場買氣趨向理性，高總價物件去化速度放緩，呈現「量縮價穩」格局。

2. **值得注意的區域與類型**  
   - **台北市精華區華廈**：低樓層、高單價產品（如大安區案例）因稀缺性與隱私性，仍受高端買家青睞。  
   - **新興重劃區住宅大樓**：部分區域（如新北、桃園）高總價大樓成交單價約28-37萬/坪，反映外溢效應與自住剛需支撐。

3. **對自住買方建議**  
   優先鎖定「實價登錄區間中低價位」的住宅大樓，避開追高近期創價物件；可關注591平台掛牌量增加區域，議價空間可能擴大。

4. **對投資者建議**  
   短期避開高總價豪宅（流動性風險高），轉向總價3000-5000萬、具捷運或產業園區題材的中古大樓，租金投報率較穩健。

5. **風險提醒**  
   注意央行後續選擇性信用管制動向，以及2026下半年新成屋大量交屋可能帶來的賣壓，避免過度槓桿。

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
> `2026-07-23 08:59:51`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 212.06 ▲2.30% |
| Market Cap | $5.14T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.1% / 64.0% / 63.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 26.35 |
| Beta | 2.21 |
| 52-Week | 164.07 – 236.54 |
| Div. Yield | — |

**Recent News:**
- [Alphabet Just Delivered 82% Cloud Growth. Why It Wasn't Enough](https://finance.yahoo.com/m/c32d583a-ecbd-3fde-b2e1-467634c0c72e/alphabet-just-delivered-82%25.html) — Motley Fool
- [Where Will Solana Be in 3 Years?](https://finance.yahoo.com/m/294d3c66-451a-3f2e-b686-e2da16f823db/where-will-solana-be-in-3.html) — Motley Fool
- [Did AI-Euphoria and Volatile Options Pricing Just Shift Marvell Technology's (MRVL) Investment Narrative?](https://finance.yahoo.com/markets/options/articles/did-ai-euphoria-volatile-options-001600472.html) — Simply Wall St.

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 552.33 ▲1.45% |
| Market Cap | $900.63B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 50.3% / 11.7% / 13.4% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.97 |
| Beta | 2.47 |
| 52-Week | 149.22 – 584.73 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures Rise; Google, Tesla Fall On Earnings, Capex, But AI Stocks Climb](https://finance.yahoo.com/m/092ff924-f233-311d-95de-ed11a4dabc57/dow-jones-futures-rise%3B.html) — Investor's Business Daily
- [AMD (AMD) Lands $5 Billion Anthropic Partnership For AI Chips](https://finance.yahoo.com/technology/ai/articles/amd-amd-lands-5-billion-221044285.html) — Simply Wall St.
- [Tesla's New AI Business Idea Could Help Intel](https://finance.yahoo.com/m/e2429440-64cb-372e-b35a-2a6b84b13e37/tesla%27s-new-ai-business-idea.html) — Barrons.com

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 390.34 ▼1.86% |
| Market Cap | $2.90T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 68.3% / 46.8% / 39.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 7.00 |
| Beta | 1.13 |
| 52-Week | 349.20 – 555.45 |
| Div. Yield | — |

**Recent News:**
- [AMD, Cerebras Strike AI Chip Deals](https://finance.yahoo.com/m/eb24034f-91e3-3778-88a4-ebbde26313bf/amd%2C-cerebras-strike-ai-chip.html) — Investor's Business Daily
- [The Ultimate Bull Run for NVIDIA, Micron, and SanDisk May Be Closer Than Investors Think](https://finance.yahoo.com/m/0d00fceb-ad7d-3657-bac7-51b2dd51958c/the-ultimate-bull-run-for.html) — 24/7 Wall St.
- [Alphabet Stock Falls as AI Spending Continues to Mount](https://finance.yahoo.com/m/61ef1def-7f89-3879-b5f4-6853dbcbdb75/alphabet-stock-falls-as-ai.html) — Barrons.com

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 342.09 ▼1.46% |
| Market Cap | $4.14T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.1% / 54.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.49 |
| Beta | 1.25 |
| 52-Week | 187.82 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures Rise; Google, Tesla Fall On Earnings, Capex, But AI Stocks Climb](https://finance.yahoo.com/m/092ff924-f233-311d-95de-ed11a4dabc57/dow-jones-futures-rise%3B.html) — Investor's Business Daily
- [Alphabet Just Delivered 82% Cloud Growth. Why It Wasn't Enough](https://finance.yahoo.com/m/c32d583a-ecbd-3fde-b2e1-467634c0c72e/alphabet-just-delivered-82%25.html) — Motley Fool
- [Market Chatter: Wall Street Banks Begin Trading Portions of $35 Billion AI Financing Deal for Broadcom, Anthropic](https://finance.yahoo.com/technology/ai/articles/market-chatter-wall-street-banks-234033284.html) — MT Newswires

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 244.85 ▼1.09% |
| Market Cap | $2.63T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 50.6% / 11.5% / 12.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 5.95 |
| Beta | 1.46 |
| 52-Week | 196.00 – 278.56 |
| Div. Yield | — |

**Recent News:**
- [AMZN Stock Drops Nearly 2% After-Hours — Senate Panel Reportedly Probes Amazon Over Alleged Chinese Influence](https://finance.yahoo.com/m/c2754e95-0da2-37c7-9fcd-4ed66524fb16/amzn-stock-drops-nearly-2%25.html) — Stocktwits
- [S&P 500, Nasdaq End Lower, Futures Extend Declines As Attention Shifts To Tech Earnings, Geopolitics —  TSLA, GOOGL, PSKY, RDDT, AMZN In Focus](https://finance.yahoo.com/m/0e600225-97be-3c2e-9267-aea6e1341132/s%26p-500%2C-nasdaq-end-lower%2C.html) — Stocktwits
- [Molina Healthcare Earnings Beat Estimates. The Medicaid Insurer Is Confronting Investor Doubts.](https://finance.yahoo.com/m/7b6d66d6-200a-36cc-a65e-9a96f6d198e6/molina-healthcare-earnings.html) — Barrons.com

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 627.17 ▼2.58% |
| Market Cap | $1.59T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.9% / 41.2% / 32.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.52 |
| Beta | 1.25 |
| 52-Week | 520.26 – 796.25 |
| Div. Yield | — |

**Recent News:**
- [Peter Thiel Turned a $2,000 Roth IRA Into $5 Billion and Will Never Owe a Penny of Tax. The Same Rules Apply to Your Account](https://finance.yahoo.com/m/634a7070-ae9f-3406-b94d-fa1a3431ecdb/peter-thiel-turned-a-%242%2C000.html) — 24/7 Wall St.
- [Teen Withdraws Social Media Addiction Lawsuit Against Meta](https://finance.yahoo.com/media-advertising/articles/teen-withdraws-social-media-addiction-232206771.html) — MT Newswires
- [Google Shares Slide as AI Spending Overshadows Cloud Growth](https://finance.yahoo.com/m/099a61f6-f04e-3f7d-b3e3-5b1f14c6c7bf/google-shares-slide-as-ai.html) — The Wall Street Journal

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 396.81 ▲4.93% |
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
- [Market Chatter: Wall Street Banks Begin Trading Portions of $35 Billion AI Financing Deal for Broadcom, Anthropic](https://finance.yahoo.com/technology/ai/articles/market-chatter-wall-street-banks-234033284.html) — MT Newswires
- [Chasing Yield Is a Trap. These 3 Dividend ETFs Pay You Without the Risk](https://finance.yahoo.com/m/584ad069-8ba4-3a21-aeed-b05d383c5cd4/chasing-yield-is-a-trap..html) — 24/7 Wall St.
- [This $222 Billion Vanguard ETF Is Trailing the S&P 500. That Almost Never Happens.](https://finance.yahoo.com/m/353aa2d7-3672-3f6c-82ce-de434d7c6973/this-%24222-billion-vanguard.html) — 24/7 Wall St.

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 283.40 ▲5.11% |
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
- [Arm Gains Ground in AI Servers](https://finance.yahoo.com/technology/ai/articles/arm-gains-ground-ai-servers-180039110.html) — GuruFocus.com
- [ARM Stock Takes A Breather After Three Days Of Gains — Wells Fargo Cuts Price Target, Warning Of A 'Tough Setup' Ahead](https://finance.yahoo.com/m/02cdc784-5218-3754-b1cd-3d70758bd747/arm-stock-takes-a-breather.html) — Stocktwits
- [Prediction: Up 144% YTD, Is Arm Holdings The Next Nvidia?](https://finance.yahoo.com/m/d50c8765-a181-3f5d-af95-e594221a0962/prediction%3A-up-144%25-ytd%2C-is.html) — 24/7 Wall St.

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 124.57 ▼6.10% |
| Market Cap | $286.02B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.1% / 38.1% / 43.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 35.29 |
| Beta | 1.56 |
| 52-Week | 106.37 – 207.52 |
| Div. Yield | — |

**Recent News:**
- [Peter Thiel Turned a $2,000 Roth IRA Into $5 Billion and Will Never Owe a Penny of Tax. The Same Rules Apply to Your Account](https://finance.yahoo.com/m/634a7070-ae9f-3406-b94d-fa1a3431ecdb/peter-thiel-turned-a-%242%2C000.html) — 24/7 Wall St.
- [This 1 Momentum ETF Is Still Beating the S&P 500 With Lower Drawdowns](https://finance.yahoo.com/m/decdd59c-3cb8-378a-a2a8-ebe6b1bdc328/this-1-momentum-etf-is-still.html) — 24/7 Wall St.
- [After a Tough Day, ServiceNow Reports Solid Earnings](https://finance.yahoo.com/m/31088c05-a161-3384-aa17-c20601fdddd9/after-a-tough-day%2C-servicenow.html) — Barrons.com

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 30.56 ▲28.24% |
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
- [Dow Jones Futures Rise; Google, Tesla Fall On Earnings, Capex, But AI Stocks Climb](https://finance.yahoo.com/m/092ff924-f233-311d-95de-ed11a4dabc57/dow-jones-futures-rise%3B.html) — Investor's Business Daily
- [Stock Market Today, July 22: Nasdaq Slides Prior to Tesla and Alphabet's Earnings After Market Close](https://finance.yahoo.com/m/b77196bf-999e-3011-889b-0283fcf14e7c/stock-market-today%2C-july-22%3A.html) — Motley Fool
- [Is Dell Technologies (DELL) Undervalued On AI Server Volatility?](https://finance.yahoo.com/markets/stocks/articles/dell-technologies-dell-undervalued-ai-210916868.html) — Simply Wall St.

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 374.01 ▼1.30% |
| Market Cap | $1.40T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.1% / 5.0% / 4.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 14.38 |
| Beta | 1.80 |
| 52-Week | 297.82 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures Rise; Google, Tesla Fall On Earnings, Capex, But AI Stocks Climb](https://finance.yahoo.com/m/092ff924-f233-311d-95de-ed11a4dabc57/dow-jones-futures-rise%3B.html) — Investor's Business Daily
- [Tesla shares fall as Musk touts ambitious -- and costly -- plans](https://finance.yahoo.com/markets/stocks/articles/tesla-shares-dip-profit-misses-210534033.html) — AFP
- [Market Chatter: Tesla Received Reasonable-Terms Chip Supply From Micron, Musk Says](https://finance.yahoo.com/markets/stocks/articles/market-chatter-tesla-received-reasonable-000108352.html) — MT Newswires

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 687.03 ▲0.71% |
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
- [Brent Sullivan: Why 351 Exchange ETFs Are Now Everywhere](https://finance.yahoo.com/m/1b34c342-6e8e-3d8c-8af0-18270b15fc81/brent-sullivan%3A-why-351.html) — etf.com
- [This $222 Billion Vanguard ETF Is Trailing the S&P 500. That Almost Never Happens.](https://finance.yahoo.com/m/353aa2d7-3672-3f6c-82ce-de434d7c6973/this-%24222-billion-vanguard.html) — 24/7 Wall St.
- [Everyone’s Launching an ETF… But Should They?](https://finance.yahoo.com/m/362b524f-6186-3800-8dd4-1cc88f1bd363/everyone%E2%80%99s-launching-an-etf%E2%80%A6.html) — etf.com

## 🌍 News

### 🌍 World News
> `2026-07-23 09:00:21`

- [US signs landmark nuclear deal with Saudi Arabia](https://www.bbc.co.uk/news/articles/cj03r59z73po?at_medium=RSS&at_campaign=rss)
- [Trump threatens to target Iran's bridges and power plants if Hormuz attacks persist](https://www.bbc.co.uk/news/articles/cdrv0p37k8jo?at_medium=RSS&at_campaign=rss)
- [Tankers make sharp U-turns after Houthi shipping threat](https://www.bbc.co.uk/news/articles/cn0n127lpzgo?at_medium=RSS&at_campaign=rss)
- [Russia's businesses under strain from Ukraine's attacks on Wildberries](https://www.bbc.co.uk/news/articles/cvg9n2y61w6o?at_medium=RSS&at_campaign=rss)
- [Fire kills 10 members of same family in Peru, police say](https://www.bbc.co.uk/news/articles/cm2g11ng7j2o?at_medium=RSS&at_campaign=rss)
- [British woman jailed for blackmail after accusing banker of rape in Hong Kong](https://www.bbc.co.uk/news/articles/cz97gdjgezno?at_medium=RSS&at_campaign=rss)
- [Canada's 'powerful' dairy sector is in Trump's trade crosshairs](https://www.bbc.co.uk/news/articles/ce8kvm84lxmo?at_medium=RSS&at_campaign=rss)
- [Wreckage of Pan Am plane that shaped aviation safety found 74 years on](https://www.bbc.co.uk/news/articles/cdrvyllxj71o?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-07-23 09:00:44`

#### AI Tips
Here’s your tailored photography expert advice for **July 23, 2026** in Taiwan.

---

#### 【購買優惠】Best Places & July Sale Tips

**1. Best places to buy camera gear in Taiwan (ranked by value & safety)**

- **PChome 24h / momo購物網** – Best for **new releases & fast delivery**. Use a credit card with high rebate (e.g., 2–3% cashback or 0% installment). *Watch for “品牌日” (Brand Days) – Sony, Canon, Nikon often have 5–10% off + gift vouchers.*
- **光華商場 (Guanghua Digital Plaza)** – Best for **price negotiation & accessories**. Go on a weekday afternoon. Ask for “現金價” (cash price) – you can save 3–8% vs. listed price. *Avoid buying gray-market lenses here unless you know the shop’s warranty policy.*
- **日本代購 (Japan Proxy / Buyee, ZenMarket)** – Best for **rare or high-end lenses** (e.g., Nikon Z 400mm f/2.8). Current JPY/TWD rate is favorable (approx. 0.21). Add 10% for shipping + customs. *Only for items with >15% price gap after fees.*
- **二手 (Used – DCView, 蝦皮, 臉書社團)** – Best for **budget bodies & vintage glass**. Check shutter count (use free tools like EOSInfo for Canon). *Avoid buying used Sony A7III now – many have sticky shutter issues from 2024 batches.*

**2. July seasonal sale tips**

- **Mid-year clearance (年中慶)** is active now at **PChome & momo**. Look for “夏日攝影節” banners. Typical deals:
  - Entry-level mirrorless (Sony ZV-E10, Canon R50) – **10–15% off** + free SD card.
  - Tripods & filters – **20–30% off** (e.g., Manfrotto, NiSi).
- **光華商場** – July is slow for them. *Negotiate harder* – say “我在PChome看到更便宜” (I saw a lower price on PChome). They’ll often match or beat it by 2

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-07-23 09:00:50`

#### AI Tips
Here’s a practical, Taiwan-focused answer for July 2026.

---

**【購買優惠 – Best Places & July Tips】**

**1. Top places to buy in Taiwan (July 2026)**

- **實體店 (Physical Stores):**  
  - **台北:** 內湖「潛水者之家」、八德路「海人潛水」— 庫存深，可試穿尺寸。  
  - **台中:** 西屯「潛水王國」— 常有過季折扣。  
  - **墾丁:** 恆春「潛水客棧」— 適合現場買配件，但價格偏高。  
- **線上 (Online):**  
  - **PChome 24h / 蝦皮商城** — 搜尋「潛水裝備」並篩選「商城」確保正品。  
  - **Facebook 社團:** 「台灣潛水裝備二手交流」、「Dive Gear Taiwan Buy & Sell」— 7月很多人出清二手裝備（因換季或升級），可撿便宜。  
- **July 2026 季節優惠提醒:**  
  - **百貨年中慶** (如新光三越、SOGO) 通常到7月底，部分潛水品牌（如Mares、Cressi、Suunto）可能配合滿千送百。  
  - **墾丁/小琉球店家** 7月是旺季，新裝備折扣少，但「租借轉購買」方案划算（例如租3天面鏡，租金可全抵買新）。  

**2. July seasonal sale & diving notes for Taiwan/Asia**

- **台灣7月潛水季:**  
  - 水溫約26–29°C，穿3mm防寒衣或水母衣即可。  
  - **注意:** 7月是颱風

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-07-23 09:00:37`

#### AI Flight Tips — July
Here are specific, actionable flight deal tips for July 2026 departures from Taiwan (TPE/TSA):

**Japan (Tokyo/Osaka/Sapporo)**  
- **Peak:** High season (summer holidays, Obon in mid-August).  
- **Book:** 8–12 weeks out; last-minute deals are rare in July.  
- **Cheapest:** Peach Aviation (TPE–KIX/TPE–NRT) or Jetstar Japan; consider flying to KIX (Osaka) then taking a domestic LCC to Sapporo.  
- **Deals:** Watch for Peach’s “Happy Peach” flash sales (usually 2–3 weeks before departure) and ANA’s “Experience Japan” fare for foreign visitors.

**Thailand (Bangkok/Chiang Mai)**  
- **Off-peak:** July is rainy season, so demand is lower.  
- **Book:** 4–6 weeks ahead; good last-minute availability.  
- **Cheapest:** Thai Lion Air (TPE–DMK) or AirAsia (TPE–CNX); often under $150 round-trip.  
- **Deals:** AirAsia’s “Big Sale” typically runs in late July; check for 30–40% off base fares.

**Europe (any major city)**  
- **Peak:** July is absolute peak; prices are 40–60% higher than May/September.  
- **Book:** 12–16 weeks in advance (by late April/May) for best rates; now is late but still check.  
- **Cheapest:** China Airlines or EVA Air via Taipei (TPE) to London/Amsterdam/Paris; consider a stopover in Bangkok (BKK) on Thai Airways for lower fares.  
- **Deals:** Look for “Summer Sale” on Turkish Airlines (via IST) or Emirates (via DXB); also check Scoot’s “Escape” sale for budget options (SIN stopover).

**USA (West Coast/East Coast)**  
- **Peak:** July is high season, especially for West Coast (LAX/SFO).  
- **Book:** 10–14 weeks ahead; East Coast (JFK/EWR) slightly easier to find deals.  
- **Cheapest:** EVA Air (TPE–LAX/SFO) often beats China Airlines; for East Coast, consider a connection via Seoul (ICN) on Korean Air or via Tokyo (NRT) on Zipair (budget).  
- **Deals:** Zipair Tokyo frequently offers TPE–NRT–LAX for under $500 one-way; check their “Flash Sale” every Tuesday.

**Egypt (Cairo)**  
- **Off-peak:** July is extremely hot (40°C+), so tourism is low—good for deals.  
- **Book:** 6–8 weeks ahead; avoid last-minute due to limited direct options.  
- **Cheapest:** Fly EgyptAir (TPE–CAI via BKK) or Turkish Airlines (via IST); often $600–800 round-trip.  
- **Deals:** EgyptAir’s “Summer Escape” promotion (usually 20% off for July travel) ends in early July; also check Qatar Airways’ “Stopover in Doha” deals.

**

### 🗺️ Travel Deals
> `2026-07-23 09:00:28`

#### r/solotravel
- [Weekly Destination Thread - Egypt](https://www.reddit.com/r/solotravel/comments/1v1wzec/weekly_destination_thread_egypt/)
- [After action report: Solo trip to Europe](https://www.reddit.com/r/solotravel/comments/1v2uswf/after_action_report_solo_trip_to_europe/)
- [Planning my first Europe solo trip (Germany,Poland,Czech Republic), looking for advice.](https://www.reddit.com/r/solotravel/comments/1v3ilbn/planning_my_first_europe_solo_trip/)
- [Advice second solo trip (Beijing China, or Thailand)](https://www.reddit.com/r/solotravel/comments/1v3o3ke/advice_second_solo_trip_beijing_china_or_thailand/)
- [North of Europe around Christmas?](https://www.reddit.com/r/solotravel/comments/1v2wl4s/north_of_europe_around_christmas/)

## 📚 Learning

### 📚 Learning — Finance
> `2026-07-23 09:00:54`

#### 📚 Today's Concept: Enterprise Value (EV) and EV/EBITDA

What it is: Enterprise Value (EV) is the total theoretical cost to buy an entire company, calculated as market capitalization plus debt minus cash. EV/EBITDA compares that purchase price to the company’s earnings before interest, taxes, depreciation, and amortization—essentially its operating cash flow.

Why it matters: EV/EBITDA lets you compare companies with different debt levels or capital structures more fairly than P/E. It’s widely used in acquisitions and for valuing capital-intensive businesses like manufacturing or telecoms.

Example: Company A has a market cap of $500M, $200M in debt, and $50M cash → EV = $500M + $200M - $50M = $650M. Its EBITDA is $100M → EV/EBITDA = 6.5x. If Company B has the same market cap but $0 debt and $50M cash, its EV = $450M, and with the same EBITDA, its multiple is 4.5x—showing A is relatively more expensive.

Rule of thumb: An EV/EBITDA below 10x is often considered cheap for stable industries; above 15x may signal overvaluation or high growth expectations. Warning sign: if EBITDA is negative, the ratio is meaningless—check free cash flow instead.

### 🧩 LeetCode Blind 100
> `2026-07-23 09:00:59`

#### 🧩 Blind 100 — 424. Longest Repeating Character Replacement [Sliding Window]
**連結:** https://leetcode.com/problems/longest-repeating-character-replacement/
> 📅 **Today's Daily Challenge:** #3824 Number of Unique XOR Triplets I [Medium] — Tags: Array, Math, Bit Manipulation — https://leetcode.com/problems/number-of-unique-xor-triplets-i/

## 424. Longest Repeating Character Replacement

**Problem Type:** Sliding Window / Frequency Map

**Key Insight:** The window is valid if `window_size - max_freq <= k`. We don't need to shrink the window when max_freq changes—only the window size matters for the answer.

**Approach:**
1. Use two pointers `l, r` to maintain a sliding window
2. Track character frequencies in a dict/array
3. Track `max_freq` of any character in current window
4. Expand `r` rightward; if `(r-l+1) - max_freq > k`, shrink from left
5. Update answer as `max(ans, r-l+1)` after each expansion

**Python3 Solution:**
```python
class Solution:
    def characterReplacement(self, s: str, k: int) -> int:
        count = [0] * 26
        l = max_freq = ans = 0
        
        for r in range(len(s)):
            count[ord(s[r]) - ord('A')] += 1
            max_freq = max(max_freq, count[ord(s[r]) - ord('A')])
            
            while (r - l + 1) - max_freq > k:
                count[ord(s[l]) - ord('A')] -= 1
                l += 1
                # No need to update max_freq here—only matters for answer
                
            ans = max(ans, r - l + 1)
        
        return ans
```

**Complexity:** Time O(n) | Space O(1) (fixed 26 chars)

**Blind 100 Note:** Classic sliding window with frequency tracking. Tests understanding of when to shrink vs. expand. Similar: *Longest Substring Without Repeating Characters*, *Minimum Window Substring*.

**Contest Tips:**
- Don't recalculate `max_freq` on shrink—it can only decrease, and we only care about the largest window we've seen
- Use array of 26 ints instead of dict for O(1) space and faster access
- Edge case: k >= len(s) → answer is len(s)
- Edge case: all same character → answer is len(s)

### 📷 Learning — Photography
> `2026-07-23 09:01:06`

#### 📷 Today's Concept: Light — Using Reflectors and Diffusers

**What it is:** A reflector bounces existing light onto your subject to fill shadows or add catchlights; a diffuser softens harsh light by scattering it through a translucent panel. Both are portable tools that shape light without adding artificial sources.

**Why it matters:** They give you control over contrast and mood—turning harsh midday sun into flattering, even light or adding a subtle glow to a portrait’s eyes—without expensive gear.

**How to apply it:**
1. **Position the reflector** opposite your main light source (e.g., sun) to bounce fill light into shadowed side of the face.
2. **Use a diffuser** held between the sun and your subject to soften shadows and reduce squinting—ideal for portraits.
3. **For street or landscape**, use a silver reflector to add a specular highlight to eyes or a white one for a natural fill.
4. **In cinematic video**, place a diffuser close to the subject for a soft, wrap-around light that mimics overcast skies.
5. **Adjust distance**—closer = stronger fill/softer diffusion; farther = subtler effect.

**Sony A7C tip:** Enable **Zebra (Menu > Camera Settings > Zebra)** set to 100% to spot blown highlights when bouncing silver reflectors—adjust distance or angle to keep skin detail.

**Common mistake:** Placing the reflector too far from the subject, creating weak, unusable fill. *Fix:* Hold it within arm’s length of the face for effective bounce.

### 📚 Learning — Tech
> `2026-07-23 09:01:01`

#### 📚 Today's Concept: Blue-Green vs Canary Deployments

**Blue-Green vs Canary Deployments**

**What it is:** Blue-Green runs two identical environments (Blue = live, Green = staging) and switches traffic instantly via router. Canary gradually shifts a small percentage of users to a new version, monitoring for errors before full rollout.

**When to use it:** Blue-Green for zero-downtime swaps when you need immediate rollback (e.g., e-commerce checkout update). Canary for risk-sensitive features where you want real user validation before full release (e.g., a new recommendation algorithm).

**Example:**  
*Blue-Green:* Swap DNS from Blue to Green after smoke tests.  
*Canary:* Deploy v2 to 5% of servers, then increase to 50% if error rate < 0.1%.

**Gotcha:** Blue-Green can cause database schema incompatibility if both versions write to the same DB; Canary can mask regional failures if the small sample isn’t geographically diverse.

### 🎬 Learning — YouTube
> `2026-07-23 09:01:10`

#### 🎬 今日主題：剪輯 — J-Cut 和 L-Cut：讓影片剪輯流暢的技巧
**類別：** 剪輯

**是什麼：**  
J-Cut 是讓聲音先於畫面出現，L-Cut 則是畫面先切換、聲音延續。兩者都能讓剪輯過渡更自然，避免生硬切換。

**為什麼重要：**  
對初學者來說，這能讓影片節奏更流暢，觀眾不會因畫面跳動而出戲，提升觀看完成率。

**怎麼做：**  
1. 在剪輯軟體中，將音軌與視軌分開處理。  
2. 想做 J-Cut：先將下一段聲音拖到前一段畫面結束前 1-2 秒。  
3. 想做 L-Cut：讓前一段聲音延續到下一段畫面開始後 1-2 秒。  
4. 調整音量交叉淡出/淡入，避免突兀。  
5. 預覽並微調時間點，直到聽覺與視覺自然銜接。

**新手常犯的錯：**  
只剪畫面不剪聲音，導致對話或背景音突然中斷。**解決方式**：養成先對齊音軌再調整畫面的習慣。

**延伸 idea：**  
拍攝「一天用 AI 剪輯工具完成一支旅遊 Vlog」的實戰影片，邊剪邊解說 J-Cut / L-Cut 的應用，適合攝影與生活頻道。

## 🛂 Immigration

### 🇦🇺 Australia Immigration
> `2026-07-23 09:01:15`

- [Student Visas Mega Thread](https://www.reddit.com/r/AusVisa/comments/1uo2jha/student_visas_mega_thread/)
- [Visa 189 (PR) granted](https://www.reddit.com/r/AusVisa/comments/1v3hbkn/visa_189_pr_granted/)
- [190 Granted](https://www.reddit.com/r/AusVisa/comments/1v3rpe3/190_granted/)
- [Visa Granted 🧿🥳](https://www.reddit.com/r/AusVisa/comments/1v3hsyv/visa_granted/)
- [Subclass 600 - granted for russian 🤯](https://www.reddit.com/r/AusVisa/comments/1v3kxka/subclass_600_granted_for_russian/)
