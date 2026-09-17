---
date: 2026-09-17
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "savings_travel", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-09-17

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

- **US rates hiked for the first time in 3 years** — unanimous decision despite Trump's opposition; expect volatility in USD/TWD and tech valuations. ([BBC](https://www.bbc.co.uk/news/articles/cw4gmlyvj422o))
- **台股加權 +1.87% to 46,705** — strongest of the three indices, but S&P 500 -0.89% may pressure export tech names tomorrow. Semis (AMD +1.65%, ARM +2.08%) led AI names.
- **Google ADK for Kotlin 1.0** — full parity with Python/Java cores; worth a look if you're building multi-agent AI on Android/Kotlin. ([Link](https://developers.googleblog.com/announcing-adk-for-kotlin-10-building-production-ready-ai-agents-in-kotlin-android-and-beyond/))
- **Ternary LLM breaks 1.58-bit barrier** — ultra-low-precision models edging toward practical viability; relevant if you're tracking on-device inference. ([arXiv](https://arxiv.org/abs/2609.16338))
- **9月是潛水裝備季末出清黃金期** — FB 社團二手常打到 5–7 折；同時 9 月底是相機新機發表後舊機降價甜蜜點，想撿 A7C 後繼或鏡頭可等這波。

---

- 💻 **Tech**: Query planning with 4B LLMs beats Postgres by 81%; ternary LLM progress; Claude Cowork merged into Claude.
- 🤖 **AI 公司動態**: All Tesla today — Jensen Huang on Terafab, Ron Baron bullish, Michael Burry on AI bubble. No OpenAI/Anthropic news.
- 🔵 **Google**: ADK for Kotlin 1.0, Agent Anomaly Detection (private preview), zero-trust AI agents, Tunix autonomous post-training on TPUs.
- 📈 **Markets**: 台股 +1.87% leads; S&P 500 -0.89% only decliner; 日經 +0.49%.
- 🏠 **台灣房市**: 量縮價盤 K 型走勢；蛋白區讓利 5–10%，蛋黃區剛需撐盤；留意第八波管制與 2027 交屋潮。
- 📊 **Watchlist**: Semis up (AMD/ARM/NVDA), hyperscalers down (MSFT/AMZN/GOOGL), AVGO -1.51% weakest; all fundamentals N/A.
- 🌍 **World News**: US rate hike, Snapchat teen limits, Iran attack damage photos, EU-Canada associate membership, Gaza building collapse (21 dead).
- 📷 **Camera Deals**: 9月開學季+中秋檔期；PChome/momo 組合包、光華議價、日本代購價差 10–20% 但無台灣保固；9月底舊機降價甜蜜點。
- 🤿 **Dive Gear Deals**: 9–10月季末出清；實體店試穿 vs FB 社團二手 5–7 折；防寒衣尺寸齊、折扣多。
- ✈️ **Flight Tips**: Japan/Thailand 9月便宜（泰國 NT$5–7k 來回）；Europe 中旬後降價；Egypt 經 IST/DOH 最划算；Australia 早春 shoulder。
- 🗺️ **Travel Deals**: Japan 8天 solo、Thailand 島+北 combo、Italy 7天3城偏趕、Australia 2週含 Airlie Beach。
- 📚 **Learning — Finance**: Dividend yield vs payout ratio — >80% payout 是紅旗，>6–7% yield 常暗示砍股息。
- 🧩 **LeetCode Blind 100**: #252 Meeting Rooms — sort by start, scan for overlap; foundation for entire interval family.
- 📷 **Learning — Photography**: Complementary colors (blue/orange, red/cyan) — 一主一輔，別 50/50；A7C 用 Vivid 或 PP6 預覽。
- 📚 **Learning — Tech**: Caching strategies — cache-aside 記得寫入後主動 invalidate，不然會 serve stale data。
- 🎬 **Learning — YouTube**: 攝影 Vlog 三段結構（出發/拍攝/反思）；先寫三行大綱再剪，避免流水帳。

---

## 💻 Tech

### 💻 Tech & AI
> `2026-09-17 09:35:00`

