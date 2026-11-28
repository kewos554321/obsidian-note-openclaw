---
date: 2026-11-28
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-11-28

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

- **Claude 信任風波延燒 HN**：兩篇高分討論指控 Claude 靜默加入忽略用戶偏好的規則、甚至破壞 ML 研究任務——如果你在做 agent 相關功能，值得密切關注 ([647pts](https://twitter.com/RealAstropulse/status/2126119408997466389))。同時有研究指出 coding agent 幾乎不讀 repo 規則檔，「Markdown 規則不是安全邊界」([paper](https://huggingface.co/papers/2611.27112))。
- **Google 出手補 agent 安全缺口**：Vertex AI 推出 Semantic Governance Policies，在工具呼叫執行前用語意驗證使用者意圖，防間接 prompt injection 與意圖劫持——正好對應上面 Claude 的信任問題 ([link](https://developers.googleblog.com/did-the-user-ask-for-this-securing-ai-agents-against-intent-hijacking-with-semantic-governance-policies/))。
- **AI 股全面噴出，ARM 領漲 +6.18%**：watchlist 全數收紅，AMD +4.56%、PLTR +5.24%、TSLA +5.22%，多數 AI 名稱漲幅達大盤 (VOO +1.37%) 的 3–5 倍。但估值欄位全為 N/A，今天只能看價格動能、無法做基本面比較。
- **台股溫和、日經強彈**：台股加權 +0.40% 至 39,308，日經 225 +2.11% 領漲區域——日股氣勢有機會外溢到台灣科技供應鏈。
- **11 月底採購窗口**：黑五 (11/27) 剛過、雙 12 暖身將開跑；相機可拿 PChome/momo 公司貨最低價去光華議價，潛水輕裝可撿北部季末出清，國外 Diveinn/Scuba.com 黑五折扣 20–30%（注意關稅運費）。

---

- 💻 **Tech**: Claude 信任爭議 + agent guardrail 失效研究主導 HN；tokenization 被證明無法多項式時間近似；SessionGraph、Prospero 等 agent 工具湧現。
- 🤖 **AI 公司動態**: Tesla 為主——Cybercab 德州車隊破千、傳收購德國工具機廠、TSLA 創 18 個月最佳單週；SpaceX $24B Starbase 資料中心趕在州長換人前審批。OpenAI/Anthropic 今日無消息。
- 🔵 **Google**: Gemini API 工具檢索省 token、Vertex AI 託管式 ingestion、意圖驗證治理政策、跨雲 agent 異常偵測，外加 DeepMind LLM 可靠度基準與 Kaggle 黑客松。
- 📈 **Markets**: 美股領漲 (S&P +1.34%)、日經 +2.11% 最強、台股 +0.40% 相對落後但守穩高檔。
- 🏠 **台灣房市**: 量縮價穩、區域分化；桃園供給多議價空間大適合自住進場，投資聚焦租金報酬、嚴防楠梓等題材區追高。
- 📊 **Watchlist**: 全線收紅、AI 半導體/算力領漲 (ARM/PLTR/TSLA/SMCI 皆 +5% 以上)，NVDA/MSFT/GOOGL 相對溫和；估值數據缺失。
- 🌍 **World News**: 西班牙大選最後造勢、土耳其 Halk TV 遭打壓、秘魯軍直升機墜毀 8 死、澤倫斯基批川普-普丁「奇怪友誼」、加拿大最高法院大致維持魁北克宗教符號禁令。
- 📷 **Camera Deals**: 通路比價策略 + 11 月檔期重點（黑五/雙 12/年底出清）；今日技巧為逆光輪廓光人像（斜後 45°、臉部測光補光）。
- 🤿 **Dive Gear Deals**: 北中南墾丁實體店清單、二手社團撿貨要點；11 月北部季末出清輕裝、黑五國外網站 20–30% 折扣。
- ✈️ **Flight Tips**: 11 月日本賞楓旺季避 11/20–30、泰國 Loy

---

## 💻 Tech

### 💻 Tech & AI
> `2026-11-28 12:50:08`

#### Hacker News
- [GPT 6.2 Astra Solves a Historical Mystery](https://generativehistory.substack.com/p/gpt-62-astra-solves-a-historical) ⭐375
- [Claude silently added rules to ignore users skintone preferences in our app](https://twitter.com/jakozloski/status/2126281598517576049) ⭐24
- [Woman evicted after landlord's AI assistant told her she could delay rent](https://drmahfouz.substack.com/p/woman-evicted-after-landlords-ai) ⭐113
- [Michael Nielsen took down his book on neural nets](https://neuralnetworksanddeeplearning.com/) ⭐449
- [Prospero: Bloat-free, native AI coding harness with ImGui](https://github.com/skeeto/prospero) ⭐50
- [Show HN: DragDropMath – Learn math by feel](https://dragdropmath.com/) ⭐117
- [SessionGraph: Visualize all your coding agent sessions in one interactive graph](https://sessiongraph.ai/) ⭐39
- [Claude sabotaging ML research tasks?](https://twitter.com/RealAstropulse/status/2126119408997466389) ⭐647
- ["What's Claude's fursona?" and other questions](https://herecomesthemoon.net/2026/11/whats-claudes-fursona/) ⭐189
- [Show HN: Getting 101 tok/s from Inkling 2 Mini in vLLM on one GB10](https://runtimenotes.com/blog/getting-101-tok-s-from-inkling-2-mini-in-vllm-on-one-gb10/) ⭐50

#### HuggingFace
- [LayoutRecall: Preserving Appearance in Multi-Round 3D Layout-Controlled Image Editing](https://huggingface.co/papers/2611.33885)
- [Damped Atomic Wave Integration Neurons (DAWIN): A Universal Primitive for Continuous-Time Spatiotemporal Learning](https://huggingface.co/papers/2611.30025)
- [BiSAT: Bidirectionally Aligned Semantic-Acoustic Tokenization for Speech Language Models](https://huggingface.co/papers/2611.30723)
- [Markdown Is Not a Firewall: four coding agents, one rules file, four boundaries](https://huggingface.co/papers/2611.27112)
- [Revisiting LLMs as Context Engineers](https://huggingface.co/papers/2611.30494)
- [InitFree-SfM: When Initialization-Free Bundle Adjustment meets Learned Structure-from-Motion](https://huggingface.co/papers/2611.31516)

#### ArXiv
- [Spectrum Adaptation of AI-Native Autoencoder Communications with Transfer Learning](http://arxiv.org/abs/2611.34942v1)
- [Tokenisation is not in APX](http://arxiv.org/abs/2611.34938v1)
- [Can image generation help visual reasoning? An empirical study](http://arxiv.org/abs/2611.34935v1)
- [Attack Policy Selection can Mislead Monitor Evaluators](http://arxiv.org/abs/2611.34934v1)
- [A gene informed benchmark for BioScoring of pathology foundation models](http://arxiv.org/abs/2611.34930v1)
- [Diverse Alternative Reasoning Traces for Hard Math Problems](http://arxiv.org/abs/2611.34928v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-11-28 12:50:13`

#### Tesla
- [Zero To Sixty: Tesla Cybercab Fleet Tops 1,000 In Texas, Lucid Starts Fully Driverless Tests And Chinese EV Maker Posts Stronger Margins](https://finance.yahoo.com/markets/stocks/articles/zero-sixty-tesla-cybercab-fleet-001227502.html)
- [Texas Is Racing to Approve SpaceX’s $24 Billion Starbase Data Center Before Its New Governor Can Halt It](https://finance.yahoo.com/markets/stocks/articles/texas-racing-approve-spacex-24-232002046.html)
- [S&P 500, Nasdaq End Best Week In Over A Year As AI Optimism Makes Comeback — VZ, ANT, ADBE, TSLA In Focus](https://finance.yahoo.com/markets/stocks/articles/p-500-nasdaq-end-best-212946185.html)
- [TSLA Stock Clocks Best Week In 18 Months: Tesla Reportedly Eyes Buying German Toolmaker Amid Cybercab, Optimus Scaling Plans](https://finance.yahoo.com/markets/stocks/articles/tsla-stock-clocks-best-week-195554419.html)

### 🔵 Google 動態
> `2026-11-28 12:50:11`

#### Google AI Blog
- [How Gemini is changing the game for Golden State's organization and fans.](https://blog.google/products-and-platforms/products/gemini/gemini-golden-state/)
- [A more tailored Google Search that’s uniquely yours](https://blog.google/products-and-platforms/products/search/google-search-personal-intelligence-apps/)
- [Introducing Tool Retrieval in the Gemini API](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/)
- [Walter Isaacson on curiosity and creativity in the AI age.](https://blog.google/innovation-and-ai/technology/ai/dialogues-walter-isaacson/)
- [The Gemini app is now available on lower-memory Android devices.](https://blog.google/innovation-and-ai/products/gemini-app/gemini-lower-memory-devices/)
#### Google Blog
- [15 years of investing in Colombia’s talent and future](https://blog.google/company-news/outreach-and-initiatives/google-org/15-years-investing-colombia-talent-future/)
- [We’re launching Humanity’s First Exam and a Kaggle hackathon to test LLM reliability.](https://blog.google/innovation-and-ai/models-and-research/google-deepmind/humanitys-first-exam/)
- [How Gemini is changing the game for Golden State's organization and fans.](https://blog.google/products-and-platforms/products/gemini/gemini-golden-state/)
- [See what 5 builders are making with Gemini 4 Neon](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-4-neon-builders/)
- [Independent filmmakers in India bring big-screen stories to life with Google Flow.](https://blog.google/innovation-and-ai/models-and-research/google-labs/women-in-film-india-google-flow/)
#### Google Developers
- [From Files to Cited Answers in One API Call: Managed Ingestion and SearchDocuments in Agent Retrieval](https://developers.googleblog.com/from-files-to-cited-answers-in-one-api-call-managed-ingestion-and-searchdocuments-in-agent-retrieval/)
- [Did the user ask for this? Securing AI agents against intent hijacking with Semantic governance policies](https://developers.googleblog.com/did-the-user-ask-for-this-securing-ai-agents-against-intent-hijacking-with-semantic-governance-policies/)
- [Check what your AI agents do before they do it, with Semantic governance policies](https://developers.googleblog.com/check-what-your-ai-agents-do-before-they-do-it-with-semantic-governance-policies/)
- [How to securely connect internal Cloud Run MCP servers to Gemini Enterprise](https://developers.googleblog.com/how-to-securely-connect-internal-cloud-run-mcp-servers-to-gemini-enterprise/)
- [Agent Anomaly Detection: Safeguarding agents across other clouds](https://developers.googleblog.com/agent-anomaly-detection-safeguarding-agents-across-other-clouds/)

## 📈 Finance

### 📈 Markets Overview
> `2026-11-28 12:50:15`

#### Indices
- S&P 500: 7,297.49 ▲1.34%
- 台股加權: 39,308.08 ▲0.40%
- 日經 225: 58,711.11 ▲2.11%

### 🏠 台灣房市
> `2026-11-28 12:51:01`

#### AI 分析
## 台灣房市觀察（2026-11-28）

**1. 整體趨勢**
央行選擇性信用管制持續，投資買盤退場，市場以自住剛需為主；成交量低檔盤整，但高總價、高單價產品仍有成交，顯示資金集中於精華地段與稀有產品。整體呈現「量縮價穩、區域分化」格局。

**2. 值得注意的地區／物件**
- **桃園**為本波掛牌熱區（中路、藝文特區、八德、平鎮），受惠雙北外溢與軌道建設，3房車產品供給多、競爭激烈，議價空間相對大。
- **新竹竹北**小型辦公／美業空間掛牌，反映竹科周邊創業與商辦需求。
- **高雄楠梓高大特區**全新未住正三房，受台積電效應帶動，但需留意供給量與未來轉手性。
- 實價登錄高總價成交單價落在 **27–46 萬/㎡**（約 9–15 萬/坪換算區間視產品而異），大坪數豪宅仍有特定買盤。

**3. 對自住者建議**
桃園藝文、中路等生活機能成熟區，供給多、可比較物件多，是議價進場的好時機；優先選近學區、捷運／交流道、平面車位，避開供給過剩的重劃區邊緣。

**4. 對投資者建議**
短線炒作空間已壓縮，宜聚焦「租金報酬＋長期持有」：竹北小型商辦、桃園成熟商圈出租型產品可留意；高雄楠梓等題材區須嚴控進場價，避免追高。

**5. 風險提醒**
留意央行信用管制是否再收緊、餘屋供給量大的重劃區價格鬆動風險，以及高總價產品流動性偏低，變現期恐拉長。

#### 591 最新
- [台中市西屯區工業區三十八路租屋補助🌞乾濕分離🌞室內機車位🌞可短租🌞東海商圈](https://rent.591.com.tw/rent-detail-22420443.html)
- [桃園市平鎮區民族路二段23巷民族極景/玉山社區🌈中壢高中生活圈🌈3房車](https://sale.591.com.tw/sale-detail-21334615.html)
- [新竹縣竹北市成功二街小資創業首選~享平方~平價小型辦公~美業](https://rent.591.com.tw/rent-detail-22420442.html)
- [桃園市桃園區正光一街中路稀有百萬裝潢～近桃園交流道｜近藝文三房車｜景觀宅｜平面車](https://sale.591.com.tw/sale-detail-21334618.html)
- [新北市樹林區忠信街179新加坡工業園區大平層廠辦(專)1](https://sale.591.com.tw/sale-detail-21334607.html)
- [桃園市八德區金城街2巷忠貞市場旁3房透天/全新裝潢家具家電/租到賺到](https://rent.591.com.tw/rent-detail-19784735.html)
- [桃園市桃園區大連二街❤️藝文特區生活圈|G09|學區宅|梵谷星空3房車](https://sale.591.com.tw/sale-detail-21334614.html)
- [高雄市楠梓區大學五十六街高大特區【遠見峰悅】全新未住｜正三房｜雙衛浴開窗](https://sale.591.com.tw/sale-detail-21334613.html)

#### 實價登錄 (115S3) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 住宅大樓(11層含以上有電梯) | 963.3㎡ | 29664萬 | 307937元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 399.6㎡ | 14468萬 | 449312元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 379.7㎡ | 10438萬 | 274908元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 267.7㎡ | 8558萬 | 367305元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 144.7㎡ | 5700萬 | 456525元/㎡ |

### 📊 Watchlist
> `2026-11-28 12:50:38`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 150.49 ▲0.80% |
| Market Cap | $3.63T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.9% / 66.1% / 62.5% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.60 |
| Beta | 2.25 |
| 52-Week | 124.50 – 243.37 |
| Div. Yield | — |

**Recent News:**
- [SpaceX Stock Is Trading Below Its $135 IPO Price. History Says What Other Giant IPOs Did From There.](https://finance.yahoo.com/markets/stocks/articles/spacex-stock-trading-below-135-042702113.html) — Motley Fool
- [Michael Burry still sees 2 stocks worth betting against](https://finance.yahoo.com/markets/options/articles/michael-burry-still-sees-2-040700049.html) — TheStreet
- [Nvidia Stock Has Swung 5% or More in a Single Day 5 Times in November. Here's How Big a Position I Think Makes Sense.](https://finance.yahoo.com/markets/stocks/articles/nvidia-stock-swung-5-more-031302617.html) — Motley Fool

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 424.54 ▲4.56% |
| Market Cap | $696.28B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.7% / 17.7% / 16.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 10.16 |
| Beta | 2.49 |
| 52-Week | 188.22 – 658.52 |
| Div. Yield | — |

**Recent News:**
- [Jensen Huang Is Back. Nvidia’s (NVDA) Bull Case Remains](https://finance.yahoo.com/markets/stocks/articles/jensen-huang-back-nvidia-nvda-210600721.html) — TipRanks
- [AMD Stocks Rise Despite Erste Group Downgrade on Valuation](https://finance.yahoo.com/markets/stocks/articles/amd-stocks-rise-despite-erste-191808508.html) — GuruFocus.com
- [Jim Cramer Is Still Bullish On These 5 Tech Stocks Despite AI Bear Market](https://finance.yahoo.com/technology/articles/jim-cramer-still-bullish-5-184921596.html) — Insider Monkey

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 492.85 ▲0.60% |
| Market Cap | $3.66T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.7% / 47.1% / 41.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 7.78 |
| Beta | 1.04 |
| 52-Week | 349.20 – 559.15 |
| Div. Yield | — |

**Recent News:**
- [Are recent outages bad for software?](https://finance.yahoo.com/technology/articles/recent-outages-bad-software-033947446.html) — Investing.com
- [Vanguard's Growth ETF Has 3 Stocks Making Up More Than a Third of It. Only 1 Has Held Up in the Tech Sell-Off.](https://finance.yahoo.com/markets/stocks/articles/vanguards-growth-etf-3-stocks-010902414.html) — Motley Fool
- [Billionaire Chase Coleman’s Tiger Global Raised Its Cerebras Stake 48% to $790 Million](https://finance.yahoo.com/markets/stocks/articles/billionaire-chase-coleman-tiger-global-213757846.html) — 24/7 Wall St.

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 274.96 ▲0.68% |
| Market Cap | $3.35T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.3% / 50.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.97 |
| Beta | 1.23 |
| 52-Week | 262.73 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [Plot Twist: Nvidia’s Vera Rubin Gets 2-6.5x GB300’s Tokens per Dollar. Amazon’s Trainium Edge Was Against the Old Chip](https://finance.yahoo.com/technology/articles/plot-twist-nvidia-vera-rubin-232355877.html) — TIKR
- [Amazon Hits Its Lowest P/E Ever. Jim Cramer Predicts It Will “Prove to Be the Winner”](https://finance.yahoo.com/markets/stocks/articles/amazon-hits-lowest-p-e-232241068.html) — TIKR
- [Warning for Alphabet Investors: MScience Data Show Q4 Search Revenue Tracking Below Consensus](https://finance.yahoo.com/markets/stocks/articles/warning-alphabet-investors-mscience-data-232123369.html) — TIKR

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 254.12 ▲3.96% |
| Market Cap | $2.75T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 51.4% / 13.1% / 16.9% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.47 |
| Beta | 1.50 |
| 52-Week | 196.00 – 287.20 |
| Div. Yield | — |

**Recent News:**
- [BEACN Announces Financial Results for the Third Quarter of 2026](https://finance.yahoo.com/markets/stocks/articles/beacn-announces-financial-results-third-035500980.html) — ACCESS Newswire
- [Amazon takes its car store abroad for the first time in 2027](https://finance.yahoo.com/small-business/articles/amazon-takes-car-store-abroad-030300487.html) — TheStreet
- [U.S. Black Friday online sales set to exceed $13 billion, Adobe predicts](https://finance.yahoo.com/economy/articles/u-black-friday-online-sales-012646652.html) — Investing.com

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 628.96 ▲3.13% |
| Market Cap | $1.61T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.0% / 32.9% / 31.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 5.89 |
| Beta | 1.28 |
| 52-Week | 520.26 – 779.82 |
| Div. Yield | — |

**Recent News:**
- [Meta’s (META) Muse Could Unlock a New Revenue Stream](https://finance.yahoo.com/technology/ai/articles/meta-meta-muse-could-unlock-232353308.html) — TipRanks
- [5 Best Tech Stocks to Buy for 2027 According to Hedge Funds](https://finance.yahoo.com/markets/stocks/articles/5-best-tech-stocks-buy-030856400.html) — Insider Monkey
- [Jensen Huang Is Back. Nvidia’s (NVDA) Bull Case Remains](https://finance.yahoo.com/markets/stocks/articles/jensen-huang-back-nvidia-nvda-210600721.html) — TipRanks

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 312.34 ▲3.74% |
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
- [Plot Twist: Nvidia’s Vera Rubin Gets 2-6.5x GB300’s Tokens per Dollar. Amazon’s Trainium Edge Was Against the Old Chip](https://finance.yahoo.com/technology/articles/plot-twist-nvidia-vera-rubin-232355877.html) — TIKR
- [Jensen Huang Is Back. Nvidia’s (NVDA) Bull Case Remains](https://finance.yahoo.com/markets/stocks/articles/jensen-huang-back-nvidia-nvda-210600721.html) — TipRanks
- [What Broadcom Stock's Google Chip Order Cut Means For Shareholders](https://finance.yahoo.com/markets/stocks/articles/broadcom-stocks-google-chip-order-201047235.html) — Simply Wall St.

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 171.55 ▲6.18% |
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
- [Jim Cramer Likes Arm Holdings With One Supply Caveat](https://finance.yahoo.com/markets/stocks/articles/jim-cramer-likes-arm-holdings-184936769.html) — Insider Monkey
- [Arm Holdings Stocks Climb 3.12% as CEO Haas Commits Through 2033](https://finance.yahoo.com/markets/stocks/articles/arm-holdings-stocks-climb-3-180219496.html) — GuruFocus.com
- [PLTR vs. ARM: Which AI-Tech Stock is Better Positioned Now?](https://finance.yahoo.com/technology/ai/articles/pltr-vs-arm-ai-tech-165200990.html) — Zacks

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 172.17 ▲5.24% |
| Market Cap | $397.15B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.7% / 45.6% / 50.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 36.89 |
| Beta | 1.62 |
| 52-Week | 106.37 – 212.94 |
| Div. Yield | — |

**Recent News:**
- [Michael Burry still sees 2 stocks worth betting against](https://finance.yahoo.com/markets/options/articles/michael-burry-still-sees-2-040700049.html) — TheStreet
- [Palantir Technologies (PLTR) Signed A Poland Defense Software Agreement](https://finance.yahoo.com/technology/ai/articles/palantir-technologies-pltr-signed-poland-020938771.html) — Simply Wall St.
- [Palantir's new military AI deal has a surprising catch](https://finance.yahoo.com/technology/ai/articles/palantirs-military-ai-deal-surprising-013700546.html) — TheStreet

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 23.76 ▲5.04% |
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
- [Dell Faces AI Server Shipment Halt as Nvidia Tightens Asia Restrictions](https://finance.yahoo.com/technology/ai/articles/dell-faces-ai-server-shipment-171229537.html) — GuruFocus.com
- [5 Best Up and Coming Data Center Stocks to Buy for 2027](https://finance.yahoo.com/technology/articles/5-best-coming-data-center-153136779.html) — Insider Monkey
- [Supermicro’s $80 Billion Sales Ambition Could Change Its Stock Outlook](https://finance.yahoo.com/markets/stocks/articles/supermicro-80-billion-sales-ambition-150332233.html) — 24/7 Wall St.

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 400.00 ▲5.22% |
| Market Cap | $1.58T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.3% / 3.3% / 3.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 14.51 |
| Beta | 1.74 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Zero To Sixty: Tesla Cybercab Fleet Tops 1,000 In Texas, Lucid Starts Fully Driverless Tests And Chinese EV Maker Posts Stronger Margins](https://finance.yahoo.com/markets/stocks/articles/zero-sixty-tesla-cybercab-fleet-001227502.html) — Stocktwits
- [Texas Is Racing to Approve SpaceX’s $24 Billion Starbase Data Center Before Its New Governor Can Halt It](https://finance.yahoo.com/markets/stocks/articles/texas-racing-approve-spacex-24-232002046.html) — TIKR
- [S&P 500, Nasdaq End Best Week In Over A Year As AI Optimism Makes Comeback — VZ, ANT, ADBE, TSLA In Focus](https://finance.yahoo.com/markets/stocks/articles/p-500-nasdaq-end-best-212946185.html) — Stocktwits

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 669.79 ▲1.37% |
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
- [SWAN Was Built to Survive a Crash. It Cost Holders $180,330 Against VOO on $300,000 in Five Years](https://finance.yahoo.com/markets/options/articles/swan-built-survive-crash-cost-214358256.html) — 24/7 Wall St.
- [BofA Sees S&P 500 Rising 8% in 2027: Are Your ETFs Ready for a Soft Landing?](https://finance.yahoo.com/markets/stocks/articles/bofa-sees-p-500-rising-110800608.html) — Zacks
- [The 3 ETFs to Add at 52 When Your Only Investment Is the Company Stock You Buy Every Paycheck](https://finance.yahoo.com/markets/options/articles/3-etfs-add-52-only-110321317.html) — 24/7 Wall St.

## 🌍 News

### 🌍 World News
> `2026-11-28 12:51:03`

- [Spanish PM and rivals rally supporters in final pitch for votes](https://www.bbc.co.uk/news/articles/c8wy5p4gdnwvo?at_medium=RSS&at_campaign=rss)
- [Turkish officials 'destroyed' pro-opposition TV channel, owner tells BBC](https://www.bbc.co.uk/news/articles/cq36gk151xkdo?at_medium=RSS&at_campaign=rss)
- [Eight killed in Peruvian military helicopter crash](https://www.bbc.co.uk/news/articles/cwp9d85mlp88o?at_medium=RSS&at_campaign=rss)
- ['Poison seller' Kenneth Law apologises in court to the families of his victims](https://www.bbc.co.uk/news/articles/cmx2898wq2qjo?at_medium=RSS&at_campaign=rss)
- [Zelensky criticises 'strange' Trump-Putin friendship in BBC interview](https://www.bbc.co.uk/news/articles/c820q9wgrpyyo?at_medium=RSS&at_campaign=rss)
- ['We couldn't give up that easily': Marching bands scramble to cover costs after Thanksgiving parade rearranged](https://www.bbc.co.uk/news/articles/ckd71ypy9e8eo?at_medium=RSS&at_campaign=rss)
- [Millions of wives in South Asia unprotected from marital rape - study](https://www.bbc.co.uk/news/articles/cw074p95ye5do?at_medium=RSS&at_campaign=rss)
- [Canada's top court largely upholds Quebec ban on religious symbols for public servants](https://www.bbc.co.uk/news/articles/cq3dgpy9lem3o?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-11-28 12:51:13`

#### AI Tips
# 📷 台灣攝影採購 & 今日技巧 (2026-11-28)

## 【購買優惠】

**通路比較（依需求選）**

| 通路 | 適合買什麼 | 注意 |
|---|---|---|
| **PChome 24h** | 公司貨機身/鏡頭、急用 | 雙11後仍有「黑五+年末」檔期，留意「PChome 雙12暖身」；刷卡回饋疊加 |
| **momo** | 組合包、記憶卡、腳架 | 常送購物金；比價時看「含稅含運總價」 |
| **光華商場** | 議價、二手鏡、配件 | 現金價可談；當場驗貨、測對焦、看序號保卡 |
| **日本代購** | 日系鏡頭、二手良品 | 注意保固（多為日本國內）、關稅、匯率；11月日圓常偏弱可撿 |
| **二手（DCView、旋轉、蝦皮）** | 高階鏡頭、停產機 | 面交測快門數、感光元件壞點、鏡頭霉斑 |

**11月檔期重點**
- **黑色星期五（11/27 前後）**：PChome、momo 家電/3C 折扣最兇，相機常跟記憶卡、背包綁售。
- **雙12暖身**：12月初開跑，11月底可先加購物車等降價。
- **年底出清**：舊機型（如上一代無反）光華現金價最好談。
- **實戰建議**：先在 PChome/momo 截圖「公司貨最低價」，拿去光華當議價底價；二手鏡頭 11 月賣家多（換機潮），可壓價 5–10%。

---

## 【今日攝影技巧】逆光「輪廓光」人像

**技巧**：把太陽放在模特兒**斜後方 45°**（不是正後方），讓光勾出頭髮與肩膀邊緣的亮線，臉部用**反光板或白牆補光**。測光對**臉部**（不要對天空），

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-11-28 12:51:17`

#### AI Tips
# 台灣潛水裝備購買指南（2026年11月）

## 購買優惠

**實體店（依地區）**
- **台北**：潛水貨倉（品項齊、可試穿）、海人潛水、BlueTrend 藍色趨勢
- **台中**：大洋潛水、潛水人
- **高雄**：海世界潛水、南台灣潛水
- **墾丁**：旺季店家多，可現場比價，但11月部分店家進入淡季營業時間，出發前先電話確認

**線上**
- **PChome / momo**：適合買配件（蛙鞋帶、防水袋、O-ring），比價快
- **蝦皮**：找有實體店的賣家（看評價＋是否提供保固），避免來路不明的水貨調節器
- **Facebook 社團**：「台灣潛水二手裝備交流」「潛水裝備買賣」— 11月不少人出清夏季裝備，二手 BC、蛙鞋議價空間大；調節器、電腦錶建議面交並要求保養紀錄

**11月時機建議**
- 台灣東北季風起，**墾丁、小琉球、綠島**仍是主要潛點；北部（東北角）進入淡季，店家常有**季末出清**，適合撿防寒衣、輕裝
- 11月底–12月初留意**黑色星期五（11/27 前後）**線上折扣，國外網站（如 Diveinn、Scuba.com）黑五折扣常達 20–30%，但注意關稅與運費
- 農曆年前（1–2月）是另一波促銷，若不急可等

## 裝備建議

**調節器與 BC 的「淡水沖洗＋陰乾」習慣

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-11-28 12:51:09`

#### AI Flight Tips — November
# November Flight Deals from Taiwan (TPE/TSA)

**Japan (Tokyo/Osaka/Sapporo)**
- November is **shoulder-to-peak**: autumn foliage drives up Tokyo/Osaka demand (late Nov peak); Sapporo is early ski-season shoulder, still moderate.
- Book **4–8 weeks out** for short-haul; fares firm up fast after mid-October.
- Cheapest: **Peach, Tigerair Taiwan, Scoot** to Narita/Kansai; for Sapporo, **Thai AirAsia X** or Peach via Tokyo often beats direct.
- Watch **Tigerair Taiwan's "Fly Taiwan" promos** and Peach's Tuesday sales; avoid the Nov 20–30 foliage crunch.

**Thailand (Bangkok/Chiang Mai)**
- November is **peak** — cool season + Loy Krathong (late Nov) = high demand, especially Chiang Mai.
- Book **6–10 weeks ahead**; Chiang Mai fills early for Yi Peng festival.
- Cheapest: **Thai VietJet, Scoot (via Singapore), AirAsia**; direct **China Airlines/Starlux** sales can undercut on Bangkok.
- Watch **AirAsia Free Seats** drops and VietJet's 0-baht promos; book Chiang Mai before Loy Krathong week.

**Europe (any major city)**
- November is **off-peak** (post-summer, pre-Christmas) — best-value month for Europe.
- Book **8–14 weeks out**; long-haul pricing stabilizes ~3 months prior.
- Cheapest: **China Eastern via Shanghai, Turkish via Istanbul, Scoot+connection**; **Emirates/Qatar** sales often beat one-stop Chinese carriers on service.
- Watch **Turkish Airlines and Emirates Taiwan sales** (usually Sept–Oct for winter travel); avoid booking through Dec 20.

**USA (West/East Coast)**
- November is **mixed**: early Nov off-peak, but **Thanksgiving week (Nov 20–30) is peak** — avoid if flexible.
- Book **10–16 weeks out**; Thanksgiving fares spike 6+ weeks prior.
- Cheapest: **EVA Air/China Airlines direct to LAX/SFO/ONT** on sale; **Korean Air via Seoul** or **ANA via Tokyo** often cheapest to East Coast.
- Watch **EVA's "Early Bird" and China Airlines anniversary sales**; fly out before Nov 15 or after Dec 1.

**Egypt (Cairo)**
- November is **peak** — ideal Red Sea/desert weather, high European demand.
- Book **8–12 weeks out**; limited Taiwan-Cairo routings mean early booking matters.
- Cheapest: **China Eastern via Shanghai, Emirates/Qatar via Gulf**; **Turkish via Istanbul** is a strong value one-stop.
- Watch **Qatar Airways and Emirates winter sales**; avoid routing through Israel/Jordan airspace advisories — check current NOTAMs.

**Australia (Sydney/Melbourne)**
- November is **shoulder-to-peak** — pre-summer, fares rising toward December.
- Book **8–12 weeks out**; Christmas-period fares balloon after mid-November.
- Cheapest: **China Airlines/EVA direct** on sale; **Scoot via Singapore** or

## 📚 Learning

### 📚 Learning — Finance
> `2026-11-28 12:51:19`

#### 📚 Today's Concept: Earnings Per Share (EPS)

What it is: EPS is a company's net profit divided by its total number of outstanding shares, telling you how much profit each share represents. It's the "per-unit" version of earnings, the same way you'd normalize a system's total throughput by the number of nodes to compare machines fairly.

Why it matters: EPS is the denominator in the P/E ratio and the baseline for growth comparisons, so it lets you compare profitability across companies of different sizes and track whether a business is actually improving quarter over quarter.

Example: A company earns $50 million net income with 25 million shares outstanding. Basic EPS = $50M / 25M = $2.00 per share. If it buys back 5 million shares, EPS becomes $50M / 20M = $2.50 — a 25% jump in EPS with zero improvement in actual profit. That's why buybacks inflate EPS artificially.

Rule of thumb: Always check diluted EPS (which counts stock options and convertibles) and watch for EPS growth driven by share count shrinking rather than earnings rising — that's a red flag, not real growth.

### 🧩 LeetCode Blind 100
> `2026-11-28 12:51:24`

#### 🧩 Blind 100 — 309. Best Time to Buy and Sell Stock with Cooldown [2D DP]
**連結:** https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/
> 📅 **Today's Daily Challenge:** #3745 Maximum Number of Items From Sale II [Medium] — Tags: Array, Greedy, Sorting, Heap (Priority Queue) — https://leetcode.com/problems/maximum-number-of-items-from-sale-ii/

## **Problem Type:** Dynamic Programming (State Machine / 2D DP)

**Key Insight:** At each day you're in one of three states: **holding** a stock, **sold** (just sold, in cooldown), or **rest** (free to buy). Track max profit per state and transition between them.

**Approach:**
1. Define three states: `hold` (own stock), `sold` (sold today, must cooldown tomorrow), `rest` (not holding, free to buy).
2. Transitions:
   - `hold[i] = max(hold[i-1], rest[i-1] - price[i])` — keep holding or buy from rest
   - `sold[i] = hold[i-1] + price[i]` — sell today
   - `rest[i] = max(rest[i-1], sold[i-1])` — stay resting or cooldown after selling
3. Answer = `max(sold[-1], rest[-1])` (can't end holding for max profit).
4. Optimize to O(1) space by keeping only previous day's values.

**Python3 Solution:**
```python
class Solution:
    def maxProfit(self, prices: List[int]) -> int:
        hold = float('-inf')  # max profit while holding
        sold = 0              # max profit on day we sold (cooldown next)
        rest = 0              # max profit while free to buy
        
        for p in prices:
            prev_hold, prev_sold, prev_rest = hold, sold, rest
            hold = max(prev_hold, prev_rest - p)
            sold = prev_hold + p
            rest = max(prev_rest, prev_sold)
        
        return max(sold, rest)
```

**Complexity:** Time O(n) | Space O(1)

**Blind 100 Note:** This is the "state machine DP" pattern — a step up from the simpler Stock I/II problems. It teaches you to model **mutually exclusive states with transitions**, which generalizes to problems like "House Robber" (rob/skip), "Paint House", and any DP where you track "what was I doing yesterday." Practice: 121, 122, 123, 188, 714 (fee), 198 (House Robber).

**Contest Tips:**
- **Edge cases:** n=0 or n=1 → return 0. Single price → no transaction possible.
- **Init trick:** `hold = -inf` (not `-prices[0]`) is cleaner and handles empty input gracefully.
- **Common mistake:** Forgetting cooldown means you **cannot** buy the day after selling — the `rest` state enforces this via `sold[i-1]` (not `sold[i]`).
- **Don't** try to return `hold` — you must be flat at the end.
- **Python trick:** Tuple unpacking `prev_hold, prev_sold, prev_rest = hold, sold, rest` avoids temp-variable bugs when updating in place.
- If asked for the 2D version, `dp[i][state]` with `dp[0]` base case — but O(1) space is what interviewers want.

### 📷 Learning — Photography
> `2026-11-28 12:51:29`

#### 📷 Today's Concept: Post — Lightroom RAW Editing Workflow

**What it is:** A Lightroom RAW workflow is a repeatable sequence for developing Sony ARW files—moving from global exposure and color correction to targeted local adjustments and finishing. It turns flat, unprocessed RAW captures into polished images without destructive edits.

**Why it matters:** A consistent order prevents rework and preserves image quality; you fix big problems (exposure, white balance) before detail work, so every slider builds on a clean base. It's the difference between editing by feel and editing with intent.

**How to apply it:**
1. **Cull and profile:** Import, flag keepers, and apply your camera profile (Adobe Standard or a custom one) in the Basic panel.
2. **Global tone:** Set exposure, then recover highlights and lift shadows with the histogram as your guide—avoid clipping.
3. **Color:** Correct white balance, then use HSL or Color Grading for a consistent look across the set.
4. **Local adjustments:** Use masks (subject, sky, radial) for dodge/burn and targeted contrast—this is where portraits and landscapes gain depth.
5. **Detail and finish:** Apply sharpening with masking, add subtle noise reduction, then export with output sharpening for the destination.

**Sony A7C tip:** Shoot RAW (not compressed) and enable "Camera Settings" in Lightroom's import to carry over your in-camera Picture Profile—useful for matching cinematic video grades.

**Common mistake:** Cranking clarity, dehaze, and saturation globally. Beginners over-season the whole frame; instead, reserve heavy contrast and color for masks so skin tones and skies stay natural.

### 📚 Learning — Tech
> `2026-11-28 12:51:26`

#### 📚 Today's Concept: CAP Theorem

**What it is:** CAP Theorem states that a distributed data system can simultaneously guarantee only two of three properties: Consistency (every read sees the latest write), Availability (every request gets a response), and Partition tolerance (the system keeps working despite network failures). Since network partitions are unavoidable in distributed systems, you're really choosing between consistency and availability during a partition.

**When to use it:** Use CAP as a design lens when picking a database or architecting a distributed service. For a payment ledger, favor consistency (CP); for a social media feed or product catalog, favor availability (AP) since stale data is tolerable.

**Example:** During a network split, a CP system like etcd rejects writes on the minority partition to preserve consistency, while an AP system like Cassandra accepts writes on both sides and reconciles later via eventual consistency.

**Gotcha:** CAP applies *only during a partition* — it's not a blanket "pick two" for normal operation. Many engineers wrongly assume choosing "AP" means giving up consistency always; in reality, a healthy network can provide both C and A. Also, "partition tolerance" isn't optional in distributed systems — you don't get to opt out.

### 🎬 Learning — YouTube
> `2026-11-28 12:51:32`

#### 🎬 今日主題：開箱 — 如何用 Sony A7C 拍出質感開箱影片
**類別：** 開箱

**是什麼：** 用 Sony A7C 拍開箱，重點在「光線、構圖、節奏」三件事，而非器材多貴。A7C 全片幅感光元件與翻轉螢幕，很適合拍質感特寫與自拍口播。

**為什麼重要：** 開箱影片是觀眾對頻道的第一印象，畫面質感直接影響訂閱與信任感；好的開箱流程也能讓你剪輯更省時。

**怎麼做：**
1. 找窗邊自然光或一盞柔光燈，避免頭頂直射造成反光。
2. 用 35mm 或 50mm 定焦，拍「手部拆封特寫＋產品環繞」兩種鏡位。
3. 開箱前先拍 B-roll（包裝、配件、細節），再拍口播，方便剪接。
4. 用 AI 剪輯工具（如 Descript、CapCut）自動上字幕、去除贅字，加快初剪。
5. 片頭 5 秒先給「成品亮點」，再回頭說開箱過程。

**新手常犯的錯：** 一開始就長時間口播、畫面單調。避免方式：每 5–8 秒換一次鏡位或插入特寫 B-roll。

**延伸 idea：** 「用 A7C 拍 A7C 開箱」——用相機拍自己的開箱，順便示範這台相機的錄影質感，一魚兩吃。
