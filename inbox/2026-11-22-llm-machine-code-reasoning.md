---
date: 2026-11-22
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-11-22

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

- **全球同步大逃殺，台股最慘**：TAIEX 單日 **-6.23%**，S&P 500 -5.64%、Nikkei -5.06%，AI 硬體股成重災區（ARM -16.72%、AVGO -14.02%、NVDA -14.01%、AMD -13.25%）。若你有定期定額或持股，這是檢視加碼紀律的時刻，不是恐慌的時刻。[來源](https://www.theguardian.com/business/2026/nov/20/global-stock-markets-slump-anthropic-ipo-ai-sell-off)
- **Anthropic IPO 第二天即遇 AI 拋售潮**，市場輪動明顯；MSFT/GOOGL 相對抗跌（-2.7~2.8%），暗示資金在 AI 曝險內部轉向防禦型標的。
- **Google 推 Agent 治理雙箭**：Semantic governance policies（每次 tool call 執行前內聯評估）+ Agent Anomaly Detection（跨 AWS/Azure/on-prem），對正在做 agent 產品的工程師是必讀架構參考。[policies](https://developers.googleblog.com/check-what-your-ai-agents-do-before-they-do-it-with-semantic-governance-policies/) ｜ [anomaly detection](https://developers.googleblog.com/agent-anomaly-detection-safeguarding-agents-across-other-clouds/)
- **LLM 能逐 byte 讀寫執行檔**（hex dump → machine code reasoning），對 tooling／security／codegen 有直接啟示，值得花 10 分鐘看原文。[Link](https://sgiannopoulos.github.io/blog/machine-code-programming/)
- **11 月採購窗口**：相機鏡頭走日本代購可省 15–25%、潛水輕裝在台灣買比東南亞便宜；機票避開美感恩節（11/24–30），日本鎖定 11/25–30 有 15–25% 降幅。

---

- 💻 **Tech**：LLM 機器碼推理能力曝光、TideCache 混合式 LLM serving、Rust CGP v0.8.0；AI 拋售抹去 Nasdaq 2026 漲幅。
- 🤖 **AI 公司動態**：Tesla FSD V15 開始推送、Cybercab 覆蓋 90% 載客里程；OpenAI/Anthropic 今日無更新。
- 🔵 **Google**：Gemini API Tool Retrieval（省 token 存取數百工具）、Agent 語意治理＋異常偵測、Cloud Run MCP 安全接入、TPU 上 agentic GRPO 教學。
- 📈 **Markets**：三大指數同步暴跌逾 5%，台股 -6.23% 領跌，全面 risk-off。
- 🏠 **台灣房市**：信用管制發酵、六都量縮 1–2 成，蛋黃撐盤蛋白鬆動；自住鎖定近捷運／產業園區，投資避高總價改收租型兩房。
- 📊 **Watchlist**：全員收黑，半導體最慘（ARM/AVGO/NVDA/AMD 皆 -13~17%），MSFT/GOOGL 相對抗跌；估值欄位全 N/A。
- 🌍 **World News**：澤倫斯基為克里米亞大橋攻擊辯護、芬蘭灣親俄船遭無人機襲擊、COP31 化石燃料僵局、墨西哥毒梟落網、丹麥控俄暗殺陰謀＋FBI 資料庫疑遭駭。
- 📷 **Camera Deals**：通路比較表＋11 月檔期（雙11返場、黑五 11/27、週年慶尾聲、年底出清）；機身買公司貨、鏡頭走日代或二手。
- 🤿 **Dive Gear**：東北角潛季收尾＝議價好時機；東南亞潛旅旺季開始，輕裝在台買較划算；電腦錶/水下相機留意雙11折扣。
- ✈️ **Flight Tips**：日本 11/25–30 較便宜、泰國清邁避開 Yi Peng 週、歐洲 11 月為 Q4 最便宜、美國避感恩節、埃及 11 月旺季需提早 10–12 週訂。
-

---

## 💻 Tech

### 💻 Tech & AI
> `2026-11-22 11:20:16`

#### Hacker News
- [Pill to treat pancreatic cancer hailed as 'biggest breakthrough in decades'](https://www.theguardian.com/society/2026/nov/20/pill-pancreatic-cancer-breakthrough-daraxonrasib) ⭐718
- [Pandex – Official European Law for AI Agents, over MCP](https://www.pandex.io) ⭐45
- [The Mythology of Conscious AI](https://www.noemamag.com/the-mythology-of-conscious-ai/) ⭐3
- [Tasklet (YC P26) Is Hiring Product and Agent Infra Engineers](https://tasklet.ai/careers) ⭐1
- [Tropical Rainforests Species may be surprisingly young](https://phys.org/news/2026-11-species-tropical-rainforests-young-emergence.html) ⭐45
- [LLMs can read and write executables byte by byte from a hex dump](https://sgiannopoulos.github.io/blog/machine-code-programming/) ⭐200
- [Levent Alpöge claims proof of the Generalized Riemann Hypothesis [pdf]](https://alpo.ge/remark.pdf) ⭐2863
- [Context-Generic Programming v0.8.0 – Pluggable trait implementations for Rust](https://contextgeneric.dev/blog/v0.8.0-release/) ⭐22
- [NINLIVE: The Nine Inch Nails live archive](https://ninlive.com/) ⭐363
- [Nasdaq erases all 2026 gains as AI sell-off dampens Anthropic’s second day](https://www.theguardian.com/business/2026/nov/20/global-stock-markets-slump-anthropic-ipo-ai-sell-off) ⭐502

#### HuggingFace
- [Time Series Structure Learning with Local Causal Parent Discovery](https://huggingface.co/papers/2611.26232)
- [Teaching Vision-Language-Action Models to Stop Safely](https://huggingface.co/papers/2611.26239)
- [PAD: Policy-Aware Data Valuation for Autonomous Driving](https://huggingface.co/papers/2611.25604)
- [Lang-SVG: Hierarchical Image Vectorization with Language Priors](https://huggingface.co/papers/2611.15941)
- [Squoosh Bench: Evaluating UX-1 on 318 Historical Website A/B Tests](https://huggingface.co/papers/2611.25200)
- [RL Post-Training in Diffusion Transformers Is Activation Steering](https://huggingface.co/papers/2611.26627)

#### ArXiv
- [RL Post-Training in Diffusion Transformers Is Activation Steering](http://arxiv.org/abs/2611.26627v1)
- [PlayCraft: Designing Engaging Games from Agent Play Experience](http://arxiv.org/abs/2611.26624v1)
- [TideCache: Efficient Hybrid LLM Serving with Transparent Cache Management and Layer-Wise Streaming](http://arxiv.org/abs/2611.26619v1)
- [One Prior, Two Dynamics: Repurposing Video Diffusion Transformers for Self-Supervised Latent Action Learning](http://arxiv.org/abs/2611.26617v1)
- [AgentRoboCritic: Understanding the Capability of Frontier Agents on Direct Robot Control](http://arxiv.org/abs/2611.26613v1)
- [Bio-PM-Guided Synthetic IMU Generation](http://arxiv.org/abs/2611.26607v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-11-22 11:20:23`

#### Tesla
- [Cathie Wood, Brad Gerstner and 16 Other Big Funds Bought Tesla Last Quarter, While 15 Sold. Who’s Right?](https://finance.yahoo.com/markets/stocks/articles/cathie-wood-brad-gerstner-16-211905292.html)
- [Tesla (TSLA) Stock Looks Richly Priced After Its 47% Three Year Run](https://finance.yahoo.com/markets/stocks/articles/tesla-tsla-stock-looks-richly-210854263.html)
- [Tesla FSD V15 Rolling Out, Goes 'Wide' Next Month. Elon Musk Says It's 'Something Special.'](https://finance.yahoo.com/m/b31af40e-5144-3249-9033-82521507fe84/tesla-fsd-v15-rolling-out%2C.html)
- [Musk Says Cybercab “Covers About 90%” of Passenger Miles. Tesla’s Next Robotaxi Is a Wheel-Less Model Y](https://finance.yahoo.com/technology/articles/musk-says-cybercab-covers-90-195203108.html)

### 🔵 Google 動態
> `2026-11-22 11:20:20`

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
> `2026-11-22 11:20:25`

#### Indices
- S&P 500: 6,910.39 ▼5.64%
- 台股加權: 36,033.29 ▼6.23%
- 日經 225: 56,436.65 ▼5.06%

### 🏠 台灣房市
> `2026-11-22 11:21:22`

#### AI 分析
## 台灣房市速報（2026-11-22）

**1. 整體趨勢**
央行選擇性信用管制持續發酵，投資買盤退場，市場回歸自住剛需；六都成交量較去年縮減約一到兩成，價格呈現「蛋黃區撐盤、蛋白區鬆動」的格局。高總價住宅（逾 5,000 萬）成交明顯放緩，但精華地段單價仍具支撐（實價登錄可見單價 27–45 萬/㎡ 的個案，換算約 90–150 萬/坪）。

**2. 值得注意的地區與物件**
- **中科、台積電周邊（台中大雅、西屯）**：租賃需求強勁，兩房平車、可租補物件去化快，適合收租型布局。
- **桃園平鎮、中壢交界**：3 房雙車露臺戶等換屋型產品供給增加，議價空間較大。
- **新北汐止、五股**：廠辦與山莊別墅等特殊產品，總價帶分散，需留意流動性風險。
- **高雄科工館、捷運沿線透天**：軌道經濟仍是少數抗跌題材。

**3. 對自住者的建議**
- 善用「新青安」與租金補貼政策紅利，優先鎖定**近捷運／近產業園區**的中小坪數產品。
- 蛋白區議價空間已打開，可大膽出價（實登價往下 5–10% 起談），但避開供給量大的重劃區。

**4. 對投資者的建議**
- 高總價、大坪數產品（如實登 9 百萬㎡ 級物件）流動性差，**不建議追高**。
- 改採「**先租後售**」或鎖定**台積電／中科就業人口**的租補型兩房，以租金現金流撐過盤整期。
- 密切關注央行是否鬆綁第二戶貸款成數，將是下一波進場訊號。

**5. 風險提醒**
115 年 Q3 實登高總價樣本集中於特定行政區，均價易失真；掛牌物件（如平鎮露臺戶、五股別墅）去化天數恐拉長，議價前務必比對同社區近半年成交。

#### 591 最新
- [桃園市桃園區福山街【雙租屋補助】木貼地板、流理臺✨電梯、貓咪友善✨獨立陽台，新](https://rent.591.com.tw/rent-detail-22388718.html)
- [台中市大雅區中清北街🌟舒潔🧻🟣大雅2房平車/租補/大雅市區/近中科台積電](https://rent.591.com.tw/rent-detail-22388717.html)
- [桃園市平鎮區中豐路南勢一段獨家專賣❗️中豐路帝王{宜雄丰疆}3房雙車露臺戶](https://sale.591.com.tw/sale-detail-21301504.html)
- [新北市汐止區福德二路259巷福德星鑽一樓大空間廠辦](https://sale.591.com.tw/sale-detail-21301503.html)
- [高雄市三民區九如一路543巷科工館車站/捷運宅/邊間透天/騎樓停車](https://sale.591.com.tw/sale-detail-21301502.html)
- [新北市五股區水碓三路水碓特區山莊別墅](https://sale.591.com.tw/sale-detail-21301501.html)
- [台中市西區大忠南街🌟舒潔🧻🟣✨兩房兩廳雙陽台✨可小型寵物✨台水台電✨](https://rent.591.com.tw/rent-detail-22388716.html)
- [新竹縣竹北市博愛街昌益四季｜台元溫馨三房平車](https://sale.591.com.tw/sale-detail-21301500.html)

#### 實價登錄 (115S3) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 住宅大樓(11層含以上有電梯) | 963.3㎡ | 29664萬 | 307937元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 399.6㎡ | 14468萬 | 449312元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 379.7㎡ | 10438萬 | 274908元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 267.7㎡ | 8558萬 | 367305元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 144.7㎡ | 5700萬 | 456525元/㎡ |

### 📊 Watchlist
> `2026-11-22 11:20:54`

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
- [The Rise of “Just-in-Case” ETFs for Uncertain Markets: What You Need to Know](https://finance.yahoo.com/markets/options/articles/rise-just-case-etfs-uncertain-025802431.html) — Motley Fool
- [ULA Vulcan Launch Ends in Disaster for Amazon's Satellite Internet Ambitions](https://finance.yahoo.com/technology/articles/ula-vulcan-launch-ends-disaster-024702998.html) — Motley Fool
- [The Smartest Dividend Stock to Buy With $1,000 Right Now](https://finance.yahoo.com/markets/stocks/articles/smartest-dividend-stock-buy-1-022102400.html) — Motley Fool

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
| 52-Week | 188.22 – 658.52 |
| Div. Yield | — |

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
- [Nvidia Stock Has Crashed 48% and Now Trades at 15 Times Earnings, Its Cheapest in More Than a Decade and Cheaper Than Microsoft and Broadcom](https://finance.yahoo.com/markets/stocks/articles/nvidia-stock-crashed-48-now-004700969.html) — 24/7 Wall St.
- [Stanley Druckenmiller, David Tepper and 45 Other Big Funds Sold Alphabet Last Quarter, While 31 Bought. Who’s Right?](https://finance.yahoo.com/markets/stocks/articles/stanley-druckenmiller-david-tepper-45-211908362.html) — TIKR
- [Dell Up 447% In 5 Years, HPE 220%: What Did Michael Dell Do Differently?](https://finance.yahoo.com/markets/stocks/articles/dell-447-5-years-hpe-183203804.html) — Trefis

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
- [Nvidia Stock Has Crashed 48% and Now Trades at 15 Times Earnings, Its Cheapest in More Than a Decade and Cheaper Than Microsoft and Broadcom](https://finance.yahoo.com/markets/stocks/articles/nvidia-stock-crashed-48-now-004700969.html) — 24/7 Wall St.
- [Alphabet (GOOGL) Stock Gets Fair Value Trim As Analysts Weigh AI Spending And Monetization](https://finance.yahoo.com/markets/stocks/articles/alphabet-googl-stock-gets-fair-001209637.html) — Simply Wall St.
- [AppLovin vs. Reddit: Which Technology Stock Is a Better Buy for 2027?](https://finance.yahoo.com/markets/stocks/articles/applovin-vs-reddit-technology-stock-233926901.html) — Motley Fool

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
- [ULA Vulcan Launch Ends in Disaster for Amazon's Satellite Internet Ambitions](https://finance.yahoo.com/technology/articles/ula-vulcan-launch-ends-disaster-024702998.html) — Motley Fool
- [Nvidia Stock Has Crashed 48% and Now Trades at 15 Times Earnings, Its Cheapest in More Than a Decade and Cheaper Than Microsoft and Broadcom](https://finance.yahoo.com/markets/stocks/articles/nvidia-stock-crashed-48-now-004700969.html) — 24/7 Wall St.
- [The Ultimate Growth Stock to Buy With $1,000 Before the End of November](https://finance.yahoo.com/markets/stocks/articles/ultimate-growth-stock-buy-1-002003561.html) — Motley Fool

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
- [Nvidia Stock Has Crashed 48% and Now Trades at 15 Times Earnings, Its Cheapest in More Than a Decade and Cheaper Than Microsoft and Broadcom](https://finance.yahoo.com/markets/stocks/articles/nvidia-stock-crashed-48-now-004700969.html) — 24/7 Wall St.
- [AppLovin vs. Reddit: Which Technology Stock Is a Better Buy for 2027?](https://finance.yahoo.com/markets/stocks/articles/applovin-vs-reddit-technology-stock-233926901.html) — Motley Fool
- [Oklo vs. NuScale Power: Which Nuclear Stock Is a Better Buy?](https://finance.yahoo.com/markets/stocks/articles/oklo-vs-nuscale-power-nuclear-223901232.html) — Motley Fool

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
- [Nvidia Stock Has Crashed 48% and Now Trades at 15 Times Earnings, Its Cheapest in More Than a Decade and Cheaper Than Microsoft and Broadcom](https://finance.yahoo.com/markets/stocks/articles/nvidia-stock-crashed-48-now-004700969.html) — 24/7 Wall St.
- [Cathie Wood Just Sold $6 Million of Broadcom](https://finance.yahoo.com/markets/stocks/articles/cathie-wood-just-sold-6-185132026.html) — TIKR
- [Microsoft Was The Only Big AI Buyer Paying Down Debt. How Much More Can It Spend?](https://finance.yahoo.com/markets/stocks/articles/microsoft-only-big-ai-buyer-183203505.html) — Trefis

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
- [SoftBank Falls 14%, and 72% of Arm’s Shares Sit Pledged Behind Its Loans](https://finance.yahoo.com/markets/stocks/articles/softbank-falls-14-72-arm-101747234.html) — TIKR
- [Arm (ARM) Stock Looks Undervalued Despite Rich Sales Expectations](https://finance.yahoo.com/markets/stocks/articles/arm-arm-stock-looks-undervalued-021442325.html) — Simply Wall St.
- [Prediction: Nvidia Stock Will Do This in the 6 Months After a New CEO Takes Over, According to History](https://finance.yahoo.com/markets/stocks/articles/prediction-nvidia-stock-6-months-000251264.html) — Motley Fool

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
- [Palantir Just Dropped 25% in a Month. Is It Time to Sell, or Load Up?](https://finance.yahoo.com/markets/stocks/articles/palantir-just-dropped-25-month-142235001.html) — TIKR
- [Alex Karp Wants to Sell $100 Million of Palantir Stock as It Slides](https://finance.yahoo.com/markets/stocks/articles/alex-karp-wants-sell-100-131740800.html) — 24/7 Wall St.
- [If You Invest $500 in Palantir Each Month Starting Now, This is What You’d Have in 5 Years](https://finance.yahoo.com/markets/stocks/articles/invest-500-palantir-month-starting-160409470.html) — 24/7 Wall St.

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
- [Dell Up 447% In 5 Years, HPE 220%: What Did Michael Dell Do Differently?](https://finance.yahoo.com/markets/stocks/articles/dell-447-5-years-hpe-183203804.html) — Trefis
- [Supermicro Stock In Focus After AI Revenue Outlook Lift](https://finance.yahoo.com/markets/stocks/articles/supermicro-stock-focus-ai-revenue-121208287.html) — Simply Wall St.
- [Super Micro Just Dropped 33% in a Month After a Record Quarter. Is It Time to Sell, or Load Up?](https://finance.yahoo.com/markets/stocks/articles/super-micro-just-dropped-33-100833209.html) — TIKR

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
- [Cathie Wood, Brad Gerstner and 16 Other Big Funds Bought Tesla Last Quarter, While 15 Sold. Who’s Right?](https://finance.yahoo.com/markets/stocks/articles/cathie-wood-brad-gerstner-16-211905292.html) — TIKR
- [Tesla (TSLA) Stock Looks Richly Priced After Its 47% Three Year Run](https://finance.yahoo.com/markets/stocks/articles/tesla-tsla-stock-looks-richly-210854263.html) — Simply Wall St.
- [Tesla FSD V15 Rolling Out, Goes 'Wide' Next Month. Elon Musk Says It's 'Something Special.'](https://finance.yahoo.com/m/b31af40e-5144-3249-9033-82521507fe84/tesla-fsd-v15-rolling-out%2C.html) — Investor's Business Daily

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
- [His Indexed Annuity Tracks the S&P 500. The Fine Print Says “Price Return,” Which Means It Leaves Out Every Dividend the 500 Companies Pay](https://finance.yahoo.com/markets/options/articles/indexed-annuity-tracks-p-500-210349574.html) — 24/7 Wall St.
- [The S&P 500 Is Now Below Every Wall Street Year-End Target for 2026](https://finance.yahoo.com/markets/stocks/articles/p-500-now-below-every-204200722.html) — 24/7 Wall St.
- [Investors Put $45.7 Billion Into U.S. Stock Funds Right Before the Stock Market Tanked](https://finance.yahoo.com/markets/stocks/articles/investors-put-45-7-billion-164358940.html) — 24/7 Wall St.

## 🌍 News

### 🌍 World News
> `2026-11-22 11:21:25`

- [Zelensky says Crimean Bridge strikes 'fair response' as he meets UK's Streeting](https://www.bbc.co.uk/news/articles/c6wy0qj7w5zqo?at_medium=RSS&at_campaign=rss)
- [Russia-bound ship attacked in Gulf of Finland](https://www.bbc.co.uk/news/articles/cj752ddve27ko?at_medium=RSS&at_campaign=rss)
- [Fight over fossil fuels leaves COP31 climate talks in deadlock](https://www.bbc.co.uk/news/articles/c6ly5w40eg07o?at_medium=RSS&at_campaign=rss)
- [Mexican drug lord on FBI's 10 most wanted list arrested in shoot-out](https://www.bbc.co.uk/news/articles/ckz749ey0r75o?at_medium=RSS&at_campaign=rss)
- [FBI reportedly investigating apparent hack of its criminal database](https://www.bbc.co.uk/news/articles/cvze7de86pk3o?at_medium=RSS&at_campaign=rss)
- [Denmark accuses Russia of plotting to assassinate US-Ukrainian rapper](https://www.bbc.co.uk/news/articles/cmde1lj4yjxno?at_medium=RSS&at_campaign=rss)
- [Man convicted of starting Palisades fire in Los Angeles](https://www.bbc.co.uk/news/articles/c64gn0gy8rj3o?at_medium=RSS&at_campaign=rss)
- [Lock of former US President George Washington's hair sells for $4,000](https://www.bbc.co.uk/news/articles/cwe9k23dpz0do?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-11-22 11:21:35`

#### AI Tips
# 📷 2026-11-22 攝影顧問日報

## 【購買優惠】台灣買相機裝備攻略

#### 通路比較（依需求選擇）

| 通路 | 適合買什麼 | 注意事項 |
|------|-----------|---------|
| **PChome 24h** | 公司貨機身/鏡頭、記憶卡、腳架 | 常有「滿萬折千」、信用卡回饋疊加；到貨快但價格偏硬，比價後再下單 |
| **momo** | 促銷組合、配件、入門機 | 雙11後仍有「黑五暖身」檔期；注意是否為公司貨、保固卡是否齊全 |
| **光華商場（台北）** | 議價空間大、二手鏡、水貨 | 當面驗貨、確認快門數與保固；現金價通常比刷卡便宜 2–3% |
| **日本代購/Bic Camera** | 日系鏡頭、富士/索尼機身 | 11月日圓匯率＋免稅＋折價券可省 15–25%；注意台灣保固不適用、關稅 |
| **二手（旋轉拍賣/DCView）** | 鏡頭、副廠配件 | 面交測試對焦、檢查霉斑與入塵；要求提供購買證明 |

#### 11月季節性優惠重點
- **雙11餘溫**：momo、PChome 11/11後一週仍有「返場」折扣，配件（電池、濾鏡、背帶）此時最划算。
- **黑五（11/27 前後）**：美系品牌（Peak Design、Manfrotto）代購與代理商常同步降價。
- **週年慶尾聲**：百貨公司相機專櫃（如法雅客）滿額贈＋禮券，適合買高單價機身。
- **年底出清**：11月底至12月，上一代機型（如 X-T4、A7 IV）降幅明顯，等新機者可留意。

> 💡 **顧問建議**：機身買公司貨（保固重要），鏡頭可考慮日本代購或二手（價差最大）。11月

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-11-22 11:21:39`

#### AI Tips
# 台灣潛水裝備購買指南（2026年11月）

## 購買優惠

**實體店（依地區）**
- **台北**：潛水人（Diving Pro）、海人潛水、BlueTrend 藍色趨勢 — 可試穿、議價空間較大，適合買防寒衣、BCD
- **台中**：潛水貨倉、海洋星球 — 中部潛友常去，二手寄賣區可撿便宜
- **高雄/墾丁**：墾丁大街周邊店家（如台灣潛水、CT Diver）— 旺季前後出清多，墾丁店家11月常推「淡季價」

**線上/社團**
- **Facebook 社團**：「台灣潛水二手裝備買賣」、「潛水裝備交流區」— 11月不少潛友換季出清防寒衣、調節器
- **蝦皮/露天**：比價用，但調節器、電腦錶建議買公司貨有保固
- **品牌官網**：Garmin（Descent系列）、Suunto 雙11前後常有折扣

**11月季節提示**
- 台灣東北角進入東北季風期，能見度下降、浪大，**本地潛季漸收**，店家開始清庫存 → 議價好時機
- 反過來，**前往東南亞（菲律賓、泰國、帛琉）的潛旅旺季開始**，出發前在台灣買輕裝（面鏡、蛙鞋、防寒衣）比當地便宜
- 雙11（11/11）電商檔期：電腦錶、水下相機（GoPro/Insta360）折扣最明顯
- 年底前買大件可留意店家「舊款出清」，新款通常春季

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-11-22 11:21:31`

#### AI Flight Tips — November
# November Flight Deals from Taiwan (TPE/TSA) — Quick Playbook

**Japan (Tokyo/Osaka/Sapporo)**
- November is peak for Kyoto/Osaka autumn foliage and early Sapporo snow, but late Nov (post-23rd) dips — target Nov 25–30 for 15–25% savings.
- Book 6–8 weeks out; LCCs (Tigerair Taiwan, Peach, Scoot) TPE–NRT/KIX run NT$4,000–7,000 one-way if booked 8 weeks ahead.
- Watch Peach's "Fly Peach" Tuesday sales and Scoot's monthly flash fares; Sapporo via Tokyo repositioning is often cheaper than direct CTS.

**Thailand (Bangkok/Chiang Mai)**
- November is start of cool/dry peak season (especially Chiang Mai for Yi Peng, ~Nov 24–25) — book Chiang Mai 10–12 weeks out; Bangkok is year-round and more forgiving at 6–8 weeks.
- Cheapest: Thai Lion Air or VietJet (via SGN/HAN) TPE–DMK ~NT$5,000–8,000; China Airlines/Starlux direct BKK often NT$9,000–12,000 round-trip on promo.
- Watch VietJet's "0đ" promos and Thai Lion's Wednesday flash sales; avoid Yi Peng week for Chiang Mai unless attending.

**Europe (any major city)**
- November is deep off-peak (post-foliage, pre-Christmas markets) — cheapest month of Q4; late Nov Christmas-market city deals (Vienna, Prague, Munich) start appearing.
- Book 10–14 weeks out for best fares; 8 weeks is the practical cutoff before prices climb.
- Cheapest routing: China Eastern/China Southern via PVG/CAN to FRA/CDG/AMS (~NT$18,000–24,000 round-trip); Turkish via IST is a strong one-stop value.
- Watch China Eastern's 11.11 and Black Friday (late Nov) promos; avoid routing through mainland China if you need visa-free transit certainty.

**USA (West/East Coast)**
- November is shoulder-to-off-peak except Thanksgiving week (Nov 24–30) — avoid that window entirely; early Nov is cheapest.
- Book 8–12 weeks out; West Coast (LAX/SFO/SEA) is far cheaper than East Coast from TPE.
- Cheapest: Starlux/China Airlines direct LAX/SFO on promo (~NT$28,000–35,000 RT); EVA Air "Early Bird" fares; for East Coast, one-stop via LAX/SEA on Alaska or via ICN on Korean often beats direct.
- Watch Black Friday/Cyber Monday (Nov 27–30) airline sales for spring 2027 travel; EVA and Starlux both run late-Nov promos.

**Egypt (Cairo)**
- November is peak for Egypt (cool, comfortable sightseeing weather) — book 10–12 weeks out; prices firm up fast.
- No direct TPE–CAI; cheapest is China Eastern via PVG or Emirates/Qatar via Gulf (~NT$30,000–38,000 RT). Turkish via IST is often the value sweet spot.

## 📚 Learning

### 📚 Learning — Finance
> `2026-11-22 11:21:42`

#### 📚 Today's Concept: Index Fund vs. ETF differences

What it is: An index fund is any fund that tracks a market index, and it can be structured as a mutual fund or an ETF; the ETF is just the container, not the strategy. The real difference is trading mechanics: mutual funds trade once daily at net asset value after market close, while ETFs trade intraday like a stock with a bid-ask spread.

Why it matters: For a buy-and-hold engineer automating contributions, a low-cost index mutual fund avoids spreads and lets you buy exact dollar amounts, while an ETF gives intraday flexibility and often lower taxes but adds trading friction.

Example: You invest $1,000 monthly in an S&P 500 tracker. A mutual fund version charges 0.04% expense ratio and fills at 4pm NAV, so you get $1,000 of exposure exactly. The ETF version charges 0.03% but trades at $450/share with a $0.02 spread, so you buy 2 shares ($900) and leave $100 idle unless you use fractional shares.

Rule of thumb: Compare total cost of ownership, not headline expense ratio; if you trade small amounts frequently, spreads and idle cash can erase the ETF's fee advantage.

### 🧩 LeetCode Blind 100
> `2026-11-22 11:21:45`

#### 🧩 Blind 100 — 150. Evaluate Reverse Polish Notation [Stack]
**連結:** https://leetcode.com/problems/evaluate-reverse-polish-notation/
> 📅 **Today's Daily Challenge:** #2243 Check if All A's Appears Before All B's [Easy] — Tags: String — https://leetcode.com/problems/check-if-all-as-appears-before-all-bs/

## **Problem Type:** Stack / Expression Evaluation

**Key Insight:** RPN is naturally stack-friendly — push operands, and when you hit an operator, pop the top two values, apply the operator, and push the result back. The final stack value is the answer.

**Approach:**
1. Initialize an empty stack.
2. Iterate through tokens:
   - If token is an operator (`+ - * /`), pop `b` then `a` (order matters!), compute `a op b`, push result.
   - Otherwise, convert token to `int` and push.
3. Return `stack[-1]`.

**Python3 Solution:**
```python
class Solution:
    def evalRPN(self, tokens: List[str]) -> int:
        stack = []
        ops = {
            "+": lambda a, b: a + b,
            "-": lambda a, b: a - b,
            "*": lambda a, b: a * b,
            "/": lambda a, b: int(a / b),  # truncate toward zero
        }
        for t in tokens:
            if t in ops:
                b = stack.pop()
                a = stack.pop()
                stack.append(ops[t](a, b))
            else:
                stack.append(int(t))
        return stack[0]
```

**Complexity:** Time O(n) | Space O(n)

**Blind 100 Note:** Classic **stack-based expression evaluation** — the canonical intro to using a stack for parsing/state. Teaches operand ordering and integer division semantics. Similar problems: *Basic Calculator I/II*, *Valid Parentheses*, *Decode String*, *Asteroid Collision*.

**Contest Tips:**
- **Order matters:** pop `b` first, then `a`; compute `a - b` and `a / b` (not reversed).
- **Division truncates toward zero**, not floor — use `int(a / b)` (or `int(a/b)` via float) rather than `a // b`, which floors negatives incorrectly (e.g. `-7 // 2 == -4`, but answer is `-3`).
- Tokens are strings — always `int(t)` before pushing.
- No need to check stack size; input is guaranteed valid RPN.
- Avoid `eval()` — slower and unsafe; the dict-of-lambdas is fast and clean.

### 📷 Learning — Photography
> `2026-11-22 11:21:50`

#### 📷 Today's Concept: Light — Hard Light vs Soft Light Characteristics

**What it is:** Hard light comes from a small or distant source and creates crisp, defined shadows with high contrast. Soft light comes from a large or close source and wraps around subjects with gradual, feathered shadow edges.

**Why it matters:** Shadow quality controls mood and texture—hard light adds drama and definition, soft light flatters skin and smooths detail. Choosing the right quality is the fastest way to change a portrait's feel.

**How to apply it:**
1. Judge the shadow edge, not the source: sharp edge = hard, gradual edge = soft.
2. For soft light, enlarge the source relative to your subject—move a window, diffuser, or bounce closer.
3. For hard light, use direct sun, a bare speedlight, or move the source farther away.
4. Match quality to purpose: soft for flattering portraits, hard for gritty street and dramatic character shots.
5. In landscape, shoot hard light at golden hour for texture, or overcast soft light for even tones.

**Sony A7C tip:** Use the flip-out screen and zebras (set to ~95%) to protect highlights when shooting hard midday light—hard light clips fast on the A7C's full-frame sensor.

**Common mistake:** Beginners soften light by lowering power instead of enlarging the source—dimming a small light keeps shadows hard. Fix it by adding diffusion or moving the modifier closer, not by turning it down.

### 📚 Learning — Tech
> `2026-11-22 11:21:47`

#### 📚 Today's Concept: Zero-downtime Database Migrations

**What it is:** Zero-downtime database migrations are schema changes deployed in backward-compatible steps so the application keeps running during the transition. Instead of one atomic change, you split it into phases where old and new code can coexist.

**When to use it:** Any production system with continuous traffic where a migration lock or breaking change would cause errors or outages. E.g., renaming a column on a high-traffic users table while the app is actively serving requests.

**Example:** Renaming `name` → `full_name` in three deploys:
```sql
-- Deploy 1: add new column, dual-write
ALTER TABLE users ADD COLUMN full_name TEXT;
-- app writes to both name and full_name
-- Deploy 2: backfill
UPDATE users SET full_name = name WHERE full_name IS NULL;
-- Deploy 3: switch reads to full_name, then drop name
ALTER TABLE users DROP COLUMN name;
```

**Gotcha:** People assume a single `ALTER TABLE` is "fast enough." On large tables, operations like adding a non-nullable column or creating an index without `CONCURRENTLY` can lock the table for minutes—causing exactly the downtime you were trying to avoid.

### 🎬 Learning — YouTube
> `2026-11-22 11:21:53`

#### 🎬 今日主題：開箱 — 開箱影片的 Amazon / 聯盟行銷 CTA 策略
**類別：** 開箱

**是什麼：** 在開箱影片中自然置入 Amazon 聯盟連結，讓觀眾看完想買時點擊購買，你賺取分潤佣金。這是開箱頻道最直接的變現方式。

**為什麼重要：** 開箱影片觀眾本來就有購買意圖，CTA 做得好能把觀看流量轉成實際收入，讓你在訂閱數還少時就有現金流支撐創作。

**怎麼做：**
1. 影片說明欄第一行放完整聯盟連結，並標註「透過此連結購買我可能獲得回饋」。
2. 片中口頭 CTA 放在「使用心得」之後，例如「連結在下方，有興趣可以看看」。
3. 用固定片尾畫面（End Screen）放「商品連結在說明欄」字卡。
4. 挑 1–2 個你真心推薦的產品做重點 CTA，不要每個都推。
5. 在留言置頂補一次連結，方便手機觀眾。

**新手常犯的錯：** 開頭就急著推銷連結，觀眾還沒看到價值就跳出。先給完整開箱與真實評價，CTA 放中後段才有效。

**延伸 idea：** 拍「A7C 實拍一個月後，我後悔嗎？」——用真實使用心得開箱相機，中段自然帶入配件聯盟連結（記憶卡、電池、背帶），符合攝影主題又有說服力。