#### Hacker News
- [Training a 4B model to produce 81% faster query plans than Postgres](https://rohanbansal.com/qorl) ⭐392
- [Breaking the 1.58-bit Barrier for Ternary LLMs](https://arxiv.org/abs/2609.16338) ⭐141
- [Xiaomi Mimo 2.6 live post-training dashboard](https://mimo.xiaomi.com/rl/) ⭐247
- [OpenSpec – A lightweight and configurable AI spec framework](https://openspec.dev/) ⭐60
- [HarnessTax: How Much Does the Harness Matter for Coding Agents?](https://harnesstax.github.io/) ⭐30
- [OpenAI Discloses Six New Incidents of ‘Concerning’ A.I. Behavior](https://www.nytimes.com/2026/09/16/technology/openai-model-safety-guardrails.html) ⭐18
- [The Return of Sail Power: Cargo Ships Are Turning Back to the Wind](https://gcaptain.com/the-return-of-sail-power-cargo-ships-are-turning-back-to-the-wind/) ⭐6
- [Training Text-to-Image Models 3.6× Faster](https://www.linum.ai/field-notes/jit-ddt) ⭐36
- [The Siberian Ice Maiden and the Scythian World](https://patrickwyman.substack.com/p/the-siberian-ice-maiden-and-the-scythian) ⭐46
- [Claude Cowork and chat are now one Claude](https://claude.com/blog/cowork-is-now-claude) ⭐203

#### HuggingFace
- [LimiX-2: A Contextual Mechanism Network Towards General Structured-Data Intelligence](https://huggingface.co/papers/2609.17488)
- [Register Tokens for Bounded-State Reasoning in Diffusion Language Models](https://huggingface.co/papers/2609.16372)
- [FLAT: Resampling Image and Text into 1D Flexible-Length Aligned Transmodal Tokens for Retrieval and Generation](https://huggingface.co/papers/2609.16591)
- [RelateAnything: Real-Time Open-Vocabulary Relation Prediction From Any Inputs](https://huggingface.co/papers/2609.12552)
- [Generalized Agent Iteration: One Formal Framework for Iterative Policy Improvement and Recursive Self-Improvement](https://huggingface.co/papers/2609.13406)
- [OmniHarness: Harnessing Generalizable Visual Generation via Symbolic Policy Learning](https://huggingface.co/papers/2609.16057)

#### ArXiv


### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-09-17 09:35:06`

#### Tesla
- [Billionaire Ron Baron is Extremely Bullish on Tesla Stock. What’s His Reason?](https://finance.yahoo.com/markets/stocks/articles/billionaire-ron-baron-extremely-bullish-002248689.html)
- [Nvidia CEO Jensen Huang Says Elon Musk’s Terafab May Look Audacious, But ‘If Anybody Could Do It, He Can’](https://finance.yahoo.com/technology/ai/articles/nvidia-ceo-jensen-huang-says-233027419.html)
- [Michael Burry reveals his verdict on the ongoing AI bubble](https://finance.yahoo.com/technology/ai/articles/michael-burry-reveals-verdict-ongoing-221700327.html)
- [Who are the richest Americans today? Forbes drops 2026 ranking](https://finance.yahoo.com/markets/stocks/articles/richest-americans-today-forbes-drops-221105964.html)

### 🔵 Google 動態
> `2026-09-17 09:35:03`

#### Google AI Blog
- [AI for Societal Impact](https://blog.google/innovation-and-ai/technology/ai/ai-for-societal-impact/)
- [Building AI to accelerate science and improve lives](https://blog.google/innovation-and-ai/technology/ai/ai-applications-science-people/)
- [AI for everyone in every language](https://blog.google/innovation-and-ai/technology/ai/ai-for-every-language/)
- [New insights from Google’s AI & Economy ATLAS](https://blog.google/innovation-and-ai/technology/ai/ai-economy-atlas-september-2026/)
- [Watch astronaut Christina Koch and Google’s James Manyika discuss space, technology, and discovery.](https://blog.google/innovation-and-ai/technology/ai/dialogues-christina-koch/)
#### Google Blog
- [3 new ways we're improving Search profiles for publishers](https://blog.google/products-and-platforms/products/search/3-new-ways-were-improving-search-profiles-for-publishers/)
- [Rethink your strategy to drive sales this holiday season.](https://blog.google/products/ads-commerce/ads-decoded-podcast-holiday-sales-strategies/)
- [5 things to know about teens' views on AI today](https://blog.google/innovation-and-ai/technology/families/teens-ai-research-findings/)
- [Boost your holiday sales with these agentic commerce updates](https://blog.google/products-and-platforms/products/shopping/google-shopping-updates-holiday-shopping/)
- [Rethink 2026](https://blog.google/products/ads-commerce/rethink-2026/)
#### Google Developers
- [Agent Anomaly Detection, now in Private Preview on the Gemini Enterprise Agent Platform](https://developers.googleblog.com/agent-anomaly-detection-now-in-private-preview-on-the-gemini-enterprise-agent-platform/)
- [Build zero-trust AI agents that judge intent, not just syntax](https://developers.googleblog.com/build-zero-trust-ai-agents-that-judge-intent-not-just-syntax/)
- [Autonomous LLM post-training with Tunix on TPUs](https://developers.googleblog.com/autonomous-llm-post-training-with-tunix-on-tpus/)
- [The Anatomy of Harness Engineering: How to Evaluate, Iterate, and Guard AI Coding Agents](https://developers.googleblog.com/the-anatomy-of-harness-engineering-how-to-evaluate-iterate-and-guard-ai-coding-agents/)
- [Announcing ADK for Kotlin 1.0: Building Production-Ready AI Agents in Kotlin, Android, and Beyond](https://developers.googleblog.com/announcing-adk-for-kotlin-10-building-production-ready-ai-agents-in-kotlin-android-and-beyond/)

## 📈 Finance

### 📈 Markets Overview
> `2026-09-17 09:35:08`

#### Indices
- S&P 500: 7,551.81 ▼0.89%
- 台股加權: 46,705.46 ▲1.87%
- 日經 225: 64,237.13 ▲0.49%

### 🏠 台灣房市
> `2026-09-17 09:36:08`

#### AI 分析
**1. 整體趨勢（2026年9月）**
央行第七波信用管制與高利率環境持續壓抑買氣，投資客退場、成交量緊縮，房市進入「量縮價盤」格局。惟蛋黃區剛需與都更危老案仍撐盤，整體呈現「自住撐場、投資觀望」的K型走勢，價格鬆動以蛋白區、老舊大坪數產品最明顯。

**2. 值得注意的地區與物件**
- **蛋黃區店面／商圈出租**：永康街、頂溪站、條通商圈等店面釋出增加，反映零售租金投報率受電商與觀光波動影響，議價空間變大，適合長線收租族進場談判。
- **桃園、台中蛋白區新成屋**：平鎮、大雅等三房含車位產品掛售量增，「屋主決心出售」字眼頻現，讓利幅度約5–10%，是自住首購可鎖定的區塊。
- **高總價豪宅（實價登錄破億）**：單價落差大（27–52萬/㎡），顯示豪宅市場分化，精華地段仍抗跌，非核心區高總價產品去化困難。

**3. 對自住者的建議**
優先鎖定捷運／商圈周邊中古三房，善用賣方讓利與高利率下的議價優勢，避開大坪數老屋與供給量大的重劃區，並預留裝修與持有成本。

**4. 對投資者的建議**
短線炒作已無空間，應轉向「租金投報率＞3%」的商圈店面或學區套房；蛋白區預售與大坪數產品建議觀望，等價格明顯修正再進場。

**5. 風險提醒**
留意央行是否再推第八波管制、以及2027年大量新成屋交屋潮帶來的賣壓，蛋白區價格修正風險仍高。

#### 591 最新
- [桃園市平鎮區延平路二段239巷城上水美｜景觀大兩房｜室內約19坪](https://sale.591.com.tw/sale-detail-20919121.html)
- [台北市大安區永康街2巷🌟🌟永康街商圈｜優質店面出租｜觀光遊客人潮聚集](https://rent.591.com.tw/rent-detail-21057433.html)
- [台北市中山區朱崙街達官苑名宅｜捷運大三房｜保全管理](https://rent.591.com.tw/rent-detail-21990868.html)
- [台中市大雅區雅潭路四段661巷專售｜鼎佳二和｜三房+平車｜視野宅｜屋主決心出售](https://sale.591.com.tw/sale-detail-20919120.html)
- [新北市永和區永和路二段🌟🌟【頂溪站】熱鬧商圈｜人潮匯聚｜優質店面出租](https://rent.591.com.tw/rent-detail-21763530.html)
- [台北市中山區林森北路溫水泳池社區｜中山精華區](https://rent.591.com.tw/rent-detail-21969816.html)
- [桃園市中壢區富強西街桃園/中壢/內壢/工業區專屬洗衣機套房](https://rent.591.com.tw/rent-detail-22027402.html)
- [台北市中山區林森北路107巷🌟🌟條通商圈｜優質店面出租｜知名品牌聚集](https://rent.591.com.tw/rent-detail-21415718.html)

#### 實價登錄 (115S2) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 華廈(10層含以下有電梯) | 342.6㎡ | 17800萬 | 519496元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 675.5㎡ | 17000萬 | 279512元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 294.7㎡ | 10848萬 | 368078元/㎡ |
|  | 其他 | 0.0㎡ | 9369萬 | 36623元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 261.6㎡ | 8350萬 | 357414元/㎡ |

### 📊 Watchlist
> `2026-09-17 09:35:37`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 213.90 ▲0.82% |
| Market Cap | $5.18T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.7% / 65.2% / 63.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 22.60 |
| Beta | 2.22 |
| 52-Week | 164.27 – 236.54 |
| Div. Yield | — |

**Recent News:**
- [Vistra vs. Constellation vs. Talen Energy: Which Nuclear-Heavy Stock Is the Better AI-Power Bet?](https://finance.yahoo.com/energy/articles/vistra-vs-constellation-vs-talen-012500911.html) — Motley Fool
- [This Ethereum Treasury Company Is Close to Owning 5% of All ETH in Circulation. Does That Make It a Buy?](https://finance.yahoo.com/markets/crypto/articles/ethereum-treasury-company-close-owning-010100563.html) — Motley Fool
- [More Than a Quarter of Nvidia's Revenue Now Comes From Customers Based in Taiwan. Should Investors Be Worried?](https://finance.yahoo.com/markets/stocks/articles/more-quarter-nvidias-revenue-now-005401979.html) — Motley Fool

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 512.50 ▲1.65% |
| Market Cap | $835.68B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.2% / 15.7% / 15.6% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 12.43 |
| Beta | 2.48 |
| 52-Week | 149.85 – 584.73 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures Rise After Hawkish Fed, Warsh Hit Stocks, Trump Fumes; AMD, Bloom Energy Eye Buy Points](https://finance.yahoo.com/m/d657761c-bf99-3091-88b4-e770125e96a8/dow-jones-futures-rise-after.html) — Investor's Business Daily
- [AMD, IBD Stock Of The Day, Gains As Heavyweights Dismiss AI Slowdown](https://finance.yahoo.com/m/65f68f37-8011-33ac-af60-a2d54da41be8/amd%2C-ibd-stock-of-the-day%2C.html) — Investor's Business Daily
- [Stock Market Today, Sept. 16: Intel Jumps on SK Hynix Memory-Chip Manufacturing Talks](https://finance.yahoo.com/markets/stocks/articles/stock-market-today-sept-16-212959692.html) — Motley Fool

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 490.30 ▼1.37% |
| Market Cap | $3.64T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.9% / 46.8% / 40.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 8.23 |
| Beta | 1.11 |
| 52-Week | 349.20 – 553.72 |
| Div. Yield | — |

**Recent News:**
- [archTIS secures US regional bank contract as Spirion gains commercial traction](https://finance.yahoo.com/technology/articles/archtis-secures-us-regional-bank-011100309.html) — Proactive
- [The Next Short? Economist Compares Hyperscaler AI Debt Stress to 2008 Housing Collapse](https://finance.yahoo.com/markets/stocks/articles/next-short-economist-compares-hyperscaler-223915125.html) — BeInCrypto
- [Anthropic IPO Underwriter Says AI Spending Won't Slow: Can He Be Neutral?](https://finance.yahoo.com/technology/ai/articles/anthropic-ipo-underwriter-says-ai-214112519.html) — BeInCrypto

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 342.87 ▼0.61% |
| Market Cap | $4.15T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.1% / 54.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.44 |
| Beta | 1.23 |
| 52-Week | 235.84 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [Inside the White House Tussle to Sway Trump on AI](https://finance.yahoo.com/m/3787fa3d-2edb-31d9-b7cb-4e4c36d9b8ec/inside-the-white-house-tussle.html) — The Wall Street Journal
- [S&P 500, Nasdaq, Dow Futures Inch Higher As Investors Digest First Rate Hike Since 2023 — INTC, GOOGL, AAPL, SKHY, UAL In Focus](https://finance.yahoo.com/markets/stocks/articles/p-500-nasdaq-dow-futures-232942409.html) — Stocktwits
- [The Next Short? Economist Compares Hyperscaler AI Debt Stress to 2008 Housing Collapse](https://finance.yahoo.com/markets/stocks/articles/next-short-economist-compares-hyperscaler-223915125.html) — BeInCrypto

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 245.96 ▼0.99% |
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
- [What Has Home Depot Stopped Telling You About Where Its Goods Come From?](https://finance.yahoo.com/markets/stocks/articles/home-depot-stopped-telling-where-235251448.html) — Trefis
- [The Next Short? Economist Compares Hyperscaler AI Debt Stress to 2008 Housing Collapse](https://finance.yahoo.com/markets/stocks/articles/next-short-economist-compares-hyperscaler-223915125.html) — BeInCrypto
- [Generac Stock Soars on Amazon Generator Deal](https://finance.yahoo.com/m/45a1d354-dff9-3a7e-b85f-c8a8da79044a/generac-stock-soars-on-amazon.html) — Barrons.com

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 673.31 ▲0.46% |
| Market Cap | $1.72T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.7% / 38.1% / 29.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.55 |
| Beta | 1.24 |
| 52-Week | 520.26 – 790.80 |
| Div. Yield | — |

**Recent News:**
- [What Does AppLovin Stock Do On Your Worst Days?](https://finance.yahoo.com/markets/stocks/articles/does-applovin-stock-worst-days-011349099.html) — Trefis
- [Inside the White House Tussle to Sway Trump on AI](https://finance.yahoo.com/m/3787fa3d-2edb-31d9-b7cb-4e4c36d9b8ec/inside-the-white-house-tussle.html) — The Wall Street Journal
- [Snap targets enterprises with Salesforce, Nvidia AI tools for augmented-reality glasses](https://finance.yahoo.com/technology/ai/articles/snap-targets-enterprises-salesforce-nvidia-234512914.html) — Reuters

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 339.51 ▼1.51% |
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
- [Is Ciena's Pricing Power Real, Or Just A Parts Shortage?](https://finance.yahoo.com/markets/stocks/articles/cienas-pricing-power-real-just-233841142.html) — Trefis
- [Jim Cramer Says the AI Slowdown Is Fake. Dell Is His Evidence.](https://finance.yahoo.com/technology/ai/articles/jim-cramer-says-ai-slowdown-194523294.html) — 24/7 Wall St.
- [Should You Buy Qualcomm Stock For The Cash As Apple Leaves?](https://finance.yahoo.com/markets/stocks/articles/buy-qualcomm-stock-cash-apple-193004157.html) — Trefis

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 243.98 ▲2.08% |
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
- [ARM Stock Declines 39% in 3 Months: Is This a Buying Opportunity?](https://finance.yahoo.com/markets/stocks/articles/arm-stock-declines-39-3-172800739.html) — Zacks
- [Arm Surges as the AI Selloff Tests Its Royalty Machine](https://finance.yahoo.com/technology/ai/articles/arm-surges-ai-selloff-tests-192916737.html) — GuruFocus.com
- [Arm Stock Is Down More Than 40%. Here's Why I'm Staying on the Sidelines.](https://finance.yahoo.com/markets/stocks/articles/arm-stock-down-more-40-052702402.html) — Motley Fool

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 174.34 ▲1.03% |
| Market Cap | $400.30B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.8% / 42.8% / 49.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 42.75 |
| Beta | 1.62 |
| 52-Week | 106.37 – 207.52 |
| Div. Yield | — |

**Recent News:**
- [Nebius Group (NBIS) Is Down 12.9% After Becoming Palantir’s Preferred Sovereign AI Cloud Partner – Has The Bull Case Changed?](https://finance.yahoo.com/technology/ai/articles/nebius-group-nbis-down-12-011225334.html) — Simply Wall St.
- [Inside the White House Tussle to Sway Trump on AI](https://finance.yahoo.com/m/3787fa3d-2edb-31d9-b7cb-4e4c36d9b8ec/inside-the-white-house-tussle.html) — The Wall Street Journal
- [Palantir Technologies (PLTR) Tightens Rules On External Generative AI Models](https://finance.yahoo.com/technology/ai/articles/palantir-technologies-pltr-tightens-rules-221216839.html) — Simply Wall St.

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 36.85 ▲0.30% |
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
- [Super Micro stock slips as investors look past massive growth estimates](https://finance.yahoo.com/markets/stocks/articles/super-micro-stock-slips-investors-205648878.html) — GuruFocus.com
- [SMCI Has Something Nvidia Doesn’t. Here’s Why That Matters](https://finance.yahoo.com/markets/stocks/articles/smci-something-nvidia-doesn-t-163037456.html) — 24/7 Wall St.
- [Dell Rises 5% Despite Fresh Silver Lake Share Sale Filings; Super Micro Climbs 3%, Hewlett Packard Enterprise Ticks Up](https://finance.yahoo.com/markets/stocks/articles/dell-rises-5-despite-fresh-143139136.html) — 24/7 Wall St.

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 358.08 ▲0.42% |
| Market Cap | $1.41T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 18.9% / 4.2% / 3.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.34 |
| Beta | 1.84 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Billionaire Ron Baron is Extremely Bullish on Tesla Stock. What’s His Reason?](https://finance.yahoo.com/markets/stocks/articles/billionaire-ron-baron-extremely-bullish-002248689.html) — BeInCrypto
- [Nvidia CEO Jensen Huang Says Elon Musk’s Terafab May Look Audacious, But ‘If Anybody Could Do It, He Can’](https://finance.yahoo.com/technology/ai/articles/nvidia-ceo-jensen-huang-says-233027419.html) — Benzinga
- [Michael Burry reveals his verdict on the ongoing AI bubble](https://finance.yahoo.com/technology/ai/articles/michael-burry-reveals-verdict-ongoing-221700327.html) — TheStreet

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 693.24 ▼0.87% |
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
- [Want to Leave Each Grandkid $100,000 Without Hiring a Lawyer? These 3 ETFs and a Custodial Account Do It](https://finance.yahoo.com/markets/options/articles/want-leave-grandkid-100-000-211536679.html) — 24/7 Wall St.
- [Three Stocks Are Joining the S&P 500. Will They Actually Improve VOO’s Returns?](https://finance.yahoo.com/markets/stocks/articles/three-stocks-joining-p-500-155532777.html) — 24/7 Wall St.
- [You Bought VOO and VTI for Diversification. About 85% of Your Money Sits in the Same Stocks](https://finance.yahoo.com/markets/stocks/articles/bought-voo-vti-diversification-85-210512265.html) — 24/7 Wall St.

## 🌍 News

### 🌍 World News
> `2026-09-17 09:36:11`

- [US interest rates raised for first time in three years](https://www.bbc.co.uk/news/articles/cw4gmlyvj422o?at_medium=RSS&at_campaign=rss)
- [Snapchat 'willing to implement' daily time limits for teens, boss tells BBC](https://www.bbc.co.uk/news/articles/cr3wjz3edd10o?at_medium=RSS&at_campaign=rss)
- [Photos show widespread damage at US sites from Iranian attacks](https://www.bbc.co.uk/news/articles/c8g49e0gwxeno?at_medium=RSS&at_campaign=rss)
- [EU chief backs plan for Canada to become 'associate member'](https://www.bbc.co.uk/news/articles/cjwyzrr9d3dko?at_medium=RSS&at_campaign=rss)
- [US House votes to hold billionaire Epstein associate Leon Black in contempt](https://www.bbc.co.uk/news/articles/c62l8g8qlr0ko?at_medium=RSS&at_campaign=rss)
- [Eight children among 21 killed after war-damaged Gaza building collapses, rescuers say](https://www.bbc.co.uk/news/articles/cvp8d00j9gg5o?at_medium=RSS&at_campaign=rss)
- [Michelin-starred Seoul restaurant fined for using ants as garnish](https://www.bbc.co.uk/news/articles/c639m42y43v4o?at_medium=RSS&at_campaign=rss)
- [Eight German state premiers back Merz amid speculation over future](https://www.bbc.co.uk/news/articles/c6dj4nn0n97ro?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-09-17 09:36:26`

#### AI Tips
# 📸 台灣攝影採購 & 技巧日報 — 2026/09/17

## 【購買優惠】九月買相機鏡頭攻略

**各通路優缺點速比**

| 通路 | 適合買什麼 | 注意事項 |
|------|-----------|---------|
| **PChome 24h** | 公司貨機身、配件、急用 | 常有「刷卡金回饋」+ 快速到貨；比價後再下單 |
| **momo** | 組合包（機身+鏡頭+記憶卡） | 促銷價常最低，但贈品要看實用性；注意是否為公司貨 |
| **光華商場** | 議價、水貨、二手鏡頭 | 現金價可殺；務必當場測焦、檢查快門數、要保固卡 |
| **日本代購** | 日系鏡頭、機身（價差大） | 匯率好時便宜 10–20%，但**無台灣保固**、維修要寄回 |
| **二手（DCView、旋轉拍賣、FB社團）** | 鏡頭、老機身 | 面交測焦、查快門數、看霉絲/入塵 |

**九月季節性時機**
- **開學季（9月）**：相機、筆電、記憶卡常有「學生優惠」，可問店家是否有教育價。
- **中秋節前後**：momo / PChome 常推「中秋家電攝影節」，是撿機身+鏡頭組合包的好時機。
- **策略**：9月底通常是**新機發表後舊機降價**的甜蜜點（尤其日系品牌秋季發表），想買上一代機身可等這波。
- **提醒**：9月買，10月週年慶（百貨）可能更殺，若不急可再等 2–3 週比價。

---

## 【今日攝影技巧】善用「黃金光線」拍出立體感

**技巧：側逆光 + 曝光補償 -0.7EV**

九月台灣日落約 17:50–18:10，日落前 30 分鐘是「黃金時刻」。此時把**光源

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-09-17 09:36:30`

#### AI Tips
# 台灣潛水裝備採購 & 9月裝備指南（2026-09-17）

## 一、購買優惠：台灣哪裡買最划算

**實體店（可試穿、售後有保障）**
- **台北**：潛水貨倉（Dive Warehouse）、海人潛水、藍鯨潛水 — 適合買調節器、BCD 等高單價裝備，可現場試背。
- **台中/高雄**：海洋潛水、墾丁在地店家（如台灣潛水）— 墾丁店家常有「潛季末出清」。
- **連鎖/代理**：Scubapro、Mares、Cressi 台灣代理經銷商，保固與零件最完整。

**線上 / 社團（撿便宜首選）**
- **Facebook 社團**：「台灣潛水二手買賣」「潛水裝備交流」— 9月是潛季尾聲，很多人趁機出清二手裝備，價格常打到 5–7 折。
- **蝦皮 / 露天**：適合買配件（面鏡、蛙鞋、手套、防水袋），但高單價裝備注意是否為水貨、有無保固。
- **國外代購/直送**：日系（GULL、TUSA）、歐美品牌，9月常遇品牌換季折扣，但要注意關稅與保固在台灣是否受理。

**9月採購時機提示**
- 台灣潛季約 4–10 月，**9–10 月是「季末出清」黃金期**，店家與二手社團降價最有感。
- 想買**防寒衣**：季末尺寸較齊、折扣多；但若你要的是「明年夏天用」，現在買最划算。
- 想買**輕裝

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-09-17 09:36:21`

#### AI Flight Tips — September
**Japan (Tokyo / Osaka / Sapporo)**
- September is post-summer-peak but typhoon season — fares drop ~20-30% vs August; Sapporo starts its autumn leaf rush late Sept.
- Book 6-10 weeks out; LCCs (Peach, Scoot, Tigerair Taiwan) release promo fares Tue-Thu for TPE-NRT/KIX/CTS.
- Watch Peach's "Happy Peach" flash sales and EVA/China Airlines early-bird for Osaka; CTS is priciest, route via KIX + domestic if flexible.

**Thailand (Bangkok / Chiang Mai)**
- September is low season (rainy) — cheapest month for TPE-BKK, often NT$5,000-7,000 round trip.
- Book 4-8 weeks ahead; Thai Lion Air, AirAsia, and VietJet (via Vietnam) are cheapest; EVA/China Airlines for comfort.
- Chiang Mai is quieter/cheaper than Bangkok; watch AirAsia and Thai Vietjet promos, plus Taiwan's autumn travel fairs (ITF in Nov).

**Europe (any major city)**
- September is shoulder season — still pricey early month, drops sharply after mid-Sept as summer demand fades.
- Book 3-5 months ahead for best fares; avoid booking under 6 weeks.
- Cheapest routings: China Airlines/EVA direct to AMS/FRA/LHR, or one-stop via Istanbul (Turkish), Dubai (Emirates), or Seoul/Shanghai for lower fares.
- Watch China Airlines and EVA early-bird promos; Turkish Airlines often undercuts on TPE-Europe via IST.

**USA (West Coast / East Coast)**
- September is off-peak post-Labor Day — good value, especially after mid-month; Thanksgiving (late Nov) fares start climbing.
- Book 8-12 weeks ahead; West Coast (LAX/SFO/SEA) cheaper than East Coast (JFK/EWR/BOS).
- Cheapest: EVA/China Airlines nonstop to LAX/SFO/SEA/ONT; for East Coast, one-stop via Seoul (Korean Air) or Tokyo (ANA/JAL) often beats nonstop.
- Watch EVA Air and China Airlines promos; Starlux flash sales on TPE-LAX/SFO are worth tracking.

**Egypt (Cairo)**
- September is still hot but shoulder — fares moderate; peak is Oct-Apr (Nile cruise season).
- Book 8-12 weeks ahead; no nonstop from Taiwan — connect via Istanbul (Turkish), Dubai (Emirates), Doha (Qatar), or Cairo via Europe.
- Turkish Airlines via IST and Qatar Airways via DOH are usually cheapest/most convenient; EgyptAir via Bangkok or Guangzhou can be cheaper but longer.
- Watch Turkish/Qatar seasonal promos and Egypt tourism board campaigns (often bundled with Nile cruises).

**Australia (Sydney / Melbourne)**
- September is early spring — shoulder season, decent fares before Dec-Jan summer peak.
- Book 6-10 weeks ahead; direct TPE-SYD/BNE on China Airlines/EVA, or via Singapore/Hong Kong for cheaper.
- Cheapest: Scoot via Singapore, or China Airlines/EVA promo fares; Melbourne often cheaper than Sydney.
- Watch China Airlines and EVA seasonal sales, plus Sco

### 🗺️ Travel Deals
> `2026-09-17 09:36:15`

#### r/solotravel
- [Has anyone ever travelled by simply taking the cheapest flight every 2 days?](https://www.reddit.com/r/solotravel/comments/1whvlrk/has_anyone_ever_travelled_by_simply_taking_the/)
- [Rate my Australia Itinerary (2 weeks, possibly cursed) / is Airlie worth it?](https://www.reddit.com/r/solotravel/comments/1wiad7b/rate_my_australia_itinerary_2_weeks_possibly/)
- [Thailand - Koh samui, Koh Phangan and Chiang mai.](https://www.reddit.com/r/solotravel/comments/1wi6p40/thailand_koh_samui_koh_phangan_and_chiang_mai/)
- [Is Rome, Florence & Venice too much for a 7-day solo trip?](https://www.reddit.com/r/solotravel/comments/1whngx3/is_rome_florence_venice_too_much_for_a_7day_solo/)
- [8 days in japan as a solo traveller](https://www.reddit.com/r/solotravel/comments/1wi9c8i/8_days_in_japan_as_a_solo_traveller/)

## 📚 Learning

### 📚 Learning — Finance
> `2026-09-17 09:36:33`

#### 📚 Today's Concept: Dividend Yield and Payout Ratio

What it is: Dividend yield is the annual dividend per share divided by the stock price, showing your cash return on investment. Payout ratio is the percentage of earnings a company pays out as dividends, revealing how much profit is retained for growth.

Why it matters: Yield tells you income potential, but payout ratio tells you if that dividend is sustainable. A high yield with an unsustainable payout ratio is a trap, not a bargain.

Example: Company X trades at $50, pays $2 annually. Yield = 2/50 = 4%. It earns $4 per share (EPS), so payout ratio = 2/4 = 50%. Half the profit goes to shareholders, half funds growth. If EPS drops to $1.50, that same $2 dividend becomes a 133% payout ratio, meaning the company pays more than it earns. That dividend is at risk of being cut.

Rule of thumb: A payout ratio above 80% for non-REITs is a red flag; a yield above 6-7% often signals the market expects a cut.

### 🧩 LeetCode Blind 100
> `2026-09-17 09:36:36`

#### 🧩 Blind 100 — 252. Meeting Rooms [Intervals]
**連結:** https://leetcode.com/problems/meeting-rooms/
> 📅 **Today's Daily Challenge:** #1573 Find Two Non-overlapping Sub-arrays Each With Target Sum [Medium] — Tags: Array, Hash Table, Binary Search, Dynamic Programming, Sliding Window — https://leetcode.com/problems/find-two-non-overlapping-sub-arrays-each-with-target-sum/

**Problem Type:** Intervals / Sorting

**Key Insight:** A person can attend all meetings iff no two meetings overlap. Sort by start time; then it's enough to check that each meeting starts at or after the previous one ends.

**Approach:**
1. Sort `intervals` by start time.
2. Iterate from index 1, comparing `intervals[i][0]` (start) with `intervals[i-1][1]` (prev end).
3. If `start < prev_end`, return `False`.
4. Return `True` if no overlaps found.

**Python3 Solution:**
```python
class Solution:
    def canAttendMeetings(self, intervals: List[List[int]]) -> bool:
        intervals.sort(key=lambda x: x[0])
        for i in range(1, len(intervals)):
            if intervals[i][0] < intervals[i-1][1]:
                return False
        return True
```

**Complexity:** Time O(n log n) | Space O(1) (ignoring sort's internal space; O(n) if counting Timsort worst case)

**Blind 100 Note:** This is the canonical "sort intervals by start, then scan for overlap" pattern. It's the foundation for the entire interval family: Merge Intervals (56), Insert Interval (57), Non-overlapping Intervals (435), Minimum Number of Arrows (452), and Meeting Rooms II (253, the heap variant). Master this one and the rest are variations on the same sort-then-scan skeleton.

**Contest Tips:**
- **Edge cases:** empty list → `True`; single meeting → `True`; touching intervals (`[0,5]` and `[5,10]`) do **not** overlap — use strict `<`, not `<=`.
- **Python trick:** `intervals.sort()` works too since lists compare lexicographically, but `key=lambda x: x[0]` is clearer and slightly faster for large inputs.
- **Common mistake:** Sorting by end time instead of start. End-time sorting is for *max non-overlapping* problems (435, 452), not for detecting any overlap.
- **Follow-up prep:** If asked "how many rooms?", that's Meeting Rooms II — use a min-heap of end times.

### 📷 Learning — Photography
> `2026-09-17 09:36:43`

#### 📷 Today's Concept: Color — Complementary Colors in Photography

**What it is:** Complementary colors are pairs opposite each other on the color wheel — red/cyan, blue/orange, yellow/purple. When placed together in a frame, they create maximum color contrast and visual tension.

**Why it matters:** This contrast makes subjects pop instantly and gives images that polished, cinematic look — it's the backbone of the teal-and-orange grade you see in films.

**How to apply it:**
1. Scout for existing pairs: a blue wall with a subject in orange, golden-hour skin against blue sky, red jacket on green foliage.
2. Pick one dominant color and let the other accent it — don't split the frame 50/50.
3. Position your subject against the complementary background, then expose for the brighter element.
4. In post, push saturation slightly on both hues using HSL panels rather than global saturation.
5. For video, lock white balance manually so the relationship stays consistent across shots.

**Sony A7C tip:** Use Creative Style → Vivid or Picture Profile PP6 (cine-style) to preview richer complementary tones in-camera. A fast prime like the Sony 35mm f/1.8 or 85mm f/1.8 helps isolate color pairs with shallow depth of field.

**Common mistake:** Over-saturating everything until colors clash and look artificial. Instead, keep one color muted and let the complementary pair do the work — restraint reads as intentional, not accidental.

### 📚 Learning — Tech
> `2026-09-17 09:36:40`

#### 📚 Today's Concept: Caching Strategies (Cache-aside, Write-through, Write-back)

**What it is:** Caching strategies define how your app reads/writes data between a cache and the source of truth (DB). Cache-aside: app checks cache, on miss loads from DB and populates cache. Write-through: writes go to cache and DB synchronously. Write-back: writes go to cache only, flushed to DB later.

**When to use it:** Cache-aside for read-heavy workloads (product listings). Write-through when consistency matters (user profiles). Write-back for write-heavy, latency-sensitive workloads (counters, metrics) where some data loss is tolerable.

**Example:**
```python
# Cache-aside
val = cache.get(key)
if val is None:
    val = db.query(key)
    cache.set(key, val, ttl=300)
return val
```

**Gotcha:** Cache-aside doesn't invalidate on writes — you must explicitly delete/update the cache key after DB writes, or you'll serve stale data. Many devs assume the cache "knows" the DB changed; it doesn't.

### 🎬 Learning — YouTube
> `2026-09-17 09:36:46`

#### 🎬 今日主題：攝影Vlog — 攝影 Vlog 的敘事結構：出發 / 拍攝 / 反思
**類別：** 攝影Vlog

**是什麼：** 攝影 Vlog 的敘事結構，是把影片拆成「出發（動機與期待）→ 拍攝（過程與挑戰）→ 反思（成品與心得）」三段。它讓零散畫面有了起承轉合，觀眾才跟得上你的故事。

**為什麼重要：** 沒有結構的 Vlog 容易變成流水帳，觀眾看不到重點就離開；有結構能提升完播率，也讓你在剪輯時知道該留哪些片段。

**怎麼做：**
1. 出發：用 10 秒交代「今天去哪、想拍什麼、為什麼」，可對著 A7C 自拍或用手機補拍。
2. 拍攝：挑 2–3 個關鍵時刻（找景、設定、突發狀況），不要全放。
3. 反思：結尾 30 秒講「拍到什麼、學到什麼、下次想改什麼」。
4. 剪輯時先寫三行大綱，再對應素材，避免迷路。
5. 用 AI 工具（如 Descript、CapCut）自動上字幕、粗剪，你專注在結構與節奏。

**新手常犯的錯：** 把當天所有片段照時間順序全放進去。避免方法：每個段落只留「推進故事」的畫面，其餘果斷刪。

**延伸 idea：** 拍一集「只用一顆鏡頭拍完台北一日攝影 Vlog」，出發講挑戰、拍攝記錄限制、反思比較成品與預期。
