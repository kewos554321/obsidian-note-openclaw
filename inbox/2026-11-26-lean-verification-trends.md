---
date: 2026-11-26
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-11-26

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

- **AI 硬體全面殺盤，半導體最慘** — ARM 暴跌 8.58%、SMCI -4.97%、AVGO -4.05%、NVDA -3.91%，而 VOO 僅跌 0.76%，顯示這是 AI/半導體集中性拋售而非大盤崩跌。若你持有 AI 硬體部位，今天是檢視 beta 曝險的好時機（延伸閱讀：今日 Beta 教學）。[BBC 報導](https://www.bbc.co.uk/news/articles/cq0md8g14zryo)
- **台股逆勢大漲 2.63% 至 39,201** — 在全球 AI 恐慌中台股一枝獨秀，但美股走弱可能壓抑出口導向科技股，留意明日補跌風險。
- **Google 推出 Agent 治理三件套** — Tool Retrieval（省 token 存取數百工具）、Semantic Governance Policies（防間接 prompt injection / intent hijacking）、Agent Anomaly Detection（跨雲監控 ADK agent）。做 agent 產品的直接受用。[Tool Retrieval](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/) · [Semantic Governance](https://developers.googleblog.com/did-the-user-ask-for-this-securing-ai-agents-against-intent-hijacking-with-semantic-governance-policies/)
- **美國對中國、歐盟等主要貿易夥伴加徵新關稅** — 牽動全球供應鏈與台廠出口，值得追蹤後續。[BBC](https://www.bbc.co.uk/news/articles/c893r9ke5p97o)
- **OpenAI 砍用量限制** — GPT-6.2 Astra 雖在 code golf 奪冠，但觸頂速度快 40%（Sol 快 25%），若你重度使用 API 要重新估算成本。[Limits 公告](https://twitter.com/thsottiaux/status/2125784147889393806)

---

- 💻 **Tech**: Anthropic GRH Lean 精簡版登上 HN、Astra 稱霸 code golf 但限額收緊、tokenizer 近似複雜度新證明（P≠NP 前提下無常數近似）。
- 🤖 **AI 公司動態**: 無 OpenAI/Anthropic 實質更新；本節全為 Tesla/SpaceX 合併臆測與 Ron Baron 的 $50B/資料中心營收預測。
- 🔵 **Google**: Agent 工具檢索、Vertex AI 託管檢索、語意治理政策、跨雲異常偵測、DeepMind LLM 可靠度基準 + Kaggle 黑客松。
- 📈 **Markets**: 台股 +2.63% 領漲全球，美股 S&P -0.75% 轉弱，日經 +1.59% 亞洲偏多。
- 🏠 **台灣房市**: 高總價盤整、租賃熱、外圍讓利；台中梧棲賠售案是議價訊號，自住可大膽出價。
- 📊 **Watchlist**: 12 檔中 10 檔下跌，ARM 最慘 -8.58%；META +3.40%、PLTR +1.50% 逆勢；估值數據全 N/A。
- 🌍 **World News**: 美新關稅、NASA 撞擊小行星留下球場級隕石坑、開羅油罐車大火 31 死、納坦雅胡最重指控建議撤銷、AI 恐慌拖累美股。
- 📷 **Camera Deals**: 雙11後等黑五/年終第二波；光華現金議價 3–8%；日圓弱則日本代購二手良品划算，價差 <10% 選公司貨。
- 🤿 **Dive Gear Deals**: 東北季風起，東北角海況轉差，改攻墾丁/小琉球/綠島；11月換季撿便宜夏季防寒衣，二手調節器/電腦錶必查保養紀錄。
- ✈️ **Flight Tips**: 日本避開 11/20–30 賞楓+假期；歐洲 11 月最超值（10–16 週前訂）；埃及為旺季（10–14 週前）；澳洲 8–12 週前。
- 📚 **Finance**: Beta 衡量系統性風險——beta

---

## 💻 Tech

### 💻 Tech & AI
> `2026-11-26 13:16:50`

#### Hacker News
- [Much shorter version of GRH Lean verification from Anthropic](https://github.com/lsernau/grh-lean) ⭐362
- [Tell HN: Lots of Ask HNs again](https://news.ycombinator.com/item?id=50649864) ⭐173
- [GPT-6.2 Astra is the first model to beat Googlers' code golf records](https://bjin.github.io/go-codegolf-benchmark/#leaderboard) ⭐316
- [OpenAI cuts GPT-6.2 usage: Astra hits limits 40% faster, Sol 25% faster](https://twitter.com/thsottiaux/status/2125784147889393806) ⭐66
- [The New York Times warns photographers not to update Photoshop over AI features](https://www.theverge.com/ai-artificial-intelligence/1041227/the-new-york-times-warns-photographers-not-to-update-photoshop-over-ai-features) ⭐276
- [Marginal Grains](https://asteriskmag.com/issues/16/marginal-grains) ⭐4
- [Porting Rockbox to an undocumented $9 AliExpress 'YP3' MP3 player with LLMs](https://jayd.ml/2026/11/14/rockbox-on-yp3.html) ⭐243
- [Britain's ghost stations](https://spectator.com/article/britains-ghost-stations-are-fascinating/) ⭐117
- [Show HN: An agent skill that optimizes code with falsifiable hypotheses](https://chszlab.github.io/AgenticAlgorithmEngineering/) ⭐94
- [Show HN: Old Nvidia and ATI tech demos, running again in the browser](https://gpu-demo-gallery.pages.dev/) ⭐342

#### HuggingFace
- [Negative-Only Policy Optimization for One-Sided Verifiable Rewards](https://huggingface.co/papers/2611.17287)
- [RoboEvo^2: Recursive Robot Self-Improvement via Harness-Policy Co-Evolution](https://huggingface.co/papers/2611.34675)
- [FoundSurface: Feedforward Ray-Based 3D Scene Surface Reconstruction from Unposed Images](https://huggingface.co/papers/2611.34128)
- [3D CoCa v3: Contrastive Learners with Scene Graphs for Urban Scene Understanding](https://huggingface.co/papers/2611.33835)
- [What Is Redundant at High Resolution? Efficient Attention and Feed-Forward Design for All-in-One Image Restoration](https://huggingface.co/papers/2611.33636)
- [Sage-Med: Scaling Medical Multimodal Intelligence](https://huggingface.co/papers/2611.34575)

#### ArXiv
- [Spectrum Adaptation of AI-Native Autoencoder Communications with Transfer Learning](http://arxiv.org/abs/2611.34942v1)
- [Tokenisation is not in APX](http://arxiv.org/abs/2611.34938v1)
- [Can image generation help visual reasoning? An empirical study](http://arxiv.org/abs/2611.34935v1)
- [Attack Policy Selection can Mislead Monitor Evaluators](http://arxiv.org/abs/2611.34934v1)
- [A gene informed benchmark for BioScoring of pathology foundation models](http://arxiv.org/abs/2611.34930v1)
- [Diverse Alternative Reasoning Traces for Hard Math Problems](http://arxiv.org/abs/2611.34928v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-11-26 13:16:58`

#### Tesla
- [Cathie Wood Buys More SpaceX Amid Tesla Merger Talks — Ron Baron Says SpaceX Could Make $50B A Year From One Data Center](https://finance.yahoo.com/markets/stocks/articles/cathie-wood-buys-more-spacex-033235789.html)
- [Mark Cuban Says the Most Common Mistake He Saw Founders Make on 'Shark Tank' Was a Job They Kept Handing Off: 'You're Going to Fail'](https://finance.yahoo.com/small-business/articles/mark-cuban-says-most-common-033007508.html)
- [Elon Musk tells Tesla investors there is 'only one way' to eliminate poverty](https://finance.yahoo.com/economy/policy/articles/elon-musk-tells-tesla-investors-003700193.html)
- [If SpaceX and Tesla Merge Next Year, Here's What a $5,000 Investment in the Combined Company Could Be Worth by the End of 2028](https://finance.yahoo.com/markets/stocks/articles/spacex-tesla-merge-next-heres-232402788.html)

### 🔵 Google 動態
> `2026-11-26 13:16:53`

#### Google AI Blog
- [How Gemini is changing the game for Golden State's organization and fans.](https://blog.google/products-and-platforms/products/gemini/gemini-golden-state/)
- [A more tailored Google Search that’s uniquely yours](https://blog.google/products-and-platforms/products/search/google-search-personal-intelligence-apps/)
- [Introducing Tool Retrieval in the Gemini API](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/)
- [Walter Isaacson on curiosity and creativity in the AI age.](https://blog.google/innovation-and-ai/technology/ai/dialogues-walter-isaacson/)
- [The Gemini app is now available on lower-memory Android devices.](https://blog.google/innovation-and-ai/products/gemini-app/gemini-lower-memory-devices/)
#### Google Blog
- [We’re launching Humanity’s First Exam and a Kaggle hackathon to test LLM reliability.](https://blog.google/innovation-and-ai/models-and-research/google-deepmind/humanitys-first-exam/)
- [How Gemini is changing the game for Golden State's organization and fans.](https://blog.google/products-and-platforms/products/gemini/gemini-golden-state/)
- [See what 5 builders are making with Gemini 4 Neon](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-4-neon-builders/)
- [Independent filmmakers in India bring big-screen stories to life with Google Flow.](https://blog.google/innovation-and-ai/models-and-research/google-labs/women-in-film-india-google-flow/)
- [We’re expanding our London home in King's Cross.](https://blog.google/company-news/inside-google/around-the-globe/google-europe/united-kingdom/expanding-london-home-kings-cross/)
#### Google Developers
- [From Files to Cited Answers in One API Call: Managed Ingestion and SearchDocuments in Agent Retrieval](https://developers.googleblog.com/from-files-to-cited-answers-in-one-api-call-managed-ingestion-and-searchdocuments-in-agent-retrieval/)
- [Did the user ask for this? Securing AI agents against intent hijacking with Semantic governance policies](https://developers.googleblog.com/did-the-user-ask-for-this-securing-ai-agents-against-intent-hijacking-with-semantic-governance-policies/)
- [Check what your AI agents do before they do it, with Semantic governance policies](https://developers.googleblog.com/check-what-your-ai-agents-do-before-they-do-it-with-semantic-governance-policies/)
- [How to securely connect internal Cloud Run MCP servers to Gemini Enterprise](https://developers.googleblog.com/how-to-securely-connect-internal-cloud-run-mcp-servers-to-gemini-enterprise/)
- [Agent Anomaly Detection: Safeguarding agents across other clouds](https://developers.googleblog.com/agent-anomaly-detection-safeguarding-agents-across-other-clouds/)

## 📈 Finance

### 📈 Markets Overview
> `2026-11-26 13:17:01`

#### Indices
- S&P 500: 7,182.78 ▼0.75%
- 台股加權: 39,201.58 ▲2.63%
- 日經 225: 57,919.23 ▲1.59%

### 🏠 台灣房市
> `2026-11-26 13:17:49`

#### AI 分析
## 台灣房市速報（2026-11-26）

**1. 整體趨勢**
高總價住宅交易仍以蛋黃區大坪數產品為主力，實價登錄顯示單價落在 27–46 萬/㎡（約 90–150 萬/坪）區間，顯示精華地段價格具支撐但去化放緩。租賃市場掛牌活躍，尤其雙北捷運沿線小坪數與店面型產品供給穩定，反映「以租代買」與資金停泊需求仍強。整體呈現「高總價盤整、租賃熱、外圍讓利」的格局。

**2. 值得注意的地區/物件**
- **台中梧棲「賠售」案**：賣方明示讓利，外圍重劃區與新成屋供給壓力浮現，是議價空間最大的訊號區。
- **台中西屯歌劇院第一排豪宅**：蛋黃區 SRC 大坪數仍掛高總價，去化考驗買方信心。
- **桃園蘆竹/大園土地與停車場用地**：交流道與都內農地掛牌增，顯示資金轉向「收益型土地」與低維護資產。
- **雙北捷運站周邊租案**（中山、信義永春）：小坪數、含車位、門廳氣派者仍搶手，租金支撐力強。

**3. 對自住者建議**
優先鎖定「捷運/交流道 + 成屋 + 賣方讓利」物件（如台中梧棲、南區兩房含車位），現在是議價窗口，可大膽出價、要求實登比價；避開供給量大的新重劃區預售，改看中古成屋的實際單價。

**4. 對投資者建議**
高總價豪宅（歌劇院第一排、信義大坪數）流動性偏弱，不宜追高；可關注「賠售案」與外圍讓利產品的租金投報，以及桃園交流道周邊土地/停車場等收益型資產。雙北捷運小宅仍是穩健收租標的，但須精算管理成本與空置率。

**5. 風險提醒**
實登高總價樣本單價離散大（27–46 萬/㎡），顯示個案差異極大，勿以單筆成交推估行情；外圍「賠售」訊號若擴大，恐牽動重劃區價格修正，進場前務必查核社區近期成交與待售量。

#### 591 最新
- [桃園市蘆竹區大竹北路優質大竹交流道空地最後倒數~適宜停車場](https://rent.591.com.tw/rent-detail-22410436.html)
- [台北市中山區錦州街D09租雙連/中山國小站一層一戶好規劃](https://rent.591.com.tw/rent-detail-20941389.html)
- [台中市西屯區惠中三街歌劇院第一排SRC豪宅聚合發獨秀四房四衛雙車](https://sale.591.com.tw/sale-detail-21324217.html)
- [台北市信義區忠孝東路五段Y05租永春站氣派門廳含平面車位採光佳](https://rent.591.com.tw/rent-detail-22254066.html)
- [台中市梧棲區中央路二段219巷閱好書房｜全新3房平車📍賠售、撿便宜的好時機](https://sale.591.com.tw/sale-detail-21324214.html)
- [台中市北屯區僑孝街北屯近一中超值公寓兩房✨寵物友善✨台水電](https://rent.591.com.tw/rent-detail-22410433.html)
- [桃園市大園區正航城路30米都內農地](https://sale.591.com.tw/sale-detail-21324215.html)
- [台中市南區崇倫街專任南區｜中山醫秀泰好市多旁｜兩房兩衛車位可停休旅｜馬上看屋](https://sale.591.com.tw/sale-detail-21324213.html)

#### 實價登錄 (115S3) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 住宅大樓(11層含以上有電梯) | 963.3㎡ | 29664萬 | 307937元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 399.6㎡ | 14468萬 | 449312元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 379.7㎡ | 10438萬 | 274908元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 267.7㎡ | 8558萬 | 367305元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 144.7㎡ | 5700萬 | 456525元/㎡ |

### 📊 Watchlist
> `2026-11-26 13:17:24`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 149.30 ▼3.91% |
| Market Cap | $3.60T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.9% / 66.1% / 62.5% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.50 |
| Beta | 2.25 |
| 52-Week | 124.50 – 243.37 |
| Div. Yield | — |

**Recent News:**
- [Global markets rebound as tech shares recover and tariff fears ease](https://finance.yahoo.com/markets/world-indices/articles/global-markets-rebound-tech-shares-042539373.html) — Euronews
- [Kioxia and NVIDIA Collaborate to Expand Effective High-Bandwidth Memory Capacity with SSDs](https://finance.yahoo.com/technology/ai/articles/kioxia-nvidia-collaborate-expand-effective-041900475.html) — Business Wire
- [‘I Don’t Think He Needs a Pardon at All’: JD Vance Defends Nvidia CEO Jensen Huang as Crypto Bettors Put Him Atop Trump’s List](https://finance.yahoo.com/markets/stocks/articles/don-t-think-needs-pardon-041403554.html) — Benzinga Prediction Markets

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 406.03 ▼1.75% |
| Market Cap | $665.93B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.7% / 17.7% / 16.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 9.71 |
| Beta | 2.49 |
| 52-Week | 188.22 – 658.52 |
| Div. Yield | — |

**Recent News:**
- [Why Retail Investors Are Watching AMD and AI Infrastructure Stocks After SpaceX Satellite News](https://finance.yahoo.com/technology/ai/articles/why-retail-investors-watching-amd-021215050.html) — Simply Wall St.
- [Tech Stocks Stall Into Thanksgiving: Will the AI Rebound Return?](https://finance.yahoo.com/markets/stocks/articles/tech-stocks-stall-thanksgiving-ai-011953375.html) — BeInCrypto
- [Big AI Buyers Want a Second Source. Is AMD (AMD) It?](https://finance.yahoo.com/technology/ai/articles/big-ai-buyers-want-second-005602621.html) — Insider Monkey

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 489.93 ▼1.25% |
| Market Cap | $3.64T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.7% / 47.1% / 41.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 7.73 |
| Beta | 1.04 |
| 52-Week | 349.20 – 559.15 |
| Div. Yield | — |

**Recent News:**
- [Nvidia’s Market Cap Falls Below Microsoft’s: Analyst Flags Five Overhangs For NVDA Stock](https://finance.yahoo.com/markets/stocks/articles/nvidia-market-cap-falls-below-023942800.html) — Stocktwits
- [Apple Stock Defies AI Selloff: Is It the Market's Safe Haven?](https://finance.yahoo.com/markets/stocks/articles/apple-stock-defies-ai-selloff-010000265.html) — BeInCrypto
- [Microsoft's Green Card Filings Reveal A Striking Pattern After Mass Layoffs. Trump's New Rule Could Freeze Sponsorships For Two Years.](https://finance.yahoo.com/technology/articles/microsofts-green-card-filings-reveal-234807020.html) — International Business Times

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 273.10 ▼2.13% |
| Market Cap | $3.33T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.3% / 50.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.94 |
| Beta | 1.23 |
| 52-Week | 262.73 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [SpaceX gets approval for 1 million data center satellites](https://finance.yahoo.com/technology/ai/articles/spacex-gets-approval-1-million-023847485.html) — LA Times
- [Apple Stock Defies AI Selloff: Is It the Market's Safe Haven?](https://finance.yahoo.com/markets/stocks/articles/apple-stock-defies-ai-selloff-010000265.html) — BeInCrypto
- [5 Best Strong Buy Growth Stocks to Buy for 2027](https://finance.yahoo.com/markets/stocks/articles/5-best-strong-buy-growth-004610627.html) — Insider Monkey

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 244.43 ▼3.12% |
| Market Cap | $2.64T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 51.4% / 13.1% / 16.9% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.30 |
| Beta | 1.50 |
| 52-Week | 196.00 – 287.20 |
| Div. Yield | — |

**Recent News:**
- [MegazoneCloud Launches Its Amazon Quick Center of Excellence to Turn Enterprise Data Into Autonomous Action](https://finance.yahoo.com/technology/ai/articles/megazonecloud-launches-amazon-quick-center-042800157.html) — PR Newswire
- [Washington Calls It a Goldilocks Economy. On a $2,071 Social Security Check, She Calls It the Annoyance Economy: Prices Up 3.7%, and Her Real Raise Is Just 3.3%](https://finance.yahoo.com/economy/articles/washington-calls-goldilocks-economy-2-020325062.html) — 24/7 Wall St.
- [Apple Stock Defies AI Selloff: Is It the Market's Safe Haven?](https://finance.yahoo.com/markets/stocks/articles/apple-stock-defies-ai-selloff-010000265.html) — BeInCrypto

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 609.89 ▲3.40% |
| Market Cap | $1.56T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.0% / 32.9% / 31.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 5.71 |
| Beta | 1.28 |
| 52-Week | 520.26 – 779.82 |
| Div. Yield | — |

**Recent News:**
- [Apple Stock Defies AI Selloff: Is It the Market's Safe Haven?](https://finance.yahoo.com/markets/stocks/articles/apple-stock-defies-ai-selloff-010000265.html) — BeInCrypto
- [5 Best Strong Buy Growth Stocks to Buy for 2027](https://finance.yahoo.com/markets/stocks/articles/5-best-strong-buy-growth-004610627.html) — Insider Monkey
- [Bill Gurley: Investors Weren’t “Scrambling to Actually Own Anthropic.” That’s a Problem for Amazon and Alphabet](https://finance.yahoo.com/markets/stocks/articles/bill-gurley-investors-weren-t-234306800.html) — TIKR

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 300.86 ▼4.05% |
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
- [Why Retail Investors Are Watching AMD and AI Infrastructure Stocks After SpaceX Satellite News](https://finance.yahoo.com/technology/ai/articles/why-retail-investors-watching-amd-021215050.html) — Simply Wall St.
- [Broadcom Stock Hasn't Traded This Low Since July 2025. I Think It's a Buy.](https://finance.yahoo.com/markets/stocks/articles/broadcom-stock-hasnt-traded-low-010302052.html) — Motley Fool
- [5 Best Strong Buy Growth Stocks to Buy for 2027](https://finance.yahoo.com/markets/stocks/articles/5-best-strong-buy-growth-004610627.html) — Insider Monkey

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 161.51 ▼8.58% |
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
- [Nvidia Sinks 9% as Huang Rally Fades: Stephanie Link Sees “A Cloud Over It”](https://finance.yahoo.com/markets/stocks/articles/nvidia-sinks-9-huang-rally-172416717.html) — TIKR
- [Chip stocks tumble as Nvidia-led AI rally unravels, tariff fears weigh](https://finance.yahoo.com/technology/ai/articles/chip-stocks-tumble-nvidia-led-164900978.html) — Proactive
- [Dow Craters Over 1000 Points, Nasdaq Slips 4% As AI Trade Unravels – Investors Digest PCE Inflation, Fresh Tariff Proposal](https://finance.yahoo.com/markets/stocks/articles/dow-craters-over-1000-points-150503134.html) — Stocktwits

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 163.59 ▲1.50% |
| Market Cap | $377.35B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.7% / 45.6% / 50.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 35.05 |
| Beta | 1.62 |
| 52-Week | 106.37 – 212.94 |
| Div. Yield | — |

**Recent News:**
- [Michael Burry Says His Portfolio Was Discussed 'About the Time the Market Reversed Off Its Lows': He Is 'Temporarily Almost Entirely Long'](https://finance.yahoo.com/markets/stocks/articles/michael-burry-says-portfolio-discussed-025825540.html) — Benzinga
- [Are You Overpaying For Palantir Stock Versus Its Rivals?](https://finance.yahoo.com/markets/stocks/articles/overpaying-palantir-stock-versus-rivals-233104992.html) — Trefis
- ['Big Short' Investor Michael Burry Just Closed His Bet Against the Nasdaq. Here's What Investors Should Do Now](https://finance.yahoo.com/markets/stocks/articles/big-short-investor-michael-burry-232028325.html) — Motley Fool

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 23.31 ▼4.97% |
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
- [The Other Nvidia Romance With an Executive at a Company Linked to China](https://finance.yahoo.com/m/2f6a3433-edd6-36a1-ab49-a5f6a23fc125/the-other-nvidia-romance-with.html) — The Wall Street Journal
- [Explainer-How China got access to Nvidia's AI chips despite rules to stop them](https://finance.yahoo.com/news/explainer-china-got-access-nvidias-193901126.html) — Reuters
- [How the Trump administration determined Jensen Huang is not a national security threat](https://finance.yahoo.com/news/us-justice-department-did-not-173024901.html) — Reuters

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 380.14 ▼1.18% |
| Market Cap | $1.50T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.3% / 3.3% / 3.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.79 |
| Beta | 1.74 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Cathie Wood Buys More SpaceX Amid Tesla Merger Talks — Ron Baron Says SpaceX Could Make $50B A Year From One Data Center](https://finance.yahoo.com/markets/stocks/articles/cathie-wood-buys-more-spacex-033235789.html) — Stocktwits
- [Mark Cuban Says the Most Common Mistake He Saw Founders Make on 'Shark Tank' Was a Job They Kept Handing Off: 'You're Going to Fail'](https://finance.yahoo.com/small-business/articles/mark-cuban-says-most-common-033007508.html) — Benzinga
- [Elon Musk tells Tesla investors there is 'only one way' to eliminate poverty](https://finance.yahoo.com/economy/policy/articles/elon-musk-tells-tesla-investors-003700193.html) — TheStreet

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 658.87 ▼0.76% |
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
- [Is XRP a Good Investment for Building Wealth by 2035?](https://finance.yahoo.com/markets/crypto/articles/xrp-good-investment-building-wealth-234250300.html) — 24/7 Wall St.
- [Is AI's Circular Money Machine In Peril?](https://finance.yahoo.com/technology/ai/articles/ais-circular-money-machine-peril-215010831.html) — etf.com
- [$1 Million In VYM Matched VOO With Smaller Falls](https://finance.yahoo.com/markets/stocks/articles/1-million-vym-matched-voo-131452847.html) — Trefis

## 🌍 News

### 🌍 World News
> `2026-11-26 13:17:52`

- [US announces new tariffs on host of countries including China](https://www.bbc.co.uk/news/articles/c893r9ke5p97o?at_medium=RSS&at_campaign=rss)
- [Images of asteroid targeted to test Earth's defences reveal stadium-sized crater](https://www.bbc.co.uk/news/articles/cw8dv112r5gmo?at_medium=RSS&at_campaign=rss)
- [Thirty-one killed in massive fire as fuel tanker crashes on Cairo highway](https://www.bbc.co.uk/news/articles/cqy7rn30v314o?at_medium=RSS&at_campaign=rss)
- [Has global jihadism failed, or is it simply changing shape?](https://www.bbc.co.uk/news/articles/cmx2x4e0n5jro?at_medium=RSS&at_campaign=rss)
- [Israeli judges recommend dropping most serious charges against Netanyahu](https://www.bbc.co.uk/news/articles/cxj05mv723r2o?at_medium=RSS&at_campaign=rss)
- [US stocks fall further as fears over AI intensify](https://www.bbc.co.uk/news/articles/cq0md8g14zryo?at_medium=RSS&at_campaign=rss)
- [US Army says controlled blast of explosives in Iowa was 'huge success'](https://www.bbc.co.uk/news/articles/cwg7l5ve251ko?at_medium=RSS&at_campaign=rss)
- [California warns of flooding as King Tides peak over Thanksgiving](https://www.bbc.co.uk/news/articles/ckn806qq760po?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-11-26 13:18:02`

#### AI Tips
# 📷 2026-11-26 攝影顧問日報

## 【購買優惠】台灣買相機鏡頭攻略

**通路比較（依需求選）**

| 通路 | 適合買什麼 | 注意事項 |
|---|---|---|
| **PChome 24h** | 公司貨機身、記憶卡、腳架 | 常有「24h到貨」+ 信用卡回饋疊加；比價快但價格偏硬 |
| **momo** | 促銷檔期撿便宜、配件 | 雙11後仍有「黑五/年終」檔；注意是否為平輸（水貨） |
| **光華商場** | 議價空間大、二手鏡頭、當場驗貨 | 現金價通常比標價低 3–8%；務必當場測對焦、看序號、要保固卡 |
| **日本代購** | 日系鏡頭、二手良品（Map Camera、Kitamura） | 匯率好時省 10–20%，但**無台灣保固**、維修要寄回；留意電壓/韌體語言 |
| **二手（旋轉拍賣、DCView、FB社團）** | 高階鏡頭、停產機 | 面交必測：快門數、感光元件壞點、鏡頭入塵/霉、對焦環阻尼 |

**11月檔期重點**
- **雙11剛過（11/11）**：別急，**11月底–12月初的「黑五 + 年終慶」** 常有第二波，momo/PChome 會再殺一輪。
- **光華商場**：年底資訊月/週年慶，現金議價最好談，平日下午人少更好殺。
- **日本代購**：日圓若偏弱，11–12月是入手二手良品好時機（日本店家年末出清）。
- **實用建議**：先鎖定型號 → 用「BigGo / FindPrice」比價 → 公司貨比保固、水貨比價差，**價差 <10% 選公司貨**。

---

## 【今日攝影技巧】逆光下的「曝光補償 + 對焦鎖

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-11-26 13:18:06`

#### AI Tips
# 台灣潛水裝備購買 & 11月實用指南

## 【購買優惠】

**實體店（北/中/南）**
- **台北**：潛水貨倉（品項齊、可試穿）、海人潛水、BlueTrend 藍色趨勢（自由潛水強項）
- **台中**：潛水易購網實體門市、大西洋潛水
- **高雄**：海王子潛水、南台灣潛水（墾丁出發前補貨方便）
- 建議：**防寒衣、BCD、蛙鞋務必現場試**，別純網購尺寸。

**線上 / 社團**
- 蝦皮、PChome 找配件（蛙鞋帶、O-ring、防水袋）比價快
- **Facebook 社團**：「台灣潛水二手交流」「潛水裝備買賣」— 二手調節器、電腦錶流通多，但**調節器/電腦錶二手務必要求近期保養紀錄**，否則省小錢賠大錢
- 11月留意：**雙11（11/11）電商檔期**是全年配件折扣最大檔，蛙鞋、防寒衣、潛水錶常有 7–8 折；黑色星期五（11月底）部分進口品牌跟進

**11月季節提醒**
- 東北季風起，**東北角（龍洞、鼻頭角）能見度與海況轉差**，下水前查中央氣象署海況；此時**墾丁、小琉球、綠島**海況較穩，是南台灣潛季主力
- 11月是**換季撿便宜**時機：店家出清夏季防寒衣、短袖款；但若要**3mm以上防寒衣**，反而是旺季

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-11-26 13:17:57`

#### AI Flight Tips — November
# Flight Deals Playbook — Departing Taiwan (TPE/TSA), November 2026

**Japan (Tokyo/Osaka/Sapporo)**
- November is **shoulder-to-peak**: autumn foliage peaks mid–late Nov (Kyoto/Osaka crowds), Sapporo enters ski-season pricing; book **6–10 weeks out** for the sweet spot.
- Cheapest: LCCs **Peach, Tigerair Taiwan, Scoot** into Narita/Kansai; for Sapporo, **Peach or Tigerair** via Tokyo often beats direct.
- Watch **Tigerair Taiwan** and **Peach** "early-bird" promos (Tue/Wed sales); avoid flying Nov 20–30 (foliage + Japan holidays).

**Thailand (Bangkok/Chiang Mai)**
- November is **peak** — cool, dry season + Loy Krathong (late Nov); Chiang Mai also enters high season. Book **8–12 weeks ahead**.
- Cheapest: **Thai Lion Air, VietJet (via SGN/HAN), Scoot (via SIN)**; direct **China Airlines/EVA** if you value nonstop.
- Watch **AirAsia** and **Thai Lion** flash sales; Chiang Mai via Bangkok is often cheaper than direct.

**Europe (any major city)**
- November is **off-peak** (post-summer, pre-Christmas) — best-value month; book **10–16 weeks out** for lowest fares.
- Cheapest: **China Airlines/EVA to Amsterdam/Frankfurt/Vienna**, or **Turkish Airlines via IST**; **Scoot/AirAsia via SIN/KUL** for budget.
- Watch **China Airlines** and **EVA Air** winter promos; Black Friday/Cyber Monday (late Nov) often triggers Europe fare drops.

**USA (West/East Coast)**
- November is **off-peak except Thanksgiving week (Nov 20–30)** — avoid that window; book **8–14 weeks ahead**.
- Cheapest: **China Airlines/EVA to LAX/SFO/SEA** (West), **EVA/China Airlines to JFK/ORD** (East); **Korean Air/Asiana via ICN** often undercuts.
- Watch **EVA Air** and **China Airlines** Black Friday sales; West Coast is consistently cheaper than East.

**Egypt (Cairo)**
- November is **peak** — ideal weather, high demand; book **10–14 weeks ahead**.
- Cheapest: **Emirates/Qatar/Etihad via Gulf hubs**; **China Airlines via BKK** or **Turkish via IST** can be competitive.
- Watch **Qatar Airways** and **Emirates** November promos; Gulf-hub routings beat direct options (no TPE–CAI nonstop).

**Australia (Sydney/Melbourne)**
- November is **shoulder-to-peak** (pre-summer, school-holiday buildup); book **8–12 weeks out**.
- Cheapest: **China Airlines/EVA to SYD/MEL**; **Scoot via SIN** or **AirAsia X via KUL** for budget.
- Watch **China Airlines** and **EVA** spring/summer promos; Melbourne often slightly cheaper than Sydney.

**Cross-cutting tips:**

## 📚 Learning

### 📚 Learning — Finance
> `2026-11-26 13:18:08`

#### 📚 Today's Concept: Beta and Volatility

What it is: Beta measures how much a stock's price moves relative to the overall market, where the market has a beta of 1.0. A stock with beta 1.5 tends to move 50% more than the market in either direction, while beta 0.5 moves half as much.

Why it matters: Beta quantifies the systematic risk you're adding to a portfolio, letting you size positions appropriately and understand what you're actually buying when you pick a "safe" or "aggressive" stock.

Example: The S&P 500 rises 10%. Stock A (beta 1.4) gains roughly 14%; Stock B (beta 0.6) gains roughly 6%. If the market drops 10%, A falls ~14% and B falls ~6%. A $10,000 position in A carries the same market risk as $14,000 in the index.

Rule of thumb: Beta above 1.5 means you're leveraged to market swings—size the position smaller, not larger. And remember beta only captures market-correlated risk: a low-beta stock can still blow up on company-specific news.

### 🧩 LeetCode Blind 100
> `2026-11-26 13:18:14`

#### 🧩 Blind 100 — 684. Redundant Connection [Graphs]
**連結:** https://leetcode.com/problems/redundant-connection/
> 📅 **Today's Daily Challenge:** #3625 Stone Removal Game [Easy] — Tags: Math, Simulation — https://leetcode.com/problems/stone-removal-game/

# 684. Redundant Connection

**Problem Type:** Union-Find (DSU) / Cycle Detection in Undirected Graph

**Key Insight:** In a tree with one extra edge, the first edge that connects two already-connected nodes is the redundant one. Process edges in order with DSU — the first union that fails is the answer.

**Approach:**
1. Initialize DSU with `n` nodes (1-indexed), each its own parent, rank/size = 1.
2. Iterate edges `[u, v]` in given order.
3. For each edge, attempt `union(u, v)`.
4. If `find(u) == find(v)` before union → this edge creates a cycle → return `[u, v]`.
5. (Guaranteed to find one since input is a tree + 1 edge.)

**Python3 Solution:**
```python
class Solution:
    def findRedundantConnection(self, edges: List[List[int]]) -> List[int]:
        n = len(edges)
        parent = list(range(n + 1))
        rank = [1] * (n + 1)

        def find(x):
            while parent[x] != x:
                parent[x] = parent[parent[x]]  # path halving
                x = parent[x]
            return x

        def union(a, b):
            ra, rb = find(a), find(b)
            if ra == rb:
                return False
            if rank[ra] < rank[rb]:
                ra, rb = rb, ra
            parent[rb] = ra
            rank[ra] += rank[rb]
            return True

        for u, v in edges:
            if not union(u, v):
                return [u, v]
        return []
```

**Complexity:** Time O(n · α(n)) ≈ O(n) | Space O(n)

**Blind 100 Note:** Canonical Union-Find problem — teaches DSU with path compression + union by rank, and the "first failing union = cycle edge" pattern. Directly generalizes to **Number of Connected Components (323)**, **Graph Valid Tree (261)**, **Accounts Merge (721)**, **Connecting Cities (1135)**, and **Redundant Connection II (685)** (directed variant — harder, worth doing after).

**Contest Tips:**
- **1-indexed nodes** — size arrays as `n+1`, not `n`. Off-by-one here is the #1 bug.
- **Path halving** (`parent[x] = parent[parent[x]]`) is faster in Python than full path compression recursion — avoids recursion overhead.
- **Union by rank/size matters** — without it, worst case degrades to O(n) per find on adversarial inputs.
- **Don't sort edges** — the problem asks for the edge that appears *last* in the input order among cycle edges; processing in given order handles this naturally.
- **Alternative:** DFS cycle detection works but is O(n²) — DSU is the intended solution and what interviewers want to see.
- **685 (Redundant Connection II)** is a trap: directed graph needs case analysis (two parents / cycle). Don't assume the same code works.

### 📷 Learning — Photography
> `2026-11-26 13:18:20`

#### 📷 Today's Concept: Composition — Leading Lines and Visual Flow

**What it is:** Leading lines are real or implied lines in a scene—roads, railings, shorelines, shadows, architecture—that guide the viewer's eye toward your subject. Visual flow is how those lines and shapes move the eye through the frame in a deliberate path.

**Why it matters:** Lines create depth and direction, turning a flat image into a journey. They tell the viewer where to look first and keep them engaged, which is the difference between a snapshot and a composed photograph.

**How to apply it:**
1. Before shooting, scan for lines: curbs, fences, rivers, light streaks, building edges. Ask where each one points.
2. Position lines to converge on your subject—place them starting near a corner and running toward your subject's face or the horizon.
3. Get low or change height to exaggerate the line's length and drama.
4. Use lines to lead *into* the frame, not out of it—avoid lines that pull the eye off the edge.
5. In street and video, use motion (a path, a corridor) so the eye flows naturally through the scene.

**Sony A7C tip:** Use the 28mm end of the kit lens (or a 24–35mm prime) for exaggerated perspective on converging lines; enable the grid display (Menu → Shooting → Grid Line) to align lines with the rule-of-thirds intersections.

**Common mistake:** Letting lines point away from the subject or out of the frame, which drains attention. Always trace the line's destination before you press the shutter.

### 📚 Learning — Tech
> `2026-11-26 13:18:18`

#### 📚 Today's Concept: Consistent Hashing

**What it is:** A hashing technique that maps both servers and keys onto a circular hash ring, so adding or removing a node only remaps a small fraction of keys (~1/N) instead of nearly all of them. Each key belongs to the first node clockwise from its hash position.

**When to use it:** Distributed caches, sharded databases, and load balancers where nodes join/leave dynamically and you can't afford mass key remapping (e.g., a Redis cluster scaling from 10 to 11 nodes without invalidating 90% of cached data).

**Example:**
```python
ring = sorted(hash(f"node{i}") for i in range(N))
def get_node(key):
    h = hash(key)
    idx = bisect.bisect(ring, h) % len(ring)
    return ring[idx]  # first node clockwise
```

**Gotcha:** Plain consistent hashing gives uneven distribution with few nodes — a handful of nodes can own huge arcs of the ring. The fix is **virtual nodes**: map each physical node to many points on the ring (e.g., 100–200 replicas) to smooth the load. Skipping vnodes is the most common production mistake.

### 🎬 Learning — YouTube
> `2026-11-26 13:18:24`

#### 🎬 今日主題：旅遊 — 旅遊影片的 3 幕結構：期待 / 現場 / 反思
**類別：** 旅遊

**是什麼：** 把旅遊影片拆成「期待（出發前鋪陳）／現場（旅途主體）／反思（回顧收尾）」三段，讓觀眾跟著你經歷一趟完整的情緒旅程。這是敘事骨架，不是流水帳。

**為什麼重要：** 新手最常把旅遊片剪成「景點合輯」，觀眾沒有情緒錨點就滑走；三幕結構能讓你的 A7C 素材有主線，也讓 AI 剪輯工具知道該把哪些片段放前面、哪些留給收尾。

**怎麼做：**
1. 出發前先拍 30 秒「期待」：收行李、查地圖、說出這趟想驗證什麼。
2. 現場只鎖定 3–5 個關鍵時刻，其餘當 B-roll，別全塞。
3. 用 AI 工具（如 Descript、CapCut 自動剪）先粗剪現場段，再手動補轉場。
4. 結尾錄一段「反思」：這趟改變了你什麼看法，30 秒內講完。
5. 三幕各配一種音樂情緒，讓結構聽得出來。

**新手常犯的錯：** 把「反思」拍成感謝名單或流水帳心得。避免方式：反思只回答一個問題——「這趟讓我原本以為的什麼被推翻了？」

**延伸 idea：** 拍「一趟只帶 A7C 和一支定焦鏡的週末小旅行」，用三幕結構呈現：出發前的期待、現場因器材限制做的取捨、回來後對「少即是多」的反思。
