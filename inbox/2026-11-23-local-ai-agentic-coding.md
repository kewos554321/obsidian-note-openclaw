---
date: 2026-11-23
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-11-23

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

## 🔥 今日重點 Top Highlights

- **全球AI股災，台股逆勢獨強**：S&P 500 單日暴跌 5.64%、日經 -5.06%，AI 晶片股全面崩跌（ARM -16.7%、NVDA -14%、AVGO -14%），但台股加權逆勢 +2.55% 至 36,953。若你有美股/海外曝險，這是重災日；台股則出現罕見背離，留意後續波動風險。
- **AI 能源足跡震撼數據**：分析預測 2028 年 Anthropic 87% 電力來自天然氣、11% 來自燃煤（914pts 熱議）——對關注 AI infra 與 compute 趨勢的你是重要基本面訊號。https://betterdatacenterproject.com/2026/11/16/how-ai-is-powered-a-breakdown-of-byop-and-grid-power/
- **Google Agent 治理工具鏈成熟**：Gemini API Tool Retrieval（數百工具省 token）+ Semantic Governance（執行前逐筆審核 tool call）+ Agent Anomaly Detection，對正在做 agentic 系統的工程師是可直接落地的參考架構。https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/
- **Musk 警告 2027 AI「現金緊縮」**：同時分析師開始把 SpaceX 視為潛在 AI hyperscaler——搭配今日 AI 股崩跌，值得納入你的總經/產業判斷。https://finance.yahoo.com/technology/ai/articles/elon-musk-says-2027-ai-023231321.html
- **11月採購窗口**：相機黑五（11/27）美系品牌官網下殺、潛季結束二手調節器/BCD 出清（務必確認保養紀錄）、機票黑五華航/長榮歐洲線常打 8–9 折（可鎖 2027 春季行程）。

---

- 💻 **Tech**: 本地 AI/agentic coding 工具熱潮（Inkling/Qwen/Unsloth 指南、Localcode）、C++26 定案、Clover-35B MoE diffusion 新模型。
- 🤖 **AI 公司動態**: 無 OpenAI/Anthropic 消息；Tesla/SpaceX 聚焦 AI 現金緊縮與 hyperscaler 想像，XPeng 巴黎開放 ADAS 試乘。
- 🔵 **Google**: Agent 治理（semantic governance + anomaly detection）、Tool Retrieval、Gemini Enterprise MCP 安全連接、Tunix+Gemma 4 agentic RL。
- 📈 **Markets**: 全球 risk-off，S&P -5.64%、日經 -5.06%，台股逆勢 +2.55% 背離。
- 🏠 **台灣房市**: 央行管制下量縮盤整，「蛋黃穩、蛋白修正」，買方市場議價空間大。
- 📊 **Watchlist**: 全線重挫，AI 硬體最慘（ARM/NVDA/AVGO/AMD -13~17%），MSFT/GOOG 相對抗跌；估值欄位全 N/A。
- 🌍 **World News**: COP31 破局無協議、俄烏攻擊傷亡、芬蘭灣俄船遭無人機襲、舊金山 AI 泡沫憂慮、英相推歐盟協議。
- 📷 **Camera Deals**: 11月通路攻略（PChome/momo/光華/代購/二手）+ 逆光輪廓光人像技巧。
- 🤿 **Dive Gear Deals**: 北台灣實體店與線上比價、季末出清時機、調節器冬季保養重點。
- ✈️ **Flight Tips**: 11月各航線訂票窗口與最便宜航空（日本/泰國/歐洲/美國/埃及/澳洲）。
- 📚 **Finance**: Gross vs Operating Margin——高毛利低營益代表「產品行、賣太貴」，看缺口是否隨規模收斂。
- 🧩 **LeetCode**: #127 Word Ladder（BFS on implicit graph + wildcard bucketing）；今日挑戰 #1477。
- 📷 **Photography**: A7C 的 S-Log2 vs S-Log3 選擇與曝光實務（8-bit 別欠曝）。
- 📚 **Tech Learning**: CQRS + Event Sourcing——事件 schema 是永久契約，day one 就要

---

## 💻 Tech

### 💻 Tech & AI
> `2026-11-23 11:53:01`

