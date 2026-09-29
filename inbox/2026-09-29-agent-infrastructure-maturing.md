---
date: 2026-09-29
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "savings_travel", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-09-29

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

---

## 🔥 今日重點 Top Highlights

- **AI 股殺聲隆隆，NVDA 逆勢獨強**：Watchlist 12 檔有 10 檔收黑，ARM ▼7.51%、META ▼4.79%、TSLA ▼3.94%、AMD ▼3.61%，但 **NVDA +1.68%** 是唯一亮點，顯示資金從高本益比 AI 動能股撤出、往核心半導體集中。([Watchlist 段落](#))
- **Google 把 REST API 一鍵變成 MCP 工具**：Cloud API Gateway 現在原生支援 remote MCP server，不用寫 middleware 就能讓 AI agent 接上你現有的 API — 對做 agent 整合的工程師是即戰力。([link](https://developers.googleblog.com/turn-your-rest-apis-into-mcp-tools-with-google-cloud-api-gateway/))
- **OpenAI 因安全疑慮喊停新模型發布**，並更新其模型存取澳洲政府系統的事件 — 值得追蹤後續對 AI 監管氛圍的影響。([BBC](https://www.bbc.co.uk/news/articles/cm5y5nynl75ko))
- **相機採購黃金窗口本週關閉**：9 月底是開學季促銷尾聲＋秋季新機發表前的舊款跳水期（A7 IV、R6 II），10 月會回價 — 想入手全幅這週是低點。([Camera Deals](#))
- **9 月機票攻略：泰國全年最便宜、日本便宜 2–3 成**：TPE-BKK 常態 NT$4,000–6,000 來回，日本 NT$5,000–8,000；歐洲/澳洲/埃及則建議 8–14 週前訂。([Flight Tips](#))

---

- 💻 **Tech**: Agent 基礎設施快速成熟（Cloudflare `cf` CLI、Nvidia watchdog chip），小模型與 KV cache 效率研究持續推進。
- 🤖 **AI 公司動態**: 僅 Tesla 有消息 — 保固成本攀升、Model Y L 賣到明年，但股價受大盤拖累。
- 🔵 **Google**: Gemini 3.8 Flash 開發案例、API Gateway 支援 MCP、Antigravity SDK 支援本地模型、Colab 納入 AI 方案。
- 📈 **Markets**: 美台日三地同步小跌，台股相對抗跌（-0.44%），日經最弱（-0.89%），屬溫和整理非恐慌。
- 🏠 **台灣房市**: 信用管制下量縮價盤整，自住選捷運 3 房＋車位，投資避開店面/套房過剩區與高總價物件。
- 📊 **Watchlist**: AI 類股全面回檔，僅 NVDA、SMCI 收紅；估值數據全缺，僅能作價格面觀察。
- 🌍 **World News**: OpenAI 停發新模型、NYT 高層遭槍殺、首爾召見烏克蘭大使、法國學運 164 人被捕、田納西死刑爭議。
- 📷 **Camera Deals**: 9 月底為學生機與舊款全幅最後撿便宜窗口，光華現金價可再殺 3–5%。
- 🤿 **Dive Gear Deals**: 潛季尾聲出清起點，二手調節器/BCD/電腦錶流通量大，議價空間優於夏季。
- ✈️ **Flight Tips**: 9 月是日本/泰國/美國機票低點，歐洲仍偏貴，埃及/澳洲建議提早 10–14 週訂。
- 🗺️ **Travel Deals**: 泰國免簽、日本免簽最省事；倫敦需 ETA、中國需台胞證，日本貴但簡單、中國便宜但麻煩。
- 📚 **Learning — Finance**: 讀財報先看現金流量表再看損益表 — 營收成長但營業現金流萎縮是警訊。
- 🧩 **LeetCode Blind 100**: #46 Permutations — 回溯法模板題，choose/explore/un-choose，務必 `.copy()`。
- 📷 **Learning — Photography**: 修皮膚要保留紋理，用頻率分離＋低透明度遮罩，A7C 拍攝時關閉機身柔膚。
- 📚 **Learning — Tech**: Circuit Breaker

---

## 💻 Tech

### 💻 Tech & AI
> `2026-09-29 10:38:43`

#### Hacker News
- [Jeff – Jev-compatible 0.8B decision models, trained at home, ~30 ms](https://github.com/firelex/jeff) ⭐301
- [12,000-year-old Göbeklitepe burials explain scattered bones](https://archaeologymag.com/2026/09/gobeklitepe-burials-hundreds-of-scattered-bones/) ⭐85
- [MicroLLM Lab – Try 7 tiny LLM's in the browser](https://stateofutopia.com/experiments/microllmlab/) ⭐140
- [It's Time to Investigate the AI Labs](https://calnewport.com/its-time-to-investigate-the-ai-labs/) ⭐315
- [Nvidia wants to put a watchdog chip next to every AI agent](https://www.cnbc.com/2026/09/28/nvidia-releases.html) ⭐109
- [What reversing, modernising old games tells us about the economic impact of AI](https://this.os.isfine.org/blog/posts/what-reverse-engineering-and-modernising-an-old-war-game-tells-us-about-the-econ/) ⭐73
- [Cf: The Agentic CLI for the Cloudflare API](https://blog.cloudflare.com/cloudflare-cf-cli-launch/) ⭐124
- [3D necroprinting: Leveraging biotic material as the nozzle for 3D printing](https://www.science.org/doi/10.1126/sciadv.adw9953) ⭐20
- [What would a serious AI product look like?](https://blog.glyph.im/2026/09/serious-ai-product.html) ⭐133
- [Parley: Federated, decentralised chat that speaks plain IRC](https://git.mills.io/prologic/parley) ⭐306

#### HuggingFace
- [ControlScope: Workflow Revision and Reliability in LLM Agents](https://huggingface.co/papers/2609.34313)
- [Program-Verified Self-Evolution for Vision-Language Models](https://huggingface.co/papers/2609.33855)
- [Diffusion Reward Models](https://huggingface.co/papers/2609.33803)
- [Fewer Tokens, More Self-Teaching: On-Policy Self-Distillation for Extreme Visual Token Reduction](https://huggingface.co/papers/2609.32353)
- [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757)
- [AdaTutoRank: Learning to Rerank Document Sets via Adaptive Tutoring Optimization for RAG and Deep Research](https://huggingface.co/papers/2609.32472)

#### ArXiv
- [Steering Language Model Goals with Value Transplant](http://arxiv.org/abs/2609.34056v1)
- [PReCache: Efficient KV Cache Sharing for Multi-LoRA Agents via Low-Rank Precomputation and Neutral Reconstruction](http://arxiv.org/abs/2609.34054v1)
- [The Statistical Cost of Causal Discovery with Feedback](http://arxiv.org/abs/2609.34050v1)
- [Thinking Outside the Box: Retention and Transmission of Information in Sliding-Window KV Inference](http://arxiv.org/abs/2609.34049v1)
- [ARCH-B: Architectural Representation, Comprehension and Hierarchy Benchmark](http://arxiv.org/abs/2609.34047v1)
- [Kafila: Serving Large Language Models on a Trusted Set of Heterogeneous Commodity Machines](http://arxiv.org/abs/2609.34045v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-09-29 10:38:49`

#### Tesla
- [Dow Jones Futures: Trump Sparks Stock Market Losses; Elon Musk-Led SpaceX, Tesla Sell Off](https://finance.yahoo.com/m/35969249-b51b-3ba3-8c6c-a06251d1d0ec/dow-jones-futures%3A-trump.html)
- [Tesla (TSLA) has a Growing Warranty Bill. Are Future Margins Paying for Past Sales?](https://finance.yahoo.com/markets/stocks/articles/tesla-tsla-growing-warranty-bill-020857410.html)
- [TSLA Heads Into Friday’s Delivery Print With Family-Targeted Model Y L Already Sold Into Next Year](https://finance.yahoo.com/markets/stocks/articles/tsla-heads-friday-delivery-print-233002093.html)
- [Why Tesla Stock Is Tied to SpaceX Ahead of a Big Week for the EV Maker](https://finance.yahoo.com/m/2844904c-b31d-326e-9678-a95b607c816c/why-tesla-stock-is-tied-to.html)

### 🔵 Google 動態
> `2026-09-29 10:38:46`

#### Google AI Blog
- [Watch the winning trailer from the Future Vision XPRIZE, The Gifted.](https://blog.google/innovation-and-ai/technology/ai/winner-future-vision-xprize/)
- [Google Beam expands with new regions, partners, and customers](https://blog.google/innovation-and-ai/technology/research/google-beam-expansion/)
- [New experts join Google’s AI & Economy team](https://blog.google/innovation-and-ai/technology/ai/expanding-ai-economy-research-bench/)
- [Co-creating the future of fashion with Google](https://blog.google/innovation-and-ai/technology/ai/google-flow-fashion-week/)
- [Making global data easier to explore](https://blog.google/innovation-and-ai/technology/ai/google-un-data-commons-platform/)
#### Google Blog
- [Watch the winning trailer from the Future Vision XPRIZE, The Gifted.](https://blog.google/innovation-and-ai/technology/ai/winner-future-vision-xprize/)
- [Google Arts & Culture turns 15 — and gives its app a makeover](https://blog.google/company-news/outreach-and-initiatives/arts-culture/new-arts-culture-app/)
- [See what 4 builders are making with Gemini 3.8 Flash](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-flash-developers/)
- [3 ways this grocer cooks for 200 guests with Gemini](https://blog.google/products-and-platforms/products/gemini/edys-grocer-gemini/)
- [Introducing Vertical Video Unification with Display & Video 360.](https://blog.google/products/marketingplatform/360/vertical-video-unification/)
#### Google Developers
- [Turn your REST APIs into MCP tools with Google Cloud API Gateway](https://developers.googleblog.com/turn-your-rest-apis-into-mcp-tools-with-google-cloud-api-gateway/)
- [Reproducing Olmo 3 7B Pre-training in MaxText: case study of large scale training on TPUs](https://developers.googleblog.com/reproducing-olmo-3-7b-pre-training-in-maxtext-case-study-of-large-scale-training-on-tpus/)
- [Introducing Support for Local AI Models in the Antigravity SDK](https://developers.googleblog.com/introducing-support-for-local-ai-models-in-the-antigravity-sdk/)
- [Colab is now part of your Google AI plan](https://developers.googleblog.com/colab-is-now-part-of-your-google-ai-plan/)
- [Why client SDK generation belongs in the open](https://developers.googleblog.com/why-client-sdk-generation-belongs-in-the-open/)

## 📈 Finance

### 📈 Markets Overview
> `2026-09-29 10:38:51`

#### Indices
- S&P 500: 7,683.69 ▼0.27%
- 台股加權: 47,812.24 ▼0.44%
- 日經 225: 65,289.99 ▼0.89%

### 🏠 台灣房市
> `2026-09-29 10:39:50`

#### AI 分析
## 台灣房市快評（2026-09-29）

**1. 整體趨勢**
央行選擇性信用管制持續發酵，投資買盤退場，市場以自住剛需為主軸，成交量能偏低、價格呈「高檔盤整、區域分化」。高總價物件去化慢，但精華地段與中小坪數產品仍有撐。

**2. 值得注意的地區／物件**
- **台中**：西屯中科、西區公益／五權商圈掛牌活躍，店面與套房產品供給多，留意租金投報是否被高房價稀釋。
- **新北**：板橋（板新站）、新店（玫瑰路）自住型3房＋車位仍是主流需求，捷運沿線抗跌。
- **高總價成交**：近期破億物件集中在住宅大樓與華廈，單價落差大（27～52萬/㎡），顯示「地段與屋況」決定價格，非全面性上漲。

**3. 對自住者建議**
優先選捷運／學區／生活機能成熟區，3房＋車位為安全牌；善用賣方讓利空間，議價幅度可比去年擴大5～10%。

**4. 對投資者建議**
店面、套房供給過剩區域（如台中部分商圈）慎入，投報率低於3%不建議進場；高總價物件流動性差，避免短進短出。

**5. 風險提醒**
信用管制未鬆綁前，房價難有大漲空間；留意2027年後供給量較大的重劃區，可能出現價格修正。

#### 591 最新
- [台中市西屯區福安路中科寶輝旁【林鼎跨界】溫馨漂亮3房+平車，一戶難求，成家首選](https://sale.591.com.tw/sale-detail-20979198.html)
- [台中市西區東興路三段🔴意志力🅿🅰🅽🔵公益南屯商圈賺錢店面✨適合各業🔥](https://rent.591.com.tw/rent-detail-22083811.html)
- [新北市板橋區三民路二段正隆巷大管家房屋/板新站/民生公園/格局方正](https://rent.591.com.tw/rent-detail-22083814.html)
- [桃園市平鎮區中豐路中豐路旁。黃金賺錢質感店面！](https://rent.591.com.tw/rent-detail-22083813.html)
- [新北市新店區玫瑰路51巷獨賣🍎何店長團隊👍玫瑰賓士4改3加車位](https://sale.591.com.tw/sale-detail-20979194.html)
- [台中市北區北屯路8巷🌟北屯國小｜電線重拉｜CP值3房🌟](https://sale.591.com.tw/sale-detail-20979193.html)
- [台北市中山區松江路45巷🔥松江南京站🔥住辦皆宜💖可補助.精華地段交通便捷](https://rent.591.com.tw/rent-detail-22077569.html)
- [台中市西區五權路22巷專任找芯房❤️西區金地段❤️台中教育大學旁｜好出租套房](https://sale.591.com.tw/sale-detail-20979169.html)

#### 實價登錄 (115S2) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 華廈(10層含以下有電梯) | 342.6㎡ | 17800萬 | 519496元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 675.5㎡ | 17000萬 | 279512元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 294.7㎡ | 10848萬 | 368078元/㎡ |
|  | 其他 | 0.0㎡ | 9369萬 | 36623元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 261.6㎡ | 8350萬 | 357414元/㎡ |

### 📊 Watchlist
> `2026-09-29 10:39:21`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 228.86 ▲1.68% |
| Market Cap | $5.54T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.7% / 65.2% / 63.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 24.18 |
| Beta | 2.22 |
| 52-Week | 164.27 – 236.54 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures: Trump Sparks Stock Market Losses; Elon Musk-Led SpaceX, Tesla Sell Off](https://finance.yahoo.com/m/35969249-b51b-3ba3-8c6c-a06251d1d0ec/dow-jones-futures%3A-trump.html) — Investor's Business Daily
- [Alibaba (NYSE:BABA) Nears Approval For RTX PRO 5500 Chip Purchases In China](https://finance.yahoo.com/technology/ai/articles/alibaba-nyse-baba-nears-approval-020934628.html) — Simply Wall St.
- [Baird's strong agentic AI call on Micron is spot on](https://finance.yahoo.com/technology/ai/articles/bairds-strong-agentic-ai-call-020300420.html) — TheStreet

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 607.87 ▼3.61% |
| Market Cap | $991.19B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.2% / 15.7% / 15.6% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 14.75 |
| Beta | 2.48 |
| 52-Week | 159.33 – 639.00 |
| Div. Yield | — |

**Recent News:**
- [Bank of America resets AMD price target after major milestone](https://finance.yahoo.com/markets/stocks/articles/bank-america-resets-amd-price-023300904.html) — TheStreet
- [AMD to buy Fei-Fei Li's World Labs in $8.2 billion bet on 'physical AI'](https://finance.yahoo.com/news/amd-acquires-world-labs-8-203900428.html) — Reuters
- [AMD just spent $8.2 billion to enlist the 'Godmother of AI'](https://finance.yahoo.com/technology/article/amd-just-spent-82-billion-to-enlist-the-godmother-of-ai-230634166.html) — Yahoo Finance

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 509.22 ▼1.35% |
| Market Cap | $3.78T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.9% / 46.8% / 40.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 8.55 |
| Beta | 1.11 |
| 52-Week | 349.20 – 553.72 |
| Div. Yield | — |

**Recent News:**
- [Meta Hasn't Split Its Stock Since Its IPO. Would a Stock Split Get It Into the Dow?](https://finance.yahoo.com/markets/stocks/articles/meta-hasnt-split-stock-since-020101300.html) — Motley Fool
- [Can Cloudflare (NET) Become the Gatekeeper of the AI Web?](https://finance.yahoo.com/technology/ai/articles/cloudflare-net-become-gatekeeper-ai-005555662.html) — Insider Monkey
- [Should Microsoft (MSFT) Investors Worry About A $3 Trillion Hidden AI Risk?](https://finance.yahoo.com/technology/ai/articles/microsoft-msft-investors-worry-3-000824730.html) — Simply Wall St.

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 342.75 ▼0.34% |
| Market Cap | $4.15T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.1% / 54.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.43 |
| Beta | 1.23 |
| 52-Week | 235.84 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [Can Cloudflare (NET) Become the Gatekeeper of the AI Web?](https://finance.yahoo.com/technology/ai/articles/cloudflare-net-become-gatekeeper-ai-005555662.html) — Insider Monkey
- [Robotaxi Firms Quietly Growing Real Estate Footprint, Even Where They're Not Yet Legal](https://finance.yahoo.com/real-estate/articles/robotaxi-firms-quietly-growing-real-233411871.html) — Bisnow
- [AMD just spent $8.2 billion to enlist the 'Godmother of AI'](https://finance.yahoo.com/technology/article/amd-just-spent-82-billion-to-enlist-the-godmother-of-ai-230634166.html) — Yahoo Finance

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 246.15 ▼1.41% |
| Market Cap | $2.65T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 50.8% / 12.1% / 17.4% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.80 |
| Beta | 1.44 |
| 52-Week | 196.00 – 287.20 |
| Div. Yield | — |

**Recent News:**
- [Meta Hasn't Split Its Stock Since Its IPO. Would a Stock Split Get It Into the Dow?](https://finance.yahoo.com/markets/stocks/articles/meta-hasnt-split-stock-since-020101300.html) — Motley Fool
- [Robotaxi Firms Quietly Growing Real Estate Footprint, Even Where They're Not Yet Legal](https://finance.yahoo.com/real-estate/articles/robotaxi-firms-quietly-growing-real-233411871.html) — Bisnow
- [The S&P 500 Has Only Grown Earnings This Fast Twice Before. History Says This Is What Happens Next](https://finance.yahoo.com/markets/stocks/articles/p-500-only-grown-earnings-210501186.html) — Motley Fool

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 715.62 ▼4.79% |
| Market Cap | $1.82T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.7% / 38.1% / 29.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.97 |
| Beta | 1.24 |
| 52-Week | 520.26 – 779.82 |
| Div. Yield | — |

**Recent News:**
- [MongoDB (MDB): CEO Exit Puts Strategy Under Scrutiny Ahead of Investor Day](https://finance.yahoo.com/markets/stocks/articles/mongodb-mdb-ceo-exit-puts-021532137.html) — Insider Monkey
- [Meta Hasn't Split Its Stock Since Its IPO. Would a Stock Split Get It Into the Dow?](https://finance.yahoo.com/markets/stocks/articles/meta-hasnt-split-stock-since-020101300.html) — Motley Fool
- [Meta’s AI ambitions put BlackRock’s prediction under spotlight](https://finance.yahoo.com/technology/ai/articles/meta-ai-ambitions-put-blackrock-014600501.html) — TheStreet

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 349.57 ▼0.23% |
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
- [Top 3 Cash Flow Stocks To Watch In September 2026](https://finance.yahoo.com/markets/stocks/articles/top-3-cash-flow-stocks-210837450.html) — Simply Wall St.
- [Did The Market Read Marvell Stock Right?](https://finance.yahoo.com/markets/stocks/articles/did-market-read-marvell-stock-204449705.html) — Trefis
- [The Best ETF to Own in Your 30s, 40s, 50s, and 60s, According to the Math](https://finance.yahoo.com/markets/options/articles/best-etf-own-30s-40s-204031796.html) — 24/7 Wall St.

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 283.33 ▼7.51% |
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
- [Arm vs. Marvell Technology: Which AI Chip Stock Is a Better Buy in 2026?](https://finance.yahoo.com/technology/ai/articles/arm-vs-marvell-technology-ai-213715326.html) — Motley Fool
- [Arm Stock Sinks 7.6% as Agent Security Expands Its Compute Role](https://finance.yahoo.com/markets/stocks/articles/arm-stock-sinks-7-6-184457268.html) — GuruFocus.com
- [Chip stocks fall as AI breach fuels safety concerns, but Nvidia bucks the trend: Chart of the Day](https://finance.yahoo.com/markets/article/chip-stocks-fall-as-ai-breach-fuels-safety-concerns-but-nvidia-bucks-the-trend-chart-of-the-day-151753993.html) — Yahoo Finance

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 187.48 ▼1.15% |
| Market Cap | $430.47B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.8% / 42.8% / 49.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 45.97 |
| Beta | 1.62 |
| 52-Week | 106.37 – 207.52 |
| Div. Yield | — |

**Recent News:**
- [FISV Heads For Worst Month Since October 2025 As Jana Reportedly Pushes Fiserv To Deepen Cost Cuts, Tap Palantir](https://finance.yahoo.com/markets/stocks/articles/fisv-heads-worst-month-since-021745147.html) — Stocktwits
- [Burry Sees AI Bubble Bursting Sooner, Shifts to Put Options](https://finance.yahoo.com/markets/options/articles/burry-sees-ai-bubble-bursting-231843443.html) — MT Newswires
- [REDLattice To Become Public Via $1.25B SPAC Transaction](https://finance.yahoo.com/markets/stocks/articles/redlattice-become-public-via-1-210010981.html) — IPO-Edge.com

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 41.78 ▲0.65% |
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
- [Super Micro Computer (SMCI) Falls More Steeply Than Broader Market: What Investors Need to Know](https://finance.yahoo.com/markets/stocks/articles/super-micro-computer-smci-falls-204506607.html) — Zacks
- [Intel Shares Tumble 5% as Fresh AI Risks Rattle Chip Stocks](https://finance.yahoo.com/technology/ai/articles/intel-shares-tumble-5-fresh-163531929.html) — GuruFocus.com
- [Super Micro and Dell Drop 5% as AI Server Rally Reverses; Hewlett Packard Enterprise Falls 3%](https://finance.yahoo.com/technology/ai/articles/super-micro-dell-drop-5-160101253.html) — 24/7 Wall St.

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 357.45 ▼3.94% |
| Market Cap | $1.41T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 18.9% / 4.2% / 3.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.32 |
| Beta | 1.84 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures: Trump Sparks Stock Market Losses; Elon Musk-Led SpaceX, Tesla Sell Off](https://finance.yahoo.com/m/35969249-b51b-3ba3-8c6c-a06251d1d0ec/dow-jones-futures%3A-trump.html) — Investor's Business Daily
- [Tesla (TSLA) has a Growing Warranty Bill. Are Future Margins Paying for Past Sales?](https://finance.yahoo.com/markets/stocks/articles/tesla-tsla-growing-warranty-bill-020857410.html) — Insider Monkey
- [TSLA Heads Into Friday’s Delivery Print With Family-Targeted Model Y L Already Sold Into Next Year](https://finance.yahoo.com/markets/stocks/articles/tsla-heads-friday-delivery-print-233002093.html) — Stocktwits

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 703.61 ▼0.48% |
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
- [Retiring on $800K? These 4 ETFs Let You Take 5% Safely](https://finance.yahoo.com/markets/options/articles/retiring-800k-4-etfs-let-220114842.html) — 24/7 Wall St.
- [Still Working at 73? The 401(k) at Your Current Job Skips the RMD Entirely. These 3 ETFs Belong in It](https://finance.yahoo.com/markets/options/articles/still-working-73-401-k-214809268.html) — 24/7 Wall St.
- [Where Will the S&P 500 Be in 30 Years? History Offers a Clear Answer for Investors.](https://finance.yahoo.com/markets/stocks/articles/where-p-500-30-years-192000270.html) — Motley Fool

## 🌍 News

### 🌍 World News
> `2026-09-29 10:39:53`

- [OpenAI scraps rollout of new model over safety concerns](https://www.bbc.co.uk/news/articles/cm5y5nynl75ko?at_medium=RSS&at_campaign=rss)
- [Inside Yemen's front-line city as Houthis battle for control](https://www.bbc.co.uk/news/articles/cw98005ndz7no?at_medium=RSS&at_campaign=rss)
- [New York Times executive fatally shot allegedly by elderly in-laws](https://www.bbc.co.uk/news/articles/cred737qdv2no?at_medium=RSS&at_campaign=rss)
- [Seoul summons Ukraine envoy over North Korean prisoner-of-war row](https://www.bbc.co.uk/news/articles/c8ly40xx0dr0o?at_medium=RSS&at_campaign=rss)
- [French PM warns against escalation of school protests after 164 arrested](https://www.bbc.co.uk/news/articles/cmqxvnn49rg2o?at_medium=RSS&at_campaign=rss)
- [Tennessee governor declines to halt execution of state's lone woman on death row](https://www.bbc.co.uk/news/articles/ckr50yyddljlo?at_medium=RSS&at_campaign=rss)
- [Twelve women have been killed in one part of South Africa since July. Here's what we know so far](https://www.bbc.co.uk/news/articles/c6m27dprvzv7o?at_medium=RSS&at_campaign=rss)
- [Nigerian attempts to break world record by dancing non-stop for seven days](https://www.bbc.co.uk/news/articles/cq8r6z2gjzd1o?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-09-29 10:40:07`

#### AI Tips
# 📸 台灣攝影採購 & 技巧日報 — 2026/09/29

---

## 🛒 購買優惠

#### 各通路優缺點（2026 現況）

| 通路 | 適合買什麼 | 注意事項 |
|------|-----------|---------|
| **PChome 24h** | 公司貨機身、鏡頭、配件 | 常有「24h 到貨」+ 信用卡回饋疊加，比價快 |
| **momo** | 組合包（機身+鏡頭+記憶卡） | 促銷價常最低，但贈品品質參差，看清楚是否為公司貨 |
| **光華商場** | 議價空間大、可現場試機 | 找老店（如正妹、驊陽），現金價通常再殺 3–5% |
| **日本代購** | 日系鏡頭、限定色機身 | 匯率好時便宜 10–20%，但**無台灣保固**，維修要寄回 |
| **二手（DCView、旋轉拍賣）** | 鏡頭、腳架、閃燈 | 鏡頭比機身保值，二手鏡頭 CP 值最高；面交必測對焦+霉斑 |

#### 🍂 九月季節性時機

- **開學季尾聲（9 月底）**：學生機（Canon R50、Sony ZV-E10）促銷進入尾聲，10 月會回價，**這週是最後撿便宜窗口**。
- **秋季新品鋪貨前**：Canon／Sony 通常 10 月發表新機，**舊款（如 A7 IV、R6 II）9 月底開始跳水**，是入手全幅好時機。
- **百貨週年慶預熱**：部分百貨 9 月底開跑，搭配滿千送百 + 信用卡，實體店可談到比網路更低。
- **💡 實戰建議**：鎖定目標型號 → 用「BigGo 比價」查歷史低價 → 週年慶首日或 PChome 品牌日下單。

---

## 📷 今日攝影技巧：**「減

#### r/photomarket
- [Universal Scammer List — Lookup](https://www.reddit.com/r/photomarket/comments/1vk7dhy/universal_scammer_list_lookup/)
- [PSA: AI timestamp photos and how not to get scammed](https://www.reddit.com/r/photomarket/comments/1nkg9v6/psa_ai_timestamp_photos_and_how_not_to_get_scammed/)
- [[S][USA-TX] Pentax Spotmeter V with case](https://www.reddit.com/r/photomarket/comments/1wsxtxq/susatx_pentax_spotmeter_v_with_case/)
- [[S][USA-CO] Sony a7c - Silver, Sony 35mm f1.4 GM, Sony 85mm f1.8](https://www.reddit.com/r/photomarket/comments/1wstwcq/susaco_sony_a7c_silver_sony_35mm_f14_gm_sony_85mm/)
- [[S] [USA-IL] Mamiya 7ii, Mamiya 7 80mm, Mamiya RZ67 180mm and 210mm lenses, Mamiya RZ67 Extension Tube #1, Rodenstock Apo-Sironar-S 135mm and 210mm Large Format Lenses, and Freezer Kept Pro 400H](https://www.reddit.com/r/photomarket/comments/1wsn0bm/s_usail_mamiya_7ii_mamiya_7_80mm_mamiya_rz67/)

### 🤿 Dive Gear Deals
> `2026-09-29 10:40:10`

#### AI Tips
# 台灣潛水裝備採購 & 裝備建議（2026年9月）

## 【購買優惠】

**實體店家（北台灣）**
- **潛水貨倉（Dive Warehouse）**：台北，代理多品牌，季末常有出清。
- **海人潛水**、**藍鯨潛水**：台北/新北，維修與裝備齊全。
- **IDiver 愛潛水**：台中，線上線下都有。
- **南部**：高雄「海王子」、墾丁大街周邊店家（旺季後議價空間大）。

**線上 / 社團**
- **蝦皮、PChome、momo**：比價快，但注意是否為公司貨、有無保固。
- **Facebook 社團**：「台灣潛水二手交流」、「潛水裝備買賣」——9月是**墾丁/東北角旺季尾聲**，很多人換裝備，二手調節器、BCD、電腦錶流通量大，議價空間比夏天好。
- **Diveinn、Amazon JP**：日系品牌（GULL、TUSA）從日本買常便宜2–3成，但注意關稅與保固。

**9月季節重點**
- 台灣潛季（東北角）約到10–11月，**9月是「季末出清」起點**，店家開始清夏季庫存，折扣最實在。
- 墾丁、小琉球旺季剛過，套裝（調節器+BCD+電腦錶）常有組合價。
- 若計畫冬天去東南亞（菲律賓、泰國），9月先買好，避開年底漲價。
- **注意**：9–10月是颱風季，網購到貨可能延遲，急用請選實體

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-09-29 10:40:01`

#### AI Flight Tips — September
# Taiwan Departure Flight Deals — September 2026 Playbook

**Japan (Tokyo/Osaka/Sapporo)**
- September = shoulder/off-peak (typhoon season, post-summer). Fares dip ~20-30% vs July-August.
- Book 6-8 weeks out; TPE-NRT/ KIX on Peach, Scoot, Tigerair Taiwan or VietJet (via SGN/HAN) often NT$5,000-8,000 round-trip.
- Watch EVA/China Airlines "early bird" promos and Peach's Tuesday flash sales; Sapporo (CTS) via Tokyo repositioning is cheapest.

**Thailand (Bangkok/Chiang Mai)**
- September = low season (rainy). Cheapest month of the year for TPE-BKK.
- Book 4-6 weeks out; Thai Lion Air, AirAsia, VietJet, and Scoot (via SIN) frequently hit NT$4,000-6,000 RT.
- Chiang Mai via BKK on Thai Smile/AirAsia add-on is cheapest; watch AirAsia's "Free Seats" and Thai Lion flash sales.

**Europe (any major city)**
- September = tail-end peak/early shoulder — still pricey but dropping after mid-month.
- Book 8-12 weeks out; China Airlines/EVA direct to LHR/AMS/CDG/Vienna, or cheaper via Istanbul (Turkish), Dubai (Emirates), or Seoul (Korean Air).
- Watch China Airlines "Europe Early Bird" and Turkish Airlines TPE-IST sales; one-stop via BKK (Thai) or SIN (Singapore Airlines) often undercuts directs.

**USA (West/East Coast)**
- September = off-peak (post-summer). Best value window of the year for TPE-LAX/SFO/JFK.
- Book 8-10 weeks out; EVA/China Airlines direct to LAX/SFO/ONT/JFK, or cheaper via Seoul (Korean), Tokyo (ANA/JAL), or Hong Kong (Cathay).
- Watch EVA Air's "Early Bird" and China Airlines' US promos; one-stop via ICN on Korean Air often NT$5,000-10,000 cheaper.

**Egypt (Cairo)**
- September = shoulder (still hot, fewer tourists). Fares moderate.
- Book 10-14 weeks out; no direct TPE-CAI — cheapest via Istanbul (Turkish), Dubai (Emirates), or Doha (Qatar Airways).
- Watch Turkish Airlines' TPE-IST-CAI combined fares and Qatar's "Stopover" promos; booking TPE-IST and IST-CAI separately can sometimes save.

**Australia (Sydney/Melbourne)**
- September = shoulder/off-peak (spring, pre-summer rush). Good value.
- Book 6-10 weeks out; China Airlines and EVA direct to SYD/BNE/MEL, or cheaper via Singapore (Scoot/SQ) or Kuala Lumpur (AirAsia X).
- Watch China Airlines' "Southern Hemisphere" promos and Scoot's TPE-SIN-SYD/MEL bundles; AirAsia X via KUL is often the budget winner.

**Universal tips:** Set Google Flights alerts now; Tuesday/Wednesday departures are cheapest; clear cookies or use incognito

### 🗺️ Travel Deals
> `2026-09-29 10:39:57`

#### r/solotravel
- [How did you handle worried parents before your first solo trip? (19M, Thailand very soon)](https://www.reddit.com/r/solotravel/comments/1wsc1bk/how_did_you_handle_worried_parents_before_your/)
- [I wanna go to London. Is it worth it?](https://www.reddit.com/r/solotravel/comments/1wsewpd/i_wanna_go_to_london_is_it_worth_it/)
- [Seeking advice for solo trip: Japan versus China](https://www.reddit.com/r/solotravel/comments/1wrocsu/seeking_advice_for_solo_trip_japan_versus_china/)

## 📚 Learning

### 📚 Learning — Finance
> `2026-09-29 10:40:12`

#### 📚 Today's Concept: How to read an earnings report

What it is: An earnings report is a company's quarterly financial disclosure, containing three core statements (income statement, balance sheet, cash flow) plus management commentary. It shows revenue, expenses, profit, and cash movement for the past three months versus the same quarter last year.

Why it matters: It's the single most reliable scheduled event for judging whether a business is actually executing, and it often moves the stock 5-20% in a day. You use it to confirm or break your investment thesis with real numbers, not narratives.

Example: A SaaS company reports revenue of $120M, up 25% year-over-year, beating estimates of $115M. But net income is -$8M, and free cash flow is -$15M, worse than last year's -$5M. Gross margin holds at 75%. The headline "beat" looks good, but cash burn is accelerating, so the stock drops 10% on the guidance cut.

Rule of thumb: Always read the cash flow statement before the income statement; profit can be massaged, but operating cash flow is harder to fake. Warning sign: revenue grows while operating cash flow shrinks.

### 🧩 LeetCode Blind 100
> `2026-09-29 10:40:16`

#### 🧩 Blind 100 — 46. Permutations [Backtracking]
**連結:** https://leetcode.com/problems/permutations/
> 📅 **Today's Daily Challenge:** #2349  Check if There Is a Valid Parentheses String Path [Hard] — Tags: Array, Dynamic Programming, Matrix, Bracket Sequences — https://leetcode.com/problems/check-if-there-is-a-valid-parentheses-string-path/

## 46. Permutations

**Problem Type:** Backtracking / DFS with used-state tracking

**Key Insight:** At each position, try every unused number, recurse, then undo the choice. The "used" set (or in-place swap) prevents reusing elements — this is the canonical backtracking template.

**Approach:**
1. Maintain `path` (current permutation) and `used` (boolean array).
2. If `len(path) == len(nums)`, append a copy of `path` to results.
3. Otherwise, loop over all indices; skip if `used[i]`.
4. Mark used, append, recurse, then pop and unmark (backtrack).
5. Alternative: in-place swap-based DFS (no `used` array) — slightly faster.

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

**Swap-based variant (faster, no extra array):**
```python
class Solution:
    def permute(self, nums: List[int]) -> List[List[int]]:
        res = []
        def dfs(i):
            if i == len(nums):
                res.append(nums.copy())
                return
            for j in range(i, len(nums)):
                nums[i], nums[j] = nums[j], nums[i]
                dfs(i + 1)
                nums[i], nums[j] = nums[j], nums[i]
        dfs(0)
        return res
```

**Complexity:** Time O(n · n!) | Space O(n) recursion depth (output not counted)

**Blind 100 Note:** This is the *template* problem for backtracking — the "choose / explore / un-choose" pattern. It generalizes to Subsets, Combination Sum, Palindrome Partitioning, N-Queens, and Word Search. Master this before touching those.

**Contest Tips:**
- **Always `.copy()` or `list(path)`** when appending — appending `path` directly stores a reference that gets mutated later (classic bug).
- Swap variant mutates `nums` — fine here, but be careful if the caller needs the original.
- For duplicates (LC 47), sort first and skip `nums[i] == nums[i-1] and not used[i-1]`.
- `itertools.permutations(nums)` is a one-liner but interviewers want the manual version — know both.
- Edge cases: `n == 1` → `[[x]]`; empty input → `[[]]`.

### 📷 Learning — Photography
> `2026-09-29 10:40:21`

#### 📷 Today's Concept: Post — Skin Retouching without Overdoing It

**What it is:** Skin retouching is the selective smoothing of texture and color irregularities while preserving pores, fine lines, and natural highlights. The goal is healthy skin, not plastic skin.

**Why it matters:** Over-retouched faces look waxy and uncanny, especially in video where motion exposes smeared detail. Restraint keeps subjects recognizable and trustworthy.

**How to apply it:**
1. Retouch on a duplicate layer and zoom to 100% — judge only at final viewing size.
2. Remove temporary blemishes (spots, stray hairs) with the Healing Brush; leave permanent features (moles, scars) unless asked.
3. Smooth texture with Frequency Separation or a low-opacity (10–20%) Gaussian Blur masked to skin only — never eyes, lips, hair, or edges.
4. Even out color with a soft Curves layer, not global blur.
5. Toggle the layer off and compare. If the "before" looks better, dial back 50%.

**Sony A7C tip:** Shoot with Creative Look "Portrait" and set Soft Skin Effect to Low or Off — in-camera smoothing bakes in and can't be undone in RAW. For video, use a 50mm f/1.8 or 85mm f/1.8; softer backgrounds reduce the urge to over-smooth faces.

**Common mistake:** Smoothing the whole face uniformly. Skin has texture variation — forehead, cheeks, and nose differ. Mask by zone and keep opacity low; texture is what makes skin read as skin.

### 📚 Learning — Tech
> `2026-09-29 10:40:18`

#### 📚 Today's Concept: Circuit Breaker Pattern

**What it is:** A resilience pattern that wraps calls to a remote service and trips "open" after repeated failures, failing fast instead of hammering a dying dependency. After a cooldown, it allows a trial request ("half-open") to test recovery before closing again.

**When to use it:** Use it when calling unreliable remote services (HTTP APIs, databases, third-party vendors) where cascading failures or thread exhaustion could take down your own app. E.g., your checkout service calling a flaky payment gateway.

**Example:**
```python
if breaker.is_open():
    return fallback_response()   # fail fast
try:
    resp = payment_api.charge(order)
    breaker.record_success()
except TimeoutError:
    breaker.record_failure()     # trips after N failures
    raise
```

**Gotcha:** A circuit breaker is not a retry mechanism—retries *increase* load on a struggling service. Also, don't set the failure threshold too low or you'll trip on normal transient blips; tune it to your dependency's real error rate.

### 🎬 Learning — YouTube
> `2026-09-29 10:40:24`

#### 🎬 今日主題：AI 剪輯 — CapCut AI 自動字幕與一鍵剪輯功能教學
**類別：** AI剪輯

**是什麼：** CapCut 的 AI 自動字幕能辨識語音生成字幕，一鍵剪輯則自動偵測精彩片段並套用轉場配樂。兩者都大幅降低剪輯門檻。

**為什麼重要：** 對不熟剪輯的你，能省下數小時手動上字幕與粗剪時間，把精力留給拍攝與企劃。

**怎麼做：**
1. 匯入 A7C 影片，點「文字」→「自動字幕」，選語言後生成。
2. 檢查錯字並校正，調整字體、位置避免擋住畫面。
3. 用「智慧剪輯」或「一鍵成片」讓 AI 抓精華段落。
4. 手動微調節奏，補上開頭 hook 與結尾。
5. 匯出 1080p 以上，確認字幕同步。

**新手常犯的錯：** 完全依賴 AI 不檢查，導致字幕錯字、剪接突兀。務必逐段校對並保留個人風格。

**延伸 idea：** 拍一支「A7C 一週生活 Vlog」，用 CapCut 自動字幕記錄每天一句心情，展示 AI 剪輯效率。
