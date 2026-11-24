---
date: 2026-11-24
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-11-24

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

- **台股單日暴漲 8.99% 至 40,122.35** — 加權指數出現罕見單日狂飆，遠超全球其他市場，若你持有台股部位，今天絕對是主場焦點。同時日經 +3.91%、S&P 500 +0.85%，亞洲全面領漲。
- **NVIDIA 單日 +31.48%（$165.05）** — 這是 mega-cap 等級的異常漲幅，務必先確認催化劑（財報？guidance？）再行動，短線均值回歸風險高。Broadcom 反向 -9.55%，若屬情緒性賣壓可留意進場點。
- **GLM-5.4 發表「loop transformer」架構** — 今日 HN 最大條，主打 generalized coding，值得一看架構思路：https://z.ai/blog/glm-5.4
- **Gemini API 兩項開發者更新** — Tool Retrieval（數百工具、更省 token）與 File Slicing Controls + 原生 Office 檔支援，對 agent 開發直接可用：https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/
- **SpaceX/Tesla 傳出 $3.5 兆合併談判**（FT）— 對 Musk 的 AI/機器人 roadmap 影響深遠，值得追蹤：[link](https://finance.yahoo.com/markets/stocks/articles/spacex-tesla-directors-negotiate-potential-062339987.html)

---

- 💻 **Tech**: GLM-5.4 loop transformer 登場、C++26 定案、OpenAI 開源 Linux 防護 runtime Shirudo，agent 工具鏈（Claude Ship / Genesis Map）齊發。
- 🤖 **AI 公司動態**: Tesla 三則（合併談判、股價動能、歐洲註冊 +3.4%）；OpenAI/Anthropic 今日無新聞。
- 🔵 **Google**: Gemini API Tool Retrieval 與 File Slicing、語意治理防 prompt injection、跨雲 agent 異常偵測、Gemini Enterprise 認證與 MCP 連接指南。
- 📈 **Markets**: 台股 +8.99% 一枝獨秀，全球 risk-on，亞洲領漲、美股穩健。
- 🏠 **台灣房市**: 量縮價盤，信用管制持續；自住看雙北社宅/租補，投資避高總價大坪數。
- 📊 **Watchlist**: AI 大型股全面收紅，NVDA/TSLA/PLTR 領漲；Broadcom -9.55% 為唯一明顯拖累；估值數據全 N/A，進場前需另查本益比。
- 🌍 **World News**: Trump-Nvidia 爭議、美擬將 Megaspeed 列入黑名單、NATO 太空威脅、烏克蘭戰事延伸至利比亞、Gaza 人道與伊朗事件。
- 📷 **Camera Deals**: 黑五（11/27–30）周邊閃購最殺、機身等 12 月；日本代購價差 10–15% 但無台保固；光華月底議價成功率最高。
- 🤿 **Dive Gear Deals**: 東北季風起、北部淡季議價空間大；雙11 輕裝 5–7 折；二手調節器/氣瓶務必送檢。
- ✈️ **Flight Tips**: 11 月歐洲全年最便宜、日本賞楓旺季、泰國 Loy Krathong 訂位要早、埃及旺季票價爬升快、澳洲 11 月中後轉貴。
- 📚 **Learning — Finance**: 債券殖利率與價格反向；10 年美債殖利率是折現率旋鈕，急升時高本益比科技股承壓。
- 🧩 **LeetCode Blind 100**: #200 Number of Islands — grid 當 graph 的 flood fill 模板；今日 Daily Challenge #3702（Easy）。
- 📷 **Learning — Photography**: A7C 的 IBIS + OIS 聯手，Active SteadyShot + 忍者步 + 1/50–1/60s 快門換取電影感。
- 📚 **Learning — Tech**: Saga pattern 用補償動作換取跨服務最終一致性；別誤以為有 AC

---

## 💻 Tech

### 💻 Tech & AI
> `2026-11-24 15:01:11`

#### Hacker News
- [Declare is a UI language for you and your AI](https://davidtemkin.github.io/declarelang/) ⭐38
- [Latent Introspection: LLMs Can Detect Prior Concept Injections](https://arxiv.org/abs/2602.20031) ⭐52
- [GLM-5.4: Toward generalized coding with our first loop transformer](https://z.ai/blog/glm-5.4) ⭐1101
- [Kagi Mail (public beta)](https://blog.kagi.com/kagi-mail-public-beta) ⭐398
- [C++26 is done (again): ISO C++ meeting trip report](https://herbsutter.com/2026/11/21/c26-is-done-again-trip-report-november-2026-iso-c-standards-meeting-buzios-brazil/) ⭐112
- [Shirudo: OpenAI and Cisco's open-source runtime for shielding unpatched Linux](https://openai.com/index/introducing-shirudo/) ⭐63
- [Show HN: Genesis Map – Visualize your agent's changes. See where they can break](https://github.com/GenesisAgentInfra/genesis) ⭐5
- [Developing the perception to separate the form of a place from what it contains](https://www.thedeletedscenes.com/p/blight-and-entrepreneurship-in-manassas) ⭐18
- [Claude Ship](https://claude.com/resources/articles/introducing-claude-ship) ⭐47
- [How should an LLM see a computer?](https://www.greptile.com/blog/trex-computer-use) ⭐50

#### HuggingFace
- [What Makes Good Data for Training Coding Agents? A Systematic Study on SWE-Gym](https://huggingface.co/papers/2611.30207)
- [HIVE-Bench: Evaluating Patch-Level Visual Representations for Egocentric Robot Manipulation](https://huggingface.co/papers/2611.30813)
- [RUIBench: What Makes a Good Robot-Use Interface?](https://huggingface.co/papers/2611.31115)
- [WorldLeague: Benchmarking Physical Agency](https://huggingface.co/papers/2611.30989)
- [Write, Evolve, Read: Streaming Cameras into a Persistent World State for 4D Occupancy Forecasting](https://huggingface.co/papers/2611.30573)
- [Distill the Correction, Not the Rewrite: Hindsight Twins for Self-Improving Text-to-Image Models](https://huggingface.co/papers/2611.31048)

#### ArXiv
- [TrialAgentBench: Evaluating AI Agents for Clinical-Trial Analysis and Long-Horizon Drug-Development Decisions](http://arxiv.org/abs/2611.30916v1)
- [Replay Before You Reply: Second-Look Prompting for Unified Multimodal Encoding](http://arxiv.org/abs/2611.30909v1)
- [DexLatentWorld: 3D Cross-Embodiment Latent Action World Models for Zero-Shot Robotic Manipulation](http://arxiv.org/abs/2611.30907v1)
- [World Models as Native Latent Action Models](http://arxiv.org/abs/2611.30898v1)
- [Predicting Rare-Mode Collapse in Recursive Generative Training from Single-Generation Calibration](http://arxiv.org/abs/2611.30897v1)
- [Speak When You See It: Proactive Task Assistants Should Wait for Evidence, Not the Clock](http://arxiv.org/abs/2611.30895v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-11-24 15:01:17`

#### Tesla
- [SpaceX, Tesla directors negotiate potential $3.5 trillion merger, FT reports](https://finance.yahoo.com/markets/stocks/articles/spacex-tesla-directors-negotiate-potential-062339987.html)
- [Prediction: 1 "Magnificent Seven" Stock That Will Lag the Market in 2027](https://finance.yahoo.com/markets/stocks/articles/prediction-1-magnificent-seven-stock-062002007.html)
- [Europe new car registrations rise 3.4% in Oct as EV, hybrids maintain lead- ACEA](https://finance.yahoo.com/markets/stocks/articles/europe-car-registrations-rise-3-055350520.html)
- [Dow Jones Futures: Tech Stocks, Nvidia Snap Back On Jensen Huang's Return; Elon Musk-Led SpaceX, Tesla Rally](https://finance.yahoo.com/m/be493228-4ecf-338d-9017-054d3d6efc36/dow-jones-futures%3A-tech.html)

### 🔵 Google 動態
> `2026-11-24 15:01:14`

#### Google AI Blog
- [A more tailored Google Search that’s uniquely yours](https://blog.google/products-and-platforms/products/search/google-search-personal-intelligence-apps/)
- [Introducing Tool Retrieval in the Gemini API](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/)
- [Walter Isaacson on curiosity and creativity in the AI age.](https://blog.google/innovation-and-ai/technology/ai/dialogues-walter-isaacson/)
- [The Gemini app is now available on lower-memory Android devices.](https://blog.google/innovation-and-ai/products/gemini-app/gemini-lower-memory-devices/)
- [Put Gemini to work for you](https://blog.google/innovation-and-ai/products/gemini-app/tasks-in-gemini-free-new-features/)
#### Google Blog
- [See what 6 builders are making with Gemini 4 Hydrogen](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-4-hydrogen-builders/)
- [Here are 4 things you didn’t know you could do with Gemini Canvas.](https://blog.google/innovation-and-ai/products/gemini-app/gemini-canvas-tasks/)
- [A more tailored Google Search that’s uniquely yours](https://blog.google/products-and-platforms/products/search/google-search-personal-intelligence-apps/)
- [Organize and share your holiday memories with these five updates in Google Photos.](https://blog.google/products-and-platforms/products/photos/google-photo-tools-holiday-season-2026/)
- [Introducing file slicing controls in the Gemini API](https://blog.google/innovation-and-ai/technology/developers-tools/file-slicing-controls/)
#### Google Developers
- [Did the user ask for this? Securing AI agents against intent hijacking with Semantic governance policies](https://developers.googleblog.com/did-the-user-ask-for-this-securing-ai-agents-against-intent-hijacking-with-semantic-governance-policies/)
- [How to handle user, connector, and agent auth in Gemini Enterprise with a custom UI](https://developers.googleblog.com/how-to-handle-user-connector-and-agent-auth-in-gemini-enterprise-with-a-custom-ui/)
- [How to securely connect internal Cloud Run MCP servers to Gemini Enterprise](https://developers.googleblog.com/how-to-securely-connect-internal-cloud-run-mcp-servers-to-gemini-enterprise/)
- [Agent Anomaly Detection: Safeguarding agents across other clouds](https://developers.googleblog.com/agent-anomaly-detection-safeguarding-agents-across-other-clouds/)
- [Check what your AI agents do before they do it, with Semantic governance policies](https://developers.googleblog.com/check-what-your-ai-agents-do-before-they-do-it-with-semantic-governance-policies/)

## 📈 Finance

### 📈 Markets Overview
> `2026-11-24 15:01:19`

#### Indices
- S&P 500: 7,237.17 ▲0.85%
- 台股加權: 40,122.35 ▲8.99%
- 日經 225: 58,644.63 ▲3.91%

### 🏠 台灣房市
> `2026-11-24 15:02:09`

#### AI 分析
## 台灣房市速報（2026-11-24）

**1. 整體趨勢**
央行選擇性信用管制持續，投資買盤退場，市場以自住與剛需為主；高總價住宅交易量縮但單價仍撐，呈現「量縮價盤」格局。租賃市場因社宅與租補政策活絡，雙北租屋供給明顯增加。

**2. 值得注意的地區／物件**
- **高總價蛋黃區**：實價登錄115S3出現多筆單價45萬/㎡上下（約148萬/坪）的住宅大樓成交，顯示台北核心區高資產族群仍有撐盤力道，但總價近3億的963㎡物件單價僅30.8萬/㎡，大坪數去化壓力浮現。
- **雙北社宅租賃**：中和、三重、五股多筆「兆基社會住宅」掛牌，免仲介費、可租補，租賃CP值高，適合短期居住或小資族。
- **宜蘭壯圍華廈**：低總價新案，適合預算有限的首購或退休置產，但須留意區域機能與轉手性。

**3. 對自住者建議**
優先鎖定雙北社宅或租補物件降低居住成本；購屋則聚焦中古電梯大樓、避開大坪數高總價產品，議價空間較大。

**4. 對投資者建議**
高總價住宅流動性轉差，短線進出風險高；可關注租賃需求穩定的雙北小宅與社宅周邊，但報酬率受政策壓抑，宜以長期持有、現金流為主。

**5. 風險提醒**
信用管制與囤房稅2.0持續發酵，非自用持有成本上升；實價登錄高總價樣本偏少，不宜過度解讀單價，須留意區域差異與議價空間。

#### 591 最新
- [宜蘭縣壯圍鄉永美路二段富登新21期華廈C1棟1樓](https://sale.591.com.tw/sale-detail-21314001.html)
- [台北市中正區和平西路二段【住商侯靜怡】和平西路中華路近萬華車站](https://sale.591.com.tw/sale-detail-21313996.html)
- [新北市中和區福祥路兆基社會住宅🏠中和福祥路3樓-3房免仲可租補](https://rent.591.com.tw/rent-detail-22376768.html)
- [台中市西屯區青海路二段青海家樂福旁/精美社區電梯大三房/採光好](https://rent.591.com.tw/rent-detail-22267637.html)
- [台北市大安區安和路一段P01租忠孝敦化站有車位面101景觀高層樓辦公採光佳](https://rent.591.com.tw/rent-detail-22036953.html)
- [新北市三重區文化北路85巷兆基社會住宅🏡雙捷運全新裝修機能佳可租補](https://rent.591.com.tw/rent-detail-21544493.html)
- [新北市五股區五福路52巷兆基社會住宅🏠羅姐帶你看/五股公寓3樓/租補](https://rent.591.com.tw/rent-detail-22368019.html)
- [台中市西屯區西屯路二段華園巷重慶商圈西屯路/巷內全新粉刷店面1～2樓三房平車/可神明營登](https://rent.591.com.tw/rent-detail-22213550.html)

#### 實價登錄 (115S3) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 住宅大樓(11層含以上有電梯) | 963.3㎡ | 29664萬 | 307937元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 399.6㎡ | 14468萬 | 449312元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 379.7㎡ | 10438萬 | 274908元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 267.7㎡ | 8558萬 | 367305元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 144.7㎡ | 5700萬 | 456525元/㎡ |

### 📊 Watchlist
> `2026-11-24 15:01:42`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 165.05 ▲31.48% |
| Market Cap | $3.98T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.9% / 66.1% / 62.5% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 14.92 |
| Beta | 2.25 |
| 52-Week | 124.50 – 243.37 |
| Div. Yield | — |

**Recent News:**
- [Bitcoin And Stocks Are Moving In Different Directions: Arthur Hayes Says Nvidia's Rally Is The 'Worst Thing' For Crypto](https://finance.yahoo.com/markets/crypto/articles/bitcoin-stocks-moving-different-directions-064525257.html) — Stocktwits
- [Bitcoin hovers around $60k amid little relief from rate, regulatory jitters](https://finance.yahoo.com/markets/crypto/articles/bitcoin-hovers-around-60k-amid-064423052.html) — Investing.com
- [Prediction: 1 "Magnificent Seven" Stock That Will Lag the Market in 2027](https://finance.yahoo.com/markets/stocks/articles/prediction-1-magnificent-seven-stock-062002007.html) — Motley Fool

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 453.46 ▲6.85% |
| Market Cap | $743.72B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.7% / 17.7% / 16.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 10.85 |
| Beta | 2.49 |
| 52-Week | 188.22 – 658.52 |
| Div. Yield | — |

**Recent News:**
- [AMD Stock Dips Overnight After Nvidia-Triggered Rally: AMD Registers 337M Shares For Resale Tied To OpenAI, Meta Warrants](https://finance.yahoo.com/markets/stocks/articles/amd-stock-dips-overnight-nvidia-034748107.html) — Stocktwits
- [Jensen Huang’s Return As Nvidia CEO Sparks AI Stock Rally, But Congressional Probes Loom – And Analysts See Risks Ahead](https://finance.yahoo.com/technology/ai/articles/jensen-huang-return-nvidia-ceo-023541664.html) — Stocktwits
- [Hewlett Packard Enterprise Q4 Earnings Call Highlights](https://finance.yahoo.com/markets/stocks/articles/hewlett-packard-enterprise-q4-earnings-011326859.html) — MarketBeat

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 492.50 ▲1.65% |
| Market Cap | $3.66T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.7% / 47.1% / 41.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 7.77 |
| Beta | 1.04 |
| 52-Week | 349.20 – 559.15 |
| Div. Yield | — |

**Recent News:**
- [The Inflation Math, Updated: The Fed Is Fighting Oil](https://finance.yahoo.com/economy/policy/articles/inflation-math-updated-fed-fighting-050642342.html) — Trefis
- [The 10-Year Topped 5% For The First Time Since 2007. What Happened Next?](https://finance.yahoo.com/markets/stocks/articles/10-topped-5-first-time-050642873.html) — Trefis
- [Why Did Palo Alto Networks Stock Fall?](https://finance.yahoo.com/markets/stocks/articles/why-did-palo-alto-networks-050642734.html) — Trefis

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 282.10 ▲6.34% |
| Market Cap | $3.44T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.3% / 50.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 5.10 |
| Beta | 1.23 |
| 52-Week | 264.22 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [Not Starlink. Not Starship. This SpaceX Business Could Be Worth $80 Billion on Its Own.](https://finance.yahoo.com/markets/stocks/articles/not-starlink-not-starship-spacex-055002627.html) — Motley Fool
- [The Inflation Math, Updated: The Fed Is Fighting Oil](https://finance.yahoo.com/economy/policy/articles/inflation-math-updated-fed-fighting-050642342.html) — Trefis
- [1966 Or 1995: Which Way Does America's $2.1 Trillion Deficit Go?](https://finance.yahoo.com/economy/policy/articles/1966-1995-way-does-americas-050642358.html) — Trefis

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 255.39 ▲3.47% |
| Market Cap | $2.76T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 51.4% / 13.1% / 16.9% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.49 |
| Beta | 1.50 |
| 52-Week | 196.00 – 287.20 |
| Div. Yield | — |

**Recent News:**
- [The Inflation Math, Updated: The Fed Is Fighting Oil](https://finance.yahoo.com/economy/policy/articles/inflation-math-updated-fed-fighting-050642342.html) — Trefis
- [Stocks Opened Up, Then Fell 3% By The Close. What Happened The Last 45 Times?](https://finance.yahoo.com/markets/stocks/articles/stocks-opened-then-fell-3-050642164.html) — Trefis
- [1966 Or 1995: Which Way Does America's $2.1 Trillion Deficit Go?](https://finance.yahoo.com/economy/policy/articles/1966-1995-way-does-americas-050642358.html) — Trefis

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 597.60 ▲6.55% |
| Market Cap | $1.53T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.0% / 32.9% / 31.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 5.60 |
| Beta | 1.28 |
| 52-Week | 520.26 – 779.82 |
| Div. Yield | — |

**Recent News:**
- [The Inflation Math, Updated: The Fed Is Fighting Oil](https://finance.yahoo.com/economy/policy/articles/inflation-math-updated-fed-fighting-050642342.html) — Trefis
- [1966 Or 1995: Which Way Does America's $2.1 Trillion Deficit Go?](https://finance.yahoo.com/economy/policy/articles/1966-1995-way-does-americas-050642358.html) — Trefis
- [AMD Stock Dips Overnight After Nvidia-Triggered Rally: AMD Registers 337M Shares For Resale Tied To OpenAI, Meta Warrants](https://finance.yahoo.com/markets/stocks/articles/amd-stock-dips-overnight-nvidia-034748107.html) — Stocktwits

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 313.55 ▼9.55% |
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
- [Watch these chip stocks for bargain buys after Nvidia’s post-reinstatement rally](https://finance.yahoo.com/markets/stocks/articles/watch-chip-stocks-bargain-buys-040218865.html) — Investing.com
- [Jensen Huang’s Return As Nvidia CEO Sparks AI Stock Rally, But Congressional Probes Loom – And Analysts See Risks Ahead](https://finance.yahoo.com/technology/ai/articles/jensen-huang-return-nvidia-ceo-023541664.html) — Stocktwits
- [AMD Stock Rallies Nearly 8% as a Bernstein Analyst Remains Bullish Despite the Hunterbrook Short Report](https://finance.yahoo.com/markets/stocks/articles/amd-stock-rallies-nearly-8-235832362.html) — TipRanks

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 176.67 ▼0.28% |
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
- [Nvidia’s Board Had Other Options: Robert Maciejko](https://finance.yahoo.com/markets/stocks/articles/nvidia-board-had-other-options-222213836.html) — CorpGov.com
- [Morning Movers: Nvidia skyrockets following reinstatement of CEO Jensen Huang](https://finance.yahoo.com/markets/stocks/articles/morning-movers-nvidia-skyrockets-following-222119736.html) — TipRanks
- [Nvidia, Dell, Micron, Anthropic, CrowdStrike, UnitedHealth, and More Stocks That Explain Today’s Market](https://finance.yahoo.com/m/76a3103b-f3de-364f-8cd8-90e453a902d8/nvidia%2C-dell%2C-micron%2C.html) — Barrons.com

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 159.36 ▲11.06% |
| Market Cap | $367.60B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.7% / 45.6% / 50.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 34.14 |
| Beta | 1.62 |
| 52-Week | 106.37 – 212.94 |
| Div. Yield | — |

**Recent News:**
- [Nvidia Stock Rebound Puts AI Infrastructure Stocks Back On The Radar](https://finance.yahoo.com/technology/ai/articles/nvidia-stock-rebound-puts-ai-021257945.html) — Simply Wall St.
- [Zeta Global Targets $2.3 Billion in 2028 Revenue as Organic Growth Accelerates](https://finance.yahoo.com/media-advertising/articles/zeta-global-targets-2-3-001237824.html) — MarketBeat
- [Where the AI Trade Goes After Jensen Huang](https://finance.yahoo.com/m/016acd67-c9d7-3842-a43f-a79f3eae6363/where-the-ai-trade-goes-after.html) — Barrons.com

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 24.53 ▲2.89% |
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
- [Nvidia, Dell, Micron, Anthropic, CrowdStrike, UnitedHealth, and More Stocks That Explain Today’s Market](https://finance.yahoo.com/m/76a3103b-f3de-364f-8cd8-90e453a902d8/nvidia%2C-dell%2C-micron%2C.html) — Barrons.com
- [Dell Wants Up to 45% More on Signed AI Deals. IREN Has a Big Problem](https://finance.yahoo.com/technology/ai/articles/dell-wants-45-more-signed-193847809.html) — TIKR
- [Trump Admits Falling Stocks Pushed Him to Phone Into Nvidia’s Board Meeting Himself](https://finance.yahoo.com/markets/stocks/articles/trump-admits-falling-stocks-pushed-193215456.html) — 24/7 Wall St.

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 385.46 ▲11.46% |
| Market Cap | $1.52T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.3% / 3.3% / 3.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.99 |
| Beta | 1.74 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [SpaceX, Tesla directors negotiate potential $3.5 trillion merger, FT reports](https://finance.yahoo.com/markets/stocks/articles/spacex-tesla-directors-negotiate-potential-062339987.html) — Investing.com
- [Prediction: 1 "Magnificent Seven" Stock That Will Lag the Market in 2027](https://finance.yahoo.com/markets/stocks/articles/prediction-1-magnificent-seven-stock-062002007.html) — Motley Fool
- [Europe new car registrations rise 3.4% in Oct as EV, hybrids maintain lead- ACEA](https://finance.yahoo.com/markets/stocks/articles/europe-car-registrations-rise-3-055350520.html) — Investing.com

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 663.91 ▲0.90% |
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
- [Retirees: Is Now the Time to Ditch S&P 500 Funds?](https://finance.yahoo.com/markets/stocks/articles/retirees-now-time-ditch-p-233302471.html) — Motley Fool
- [ETFs Pull In $57B Despite Tech Rout](https://finance.yahoo.com/markets/stocks/articles/etfs-pull-57b-despite-tech-230924421.html) — etf.com
- [Retiring On $2 Million? Sell BND Before SCHD](https://finance.yahoo.com/markets/stocks/articles/retiring-2-million-sell-bnd-221427295.html) — Trefis

## 🌍 News

### 🌍 World News
> `2026-11-24 15:02:13`

- [Trump faces backlash after saying he 'convinced' Nvidia to reinstate CEO Jensen Huang](https://www.bbc.co.uk/news/articles/cq5y1k8ez407o?at_medium=RSS&at_campaign=rss)
- [US to blacklist Asian AI firm Megaspeed after Nvidia scandal](https://www.bbc.co.uk/news/articles/cv98xpg5dg5zo?at_medium=RSS&at_campaign=rss)
- [Nato chief vows defence against space threat after Russian nuclear satellite reports](https://www.bbc.co.uk/news/articles/c9x2er1ry2mzo?at_medium=RSS&at_campaign=rss)
- [India's 'cockroach' party leader says he was stopped from flying to UK](https://www.bbc.co.uk/news/articles/cm5y1ezx2gqyo?at_medium=RSS&at_campaign=rss)
- [What strike on Russian ship in Libya says about spread of Ukraine war](https://www.bbc.co.uk/news/articles/cm894p88jzxpo?at_medium=RSS&at_campaign=rss)
- [Gisèle Pelicot 'humiliated' after nude photos sent to media to promote book](https://www.bbc.co.uk/news/articles/cm3eg502nxw2o?at_medium=RSS&at_campaign=rss)
- [Israeli attacks have turned Gaza into 'toxic wasteland', Oxfam says](https://www.bbc.co.uk/news/articles/c8r4gzzxvxl3o?at_medium=RSS&at_campaign=rss)
- [Iranian authorities flog singer who performed without hijab, lawyers say](https://www.bbc.co.uk/news/articles/cq1j6585l5g6o?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-11-24 15:02:24`

#### AI Tips
# 📷 今日攝影顧問報告 — 2026/11/24（週二）

---

## 【購買優惠】台灣買相機裝備攻略

#### 各通路優劣勢（2026年11月現況）

| 通路 | 適合買什麼 | 注意事項 |
|------|-----------|---------|
| **PChome 24h** | 公司貨機身、記憶卡、腳架 | 雙11後仍有「黑五暖身」折扣；留意「福利品」標示，保固通常較短 |
| **momo** | 鏡頭組合、配件 | 常有「滿萬折千」券，但比價前先確認是否為台灣公司貨（水貨保固差很多） |
| **光華商場** | 二手鏡頭、議價空間大 | 建議平日白天去，店家較有時間談；現金價通常再省3–5% |
| **日本代購** | 日系鏡頭（如Sony、Fujifilm） | 11月日圓匯率＋日本「年末商戰」前夕，機身價差可達10–15%，但**無台灣保固**，維修需寄回 |
| **二手（旋轉拍賣/DCView）** | 高階鏡頭、停產機種 | 面交必測：快門數、感光元件壞點、鏡頭霉斑（用手電筒側照） |

#### 🎯 11月季節性省錢時機
1. **黑色星期五（11/27–11/30）**：PChome、momo 會推「相機週邊」閃購，記憶卡、電池、濾鏡折扣最深，**機身反而要等12月週年慶尾聲**。
2. **雙11後的「退貨潮」**：11月中下旬二手平台會出現一批「拆封未用」品，議價空間大。
3. **日本代購**：11月底日本店家開始清庫存迎年末，但**避開12月旺季運費漲價**，現在下單較划算。
4. **光華商場**：月底店家拼業績，最後一週議價成功率最高。

> 💡 **顧問提醒**：買公司貨

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-11-24 15:02:29`

#### AI Tips
# 台灣潛水裝備購買指南（2026年11月）

## 購買優惠

**實體店（北台灣）**
- **潛水貨倉（Dive Warehouse）**：台北市中山區，代理多個國際品牌（Scubapro、Mares、Aqualung），常有舊款出清，議價空間較大。
- **海人潛水（Ocean Man）**：新北市板橋，維修服務口碑好，買裝備可談免費保養一次。
- **藍鯨潛水**：墾丁店，適合南下潛旅時順便試裝備，淡季（11月）常有組合優惠。

**線上**
- **PChome / momo**：11月雙11檔期，防寒衣、蛙鞋、電腦錶常有5–7折，注意確認是否為公司貨（保固卡）。
- **蝦皮**：搜「潛水 二手」社團賣家，面交驗貨優先。
- **Facebook 社團**：「台灣潛水裝備買賣交換」「潛水二手裝備交流」——11月是墾丁/小琉球潛季尾聲，不少人換季出清防寒衣與輕裝，可撿便宜，但**氣瓶、調節器二手務必送店檢測**。

**11月時機提示**
- 台灣東北季風起，北部潛點浪大，店家進入淡季→**議價與組合優惠空間最大**。
- 雙11（11/11）線上檔期是全年買輕裝（面鏡、蛙鞋、防寒衣）的好時機。
- 若計畫12–2月去東南亞（菲律賓、泰國），現在買可趕上出發前試裝。

## 裝備建議

**防寒衣換季保養**：

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-11-24 15:02:19`

#### AI Flight Tips — November
# November Flight Deals from Taiwan (TPE/TSA) — Booking Guide

**Japan (Tokyo/Osaka/Sapporo)**
- November is peak for autumn foliage (late Nov especially Kyoto/Osaka); Sapporo turns off-peak as ski season hasn't fully started. Book 6–8 weeks out for Tokyo/Osaka, 4–6 weeks for Sapporo.
- Cheapest: Peach, Tigerair Taiwan, and Scoot to Narita/Kansai; for Sapporo use Scoot via Singapore or Peach direct when available. Watch Tigerair Taiwan's "flash fare" Tuesday drops.

**Thailand (Bangkok/Chiang Mai)**
- November is peak — cool season begins and Loy Krathong falls in late Nov; Chiang Mai especially books up. Book 8–10 weeks ahead for best fares.
- Cheapest: Thai Lion Air, NokScoot (if operating), and VietJet via Ho Chi Minh; China Airlines/Starlux sales often beat LCCs on TPE–BKK. Watch Starlux's anniversary promo in November.

**Europe (any major city)**
- November is deep off-peak (post-summer, pre-Christmas markets) — cheapest month of the year for Europe. Book 10–14 weeks out; fares bottom out 8–12 weeks before departure.
- Cheapest: China Eastern via Shanghai, Air China via Beijing, or Turkish Airlines via Istanbul; EVA/China Airlines direct to Amsterdam/Vienna/London price higher but avoid visa-transit hassles. Watch China Eastern's "11.11" Singles' Day sale.

**USA (West/East Coast)**
- November is shoulder-to-peak: early Nov cheap, Thanksgiving week (late Nov) spikes sharply. Book 8–12 weeks out; avoid the Nov 20–30 window for savings.
- Cheapest: China Airlines/EVA direct to LAX/SFO/SEA/ONT; for East Coast, Delta/United via Tokyo or Korean Air via Seoul often undercut. Watch EVA's "Early Bird" fares 3–4 months out.

**Egypt (Cairo)**
- November is peak — ideal weather (20–28°C) and high season for Nile cruises. Book 10–12 weeks ahead; limited direct capacity means fares climb fast.
- Cheapest: China Eastern via Shanghai or Emirates/Qatar via Gulf hubs; no direct TPE–CAI route, so 1-stop via HKG (Cathay) or BKK (EgyptAir via Bangkok) is your best bet. Watch EgyptAir's seasonal Cairo promo via Bangkok.

**Australia (Sydney/Melbourne)**
- November is shoulder-to-peak — spring weather, pre-summer rush; fares rise from mid-Nov. Book 8–10 weeks out.
- Cheapest: China Airlines and EVA direct to SYD/MEL; Scoot via Singapore and AirAsia X via KL are budget alternatives. Watch China Airlines' "Southern Hemisphere" sale and Scoot's monthly flash sales.

## 📚 Learning

### 📚 Learning — Finance
> `2026-11-24 15:02:32`

#### 📚 Today's Concept: Bond yield and its inverse relationship with price

What it is: Bond yield is the annual return you earn from a bond, calculated as the coupon payment divided by the bond's current market price. Because the coupon is fixed, yield moves inversely to price: when the price falls, yield rises, and vice versa.

Why it matters: Yields are the market's baseline cost of money, so rising yields pressure stock valuations (especially growth stocks) by raising discount rates and pulling capital toward safer bonds.

Example: A bond pays $50/year (5% coupon on $1,000 face value). If market rates rise and the bond's price drops to $800, the yield becomes $50 / $800 = 6.25%. If the price rises to $1,250, yield falls to $50 / $1,250 = 4%.

Rule of thumb: Watch the 10-year Treasury yield as your discount-rate dial — when it climbs sharply, expect high-multiple tech stocks to compress, since future cash flows are worth less today.

### 🧩 LeetCode Blind 100
> `2026-11-24 15:02:39`

#### 🧩 Blind 100 — 200. Number of Islands [Graphs]
**連結:** https://leetcode.com/problems/number-of-islands/
> 📅 **Today's Daily Challenge:** #3702 Maximum Subarray With Equal Products [Easy] — Tags: Array, Math, Sliding Window, Enumeration, Number Theory — https://leetcode.com/problems/maximum-subarray-with-equal-products/

# 200. Number of Islands

**Problem Type:** Graph traversal on a grid (connected components) — BFS/DFS flood fill

**Key Insight:** Each unvisited `'1'` starts a new island; flood-fill (BFS or DFS) all connected land and mark it visited so you never count it twice.

**Approach:**
1. Iterate every cell in the grid.
2. When you hit a `'1'`, increment the island count and launch a BFS/DFS from it.
3. During traversal, flip visited `'1'` → `'0'` (in-place) to avoid a separate `visited` set.
4. Explore all 4 neighbors (up/down/left/right) within bounds.
5. Return the count.

**Python3 Solution:**
```python
from collections import deque

class Solution:
    def numIslands(self, grid: list[list[str]]) -> int:
        if not grid or not grid[0]:
            return 0
        R, C = len(grid), len(grid[0])
        count = 0

        def bfs(r: int, c: int) -> None:
            q = deque([(r, c)])
            grid[r][c] = '0'
            while q:
                x, y = q.popleft()
                for dx, dy in ((1,0),(-1,0),(0,1),(0,-1)):
                    nx, ny = x + dx, y + dy
                    if 0 <= nx < R and 0 <= ny < C and grid[nx][ny] == '1':
                        grid[nx][ny] = '0'
                        q.append((nx, ny))

        for r in range(R):
            for c in range(C):
                if grid[r][c] == '1':
                    count += 1
                    bfs(r, c)
        return count
```

**Complexity:** Time O(R·C) | Space O(min(R,C)) for BFS queue (worst case O(R·C) for DFS recursion depth — prefer BFS or iterative DFS to avoid recursion limits on large grids).

**Blind 100 Note:** Canonical "grid as graph" problem — teaches you to treat cells as nodes and adjacency as 4-directional moves. This is the template for **connected components** on grids. Practice next: *Number of Islands II* (Union-Find), *Max Area of Island*, *Flood Fill*, *Surrounded Regions*, *Pacific Atlantic Water Flow*, *Rotting Oranges* (multi-source BFS).

**Contest Tips:**
- **Mutate in place** (`'1'` → `'0'`) — saves memory and avoids a `visited` set. If the problem forbids mutation, use a `set` or `bytearray`.
- **Recursion depth**: Python's default limit (~1000) will blow up on a 300×300 all-land grid. Use BFS or `sys.setrecursionlimit(10**6)`.
- **Empty grid guard**: `if not grid or not grid[0]` — LeetCode sometimes includes `[]`.
- **Direction tuple trick**: `for dx, dy in ((1,0),(-1,0),(0,1),(0,-1))` is faster than four separate `if`s.
- **Don't forget `deque`** — `list.pop(0)` is O(n); `deque.popleft()` is O(1).
- **Union-Find alternative**: only worth it for *Number of Islands II* (dynamic additions). For static grids, BFS/DFS is simpler and faster in Python.

### 📷 Learning — Photography
> `2026-11-24 15:02:47`

#### 📷 Today's Concept: Video — IBIS + OIS Combo for Handheld Smoothness

**What it is:** IBIS (In-Body Image Stabilization) is the A7C's sensor-shift stabilization, while OIS (Optical Image Stabilization) is stabilization built into certain lenses. Using them together—the camera correcting for body shake and the lens correcting for its own micro-movements—gives you a combined stabilization system for handheld shooting.

**Why it matters:** The result is gimbal-like smoothness without a gimbal: locked-off handheld shots, smooth walking pans, and usable slow shutter video that would otherwise look jittery and amateurish.

**How to apply it:**
1. Mount a stabilized lens (e.g., Sony 20mm f/1.8 G, 24-105mm G OSS, or 35mm f/1.8) so IBIS and OIS work in tandem.
2. Set **SteadyShot** to **Active** in the menu for walking shots (Standard for static handheld).
3. Enter the correct focal length if using a manual lens so IBIS calibrates properly.
4. Use a slow, bent-knee "ninja walk," elbows tucked, camera braced against your chest.
5. Shoot at 1/50–1/60s for natural motion blur; let stabilization handle the rest.

**Sony A7C tip:** The A7C's IBIS is weaker than larger bodies due to its compact size—pair it with an OSS lens and enable **Active SteadyShot** for the best handheld results. Note Active mode crops slightly, so frame with margin.

**Common mistake:** Beginners crank up shutter speed to "fix" shake, which kills cinematic motion blur. Instead, trust the IBIS+OIS combo at slower shutter speeds and improve your walking technique.

### 📚 Learning — Tech
> `2026-11-24 15:02:42`

#### 📚 Today's Concept: Distributed Transactions and the Saga Pattern

**What it is:** A distributed transaction spans multiple services/databases that must stay consistent, but two-phase commit (2PC) is slow and fragile across microservices. The Saga pattern instead breaks it into a sequence of local transactions, each with a compensating action that undoes it if a later step fails.

**When to use it:** Use sagas when you need consistency across services you don't control atomically—e.g., an e-commerce order that reserves inventory, charges payment, and ships, where a payment failure must release the inventory.

**Example:**
```python
def place_order(order):
    try:
        inventory.reserve(order)      # step 1
        payment.charge(order)         # step 2
        shipping.schedule(order)      # step 3
    except PaymentFailed:
        inventory.release(order)      # compensate step 1
        raise
```

**Gotcha:** Sagas provide *eventual* consistency, not ACID isolation—intermediate states are visible to other transactions. A common mistake is assuming you get atomicity/rollback semantics like a DB transaction; compensations can also fail, so you need idempotency and retries (or a coordinator like Temporal) to avoid inconsistent state.

### 🎬 Learning — YouTube
> `2026-11-24 15:02:51`

#### 🎬 今日主題：旅遊 — 旅遊 Vlog 的音樂選擇與版權注意事項
**類別：** 旅遊

**是什麼：** 旅遊 Vlog 的音樂選擇是指依影片節奏與情緒挑選合適配樂，並確認使用授權合法。版權注意事項則是避免使用未授權音樂，防止影片被下架或頻道受罰。

**為什麼重要：** 音樂直接影響觀看體驗與情緒渲染，而版權問題可能導致影片被封鎖、收益被沒收，甚至頻道遭警告，對剛起步的創作者傷害極大。

**怎麼做：**
1. 優先使用 YouTube 音效庫或 Artlist、Epidemic Sound 等授權平台。
2. 依場景選曲：開場用輕快節奏、風景用氛圍音樂、轉場用短音效。
3. 保留授權證明（截圖或訂閱紀錄），以備申訴。
4. 上傳前用 YouTube 版權檢查工具確認。
5. 若用 AI 剪輯工具（如 CapCut），注意其內建音樂授權範圍。

**新手常犯的錯：** 直接從網路下載流行歌當配樂。避免方式：只使用明確標示可商用或平台內建授權音樂。

**延伸 idea：** 拍一支「用 A7C 拍旅遊 Vlog：我如何挑選無版權配樂」幕後影片，邊示範邊教學，兼具攝影與科技主題。