#### Hacker News
- [A Beginner's Guide to Local AI with Inkling, Qwen, and Unsloth](https://www.gpupartner.com/blog/beginners-guide-local-ai-inkling-qwen-unsloth) ⭐313
- [Localcode, open source agentic coding on your Mac with one command](https://github.com/mjwsolo/localcode) ⭐37
- [Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) ⭐284
- [0rwx – A simple model of AI usage, inspired by Unix permissions](https://0rwx.com/) ⭐26
- [Harvard CS 2881R AI Safety](https://boazbk.github.io/mltheoryseminar/) ⭐54
- [87% of the Anthropic power will come from gas and 11% from coal in 2028](https://betterdatacenterproject.com/2026/11/16/how-ai-is-powered-a-breakdown-of-byop-and-grid-power/) ⭐914
- [Agentics: Mushy Software](https://12gramsofcarbon.com/p/agentics-mushy-software) ⭐42
- [Pill to treat pancreatic cancer hailed as 'biggest breakthrough in decades'](https://www.theguardian.com/society/2026/nov/20/pill-pancreatic-cancer-breakthrough-daraxonrasib) ⭐1345
- [Agent swarm trying to solve P vs. NP](https://pequalnp.com/) ⭐128
- [C++26 is done (again): November 2026 ISO C++ meeting trip report](https://herbsutter.com/2026/11/21/c26-is-done-again-trip-report-november-2026-iso-c-standards-meeting-buzios-brazil/) ⭐72

#### HuggingFace
- [Clover-35B-A3B-Preview Technical Report](https://huggingface.co/papers/2611.24636)
- [Prune to Expand: Training Prompt Enhancers with Less to Imitate](https://huggingface.co/papers/2611.27229)
- [AeroRSI: Recursive Self-Improvement for Aerial Vision-Language Navigation](https://huggingface.co/papers/2611.24077)
- [Duopra: From Full-Duplex Conversation to Full-Duplex Agency](https://huggingface.co/papers/2611.25773)
- [Lost in the Hallway: Benchmarking Persistent Spatial Memory Across Revisits](https://huggingface.co/papers/2611.21485)
- [PURE: A Diagnostic Benchmark for Multi-Granularity Multimodal Identity Matching](https://huggingface.co/papers/2611.22343)

#### ArXiv


### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-11-23 11:53:07`

#### Tesla
- [Elon Musk Says 2027 AI Cash Crunch Will Be ‘Nuts’ — Analysts Still See SpaceX Emerging As The Biggest AI Hyperscaler](https://finance.yahoo.com/technology/ai/articles/elon-musk-says-2027-ai-023231321.html)
- [Forget Flying Roadsters. Tesla Investors Have 3 Bigger Challenges to Watch.](https://finance.yahoo.com/markets/stocks/articles/forget-flying-roadsters-tesla-investors-022001912.html)
- [XPENG Launches Public Advanced ADAS Test Rides at Its Paris Store, Becoming the First Chinese Automaker to Offer the Experience Overseas](https://finance.yahoo.com/technology/ai/articles/xpeng-launches-public-advanced-adas-010200031.html)
- [Should You Buy Tesla or SpaceX Stock Before Their Potential Merger?](https://finance.yahoo.com/markets/stocks/articles/buy-tesla-spacex-stock-potential-222102160.html)

### 🔵 Google 動態
> `2026-11-23 11:53:04`

#### Google AI Blog
- [Introducing Tool Retrieval in the Gemini API](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/)
- [Walter Isaacson on curiosity and creativity in the AI age.](https://blog.google/innovation-and-ai/technology/ai/dialogues-walter-isaacson/)
- [The Gemini app is now available on lower-memory Android devices.](https://blog.google/innovation-and-ai/products/gemini-app/gemini-lower-memory-devices/)
- [Put Gemini to work for you](https://blog.google/innovation-and-ai/products/gemini-app/tasks-in-gemini-free-new-features/)
- [New Ask Maps features to help with holiday travel and prep](https://blog.google/products-and-platforms/products/maps/ask-maps-holiday-travel-features-2026/)
#### Google Blog
- [Get your year-end tasks done with new Connected Apps.](https://blog.google/products-and-platforms/products/search/connected-apps-holiday-errands/)
- [How Watch Duty is using Gemini to get wildfire alerts out faster](https://blog.google/company-news/outreach-and-initiatives/google-org/watch-duty-gemini-tool/)
- [ICYMI: Transfer your history from other AI apps into Gemini.](https://blog.google/innovation-and-ai/products/gemini-app/switch-ai-assistants-transfer-history/)
- [How we’re putting one of quantum mechanics’ deepest features to the test at scale.](https://blog.google/innovation-and-ai/models-and-research/quantum-computing/putting-one-of-quantum-mechanics-deepest-features-to-test-at-scale/)
- [Introducing Tool Retrieval in the Gemini API](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/)
#### Google Developers
- [Agent Anomaly Detection: Safeguarding agents across other clouds](https://developers.googleblog.com/agent-anomaly-detection-safeguarding-agents-across-other-clouds/)
- [How to securely connect internal Cloud Run MCP servers to Gemini Enterprise](https://developers.googleblog.com/how-to-securely-connect-internal-cloud-run-mcp-servers-to-gemini-enterprise/)
- [Check what your AI agents do before they do it, with Semantic governance policies](https://developers.googleblog.com/check-what-your-ai-agents-do-before-they-do-it-with-semantic-governance-policies/)
- [How to handle user, connector, and agent auth in Gemini Enterprise with a custom UI](https://developers.googleblog.com/how-to-handle-user-connector-and-agent-auth-in-gemini-enterprise-with-a-custom-ui/)
- [Multi-Turn Agentic Reinforcement Learning with Tunix and Gemma 4 on Google TPUs](https://developers.googleblog.com/multi-turn-agentic-reinforcement-learning-with-tunix-and-gemma-4-on-google-tpus/)

## 📈 Finance

### 📈 Markets Overview
> `2026-11-23 11:53:09`

#### Indices
- S&P 500: 6,910.39 ▼5.64%
- 台股加權: 36,953.38 ▲2.55%
- 日經 225: 56,436.65 ▼5.06%

### 🏠 台灣房市
> `2026-11-23 11:53:48`

#### AI 分析
## 台灣房市速覽（2026-11-23）

**1. 整體趨勢**
央行選擇性信用管制持續，投資買盤退場，市場以自住剛需為主；成交量低檔盤整，但高總價、精華區物件仍有支撐，價格呈「蛋黃穩、蛋白修正」格局。預售與新成屋讓利、送裝潢成常態，議價空間明顯放大。

**2. 值得注意的地區／物件**
- **高總價住宅大樓仍見成交**：實登115S3出現多筆總價5,700萬～2.9億、單價27～45萬/㎡的11層以上大樓，顯示蛋黃區大坪數、品牌建案仍有自住換屋與資產配置買盤。
- **軌道經濟發酵**：桃園八德G01（城中大璽）、高雄輕軌鼎山／建工、板橋浮洲等捷運／輕軌沿線新案持續掛牌，屬「通勤剛需＋重劃區」題材。
- **台南東區、安平**：南紡生活圈大坪數五房雙平車、安平商圈店面型出租物件，反映台南自住換屋與商用租賃需求並存。

**3. 對自住者建議**
- 現在是「買方市場」，善用議價與建商讓利，優先鎖定捷運／輕軌已通車或明確動工路段，避開只有題材、無實質交通的重劃區。
- 自備款與房貸負擔抓保守（月付不超過家庭收入1/3），預留利率與寬限期結束後的還款緩衝。

**4. 對投資者建議**
- 短線炒作空間已壓縮，信用管制下槓桿成本高，不宜追高蛋白區預售。
- 若布局，聚焦「租金報酬穩定」的商圈店面／整層出租（如台南中西區、安平美業選物店型）與精華區大樓長期持有，並緊盯實登單價偏離行情過大的物件議價。

**5. 風險提醒**
高總價物件單價落差大（27～45萬/㎡），須逐筆比對同社區實登；蛋白重劃區供給量大，留意未來轉手流動性與建商餘屋降價競爭。

#### 591 最新
- [台南市中西區環河街🥇第一首選找小瑛🥇熱門商圈🉑輕食整棟出租](https://rent.591.com.tw/rent-detail-22382486.html)
- [桃園市八德區中正一路COCO推薦♥八擴正捷運G01【城中大璽】全新落成三房車♥](https://sale.591.com.tw/sale-detail-21305889.html)
- [高雄市三民區大順二路635巷開價及實登！大順輕軌★鼎山＆建工商圈☆陽台進出三房美居](https://sale.591.com.tw/sale-detail-21305887.html)
- [新北市板橋區僑中二街中信小吳推薦<馥華原真川字2房車>浮洲最佳建案｜找我談最俗](https://sale.591.com.tw/sale-detail-21305885.html)
- [台南市東區中華東路二段✨東區稀有釋出近南紡・大空間五房雙平車✨三代同堂看過來](https://sale.591.com.tw/sale-detail-21305884.html)
- [台南市安平區華平路🥇第一首選找小瑛🥇近黃金商圈🈴美業選物店📌單層17坪](https://rent.591.com.tw/rent-detail-22335848.html)
- [台北市信義區忠孝東路五段Y05租永春站氣派門廳含平面車位採光佳](https://rent.591.com.tw/rent-detail-22254066.html)
- [新北市三重區元信一街12/1開放看屋、仁義重劃區仁仁邑高樓3房+車位](https://rent.591.com.tw/rent-detail-22392893.html)

#### 實價登錄 (115S3) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 住宅大樓(11層含以上有電梯) | 963.3㎡ | 29664萬 | 307937元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 399.6㎡ | 14468萬 | 449312元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 379.7㎡ | 10438萬 | 274908元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 267.7㎡ | 8558萬 | 367305元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 144.7㎡ | 5700萬 | 456525元/㎡ |

### 📊 Watchlist
> `2026-11-23 11:53:28`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 125.53 ▼14.01% |
| Market Cap | $3.03T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.9% / 66.1% / 62.5% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 11.35 |
| Beta | 2.25 |
| 52-Week | 124.50 – 243.37 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures Rise As Oracle, Korea Try To Ease Market Fears; Look For These Absolute Losers](https://finance.yahoo.com/m/9ef9da98-bccf-3565-9a30-9bc3e57ad4b9/dow-jones-futures-rise-as.html) — Investor's Business Daily
- [Asia stocks slide as AI rout deepens despite rebound in U.S. futures](https://finance.yahoo.com/markets/stocks/articles/asia-stocks-slide-ai-rout-033321972.html) — Investing.com
- [Worried About Nvidia? Buy This Fantastic Artificial Intelligence (AI) Stock Instead](https://finance.yahoo.com/technology/ai/articles/worried-nvidia-buy-fantastic-artificial-032002826.html) — Motley Fool

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 424.39 ▼13.25% |
| Market Cap | $696.04B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.7% / 17.7% / 16.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 10.15 |
| Beta | 2.49 |
| 52-Week | 115.06 – 658.52 |
| Div. Yield | — |

**Recent News:**
- [NVDA, INTC, MU, AMD Chip Stocks Rip Higher: Dan Ives Says ‘Bears Feel Validated,’ But There’s No Stopping The AI Wave](https://finance.yahoo.com/markets/stocks/articles/nvda-intc-mu-amd-chip-022405766.html) — Stocktwits
- [AMD vs. Nvidia Stock After Jensen Huang’s Exit: 1 Trades at Nearly 4x the Other’s Earnings Multiple. Here’s the AI Chip Stock I’d Buy Now.](https://finance.yahoo.com/markets/stocks/articles/amd-vs-nvidia-stock-jensen-212513753.html) — Barchart
- [AMD Gained From Nvidia’s China Scandal. Now a Short Seller Says AMD Has a China Problem Too.](https://finance.yahoo.com/markets/stocks/articles/amd-gained-nvidia-china-scandal-190104037.html) — Barchart

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 484.52 ▼2.77% |
| Market Cap | $3.60T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.7% / 47.1% / 41.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 7.65 |
| Beta | 1.04 |
| 52-Week | 349.20 – 559.15 |
| Div. Yield | — |

**Recent News:**
- [How Did Dell Grow From $56 Billion To $151 Billion In 20 Years?](https://finance.yahoo.com/markets/stocks/articles/did-dell-grow-56-billion-024411022.html) — Trefis
- [Amazon Spent $1.82 For Every $1 Of Cash Last Quarter. Can It Keep Going?](https://finance.yahoo.com/markets/stocks/articles/amazon-spent-1-82-every-024411676.html) — Trefis
- [15% of parents already cut college savings after Microsoft AI CEO told a mom 'probably not' to bother saving](https://finance.yahoo.com/technology/ai/articles/15-parents-already-cut-college-211500548.html) — Moneywise

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 265.29 ▼2.70% |
| Market Cap | $3.24T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.3% / 50.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.80 |
| Beta | 1.23 |
| 52-Week | 264.22 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [Amazon Spent $1.82 For Every $1 Of Cash Last Quarter. Can It Keep Going?](https://finance.yahoo.com/markets/stocks/articles/amazon-spent-1-82-every-024411676.html) — Trefis
- [Jim Cramer sends a strong signal to Google stock investors](https://finance.yahoo.com/markets/stocks/articles/jim-cramer-sends-strong-signal-003700392.html) — TheStreet
- [Her $420,000 in Employer Stock Inside Her 401(k) Lost 11% in a Day. Rolling It Into an IRA Would Turn Her Long-Term Gain Into Ordinary Income](https://finance.yahoo.com/markets/options/articles/her-420-000-employer-stock-211703896.html) — 24/7 Wall St.

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 246.82 ▼4.10% |
| Market Cap | $2.67T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 51.4% / 13.1% / 16.9% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.34 |
| Beta | 1.50 |
| 52-Week | 196.00 – 287.20 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures Rise As Oracle, Korea Try To Ease Market Fears; Look For These Absolute Losers](https://finance.yahoo.com/m/9ef9da98-bccf-3565-9a30-9bc3e57ad4b9/dow-jones-futures-rise-as.html) — Investor's Business Daily
- [Amazon Spent $1.82 For Every $1 Of Cash Last Quarter. Can It Keep Going?](https://finance.yahoo.com/markets/stocks/articles/amazon-spent-1-82-every-024411676.html) — Trefis
- [Jeff Bezos sends a strong signal to Nvidia stock investors as CEO search heats up](https://finance.yahoo.com/markets/stocks/articles/jeff-bezos-sends-strong-signal-210700013.html) — TheStreet

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 560.84 ▼5.93% |
| Market Cap | $1.43T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.0% / 32.9% / 31.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 5.25 |
| Beta | 1.28 |
| 52-Week | 520.26 – 779.82 |
| Div. Yield | — |

**Recent News:**
- [After Blockbuster Anthropic IPO, OpenAI Wants AI Rivals To Agree On Development ‘Limits’, While Meta Calls For Controlled Approach](https://finance.yahoo.com/technology/ai/articles/blockbuster-anthropic-ipo-openai-wants-031510105.html) — Stocktwits
- [Amazon Spent $1.82 For Every $1 Of Cash Last Quarter. Can It Keep Going?](https://finance.yahoo.com/markets/stocks/articles/amazon-spent-1-82-every-024411676.html) — Trefis
- [Alphabet vs. Meta Platforms: Which Media Stock Is a Better Buy for 2027?](https://finance.yahoo.com/media-advertising/articles/alphabet-vs-meta-platforms-media-171618650.html) — Motley Fool

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 304.41 ▼14.02% |
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
- [Her $420,000 in Employer Stock Inside Her 401(k) Lost 11% in a Day. Rolling It Into an IRA Would Turn Her Long-Term Gain Into Ordinary Income](https://finance.yahoo.com/markets/options/articles/her-420-000-employer-stock-211703896.html) — 24/7 Wall St.
- [Google’s 2027 chip plan is bad news for Broadcom](https://finance.yahoo.com/technology/articles/google-2027-chip-plan-bad-194700249.html) — TheStreet
- [Here's What a $1,000 Investment in Broadcom Stock Could Be Worth By 2035](https://finance.yahoo.com/markets/stocks/articles/heres-1-000-investment-broadcom-192202429.html) — Motley Fool

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 152.20 ▼16.72% |
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
- [Arm vs. Marvell Technology: Which Artificial Intelligence Stock Is a Better Buy for 2027?](https://finance.yahoo.com/technology/ai/articles/arm-vs-marvell-technology-artificial-001005246.html) — Motley Fool
- [Arm Sinks 20% in a Week as Chips Slide and Nvidia’s Headhunters Approach CEO Rene Haas. Time to Buy?](https://finance.yahoo.com/markets/stocks/articles/arm-sinks-20-week-chips-133527300.html) — TIKR
- [SoftBank Falls 14%, and 72% of Arm’s Shares Sit Pledged Behind Its Loans](https://finance.yahoo.com/markets/stocks/articles/softbank-falls-14-72-arm-101747234.html) — TIKR

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 143.49 ▼6.63% |
| Market Cap | $330.99B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.7% / 45.6% / 50.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 30.74 |
| Beta | 1.62 |
| 52-Week | 106.37 – 212.94 |
| Div. Yield | — |

**Recent News:**
- [Palantir Technologies (PLTR) Co Hosts Sovereign AI Defense Summit](https://finance.yahoo.com/technology/ai/articles/palantir-technologies-pltr-co-hosts-210650181.html) — Simply Wall St.
- [Palantir Stock Could Finish 2026 Lower. Its Only 2 Losing Years Ended Very Differently.](https://finance.yahoo.com/markets/stocks/articles/palantir-stock-could-finish-2026-185702324.html) — Motley Fool
- [UiPath vs. Palantir Technologies: Which AI Automation Platform Makes a Better Stock Buy for 2027?](https://finance.yahoo.com/markets/stocks/articles/uipath-vs-palantir-technologies-ai-183302672.html) — Motley Fool

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 21.65 ▼11.16% |
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
- [Wall Street Sees 82% Upside in Super Micro Computer (SMCI), but Margin Risks Remain](https://finance.yahoo.com/markets/stocks/articles/wall-street-sees-82-upside-165221954.html) — Insider Monkey
- [Plot Twist: As CFO, Nvidia’s Interim CEO Said “Over 99%” of Singapore Billings Were for U.S. Customers](https://finance.yahoo.com/markets/stocks/articles/plot-twist-cfo-nvidia-interim-100427473.html) — TIKR
- [Super Micro: 3 Key Takeaways for Long-Term Investors](https://finance.yahoo.com/markets/stocks/articles/super-micro-3-key-takeaways-071116384.html) — Motley Fool

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 345.82 ▼7.64% |
| Market Cap | $1.37T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.3% / 3.3% / 3.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 12.55 |
| Beta | 1.74 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Elon Musk Says 2027 AI Cash Crunch Will Be ‘Nuts’ — Analysts Still See SpaceX Emerging As The Biggest AI Hyperscaler](https://finance.yahoo.com/technology/ai/articles/elon-musk-says-2027-ai-023231321.html) — Stocktwits
- [Forget Flying Roadsters. Tesla Investors Have 3 Bigger Challenges to Watch.](https://finance.yahoo.com/markets/stocks/articles/forget-flying-roadsters-tesla-investors-022001912.html) — Motley Fool
- [XPENG Launches Public Advanced ADAS Test Rides at Its Paris Store, Becoming the First Chinese Automaker to Offer the Experience Overseas](https://finance.yahoo.com/technology/ai/articles/xpeng-launches-public-advanced-adas-010200031.html) — GlobeNewswire

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 635.54 ▼5.33% |
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
- [Billionaire Ray Dalio’s Bridgewater Keeps 16% of Its $23 Billion Stock Portfolio in S&P 500 Index Funds, Even After Cutting Them](https://finance.yahoo.com/markets/stocks/articles/billionaire-ray-dalio-bridgewater-keeps-184315356.html) — 24/7 Wall St.
- [His Indexed Annuity Tracks the S&P 500. The Fine Print Says “Price Return,” Which Means It Leaves Out Every Dividend the 500 Companies Pay](https://finance.yahoo.com/markets/options/articles/indexed-annuity-tracks-p-500-210349574.html) — 24/7 Wall St.
- [The S&P 500 Is Now Below Every Wall Street Year-End Target for 2026](https://finance.yahoo.com/markets/stocks/articles/p-500-now-below-every-204200722.html) — 24/7 Wall St.

## 🌍 News

### 🌍 World News
> `2026-11-23 11:53:52`

- [COP31 fails to reach major climate deal as talks expose deep divisions](https://www.bbc.co.uk/news/articles/cqwy06zrd26lo?at_medium=RSS&at_campaign=rss)
- [What's next after no deal at COP31 climate talks?](https://www.bbc.co.uk/news/videos/cr1ewge81q4qo?at_medium=RSS&at_campaign=rss)
- [Boy, 7, pulled alive from rubble hours after Russian strike on Ukraine, rescuers say](https://www.bbc.co.uk/news/articles/cqdr15l32d3go?at_medium=RSS&at_campaign=rss)
- [San Francisco is enjoying an AI boom, but worries about a crash are growing](https://www.bbc.co.uk/news/articles/cqe9k09j9jv4o?at_medium=RSS&at_campaign=rss)
- [Burnham to tell MPs 'landmark' EU deal could make next decade 'much better'](https://www.bbc.co.uk/news/articles/cmde1dy82lepo?at_medium=RSS&at_campaign=rss)
- [Russia-bound ship towed away after it was attacked in Gulf of Finland](https://www.bbc.co.uk/news/articles/cj752ddve27ko?at_medium=RSS&at_campaign=rss)
- [Three killed and dozens missing after fire at Indonesian factory](https://www.bbc.co.uk/news/articles/cw8dvg5pgm0eo?at_medium=RSS&at_campaign=rss)
- [Miley Cyrus marries Maxx Morando in California ceremony](https://www.bbc.co.uk/news/articles/cq8e0p87l89lo?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-11-23 11:54:03`

#### AI Tips
# 📷 台灣攝影採購 & 今日技巧 (2026-11-23)

## 【購買優惠】11月台灣買相機攻略

**通路比較（依需求選）**
- **PChome 24h**：公司貨、到貨快，適合急用；11月常有「雙11延長檔」與信用卡回饋疊加，留意**PChome 聯名卡 + 平台折價券**雙重折。
- **momo**：3C 品類折扣券多，**雙11後仍有「感恩回饋」尾檔**，適合比價後下單；注意是否為台灣公司貨保固。
- **光華商場（台北）**：可議價、當場驗機、試鏡頭；**11月週年慶尾聲**，店家衝業績好談，建議先電話詢價再現場殺。
- **日本代購**：日圓匯率有利時划算（機身/鏡頭價差可達 1–2 成），但**無台灣保固、維修寄回麻煩**；適合買台灣溢價高的鏡頭。
- **二手（旋轉拍賣、DCView、FB 社團）**：11月換機潮釋出多，**快門數、公司貨保卡、盒裝**三項必問；面交當場測對焦、感光元件壞點。

**11月季節技巧**
1. **雙11後一週是「退貨品/尾盤」撿便宜時機**，價格常再鬆動。
2. **黑色星期五（11/27 前後）** 美系品牌（Canon/Nikon/Sony）官網與通路常同步下殺，先加願望清單。
3. **年底換機潮**：11月底–12月二手市場機身供給增，議價空間大。
4. 買**公司貨**優先確認「台灣代理保固卡」，代購/水貨維修成本要算進去。

---

## 【今日攝影技巧】逆光下的「輪廓光」人像

**技巧**：把太陽（或強光源）放在主體**斜後方 45°**，讓光線勾出頭髮與肩膀邊緣的亮邊

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-11-23 11:54:07`

#### AI Tips
# 台灣潛水裝備購買指南（2026年11月）

## 購買優惠

**實體店（北台灣）**
- **潛水貨倉（Diving Warehouse）**：台北市區，代理多品牌（Scubapro、Mares），常有季末出清，可議價。
- **海人潛水**：新北，裝備齊全，適合新手一次購足。
- **藍鯨潛水**：台中，中部地區老牌，維修服務好。

**線上**
- **PChome / momo**：適合買配件（蛙鞋帶、防水袋、防霧劑），比價快。
- **蝦皮**：找有實體店的賣家（看評價+店面地址），避免水貨無保固。
- **Facebook 社團**：「台灣潛水二手交流」「潛水裝備買賣」— 11月常有潛季結束出清，二手調節器/BCD 可撿便宜，但**調節器務必確認有近期保養紀錄**。

**11月時機提示**
- 台灣東北角潛季約10月底收尾，店家開始**季末出清**（防寒衣、輕裝折扣多）。
- 11月是**墾丁/小琉球**旺季尾聲，南部店家仍有促銷；也是規劃**明年春季船潛**、趁冬季淡季談價格的好時機。
- 黑五（11月底）線上配件折扣可留意，但潛水主裝備折扣有限。

## 裝備建議

**調節器冬季保養**：每次潛後用**淡水沖洗二級頭**（按住排水鈕避免水進一級頭），晾乾存放時**一級頭防塵蓋務必蓋上**。11月潛季結束若打算封存，送店家做

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-11-23 11:53:58`

#### AI Flight Tips — November
# November Flight Deals from Taiwan (TPE/TSA) — Quick Reference

**Japan (Tokyo/Osaka/Sapporo)**
- November = peak for autumn foliage (late Nov especially); Sapporo shoulder-to-peak as ski season nears. Book 6–10 weeks out for Tokyo/Osaka, 8–12 for Sapporo.
- Cheapest: Peach, Tigerair Taiwan, Scoot to NRT/KIX; Jetstar for CTS. Watch Tigerair Taiwan's "flash fare" sales (Tue/Thu drops) and Peach's early-bird for CTS.
- Tip: Fly into KIX for Osaka/Kyoto foliage; TSA–HND (Songshan) often beats TPE–NRT on time, not price.

**Thailand (Bangkok/Chiang Mai)**
- November = start of cool/dry peak season (esp. Chiang Mai, Loy Krathong mid-Nov). Book 4–8 weeks out; Chiang Mai tighter around festival.
- Cheapest: Thai Lion Air, Nok Air, VietJet (via SGN/HAN), Scoot via SIN. Direct: China Airlines/Starlux sales beat LCC bundles on baggage.
- Watch: VietJet "0đ" promos and AirAsia Free Seats (usually launched Feb/Mar for following year).

**Europe (any major city)**
- November = deep off-peak (post-summer, pre-Christmas) — best pricing of the year outside Jan–Feb. Book 8–14 weeks out; 10–12 is the sweet spot.
- Cheapest: China Eastern/China Southern via PVG/CAN, or Turkish via IST; Scoot/Emirates via SIN for one-stop. Avoid peak-Thanksgiving-week departures.
- Watch: Black Friday (Nov 27, 2026) airline sales — China Airlines and EVA often discount Europe 10–20%; book those for spring 2027 travel.

**USA (West/East Coast)**
- November = off-peak early month, spikes around Thanksgiving (Nov 26, 2026). Book 8–12 weeks out; East Coast needs 10–14.
- Cheapest: Starlux/China Airlines direct to LAX/SFO/ONT/SEA; for East Coast, China Airlines TPE–JFK or one-stop via West Coast on Alaska/Delta. United/Delta sales via NRT/SFO.
- Watch: Thanksgiving-week fares inflate 40%+; shift departure to Nov 17–19 or Dec 1–3 for savings.

**Egypt (Cairo)**
- November = ideal peak season (cool weather, high demand). Book 10–14 weeks out — limited one-stop capacity from TPE.
- Cheapest: China Eastern via PVG, or Emirates/Qatar via DXB/DOH (often cheapest total); EgyptAir via BKK on China Airlines connection.
- Watch: Qatar Airways "Stopover" packages and Emirates early-bird; avoid Dec–Jan Christmas spike by locking November now.

**Australia (Sydney/Melbourne)**
- November = shoulder-to-peak (pre-summer, school holidays start mid-Dec). Book 8–12 weeks out; Melbourne slightly cheaper than Sydney.
- Cheapest: China Airlines/EVA direct TPE–SYD/BNE/MEL; Scoot via

## 📚 Learning

### 📚 Learning — Finance
> `2026-11-23 11:54:09`

#### 📚 Today's Concept: Gross Margin and Operating Margin

What it is: Gross margin is revenue minus cost of goods sold, divided by revenue — the percentage of each sales dollar left after paying to make or deliver the product. Operating margin subtracts operating expenses (R&D, sales, marketing, admin) from that, showing what's left before interest and taxes.

Why it matters: Gross margin tells you if the product itself is economically viable; operating margin tells you if the business can be run profitably at scale. Comparing the two reveals whether money is being lost in production or in overhead.

Example: A SaaS company books $10M revenue. Hosting and support cost $2M, so gross profit is $8M (80% gross margin). Sales, marketing, R&D, and admin total $6M, leaving $2M operating profit (20% operating margin). The 60-point gap between margins is where the company spends to grow.

Rule of thumb: A high gross margin with a low or negative operating margin means the product works but the company is overspending to sell it — watch whether that gap narrows as revenue grows, or the growth is just buying losses.

### 🧩 LeetCode Blind 100
> `2026-11-23 11:54:14`

#### 🧩 Blind 100 — 127. Word Ladder [Graphs]
**連結:** https://leetcode.com/problems/word-ladder/
> 📅 **Today's Daily Challenge:** #1477 Product of the Last K Numbers [Medium] — Tags: Array, Math, Design, Data Stream, Prefix Sum — https://leetcode.com/problems/product-of-the-last-k-numbers/

# 127. Word Ladder

**Problem Type:** BFS on implicit graph (shortest path in unweighted graph)

**Key Insight:** Each word is a node; edges connect words differing by exactly one letter. BFS from `beginWord` gives the shortest transformation sequence. Generate neighbors by wildcard patterns (`h*t` → `hot`, `hit`) to avoid O(N²) pairwise comparisons.

**Approach:**
1. Build `pattern → [words]` map from `wordList` (e.g., `"hot"` → `"*ot"`, `"h*t"`, `"ho*"`).
2. BFS from `beginWord` with `(word, level)`. Mark visited by removing from map (or a `visited` set).
3. For each word, generate its patterns, look up neighbors, enqueue unvisited ones.
4. Return `level` when `endWord` is dequeued; return 0 if BFS exhausts.

**Python3 Solution:**
```python
from collections import deque, defaultdict

class Solution:
    def ladderLength(self, beginWord: str, endWord: str, wordList: list[str]) -> int:
        if endWord not in wordList:
            return 0

        # pattern -> list of words
        adj = defaultdict(list)
        wordList.append(beginWord)
        for w in wordList:
            for i in range(len(w)):
                pat = w[:i] + "*" + w[i+1:]
                adj[pat].append(w)

        q = deque([beginWord])
        visited = {beginWord}
        steps = 1

        while q:
            for _ in range(len(q)):
                word = q.popleft()
                if word == endWord:
                    return steps
                for i in range(len(word)):
                    pat = word[:i] + "*" + word[i+1:]
                    for nei in adj[pat]:
                        if nei not in visited:
                            visited.add(nei)
                            q.append(nei)
            steps += 1

        return 0
```

**Complexity:** Time O(N · L²) where N = wordList size, L = word length (L² from string slicing per pattern) | Space O(N · L)

**Blind 100 Note:** Canonical BFS-on-implicit-graph problem. Teaches (a) modeling non-obvious state as graph nodes, (b) wildcard bucketing to avoid O(N²) neighbor checks, (c) level-order BFS for shortest path. Related: **Word Ladder II** (BFS + DFS backtracking), **Open the Lock**, **Minimum Genetic Mutation**, **Snakes and Ladders**.

**Contest Tips:**
- **Early exit:** `if endWord not in wordList: return 0` — saves a full BFS.
- **Visited on enqueue**, not dequeue — prevents duplicate work and TLE.
- **Level tracking:** use `for _ in range(len(q))` per level, or store `(word, dist)` tuples. The former is cleaner.
- **Bidirectional BFS** cuts time dramatically on large inputs — worth knowing for follow-ups, but standard BFS passes here.
- **Don't mutate `wordList`** if you might reuse it; copy or use a separate `visited` set (shown above).
- Common bug: forgetting `beginWord` may not be in `wordList` — append it before building patterns.

### 📷 Learning — Photography
> `2026-11-23 11:54:19`

#### 📷 Today's Concept: Sony A7C — S-Log2 vs S-Log3: When to Use Each

**What it is:** S-Log2 and S-Log3 are Sony's logarithmic gamma curves that flatten contrast and color to preserve maximum dynamic range for grading. S-Log2 mimics film's highlight rolloff; S-Log3 pushes further, with a wider tonal range and cleaner shadows.

**Why it matters:** Choosing the right curve means cleaner highlights in harsh sun (S-Log2) or more gradable shadow detail in controlled light (S-Log3). Pick wrong and you'll fight noise or clipped skies in post.

**How to apply it:**
1. Use **S-Log3** for controlled or flat light — interiors, overcast, golden hour — where you want maximum shadow latitude and skin tone flexibility.
2. Switch to **S-Log2** in high-contrast daylight or run-and-gun street shooting; its gentler highlight handling protects skies and windows.
3. Always expose to the right: set zebras at **95% (S-Log3)** or **100% (S-Log2)** and keep skin around 40–45 IRE.
4. Shoot **4:2:2 8-bit internally** at the lowest base ISO (ISO 100 for S-Log2, 800 for S-Log3) to minimize noise.
5. Apply Sony's official LUTs or a conversion LUT in post, then grade — never judge the flat image on set.

**Sony A7C tip:** Assign **Picture Profile** to a custom button, and save S-Log2/S-Log3 as separate PP slots (PP7/PP8) for one-tap switching.

**Common mistake:** Underexposing S-Log3 "to protect highlights" — it crushes shadows into noise on the 8-bit A7C. Expose brighter than feels right and verify with zebras.

### 📚 Learning — Tech
> `2026-11-23 11:54:16`

#### 📚 Today's Concept: CQRS and Event Sourcing

**What it is:** CQRS separates reads (queries) from writes (commands) into distinct models, so each can be optimized independently. Event Sourcing persists state as an append-only sequence of events rather than current-state rows, with state rebuilt by replaying events.

**When to use it:** Use when you need a full audit trail, temporal queries ("what did this look like last Tuesday?"), or wildly asymmetric read/write loads. Common in financial ledgers, order management, and collaborative systems where history matters.

**Example:**
```python
# Command side: append events, don't update rows
events.append(AccountOpened(id="a1", balance=0))
events.append(MoneyDeposited(id="a1", amount=100))

# Query side: project into a read model
def rebuild(account_id):
    balance = 0
    for e in events.for_aggregate(account_id):
        if isinstance(e, MoneyDeposited): balance += e.amount
    return balance
```

**Gotcha:** People conflate the two — you can use CQRS without Event Sourcing, and vice versa. Also, event schemas are forever: once events are persisted, you can't "just change the shape" without versioning or upcasting. Treat events as a public contract from day one.

### 🎬 Learning — YouTube
> `2026-11-23 11:54:23`

#### 🎬 今日主題：攝影Vlog — Photo Walk 影片：路線規劃與剪輯節奏
**類別：** 攝影Vlog

**是什麼：** Photo Walk 影片是以「邊走邊拍」為主軸的攝影 Vlog，路線本身就是敘事骨架。剪輯節奏則指鏡頭長度、轉場與音樂的搭配，決定觀眾的觀看體驗。

**為什麼重要：** 路線混亂會讓觀眾迷失、中途離開；節奏拖沓則直接拉低完播率，而完播率是新手頻道被演算法推薦的關鍵。

**怎麼做：**
1. 事前場勘或用地圖規劃 3–5 個「有視覺亮點」的停點，形成起點→高潮→收尾。
2. 每站拍一組「環境全景＋拍攝動作＋成品照」三鏡頭，剪輯時好銜接。
3. 用 AI 工具（如 Descript、CapCut 自動剪輯）先粗剪去贅字，再手動微調節奏。
4. 每個停點控制在 20–40 秒，音樂節拍點下轉場。
5. 開頭 5 秒放最強畫面當鉤子。

**新手常犯的錯：** 把整趟路程原封不動剪進去，導致前 30 秒都在走路。解法：只留「移動中有變化的畫面」，純走路片段一律加速或刪除。

**延伸 idea：** 「用一顆 35mm 定焦鏡走完一條老街」——限制器材反而讓主題更聚焦，也適合帶入科技開箱元素（鏡頭實測）。
