---
date: 2026-11-16
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "savings_travel", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube", "immigration_au"]
---

# Daily Digest — 2026-11-16

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

- **台股重挫 3.59% 至 42,108**，跌幅遠超美股（-0.76%）與日股（-1.57%），明顯是台灣本地科技/半導體賣壓主導；同時 AMD -8.75%、Arm -6.31%、SMCI -11.72%，AI 半導體全面回檔 — 若你持有台股或相關供應鏈部位，今天是檢視風險敞口的日子。
- **Google 發布 Gemini 4 Hydrogen**，同步升級全球 Search 並開放開發者用於 coding / agentic workflow；另有 **A2UI 1.0**（生成式 UI 開放協議）與 **Gemini Decisions API** — 對做 agent 或前端整合的工程師是本週最值得實測的一批工具。[Search](https://blog.google/products-and-platforms/products/search/gemini-4-hydrogen-search-upgrade/) · [Dev](https://blog.google/innovation-and-ai/technology/developers-tools/build-with-gemini-4-hydrogen/) · [A2UI](https://developers.googleblog.com/a2ui-10-build-delightful-fast-reliable-agentic-experiences/)
- **AI coding agent 開始碰硬體**：有人用 Claude Code + Codex 逆向 1994 Jeep ECU（$3 Arduino），搭配 HN 熱帖「AI 生成的程式碼都該開源」（1103 分）— 授權與 provenance 的爭論會延燒，值得先想好你團隊的 policy。[影片](https://www.youtube.com/watch?v=WPj3aQ-xxpI) · [HN 討論](https://jakub.jankiewicz.org/blog/ai-code-open-source/)
- **11 月下旬是採購窗口**：攝影（黑五 11/27 前後 momo/PChome 第二波）與潛水（東北季風淡季議價 + 黑五線上折扣）都指向同一時間點；機票方面歐洲/埃及 11 月是 Q4 最便宜月份，但日本 11/21–23 勞動節連假與清邁 Yi Peng 期間票價會飆。[相機指南] · [潛水指南] · [機票速查]
- **求職市場訊號**：HN「Who is Hiring?」貼文量接近 12 年低點，AI 已滲透半數職缺 — 若你在觀望轉職或澳洲技術移民（189/190/491），現在更該盯 invitation rounds 與各州 nomination 名單。[HN Trends](https://www.hntrends.com/2026/november.html) · [r/AusVisa megathread](https://www.reddit.com/r/AusVisa/comments/1wtaedi/megathreads_subclass_discussions/)

---

- 💻 **Tech**：Gemini 4 Hydrogen 上線、A2UI 1.0 開放協議、LLM positional embedding 深度文、多 agent 記憶與安全設計研究齊發；AI coding agent 已能動硬體。
- 🤖 **AI 公司動態**：今日無 OpenAI/Anthropic 消息；Nvidia CEO 人事傳聞、SpaceX 首次「機械筷子」從軌道接住 Starship（booster 落海）。
- 🔵 **Google**：Gemini 4 Hydrogen 全面鋪開（Search + 開發者）、Gemini Decisions API、A2UI 1.0、on-device ASR/TTS、TPU 長上下文訓練（14M tokens）。
- 📈 **Markets**：台股 -3.59% 領跌，S&P -0.76%、Nikkei -1.57%，亞太全面 risk-off 但台灣跌幅異常放大。
- 📊 **Watchlist**：AI 半導體重災（AMD -8.75%、Arm -6.31%、SMCI -11.72%），NVDA 僅 -2.01%；Meta +2.90%、AVGO +0.52% 抗跌；估值欄位全 N/A。
- 🏠 **台灣房市**：量縮價穩、區域分化；外圍新成屋議價空間 5–10%，蛋黃區高總價仍有高資產族承接但流通性差。
- 🌍 **World**：澤倫斯基促美方與 Musk 解除 Starlink 限制；Nvidia 前高層相關中國間諜疑雲（Megaspeed）；墨西哥毒梟

---

## 💻 Tech

### 💻 Tech & AI
> `2026-11-16 10:55:26`

#### Hacker News
- [Tor Project Issues Rapid-Response DoS-Defense Fix Amid Sustained DDoS Attack](https://forum.torproject.org/t/security-release-0-4-9-17/22454) ⭐46
- [A short explainer on how El Niño works [video]](https://www.youtube.com/watch?v=7_JF3etiAv8) ⭐184
- [WebGL Flight Simulator with seed generated terrain](https://baron.by.dai.studio/) ⭐96
- [Claude Code and Codex reverse engineered my 1994 Jeep's ECU over a $3 Arduino [video]](https://www.youtube.com/watch?v=WPj3aQ-xxpI) ⭐355
- ["Who is Hiring?" postings stuck near 12-year lows as AI reaches half of all jobs](https://www.hntrends.com/2026/november.html) ⭐60
- [Understanding Positional Embeddings in Modern LLMs](https://magazine.sebastianraschka.com/p/understanding-positional-embeddings) ⭐213
- [Vulcan rocket fails during return-to-flight launch, 40 Amazon satellites lost](https://www.space.com/space-exploration/launches-spacecraft/ula-vulcan-centaur-return-to-flight-amazon-leo-internet-satellite-launch) ⭐122
- [All AI-generated code should be Open Source](https://jakub.jankiewicz.org/blog/ai-code-open-source/) ⭐1103
- [Keylogger Detection and Containment [pdf]](https://www.cs.vu.nl/~ast/Theses/ortolani-thesis.pdf) ⭐20
- [Boeing-Lockheed rocket fails mid-flight, destroys payload of Amazon satellites](https://www.reuters.com/business/aerospace-defense/us-rocket-fails-after-launch-payload-amazon-internet-satellites-destroyed-2026-11-15/) ⭐70

#### HuggingFace
- [Who Remembers What? Multi-Granularity Memory Extraction for Multi-User, Multi-Agent Interaction](https://huggingface.co/papers/2611.10439)
- [EgoX: Egocentric Cross-Embodiment Manipulation with Embodiment Dreaming](https://huggingface.co/papers/2611.16728)
- [Back to Pixels: Lifting Latent Video Diffusion into Pixel Space](https://huggingface.co/papers/2611.17336)
- [Consensus Capture in Reference-Based UAV Video Stabilization: A Benchmark on Dynamic Urban Scenes](https://huggingface.co/papers/2611.17190)
- [TurtLES: A Large-Scale Benchmark for Turbulent 3D Neural PDE Surrogates](https://huggingface.co/papers/2611.09567)
- [The Value of Thinking: Learning When to Reason in Hybrid Decision Models](https://huggingface.co/papers/2611.16961)

#### ArXiv
- [AmbiSteer: Selectively Eliciting Ambiguity-Aware Responses in Vision-Language Models](http://arxiv.org/abs/2611.17900v1)
- [More Genes, Faster Inference: Efficient Large-Panel Spatial Transcriptomics Prediction from Histology](http://arxiv.org/abs/2611.17899v1)
- [Hierarchical Bayesian physics-augmented neural networks for populations of hyperelastic laws: specimen variability and uncertainty from scarce, noisy data](http://arxiv.org/abs/2611.17892v1)
- [Quantum Graph Neural Networks: Architectures, Trainability, and Applications](http://arxiv.org/abs/2611.17886v1)
- [Securing Multi-Agent Systems by Design](http://arxiv.org/abs/2611.17883v1)
- [Photogrammetric 3D Model-Based Animal Behavior Classification](http://arxiv.org/abs/2611.17881v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-11-16 10:55:33`

#### Tesla
- [Nvidia stock steady as Jensen Huang reportedly weighs CEO comeback, Musk backs return](https://finance.yahoo.com/markets/article/nvidia-stock-steady-as-jensen-huang-reportedly-weighs-ceo-comeback-musk-backs-return-015644730.html)
- [Consumer Defensive Stocks Extend Winning Streak To 6 Weeks As SPY, QQQ Rebound: TTD, CHTR, TSLA Lead Gains](https://finance.yahoo.com/markets/stocks/articles/consumer-defensive-stocks-extend-winning-011320620.html)
- [Jensen Huang may return as Nvidia chief executive - report](https://finance.yahoo.com/markets/stocks/articles/jensen-huang-may-return-nvidia-210940404.html)
- [SpaceX caught Starship from orbit with ‘robot chopsticks’ in a world 1st — but lost its booster in the Gulf of Mexico](https://finance.yahoo.com/markets/stocks/articles/spacex-caught-starship-orbit-robot-180500736.html)

### 🔵 Google 動態
> `2026-11-16 10:55:30`

#### Google AI Blog
- [Google Search gets a major upgrade with Gemini 4 Hydrogen](https://blog.google/products-and-platforms/products/search/gemini-4-hydrogen-search-upgrade/)
- [Gemini Decisions API: Fast, calibrated multimodal decisions](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/)
- [Try Tabletop: Customizable, collaborative spaces for groups to plan, play and do more together.](https://blog.google/innovation-and-ai/models-and-research/google-labs/tabletop/)
- [Experience the art and legacy of Dr. Esther Mahlangu](https://blog.google/company-news/outreach-and-initiatives/arts-culture/esther-mahlangu/)
- [Gemini Intelligence: New features, on more devices](https://blog.google/products-and-platforms/platforms/android/gemini-intelligence-november-features-devices/)
#### Google Blog
- [Claim your Google Cloud Credits in Google AI Studio](https://blog.google/innovation-and-ai/technology/developers-tools/google-cloud-credits-gdp-ai-studio/)
- [Connect Google Wallet to Gemini for personal finance insights](https://blog.google/innovation-and-ai/products/gemini-app/google-wallet-gemini-app/)
- [5 new Google Flow Tools designed by visual artists](https://blog.google/innovation-and-ai/models-and-research/google-labs/new-google-flow-tools/)
- [Google Search gets a major upgrade with Gemini 4 Hydrogen](https://blog.google/products-and-platforms/products/search/gemini-4-hydrogen-search-upgrade/)
- [Gemini 4 Hydrogen: everyday coding and agentic workflows for developers](https://blog.google/innovation-and-ai/technology/developers-tools/build-with-gemini-4-hydrogen/)
#### Google Developers
- [Catch Go bugs that fuzzing misses with Gemini and a constraint solver](https://developers.googleblog.com/catch-go-bugs-that-fuzzing-misses-with-gemini-and-a-constraint-solver/)
- [How Agent Anomaly Detection scores on benchmarks we didn't write](https://developers.googleblog.com/how-agent-anomaly-detection-scores-on-benchmarks-we-didnt-write/)
- [A2UI 1.0: Build delightful, fast, reliable, agentic experiences](https://developers.googleblog.com/a2ui-10-build-delightful-fast-reliable-agentic-experiences/)
- [On-Device Speech Recognition and Text-to-Speech in Google AI Edge Gallery](https://developers.googleblog.com/on-device-speech-recognition-and-text-to-speech-in-google-ai-edge-gallery/)
- [Announcing Long-Context Training on TPUs with MaxText Context Parallelism](https://developers.googleblog.com/announcing-long-context-training-on-tpus-with-maxtext-context-parallelism/)

## 📈 Finance

### 📈 Markets Overview
> `2026-11-16 10:55:36`

#### Indices
- S&P 500: 7,561.67 ▼0.76%
- 台股加權: 42,108.35 ▼3.59%
- 日經 225: 60,182.50 ▼1.57%

### 🏠 台灣房市
> `2026-11-16 10:56:37`

#### AI 分析
## 台灣房市速評（2026-11-16）

**1. 整體趨勢**
央行選擇性信用管制持續，投資買盤退場，市場回歸自住剛需；成交量低檔盤整，但蛋黃區高總價產品仍有支撐，呈現「量縮價穩、區域分化」格局。預售讓利與中古屋議價空間同步擴大，買方市場氛圍成形。

**2. 值得注意的訊號**
- **高總價成交仍活躍**：實價登錄 115S3 出現多筆 5,700 萬～2.9 億住宅大樓交易，單價 27～46 萬/㎡（約 8.9～15 萬/坪），顯示蛋黃區大坪數、高樓層景觀戶仍有高資產族承接，但這類產品流通性差、貸款成數受限，非一般自住客戰場。
- **租屋掛牌集中中山、內湖**：林森北路、松江路、金湖路皆為捷運沿線小宅／3房，反映市中心租賃需求穩定，但供給量也大，租金漲幅有限。
- **外圍新案讓利明顯**：金山全新3房+平車、中壢體育園區透天、桃園中平龍安商圈大坪數三房——這類「低總價、外圍、新成屋」是當前建商與屋主議價意願最高的區塊，適合撿便宜但要注意生活機能與轉手性。

**3. 對自住者建議**
- 現在是**議價黃金期**：外圍新成屋、中古大樓可從實價登錄最低價再往下談 5～10%，優先鎖定捷運站 800 公尺內、屋齡 10 年內物件。
- 避開「大坪數高總價」與「偏遠全新透天」：前者貸款成數低、後者轉手困難，自住要考慮未來 10 年脫手性。

**4. 對投資者建議**
- 短線炒作空間已消失，**租金投報率**才是核心：中山、內湖捷運小宅投報約 2～2.5%，優於高總價產品，但需精算管理成本。
- 若布局中長期，可留意**桃園中壢體育園區、台中大慶車站**周邊——軌道建設+新興重劃區，單價仍在 3 字頭以下，具補漲空間，但需承受 2～3 年盤整期。

**5. 風險提醒**
高總價成交單價離散

#### 591 最新
- [台北市中山區林森北路🔥MRT善導寺站🔥高樓景觀豪邸｜採光3房｜24H管理](https://rent.591.com.tw/rent-detail-21738032.html)
- [台北市中山區松江路N35租行天宮/松江南京站近捷運裝潢佳](https://rent.591.com.tw/rent-detail-21479485.html)
- [台北市內湖區金湖路363巷🔥MRT葫洲站🔥採光2房｜垃圾代收｜平車｜](https://rent.591.com.tw/rent-detail-22169735.html)
- [台中市南區東興路一段|立彩建設|南區|大慶車站|輕屋齡|兩房平車](https://sale.591.com.tw/sale-detail-21264401.html)
- [桃園市中壢區龍岡路二段321巷⭐️中壢體育園區透天，室內停車，7米巷寬，即可入住⭐️](https://sale.591.com.tw/sale-detail-21264448.html)
- [台北市大安區復興南路二段捷運科技~高樓景觀管理大樓~住商黃美端](https://sale.591.com.tw/sale-detail-21264447.html)
- [新北市金山區中華路金山全新未住3房+平面車位](https://sale.591.com.tw/sale-detail-21264444.html)
- [桃園市桃園區中山路愛買武陵高中中平龍安商圈稀有大坪數三房](https://sale.591.com.tw/sale-detail-21264443.html)

#### 實價登錄 (115S3) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 住宅大樓(11層含以上有電梯) | 963.3㎡ | 29664萬 | 307937元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 399.6㎡ | 14468萬 | 449312元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 379.7㎡ | 10438萬 | 274908元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 267.7㎡ | 8558萬 | 367305元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 144.7㎡ | 5700萬 | 456525元/㎡ |

### 📊 Watchlist
> `2026-11-16 10:56:09`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 162.85 ▼2.01% |
| Market Cap | $3.92T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.7% / 65.2% / 63.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 17.20 |
| Beta | 2.22 |
| 52-Week | 148.80 – 243.37 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures Waver As Jensen Huang Mulls Nvidia Return](https://finance.yahoo.com/m/53e50dc8-f137-3f6c-bfd6-912334fef9f1/dow-jones-futures-waver-as.html) — Investor's Business Daily
- [Nvidia Stock Is Down About a Third From Its October Peak. Here's My Estimate for 2030.](https://finance.yahoo.com/markets/stocks/articles/nvidia-stock-down-third-october-024302210.html) — Motley Fool
- [Jensen Huang Reportedly Considers Returning To Nvidia: FT](https://finance.yahoo.com/m/694d3941-721c-31d4-aff5-d306f1116454/jensen-huang-reportedly.html) — Investor's Business Daily

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 534.06 ▼8.75% |
| Market Cap | $875.90B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.7% / 17.7% / 16.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 12.78 |
| Beta | 2.49 |
| 52-Week | 188.22 – 658.52 |
| Div. Yield | — |

**Recent News:**
- [Jensen Huang Reportedly Considers Returning To Nvidia: FT](https://finance.yahoo.com/m/694d3941-721c-31d4-aff5-d306f1116454/jensen-huang-reportedly.html) — Investor's Business Daily
- [Advanced Micro Devices (AMD) Deepens Quantum Push With New Research And Commercial Ties](https://finance.yahoo.com/technology/ai/articles/advanced-micro-devices-amd-deepens-001906359.html) — Simply Wall St.
- [Nvidia Rival’s CEO on TSMC: “I Would Buy That Stock Every Day of the Week”](https://finance.yahoo.com/markets/stocks/articles/nvidia-rival-ceo-tsmc-buy-175956534.html) — TIKR

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 523.88 ▲0.17% |
| Market Cap | $3.89T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.7% / 47.1% / 41.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 8.27 |
| Beta | 1.04 |
| 52-Week | 349.20 – 559.15 |
| Div. Yield | — |

**Recent News:**
- [Anthropic's record IPO faces some big questions](https://finance.yahoo.com/technology/ai/articles/anthropics-record-ipo-faces-big-012430589.html) — AFP
- [Americans fear the worst after Pentagon doomsday prepping, ‘Black October’ cyberattacks, stock crash, spy scandal, Microsoft outage, and airport chaos](https://finance.yahoo.com/markets/stocks/articles/americans-fear-worst-pentagon-doomsday-232109128.html) — Fortune
- [Rigetti Computing vs. SoundHound AI: Which Technology Stock Is a Better Buy for 2027?](https://finance.yahoo.com/technology/ai/articles/rigetti-computing-vs-soundhound-ai-192505909.html) — Motley Fool

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 295.77 ▼0.98% |
| Market Cap | $3.60T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.3% / 50.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 5.29 |
| Beta | 1.23 |
| 52-Week | 272.11 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [Morgan Stanley’s Q3 filing reveals $5.6 billion SpaceX stock surprise](https://finance.yahoo.com/markets/stocks/articles/morgan-stanley-q3-filing-reveals-020300597.html) — TheStreet
- [Anthropic's record IPO faces some big questions](https://finance.yahoo.com/technology/ai/articles/anthropics-record-ipo-faces-big-012430589.html) — AFP
- [Why Fervo Energy Stock Surged This Week](https://finance.yahoo.com/energy/articles/why-fervo-energy-stock-surged-190204106.html) — Motley Fool

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 266.66 ▼0.29% |
| Market Cap | $2.88T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 51.4% / 13.1% / 16.9% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.69 |
| Beta | 1.50 |
| 52-Week | 196.00 – 287.20 |
| Div. Yield | — |

**Recent News:**
- [Etsy vs. Five Below: Which Growth Stock Is the Better Buy?](https://finance.yahoo.com/markets/stocks/articles/etsy-vs-five-below-growth-002002013.html) — Motley Fool
- [Rocket from Boeing-Lockheed firm fails mid-flight, destroys payload of Amazon satellites](https://finance.yahoo.com/news/us-rocket-fails-launch-payload-202554696.html) — Reuters
- [Rigetti Computing vs. SoundHound AI: Which Technology Stock Is a Better Buy for 2027?](https://finance.yahoo.com/technology/ai/articles/rigetti-computing-vs-soundhound-ai-192505909.html) — Motley Fool

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 641.69 ▲2.90% |
| Market Cap | $1.64T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.0% / 32.9% / 31.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.01 |
| Beta | 1.28 |
| 52-Week | 520.26 – 779.82 |
| Div. Yield | — |

**Recent News:**
- [Anthropic's record IPO faces some big questions](https://finance.yahoo.com/technology/ai/articles/anthropics-record-ipo-faces-big-012430589.html) — AFP
- [Is Meta Stock Still a Buy After Borrowing About $25 Billion This Month?](https://finance.yahoo.com/markets/stocks/articles/meta-stock-still-buy-borrowing-000701983.html) — Motley Fool

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 347.01 ▲0.52% |
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
- [Jensen Huang Reportedly Considers Returning To Nvidia: FT](https://finance.yahoo.com/m/694d3941-721c-31d4-aff5-d306f1116454/jensen-huang-reportedly.html) — Investor's Business Daily
- [Marvell’s Trillion-Dollar Target](https://finance.yahoo.com/markets/stocks/articles/marvell-trillion-dollar-target-002002774.html) — Motley Fool
- [Nvidia’s Problem: OpenAI Is “90 Plus Percent Nvidia,” and It’s the Lab Burning Cash](https://finance.yahoo.com/technology/ai/articles/nvidia-problem-openai-90-plus-180950788.html) — TIKR

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 190.53 ▼6.31% |
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
- [Jensen Huang discusses comeback as Nvidia CEO with allies, FT reports](https://finance.yahoo.com/markets/stocks/articles/jensen-huang-discusses-comeback-nvidia-192628314.html) — Reuters
- [Astera Labs vs. Arm: Which Technology Stock Is a Better Buy for 2027?](https://finance.yahoo.com/markets/stocks/articles/astera-labs-vs-arm-technology-195402917.html) — Motley Fool
- [Arm vs. ASML: Which Technology Stock Is a Better Buy for 2027?](https://finance.yahoo.com/markets/stocks/articles/arm-vs-asml-technology-stock-172201795.html) — Motley Fool

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 167.99 ▼2.09% |
| Market Cap | $387.50B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.7% / 45.6% / 50.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 35.99 |
| Beta | 1.62 |
| 52-Week | 106.37 – 212.94 |
| Div. Yield | — |

**Recent News:**
- [Top 3 Quality Stocks To Watch In November 2026](https://finance.yahoo.com/markets/stocks/articles/top-3-quality-stocks-watch-100940220.html) — Simply Wall St.
- [Top 3 AI Stocks To Watch In November 2026](https://finance.yahoo.com/technology/ai/articles/top-3-ai-stocks-watch-021005217.html) — Simply Wall St.
- [Peter Thiel’s Longtime Business Partner Says AI Is Absolutely in a Bubble: ‘This Will Correct’](https://finance.yahoo.com/technology/ai/articles/peter-thiel-longtime-business-partner-213007111.html) — Benzinga

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 26.86 ▼11.72% |
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
- [Super Micro Computer (SMCI) Under DOJ Scrutiny Over Alleged Server Smuggling To China](https://finance.yahoo.com/markets/stocks/articles/super-micro-computer-smci-under-190829678.html) — Simply Wall St.
- [Super Micro Gets Swept Up in Spreading Nvidia Scandal. Says Megaspeed Was “Never a Customer”](https://finance.yahoo.com/markets/stocks/articles/super-micro-gets-swept-spreading-163249295.html) — 24/7 Wall St.
- [Super Micro, run by Jensen Huang’s friend, says Megaspeed was ‘never’ its customer](https://finance.yahoo.com/technology/articles/super-micro-run-jensen-huang-234845498.html) — Fortune

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 390.22 ▼1.82% |
| Market Cap | $1.54T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.3% / 3.3% / 3.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 14.16 |
| Beta | 1.74 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Nvidia stock steady as Jensen Huang reportedly weighs CEO comeback, Musk backs return](https://finance.yahoo.com/markets/article/nvidia-stock-steady-as-jensen-huang-reportedly-weighs-ceo-comeback-musk-backs-return-015644730.html) — Yahoo Finance
- [Consumer Defensive Stocks Extend Winning Streak To 6 Weeks As SPY, QQQ Rebound: TTD, CHTR, TSLA Lead Gains](https://finance.yahoo.com/markets/stocks/articles/consumer-defensive-stocks-extend-winning-011320620.html) — Stocktwits
- [Jensen Huang may return as Nvidia chief executive - report](https://finance.yahoo.com/markets/stocks/articles/jensen-huang-may-return-nvidia-210940404.html) — Investing.com

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 693.38 ▼0.71% |
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
- [The Stock Market's Election Day Rally Just Taught Investors a Crucial Lesson](https://finance.yahoo.com/markets/stocks/articles/stock-markets-election-day-rally-123500167.html) — Motley Fool
- [Think politicians have an unfair edge in the stock market? These investments can help you trade the way they do](https://finance.yahoo.com/markets/stocks/articles/think-politicians-unfair-edge-stock-123000103.html) — Moneywise
- [‘65% of the S&P Is Basically AI’: Eisman’s Warning as Ramsey Tells Disabled Veteran His $500,000 Is ‘Safe’](https://finance.yahoo.com/markets/stocks/articles/65-p-basically-ai-eisman-090418551.html) — 24/7 Wall St.

## 🌍 News

### 🌍 World News
> `2026-11-16 10:56:41`

- [Zelensky urges US and Musk to lift Starlink restrictions and be on 'right side of history'](https://www.bbc.co.uk/news/articles/c6m25zg88k45o?at_medium=RSS&at_campaign=rss)
- [Suspected China spy linked to Nvidia's ex-boss left in 2025, Megaspeed says](https://www.bbc.co.uk/news/articles/cmdx1vpprk9vo?at_medium=RSS&at_campaign=rss)
- [Australian MP who lost both legs in alleged car attack discharged from hospital](https://www.bbc.co.uk/news/articles/cmpqr9j81888o?at_medium=RSS&at_campaign=rss)
- [Mexican drug lord Miguel Angel Felix Gallardo dies age 80](https://www.bbc.co.uk/news/articles/c51k9nkwrndxo?at_medium=RSS&at_campaign=rss)
- [Prince Harry praises war veterans on surprise visit to Ukraine](https://www.bbc.co.uk/news/articles/c60evn992jq8o?at_medium=RSS&at_campaign=rss)
- [South Korea's top scorer in tax accountancy exam admits cheating](https://www.bbc.co.uk/news/articles/ckvg2ezvpe08o?at_medium=RSS&at_campaign=rss)
- [Pope Leo rides in helicopter cockpit during Peru trip](https://www.bbc.co.uk/news/videos/c6pw4rl00lrjo?at_medium=RSS&at_campaign=rss)
- [Steering failure preceded New Orleans cruise ship collision, says NTSB](https://www.bbc.co.uk/news/articles/c65y131w1534o?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-11-16 10:56:58`

#### AI Tips
# 📷 2026年11月16日 攝影顧問日報

## 【購買優惠】台灣購機指南

**通路特性速覽**
- **PChome 24h**：到貨最快、常有「品牌日」折價券，適合急用機身/鏡頭；留意「PChome 儲值」加碼回饋。
- **momo**：購物節檔期折扣最深，常搭配信用卡分期 0 利率＋mo 幣回饋；適合買公司貨機身。
- **光華商場（台北）**：可現場試機、議價空間大，水貨/公司貨都有；建議先比價再進場，殺價約 3–5%。
- **日本代購**：日圓匯率有利時，機身/鏡頭價差可達 10–20%，但**無台灣保固**、維修需寄回；適合買已停產或日版限定品。
- **二手（旋轉拍賣、DCView、FB 社團）**：CP 值最高，務必面交驗快門數、感光元件壞點、鏡頭霉斑。

**11月檔期重點**
- **雙11 餘溫**：11/11 後一週仍有「延長加碼」與清庫存價，別急著當天搶。
- **黑色星期五（11/27 前後）**：momo、PChome 會跟進，鎖定「購物車降價通知」。
- **週年慶尾聲**：百貨公司相機櫃（如法雅客）滿額贈＋刷卡回饋，適合買公司貨＋延長保固。
- **實戰建議**：先設好目標型號的「歷史低價」提醒（可用 BigGo 比價），11月下旬黑五再出手。

---

## 【今日攝影技巧】逆光下的「輪廓光」人像

**技巧**：把太陽放在模特兒斜後方（約 45°），讓光線勾出頭髮與肩膀邊緣的亮線，主體正面用反光板或白色牆面補光，避免臉部死黑。測光對「臉部」而非背景，曝光補償 +0.

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-11-16 10:57:03`

#### AI Tips
# 台灣潛水裝備購買指南（2026年11月）

## 購買優惠

**實體店（北台灣）**
- **潛水貨倉（Dive Warehouse）**：台北，代理多品牌，季末出清常有7折
- **海人潛水**：新北，維修服務好，適合買調節器
- **藍鯨潛水**：台中，中南部指標店

**線上**
- **PChome 24h / momo**：適合買配件（蛙鞋扣、防水袋），比價快
- **蝦皮**：找「台灣出貨」賣家，避開中國直郵（關稅+退換麻煩）
- **Facebook社團**：「台灣潛水二手交流」「潛水裝備買賣」— 二手調節器/BCD 可省40-60%，但**務必要求看保養紀錄**

**11月時機點**
- 雙11（11/11）剛過，但**黑色星期五（11/27-30）** 線上店常有第二波折扣，鎖定潛水電腦錶、防水殼
- 台灣東北角進入**東北季風季**（11月-3月），能見度差、浪大 → 店家淡季促銷多，是**議價好時機**，尤其墾丁/小琉球店家會推「淡季裝備組合」
- 東南亞（菲律賓、泰國）11月進入乾季旺季，若計畫出國潛旅，**先在台灣買好輕裝備**（面鏡、蛙鞋、防寒衣），當地租重裝

## 裝備建議（實用保養）

**調節器一級頭：每次潛後用淡水「浸泡」而非「沖洗」**
- 潛完當天，

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-11-16 10:56:53`

#### AI Flight Tips — November
# November Flight Deals from Taiwan (TPE/TSA) — Quick Reference

**Japan (Tokyo/Osaka/Sapporo)**
- November is **peak** for Kyoto/Osaka autumn foliage and early Sapporo ski season; Tokyo is shoulder. Book **4–6 weeks out** for the best fare/availability balance.
- Cheapest: LCCs (Peach, Tigerair Taiwan, Scoot) into Narita/Kansai; for Sapporo, fly Peach/Thai AirAsia X to New Chitose via Osaka or direct charter seats.
- Watch: Peach "Winter Sale" and Tigerair Taiwan flash fares (often Tue–Thu departures); avoid Nov 21–23 (Labor Day weekend in Japan) price spikes.

**Thailand (Bangkok/Chiang Mai)**
- November is **peak** — cool season start, Loy Krathong (late Nov) and Yi Peng in Chiang Mai drive up prices. Book **6–8 weeks ahead**, earlier for Chiang Mai.
- Cheapest: Thai Lion Air, Thai Vietjet, or Scoot via Singapore; direct China Airlines/EVA often price-match on promo.
- Watch: Thai Vietjet 0-baht promos and AirAsia "Free Seat" sales; Chiang Mai flights spike hard around Yi Peng — lock those first.

**Europe (any major city)**
- November is **off-peak** (pre-Christmas lull) — best value month of Q4. Book **8–12 weeks out**; fares bottom ~10 weeks prior.
- Cheapest: China Eastern/China Southern via Shanghai/Guangzhou, or Turkish Airlines via Istanbul; Emirates/Qatar for one-stop with better luggage.
- Watch: Black Friday (Nov 27–30) airline sales — China Airlines and EVA often drop Europe fares 15–25%; also Turkey's low-season Istanbul fares.

**USA (West/East Coast)**
- November is **shoulder-to-peak**: Thanksgiving week (Nov 24–30) is peak; rest of month is off-peak. Book **8–10 weeks out**, or **3–4 weeks** for last-minute off-peak deals.
- Cheapest: China Airlines/EVA direct to LAX/SFO/SEA/ONT; for East Coast, Delta/United via Seoul or Tokyo, or China Airlines direct to JFK/ONT.
- Watch: Black Friday/Cyber Monday sales (EVA, China Airlines, Starlux); avoid departing Nov 20–26 and returning Nov 28–Dec 1.

**Egypt (Cairo)**
- November is **peak** — ideal Red Sea/Cairo weather, high European demand. Book **8–12 weeks ahead**; prices climb steadily after mid-October.
- Cheapest: China Eastern via Shanghai, or Emirates/Qatar via Gulf; EgyptAir direct TPE–CAI is rare — one-stop is standard.
- Watch: Qatar Airways and Emirates November promos; bundle Cairo + Nile cruise packages for better per-day value than separate bookings.

**Australia (Sydney/Melbourne)**
- November is **shoulder-to-peak** — spring, pre-summer rush; fares rise into December. Book **6–10 weeks out**.
- Cheapest: China Airlines/EVA direct to SYD/MEL (competitive on promo); Scoot via Singapore or AirAsia

### 🗺️ Travel Deals
> `2026-11-16 10:56:46`

#### r/solotravel
- [32 F - Looking for help about my thailand trip](https://www.reddit.com/r/solotravel/comments/1xx35tu/32_f_looking_for_help_about_my_thailand_trip/)
- [Japan and southern Thailand in 4 weeks – am I trying to do too much?](https://www.reddit.com/r/solotravel/comments/1xwto04/japan_and_southern_thailand_in_4_weeks_am_i/)
- [Japan cruise, regretting my decision](https://www.reddit.com/r/solotravel/comments/1xu4yfj/japan_cruise_regretting_my_decision/)

## 📚 Learning

### 📚 Learning — Finance
> `2026-11-16 10:57:06`

#### 📚 Today's Concept: Price-to-Book (P/B) Ratio

What it is: The Price-to-Book ratio compares a company's stock price to its book value per share, where book value is total assets minus total liabilities (the accounting net worth). It tells you how much investors pay for each dollar of accounting equity.

Why it matters: It's a quick valuation check for asset-heavy businesses like banks, insurers, and manufacturers, flagging when a stock trades cheap or rich relative to its balance sheet.

Example: A bank has $500M in assets and $450M in liabilities, so book value is $50M. With 10M shares outstanding, book value per share is $5. If the stock trades at $7.50, P/B = 7.50 / 5 = 1.5, meaning investors pay $1.50 for every $1 of equity.

Rule of thumb: A P/B below 1 can signal a bargain or a value trap (bad loans, obsolete assets), so always check why it's cheap; and skip P/B entirely for asset-light software companies, where book value misses the real value—code, talent, and recurring revenue.

### 🧩 LeetCode Blind 100
> `2026-11-16 10:57:10`

#### 🧩 Blind 100 — 46. Permutations [Backtracking]
**連結:** https://leetcode.com/problems/permutations/
> 📅 **Today's Daily Challenge:** #2361 Calculate Digit Sum of a String [Easy] — Tags: String, Simulation — https://leetcode.com/problems/calculate-digit-sum-of-a-string/

**Problem Type:** Backtracking / Permutations (build all orderings via choose → recurse → unchoose)

**Key Insight:** At each position, try every unused number; the "used" set (or in-place swap) prevents repeats. Since all elements are distinct, no dedup logic is needed.

**Approach:**
1. Maintain `path` (current partial permutation) and `used` boolean array.
2. If `len(path) == n`, append a copy of `path` to results.
3. Otherwise, loop over all indices; skip if `used[i]`.
4. Mark `used[i] = True`, append `nums[i]`, recurse, then pop and unmark.
5. (Alternative: in-place swap approach — swap `nums[i]` with `nums[start]`, recurse on `start+1`, swap back.)

**Python3 Solution:**
```python
class Solution:
    def permute(self, nums: List[int]) -> List[List[int]]:
        res = []
        n = len(nums)
        used = [False] * n
        path = []

        def backtrack():
            if len(path) == n:
                res.append(path.copy())
                return
            for i in range(n):
                if used[i]:
                    continue
                used[i] = True
                path.append(nums[i])
                backtrack()
                path.pop()
                used[i] = False

        backtrack()
        return res
```

**Complexity:** Time O(n · n!) | Space O(n) recursion depth (output itself is O(n · n!))

**Blind 100 Note:** Canonical backtracking template — the "choose/explore/unchoose" skeleton generalizes to Subsets, Combination Sum, N-Queens, Palindrome Partitioning, Word Search. Master this before tackling permutation-with-duplicates (LC 47) and next-permutation (LC 31).

**Contest Tips:**
- **Must use `path.copy()`** (or `path[:]`) when appending — appending `path` directly stores a reference and yields empty lists at the end.
- `used` array is cleaner than `if x in path` (O(n) lookup) — keeps it O(1) per check.
- For duplicates (LC 47), sort first and skip `i > 0 and nums[i] == nums[i-1] and not used[i-1]`.
- Swap-based version saves the `used` array but mutates input — fine for LeetCode, avoid if input must be preserved.
- Edge case: `n == 1` returns `[[nums[0]]]` naturally; empty input returns `[[]]`.

### 📷 Learning — Photography
> `2026-11-16 10:57:16`

#### 📷 Today's Concept: Sony A7C — 4K Video Settings and Overheating Management

**What it is:** The A7C records 4K video either oversampled from the full 6K sensor width (24p/25p, best quality) or with a 1.2x crop (30p, and all 60p). Overheating management means configuring heat-related settings so long takes don't shut you down mid-shot.

**Why it matters:** The A7C's compact body dissipates heat poorly, so a misconfigured camera can overheat in 15–20 minutes — ruining interviews, long takes, or event coverage. Correct settings let you record 4K 24p for 45+ minutes reliably.

**How to apply it:**
1. Set **Auto Power OFF Temp.** to **High** (Setup menu) — this alone roughly doubles record time.
2. Shoot **4K 24p/25p** (full-width oversampled) rather than 30p/60p when you don't need the crop or frame rate — it runs cooler and looks more cinematic.
3. Pull the screen away from the body and avoid direct sun; heat radiates through the LCD.
4. Use a **V-mount or USB-C PD power bank** instead of the internal battery — the battery is a major heat source.
5. For long takes, record externally via HDMI to an Atomos Ninja V; the camera then only outputs, generating far less internal heat.

**Sony A7C tip:** Enable **Proxy Recording** (off by default) only when needed — it adds processing heat. For interviews, pair with the Sony 35mm f/1.8 for a compact, cool-running rig.

**Common mistake:** Beginners leave Auto Power OFF Temp. on Standard and shoot 4K 60p in the sun, then blame the camera when it shuts down. Set it to High and match frame rate to your actual delivery needs.

### 📚 Learning — Tech
> `2026-11-16 10:57:12`

#### 📚 Today's Concept: gRPC vs REST vs GraphQL

**What it is:** Three API paradigms: REST uses HTTP verbs + resource URLs, GraphQL exposes a single typed endpoint where clients specify exactly what they need, gRPC uses HTTP/2 + Protocol Buffers for fast binary RPC between services.

**When to use it:** REST for public/simple CRUD APIs; GraphQL when clients need flexible, nested data (mobile apps avoiding over-fetching); gRPC for high-performance internal microservice-to-microservice calls (low latency, streaming).

**Example:**
```graphql
# GraphQL: one request, exact fields
query { user(id: 1) { name posts { title } } }
```
vs REST: `GET /users/1` then `GET /users/1/posts` (two round trips).

**Gotcha:** GraphQL isn't a REST replacement for everything — its flexibility invites N+1 query problems and complex caching; gRPC's binary format makes browser debugging painful (needs gRPC-Web proxy). Pick per boundary, not per project.

### 🎬 Learning — YouTube
> `2026-11-16 10:57:19`

#### 🎬 今日主題：開箱 — 開箱影片的 Thumbnail 設計：對比 / 表情 / 文字
**類別：** 開箱

**是什麼：** 開箱影片的縮圖設計核心是三元素：產品對比（前後／大小／價格）、誇張表情（驚喜、疑惑）、大字標題（3-5字鉤子）。目的是讓觀眾在0.5秒內決定點擊。

**為什麼重要：** 開箱類競爭激烈，縮圖決定70%點擊率；爛縮圖會讓好內容被埋沒，初學者尤其容易忽略。

**怎麼做：**
1. 拍3種表情特寫（驚喜、傻眼、得意），選最誇張那張。
2. 產品放畫面一側，另一側放「對比物」（舊款、價格標籤、手掌比例）。
3. 文字只留3-5字，用粗體+高對比色（黃底黑字最安全），放表情旁不遮臉。
4. 手機縮到小尺寸預覽，確認仍可讀。
5. 用Canva或Photoshop做2版A/B測試。

**新手常犯的錯：** 縮圖塞滿產品照+小字說明。避免：只留一個視覺焦點（臉或產品），文字當輔助。

**延伸 idea：** 「A7C vs 手機拍開箱：縮圖實測哪張點擊高？」——拍一支自嘲實驗片，同時展示攝影功力與縮圖邏輯，符合科技+攝影方向。

## 🛂 Immigration

### 🇦🇺 Australia Immigration
> `2026-11-16 10:57:24`

- [Megathreads & subclass discussions](https://www.reddit.com/r/AusVisa/comments/1wtaedi/megathreads_subclass_discussions/)
- [Student Visas Mega Thread](https://www.reddit.com/r/AusVisa/comments/1uo2jha/student_visas_mega_thread/)
- [Subsequent Entrant Visa 500](https://www.reddit.com/r/AusVisa/comments/1xxahrm/subsequent_entrant_visa_500/)
- [Construction Project Manager 189](https://www.reddit.com/r/AusVisa/comments/1xxe4lr/construction_project_manager_189/)
- [Working on subclass 500](https://www.reddit.com/r/AusVisa/comments/1xxe7i2/working_on_subclass_500/)
