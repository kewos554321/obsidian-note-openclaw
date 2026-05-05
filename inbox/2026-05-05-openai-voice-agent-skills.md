---
date: 2026-05-05
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "savings_travel", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube", "immigration_au"]
---

# Daily Digest — 2026-05-05

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

1. **Taiwan TAIEX surged 4.57% to 40,705** — massive local buying momentum, far outperforming US/Japan markets. Worth checking sector-specific catalysts. [Source](#)
2. **OpenAI published low-latency voice AI architecture** — deep dive on real-time inference optimization (model parallelism, streaming, audio tokenization). [Read more](https://openai.com/index/delivering-low-latency-voice-ai-at-scale/)
3. **Google Gemini Embedding 2 is GA** — unified multimodal embeddings (text, image, video, audio) for agentic RAG pipelines. [Read more](https://developers.googleblog.com/building-with-gemini-embedding-2/)
4. **AMD dropped 5.27%** — worst AI chipmaker performer today; SMCI (+1.9%) and Palantir (+1.36%) bucked the trend.
5. **Mother's Day sales active in Taiwan** — PChome/momo running 全站折扣 + bank rebates; good time for entry-level mirrorless (Sony ZV-E10, Canon R50) and dive computers.

---

- 💻 Tech: OpenAI voice AI architecture, Agent Skills framework, transformers succinctness proof, Odysseus RL for 100+ turn game agents, RunAgent constraint-guided execution.
- 🤖 AI 公司動態: Only Tesla updates — options strategy advice, Musk settles X lawsuit, stock among today's movers; no OpenAI/Anthropic news.
- 🔵 Google 動態: Gemini Embedding 2 GA, event-driven webhooks for Gemini API, Agents CLI for dev-to-production, 3X LLM speedup on TPUs (DFlash), LiteRT + NPU for on-device AI.
- 📈 Markets: TAIEX +4.57% (40,705), S&P 500 -0.11% (7,200), Nikkei +0.38% (59,513) — Taiwan leads strongly.
- 🏠 台灣房市: High-price market active (大安區 ~180萬/坪), rental demand stable; 青埔/台中七期 notable; caution on央行管制 & loan limits.
- 📊 Watchlist: AMD -5.27%, Arm -3.36%, SMCI +1.9%, Palantir +1.36%, NVDA flat at $198.48.
- 🌍 World News: US strikes Iranian fast boats after UAE oil facility attack; car-into-crowd in Leipzig (2 dead); hantavirus outbreak on cruise ship (3 dead); Ukrainian drone hits Moscow high-rise; 3 Russian diplomats expelled from Austria.
- 📷 Camera Deals: Mother's Day sales active (PChome/momo 88折, 滿萬送千); 光華商場 cash discounts negotiable; Japan代購 worth it for items >NT$30k;二手 market good for graduation season.
- 🤿 Dive Gear Deals: Mother's Day promos at 海人潛水/潛水易購 (買一送一 on computers, 滿5000送500 on wetsuits); 蝦皮商城 filter by "商城" to avoid counterfeits.
- ✈️ Flight Tips: Japan mid-May prices dip (Peach/Scoot); Thailand rock-bottom (AirAsia Big Sale); Europe book 10-12 weeks out (EVA/China Airlines); US Starlux undercuts competitors; Egypt via Turkish/Emirates; Australia low season (Jetstar/Scoot).
- 🗺️ Travel Deals: Japan visa-free 90 days; budget ¥10,000-15,000/day; Suica/Pasmo recommended; discounted tickets at convenience stores or Klook/KKday; avoid Golden Week.
- 📚 Learning — Finance: Revenue vs. Net Income — revenue can grow while net income stays flat if costs eat gains; compare growth rates to spot efficiency vs. cash burn.
- 🧩 LeetCode Blind 100: 312. Burst Balloons (interval DP, O(n³)); Daily Challenge: #61 Rotate List (Linked List, Two Pointers).
- 📷 Learning — Photography: Underwater housing basics for Sony A7C — Nauticam/Ikelite, dome port for wide-angle, wet lenses for macro, manual white balance, Focus Magnifier tip.
- 📚 Learning — Tech: Kubernetes Pod Scheduling — nodeSelector for simple constraints, node affinity/pod anti-affinity for complex rules; common gotcha: unschedulable pods if no matching node.
- 🎬 Learning — YouTube: Shorts + long video strategy — 3-5 Shorts/week from highlights, link to full version

---

## 💻 Tech

### 💻 Tech & AI
> `2026-05-05 07:50:22`

#### Hacker News
- [How OpenAI delivers low-latency voice AI at scale](https://openai.com/index/delivering-low-latency-voice-ai-at-scale/) ⭐205
- [Agent Skills](https://addyosmani.com/blog/agent-skills/) ⭐40
- [Let's talk about LLMs](https://www.b-list.org/weblog/2026/apr/09/llms/) ⭐121
- [Sierra Raises $950M at $15B Valuation](https://sierra.ai/blog/better-customer-experiences-built-on-sierra) ⭐80
- [Transformers Are Inherently Succinct](https://arxiv.org/abs/2510.19315) ⭐18
- [Why are neural networks and cryptographic ciphers so similar? (2025)](https://reiner.org/neural-net-ciphers) ⭐123
- [OpenAI, Google, and Microsoft Back Bill to Fund 'AI Literacy' in Schools](https://www.404media.co/literacy-in-future-technologies-artificial-intelligence-act-adam-schiff-mike-rounds/) ⭐109
- [Let's Buy Spirit Air](https://letsbuyspiritair.com/) ⭐569
- ['Staggering' number of people believe unproven health claims](https://www.nature.com/articles/d41586-026-01285-2) ⭐28
- [Usage-based pricing killing your vibe, here's how to roll your own local AI](https://www.theregister.com/2026/05/02/local_ai_coding_agents/) ⭐36

#### HuggingFace
- [Odysseus: Scaling VLMs to 100+ Turn Decision-Making in Games via Reinforcement Learning](https://huggingface.co/papers/2605.00347)
- [Soft Anisotropic Diagrams for Differentiable Image Representation](https://huggingface.co/papers/2604.21984)
- [MASCing: Configurable Mixture-of-Experts Behavior via Activation Steering Masks](https://huggingface.co/papers/2604.27818)
- [Stable-GFlowNet: Toward Diverse and Robust LLM Red-Teaming via Contrastive Trajectory Balance](https://huggingface.co/papers/2605.00553)
- [Better Models, Faster Training: Sigmoid Attention for single-cell Foundation Models](https://huggingface.co/papers/2604.27124)
- [Prox-E: Fine-Grained 3D Shape Editing via Primitive-Based Abstractions](https://huggingface.co/papers/2604.23774)

#### ArXiv
- [HyCOP: Hybrid Composition Operators for Interpretable Learning of PDEs](http://arxiv.org/abs/2605.00820v1)
- [When LLMs Stop Following Steps: A Diagnostic Study of Procedural Execution in Language Models](http://arxiv.org/abs/2605.00817v1)
- [Persistent Visual Memory: Sustaining Perception for Deep Generation in LVLMs](http://arxiv.org/abs/2605.00814v1)
- [Can Coding Agents Reproduce Findings in Computational Materials Science?](http://arxiv.org/abs/2605.00803v1)
- [Generating Statistical Charts with Validation-Driven LLM Workflows](http://arxiv.org/abs/2605.00800v1)
- [RunAgent: Interpreting Natural-Language Plans with Constraint-Guided Execution](http://arxiv.org/abs/2605.00798v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-05-05 07:50:36`

#### Tesla
- [Stock Market Today, May 4: Intel Pulls Back After Rally as AI PC Push Tests New Client Leadership](https://finance.yahoo.com/m/32738f48-7c36-34fc-8b55-3e8ac92c5c55/stock-market-today%2C-may-4%3A.html)
- [Elon Musk Settles X Lawsuit for a Cup of (Cheap) Coffee. What It Means for SpaceX’s IPO.](https://finance.yahoo.com/m/c3833aff-81e8-3e5c-b200-27cb76354f76/elon-musk-settles-x-lawsuit.html)
- [These Stocks Are Today’s Movers: Coinbase, AMD, Palantir, Tesla, eBay, GameStop, FedEx, UPS, Micron, and More](https://finance.yahoo.com/m/bf397f98-7506-3408-ae60-4cae99313630/these-stocks-are-today%E2%80%99s.html)
- [Don’t Buy Tesla Stock. Buy Options Instead.](https://finance.yahoo.com/m/8e7cb93e-d24f-351a-96b2-c1eb48460500/don%E2%80%99t-buy-tesla-stock.-buy.html)

### 🔵 Google 動態
> `2026-05-05 07:50:29`

#### Google AI Blog
- [The latest AI news we announced in April 2026](https://blog.google/innovation-and-ai/technology/ai/google-ai-updates-april-2026/)
- [Reduce friction and latency for long-running jobs with Webhooks in Gemini API](https://blog.google/innovation-and-ai/technology/developers-tools/event-driven-webhooks/)
- [Celebrating 20 years of Google Translate: Fun facts, tips and new features to try](https://blog.google/products-and-platforms/products/translate/fun-facts-google-translate-20-years/)
- [Join the new AI Agents Vibe Coding Course from Google and Kaggle](https://blog.google/innovation-and-ai/technology/developers-tools/kaggle-genai-intensive-course-vibe-coding-june-2026/)
- [8 Gemini tips for organizing your space (and life)](https://blog.google/products-and-platforms/products/gemini/gemini-spring-cleaning-tips/)
#### Google Blog
- [The latest AI news we announced in April 2026](https://blog.google/innovation-and-ai/technology/ai/google-ai-updates-april-2026/)
- [Here's how Google AI is powering small business growth](https://blog.google/company-news/outreach-and-initiatives/small-business/ai-for-small-businesses/)
- [Reduce friction and latency for long-running jobs with Webhooks in Gemini API](https://blog.google/innovation-and-ai/technology/developers-tools/event-driven-webhooks/)
- [Celebrating America’s 250th on Google Arts & Culture](https://blog.google/company-news/outreach-and-initiatives/arts-culture/celebrating-america/)
- [Supporting startups that are shaping the future of energy](https://blog.google/company-news/outreach-and-initiatives/entrepreneurs/google-for-startups-accelerator/)
#### Google Developers
- [Supercharging LLM inference on Google TPUs: Achieving 3X speedups with diffusion-style speculative decoding](https://developers.googleblog.com/supercharging-llm-inference-on-google-tpus-achieving-3x-speedups-with-diffusion-style-speculative-decoding/)
- [Building with Gemini Embedding 2: Agentic multimodal RAG and beyond](https://developers.googleblog.com/building-with-gemini-embedding-2/)
- [Speeding Up AI: Bringing Google Colossus to PyTorch via GCSFS and Rapid Bucket](https://developers.googleblog.com/speeding-up-ai-bringing-google-colossus-to-pytorch-via-gcsfs-and-rapid-bucket/)
- [Building real-world on-device AI with LiteRT and NPU](https://developers.googleblog.com/building-real-world-on-device-ai-with-litert-and-npu/)
- [Agents CLI in Agent Platform:  create to production in one CLI](https://developers.googleblog.com/agents-cli-in-agent-platform-create-to-production-in-one-cli/)

## 📈 Finance

### 📈 Markets Overview
> `2026-05-05 08:00:05`

#### Indices
- S&P 500: 7,200.75 ▼0.11%
- 台股加權: 40,705.14 ▲4.57%
- 日經 225: 59,513.12 ▲0.38%

### 🏠 台灣房市
> `2026-05-05 08:01:29`

#### AI 分析
#### 台灣房市分析報告 (2026-05-05)

1. **整體趨勢：高總價市場持續熱絡，租賃需求穩定**  
   近期內政部實價登錄顯示，高總價住宅（如台北市大安區、新北市高單價物件）成交力道強勁，單價突破每坪180萬台幣；同時，591租賃物件遍布雙北、台中、高雄，顯示自住與租屋需求並存，市場呈「買賣高檔盤整、租賃剛需支撐」格局。

2. **值得注意地區與物件類型**  
   - **桃園青埔特區**：新潤A18三房車物件（近華泰名品城）反映高鐵特區持續吸引雙北外溢買盤，具備交通與商業利多。  
   - **台中七期/西屯區**：理和質感大三房開價3980萬，顯示台中高總價豪宅市場仍有高端自住與置產需求。  
   - **台北東門/永康商圈**：3米6租件（可租補）凸顯蛋黃區小坪數租賃市場穩定，適合長期收租。

3. **對自住者建議**  
   - **鎖定交通與生活機能成熟區**：如板橋民治街、三峽北大特區（遠雄大學劍橋），此類物件保值性高，且租賃市場活絡，可降低未來轉手風險。  
   - **善用租屋補貼政策**：台北、新北多件租屋標註「可租補」，自住者可優先考慮，減輕租金負擔。

4. **對投資者建議**  
   - **高總價物件需審慎評估**：近期高總價成交單價（如大安區每坪約180萬）已達歷史高點，建議聚焦具稀有性（如景觀、格局）或重大建設（如青埔、台中水湳）的物件，避免追高一般住宅。  
   - **留意「其他」類別交易**：實價登錄出現單價148萬/㎡的「其他」類別（可能為商辦或特殊產權），投資前需確認使用分區與未來變現性，避免流動性風險。

5. **短期風險提醒**  
   - 央行選擇性信用管制與升息壓力未解除，高總價物件貸款成數可能受限，建議投資者預留3-6成自備款，並優先選擇租金報酬率達2.5%以上標的（如桃園、台中出租型套房）。

#### 591 最新
- [新北市板橋區民治街96巷全新裝潢二房一廳冷氣前後陽台近華江橋捷運生活機能方便](https://rent.591.com.tw/rent-detail-21191875.html)
- [桃園市中壢區春德路🔴新潤A18🔴青埔華泰旁邊間格局視野景觀三房車](https://sale.591.com.tw/sale-detail-20144386.html)
- [台中市西屯區台灣大道二段🏅理和質感釋出丨大三房雙平車丨只要3980萬🏅](https://sale.591.com.tw/sale-detail-20144385.html)
- [彰化縣福興鄉秀安二街157巷(我是承辦)福興秀厝靜巷透天｜田野之間的幸福雅築](https://sale.591.com.tw/sale-detail-20144384.html)
- [台北市大安區信義路二段◆東門站/中正紀念堂+永康街生活圈◆3米6/可租補](https://rent.591.com.tw/rent-detail-21191880.html)
- [台中市北區德化街全新整修⭐中國醫❤️超值❤️採光套房](https://rent.591.com.tw/rent-detail-21191879.html)
- [高雄市三民區覺民路~高樓層住家出租~採光佳視野佳~](https://rent.591.com.tw/rent-detail-21191877.html)
- [新北市三峽區學勤路AL/遠雄大學劍橋近國立臺北大學，免仲、可租補](https://rent.591.com.tw/rent-detail-21191878.html)

#### 實價登錄 (115S1) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 住宅大樓(11層含以上有電梯) | 382.2㎡ | 18305萬 | 548016元/㎡ |
|  | 透天厝 | 338.8㎡ | 10600萬 | 312848元/㎡ |
|  | 其他 | 0.0㎡ | 9954萬 | 1480149元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 222.3㎡ | 9028萬 | 406100元/㎡ |
|  | 其他 | 0.0㎡ | 8300萬 | 360870元/㎡ |

### 📊 Watchlist
> `2026-05-05 08:00:47`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 198.48 ▲0.02% |
| Market Cap | $4.82T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 71.1% / 60.4% / 55.6% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 30.67 |
| Beta | 2.33 |
| 52-Week | 110.82 – 216.83 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures: Iran Attacks Spark Stock Market Losses; Palantir Slides On Earnings](https://finance.yahoo.com/m/3d2a97f4-a6fb-34ca-8055-7af58ef956c6/dow-jones-futures%3A-iran.html) — Investor's Business Daily
- [Meta's Revenue Growth Is Impressive, but Its AI Budget Is Getting Harder to Ignore](https://finance.yahoo.com/m/e0d44b5f-93c0-345c-ace4-20d43987d173/meta%27s-revenue-growth-is.html) — Motley Fool
- [Stock Market Today, May 4: Intel Pulls Back After Rally as AI PC Push Tests New Client Leadership](https://finance.yahoo.com/m/32738f48-7c36-34fc-8b55-3e8ac92c5c55/stock-market-today%2C-may-4%3A.html) — Motley Fool

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 341.54 ▼5.27% |
| Market Cap | $556.85B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 49.5% / 10.7% / 12.5% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 8.84 |
| Beta | 2.40 |
| 52-Week | 96.88 – 362.79 |
| Div. Yield | — |

**Recent News:**
- [AMD and Pfizer earnings, job openings, Fedspeak: What to Watch](https://finance.yahoo.com/video/amd-pfizer-earnings-job-openings-230000659.html) — Yahoo Finance Video
- [Stock Market Today, May 4: Intel Pulls Back After Rally as AI PC Push Tests New Client Leadership](https://finance.yahoo.com/m/32738f48-7c36-34fc-8b55-3e8ac92c5c55/stock-market-today%2C-may-4%3A.html) — Motley Fool
- [Adeia Q1 Earnings Call Highlights](https://finance.yahoo.com/m/72096fe6-6f37-37f1-82d0-eb65afe80c12/adeia-q1-earnings-call.html) — MarketBeat

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 413.62 ▼0.20% |
| Market Cap | $3.07T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 68.3% / 46.8% / 39.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 7.41 |
| Beta | 1.11 |
| 52-Week | 356.28 – 555.45 |
| Div. Yield | — |

**Recent News:**
- [Adeia Q1 Earnings Call Highlights](https://finance.yahoo.com/m/72096fe6-6f37-37f1-82d0-eb65afe80c12/adeia-q1-earnings-call.html) — MarketBeat
- [Bond Yields Are Rising. Why That Could End the Stock Market’s Rally.](https://finance.yahoo.com/m/912a4d64-3919-3362-94a9-14a9d15ffc99/bond-yields-are-rising.-why.html) — Barrons.com
- [Adeia Announces First Quarter 2026 Financial Results](https://finance.yahoo.com/markets/stocks/articles/adeia-announces-first-quarter-2026-200500368.html) — GlobeNewswire

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 383.25 ▼0.63% |
| Market Cap | $4.64T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.4% / 32.7% / 37.9% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 9.69 |
| Beta | 1.13 |
| 52-Week | 147.84 – 387.38 |
| Div. Yield | — |

**Recent News:**
- [Stock Market Today, May 4: Intel Pulls Back After Rally as AI PC Push Tests New Client Leadership](https://finance.yahoo.com/m/32738f48-7c36-34fc-8b55-3e8ac92c5c55/stock-market-today%2C-may-4%3A.html) — Motley Fool
- [Brookwood Cuts FLXR Position by $3 Million -- What Income Investors Should Know](https://finance.yahoo.com/m/61b5aad4-fdd5-3ce9-b8d2-dc87e5e44032/brookwood-cuts-flxr-position.html) — Motley Fool
- [White House Weighs AI Working Group, Model Testing, NYT Reports](https://finance.yahoo.com/sectors/technology/articles/white-house-eyes-vetting-ai-193136483.html) — Bloomberg

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 272.05 ▲1.41% |
| Market Cap | $2.93T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 50.6% / 11.5% / 12.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.61 |
| Beta | 1.38 |
| 52-Week | 183.85 – 276.10 |
| Div. Yield | — |

**Recent News:**
- [The CEO of Saks Global Says the Company Is Ready for a Comeback](https://finance.yahoo.com/m/6839ce88-89d9-32af-b8b0-b006693e85cc/the-ceo-of-saks-global-says.html) — The Wall Street Journal
- [Met Gala 2026: Lauren Sánchez Bezos, Nicole Kidman and Anna Wintour on the Red Carpet](https://finance.yahoo.com/m/6fa3d2a6-cd15-3978-97e6-366e84322bd6/met-gala-2026%3A-lauren-s%C3%A1nchez.html) — The Wall Street Journal
- [Auto & Transport Roundup: Market Talk](https://finance.yahoo.com/m/02bb834d-f9c3-39ad-a4a5-735706dd3d70/auto-%26-transport-roundup%3A.html) — The Wall Street Journal

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 610.41 ▲0.27% |
| Market Cap | $1.55T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.9% / 41.2% / 32.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.35 |
| Beta | 1.31 |
| 52-Week | 520.26 – 796.25 |
| Div. Yield | — |

**Recent News:**
- [Meta's Revenue Growth Is Impressive, but Its AI Budget Is Getting Harder to Ignore](https://finance.yahoo.com/m/e0d44b5f-93c0-345c-ace4-20d43987d173/meta%27s-revenue-growth-is.html) — Motley Fool
- [Meta taps Morgan Stanley, JPMorgan for El Paso data center deal, Bloomberg News reports](https://finance.yahoo.com/markets/stocks/articles/meta-taps-morgan-stanley-jpmorgan-231945174.html) — Reuters
- [Reuters wins Pulitzer Prizes for Beat Reporting and National Reporting; named finalist in Illustrated Reporting and Breaking News Photography](https://finance.yahoo.com/sectors/technology/articles/reuters-wins-pulitzer-prizes-beat-203800513.html) — PR Newswire

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 416.50 ▼0.22% |
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
- [Dow Jones Futures: Iran Attacks Spark Stock Market Losses; Palantir Slides On Earnings](https://finance.yahoo.com/m/3d2a97f4-a6fb-34ca-8055-7af58ef956c6/dow-jones-futures%3A-iran.html) — Investor's Business Daily
- [Why Broadcom Inc. (AVGO) Dipped More Than Broader Market Today](https://finance.yahoo.com/markets/stocks/articles/why-broadcom-inc-avgo-dipped-214504436.html) — Zacks
- [Brookwood Cuts FLXR Position by $3 Million -- What Income Investors Should Know](https://finance.yahoo.com/m/61b5aad4-fdd5-3ce9-b8d2-dc87e5e44032/brookwood-cuts-flxr-position.html) — Motley Fool

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 203.26 ▼3.36% |
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
- [Intel appoints Qualcomm executive to lead PC and physical AI business](https://finance.yahoo.com/sectors/technology/articles/intel-appoints-qualcomm-executive-lead-215126771.html) — Reuters
- [Jim Cramer Calls Arm Holdings a “Real Good One”](https://finance.yahoo.com/markets/stocks/articles/jim-cramer-calls-arm-holdings-182126281.html) — Insider Monkey
- [Will Top-Line Improvement Aid Arm Holdings' Q4 Earnings?](https://finance.yahoo.com/markets/stocks/articles/top-line-improvement-aid-arm-174800239.html) — Zacks

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 146.03 ▲1.36% |
| Market Cap | $334.62B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.1% / 38.1% / 43.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 41.37 |
| Beta | 1.52 |
| 52-Week | 105.32 – 207.52 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures: Iran Attacks Spark Stock Market Losses; Palantir Slides On Earnings](https://finance.yahoo.com/m/3d2a97f4-a6fb-34ca-8055-7af58ef956c6/dow-jones-futures%3A-iran.html) — Investor's Business Daily
- [Palantir Just Delivered Another Quarterly Beat -- And the Company's 2026 Outlook Just Got Even Stronger](https://finance.yahoo.com/m/d34db16b-205f-3d33-963c-2f4decc3dbdb/palantir-just-delivered.html) — Motley Fool
- [Palantir (PLTR) Q1 2026 Earnings Transcript](https://finance.yahoo.com/m/45ad4ba1-fcd4-3712-9a3a-b7e2f4fec759/palantir-%28pltr%29-q1-2026.html) — Motley Fool

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 27.92 ▲1.90% |
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
- [Nvidia Stock Is Stuck Below $200. What Pushes It Higher.](https://finance.yahoo.com/m/fa25c5c2-e4fc-3aad-8193-b2437b2d6819/nvidia-stock-is-stuck-below.html) — Barrons.com
- [Super Micro Q3 Earnings Preview: What To Expect From Upcoming Report](https://finance.yahoo.com/markets/stocks/articles/super-micro-q3-earnings-preview-175626963.html) — GuruFocus.com
- [DeepInfra Closes $107M Series B to Power Production-Scale AI Inference](https://finance.yahoo.com/sectors/technology/articles/deepinfra-closes-107m-series-b-160000545.html) — GlobeNewswire

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 392.51 ▲0.43% |
| Market Cap | $1.47T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.1% / 5.0% / 4.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 15.09 |
| Beta | 1.92 |
| 52-Week | 271.00 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Stock Market Today, May 4: Intel Pulls Back After Rally as AI PC Push Tests New Client Leadership](https://finance.yahoo.com/m/32738f48-7c36-34fc-8b55-3e8ac92c5c55/stock-market-today%2C-may-4%3A.html) — Motley Fool
- [Elon Musk Settles X Lawsuit for a Cup of (Cheap) Coffee. What It Means for SpaceX’s IPO.](https://finance.yahoo.com/m/c3833aff-81e8-3e5c-b200-27cb76354f76/elon-musk-settles-x-lawsuit.html) — Barrons.com
- [These Stocks Are Today’s Movers: Coinbase, AMD, Palantir, Tesla, eBay, GameStop, FedEx, UPS, Micron, and More](https://finance.yahoo.com/m/bf397f98-7506-3408-ae60-4cae99313630/these-stocks-are-today%E2%80%99s.html) — Barrons.com

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 660.12 ▼0.07% |
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
- [Smart Retirement Planning: Balancing Taxes, Risk, and Returns](https://finance.yahoo.com/markets/options/articles/smart-retirement-planning-balancing-taxes-204600548.html) — Zacks
- [Is the Vanguard S&P 500 ETF Still Worth Buying When Markets Are Down?](https://finance.yahoo.com/m/5212c96a-568d-30a9-8d79-be8e6d536bc3/is-the-vanguard-s%26p-500-etf.html) — Motley Fool
- [Here's the Smartest Way to Invest in the S&P 500 in May](https://finance.yahoo.com/m/83a46776-9260-3174-b452-a49154e8a866/here%27s-the-smartest-way-to.html) — Motley Fool

## 🌍 News

### 🌍 World News
> `2026-05-05 08:10:06`

- [US strikes Iranian fast boats as Iran attacks UAE oil facility](https://www.bbc.com/news/articles/cjwp432d0v5o?at_medium=RSS&at_campaign=rss)
- [Two killed and many injured after car driven into crowd in German city of Leipzig](https://www.bbc.com/news/articles/ckgpzgxgz58o?at_medium=RSS&at_campaign=rss)
- [Three dead in suspected hantavirus outbreak on Atlantic cruise ship](https://www.bbc.com/news/articles/cy0294829ndo?at_medium=RSS&at_campaign=rss)
- [Former New York City mayor Rudy Giuliani recovering from pneumonia and 'now breathing on his own'](https://www.bbc.com/news/articles/cpvpnve1r24o?at_medium=RSS&at_campaign=rss)
- [Ukrainian drone hits upmarket Moscow high-rise ahead of Victory Day celebrations](https://www.bbc.com/news/articles/cwy234llx3vo?at_medium=RSS&at_campaign=rss)
- [Britney Spears pleads guilty to reckless driving after arrest](https://www.bbc.com/news/articles/ce9p09e5vnro?at_medium=RSS&at_campaign=rss)
- [Three Russian diplomats expelled from Austria over spying accusations](https://www.bbc.com/news/articles/c5yrwny111xo?at_medium=RSS&at_campaign=rss)
- [Robots move in as waste firms struggle to find staff](https://www.bbc.com/news/articles/cvg0w84q1wyo?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-05-05 08:20:26`

#### AI Tips
Here’s your **photography expert & deals advice** for Taiwan, tailored to **May 5, 2026**.

---

## 【購買優惠】— Best Places & May Sale Tips

#### Best places to buy camera gear in Taiwan (ranked by value)

| Channel | Best for | Notes |
|---------|----------|-------|
| **PChome 24h** | New gear, fast delivery, easy returns | Often has **bank-linked rebates** (e.g., 5–8% back with 玉山/台新). Watch for **限時特價** flash sales. |
| **momo購物** | Bundles (body + lens + accessories) | Better for **kit deals** and **momo幣** accumulation. Check **品牌旗艦館** for official warranty. |
| **光華商場** (e.g., 數位達人, 相機王) | Hands-on testing, cash discounts | **Price negotiable** if you pay cash. Ask for “現金價” and compare 3 stores. Beware of gray-market (水貨) — confirm “公司貨” for Taiwan warranty. |
| **日本代購** (e.g., Buyee, 樂淘) | High-end lenses, limited editions | **Yen is weak** in 2026? Check exchange rate. Add 10–15% for shipping + customs (關稅). Only worth it for items > NT$30,000. |
| **二手** (DCView, 蝦皮, 臉書社團) | Budget bodies, vintage lenses | **May is a good month** — many students sell gear before graduation. Meet in person at 捷運站, test shutter count. |

#### 🎯 Seasonal Sale Tips for May 2026

1. **母親節檔期 (Mother’s Day)** — mid-April to mid-May  
   - PChome & momo run **全站折扣** (e.g., 88折券, 滿萬送千).  
   - Best time to buy **entry-level mirrorless** (Sony ZV-E10, Canon R50) or **vlogging gear**.  
   - Pro tip: Stack **銀行刷卡回饋** + **平台折價券** + **LINE Points** for max savings.

2. **618購物節 (June

#### r/photomarket
- [PSA: Turn on ‘Persistent Messaging’ when using Chats](https://www.reddit.com/r/photomarket/comments/1mboakg/psa_turn_on_persistent_messaging_when_using_chats/)
- [PSA: AI timestamp photos and how not to get scammed](https://www.reddit.com/r/photomarket/comments/1nkg9v6/psa_ai_timestamp_photos_and_how_not_to_get_scammed/)
- [[S][USA-WA] Minty EOS 5D Mark IV (Shutter count 1,106)](https://www.reddit.com/r/photomarket/comments/1t3w0z5/susawa_minty_eos_5d_mark_iv_shutter_count_1106/)
- [[S][USA-TN] Leica IIIG body only](https://www.reddit.com/r/photomarket/comments/1t3tua5/susatn_leica_iiig_body_only/)
- [[S] [USA-PA] Sony E 16-55mm f/2.8 G (APS-C) SEL1655G](https://www.reddit.com/r/photomarket/comments/1t3s3sg/s_usapa_sony_e_1655mm_f28_g_apsc_sel1655g/)

### 🤿 Dive Gear Deals
> `2026-05-05 08:20:33`

#### AI Tips
Here’s a practical, Taiwan-specific guide for recreational divers in May 2026.

---

#### 【購買優惠】

**1. Best places to buy diving equipment in Taiwan**

- **實體潛水用品店 (Physical Shops):**  
  - **台北: 海人潛水 (Hai Ren Diving)** – Good for high-end brands (Apeks, Scubapro) and expert fitting.  
  - **墾丁: 潛水易購 (Dive Easy Go)** – Best for rental gear purchase (used BCDs, regs) and local brand deals.  
  - **台中: 潛水倉庫 (Diving Warehouse)** – Often has clearance racks for last-season wetsuits.

- **線上 (Online):**  
  - **蝦皮商城 (Shopee Mall)** – Search “潛水裝備 2026新款”. Filter by “商城” to avoid counterfeits.  
  - **PChome 24h 潛水專區** – Good for quick delivery of masks, fins, and computers (e.g., Suunto, Shearwater).  
  - **Facebook社團 (FB Groups):**  
    - 「台灣潛水裝備二手買賣」 – Best for used gear (check seller history; meet in person for regs/BCDs).  
    - 「潛水裝備新品團購」 – Often runs group buys for Mares, Cressi, or local brands like **Deepblu**.

**2. May seasonal sale tips & diving season notes**

- **May Sales:**  
  - **Mother’s Day Promotions (5月母親節):** Many shops (e.g., 海人潛水, 潛水易購) run “買一送一” on dive computers or “滿5000送500” on wetsuits. Check around **May 8–12**.  
  - **End

#### r/scuba
- [Question about Wetsuits for Washigton Waters.](https://www.reddit.com/r/scuba/comments/1t2qp4u/question_about_wetsuits_for_washigton_waters/)

### ✈️ Flight Tips
> `2026-05-05 08:20:18`

#### AI Flight Tips — May
Here are your actionable flight deal tips for May 2026 departures from Taiwan:

**Japan (Tokyo/Osaka/Sapporo)**  
May is shoulder season (post-Golden Week), so prices dip mid-month. Book **6–8 weeks out** for the best rates. Cheapest route: **Peach Aviation** or **Scoot** via Taipei (TPE) to Tokyo (NRT) or Osaka (KIX); for Sapporo, **Tigerair Taiwan** often has flash sales. Watch for **Peach’s “Happy Peach”** promos and **EVA Air’s** occasional “Early Bird” discounts on Japan routes.

**Thailand (Bangkok/Chiang Mai)**  
May is low season (rainy start), so prices are rock-bottom. Book **4–6 weeks ahead** for the lowest fares. Cheapest: **Thai Lion Air** or **AirAsia** direct from TPE to DMK/CNX; for Chiang Mai, consider a cheap flight to BKK then a separate domestic leg. Look for **AirAsia’s “Big Sale”** (usually mid-month) and **Thai Airways’** occasional “Double Miles” deals.

**Europe (any major city)**  
May is peak spring travel, but you can still find deals. Book **10–12 weeks out** for best prices. Cheapest route: **China Airlines** or **EVA Air** via Taipei to London (LHR) or Paris (CDG), often with a stop in Bangkok or Dubai; **Turkish Airlines** via Istanbul is a solid budget option. Watch for **EVA Air’s “Hello Spring”** sales and **China Airlines’** “Fly & Save” promotions on European routes.

**USA (West Coast / East Coast)**  
May is moderate demand (pre-summer spike). Book **8–10 weeks ahead** for West Coast, **10–12 weeks** for East Coast. Cheapest: **Starlux Airlines** (TPE to LAX/SFO) often undercuts competitors; for East Coast, **EVA Air** to JFK or **China Airlines** to ORD/EWR with a layover. Look for **Starlux’s “New Route”** promos and **United’s** “MileagePlay” deals from TPE.

**Egypt (Cairo)**  
May is shoulder season (hot but not peak). Book **8–10 weeks out** for decent fares. Cheapest route: **Turkish Airlines** via Istanbul (IST) or **Emirates** via Dubai (DXB) from TPE; **EgyptAir** direct from Bangkok (BKK) after a cheap flight there. Watch for **Turkish Airlines’** “Stopover Istanbul” deals and **Emirates’** occasional “Skywards” bonus miles.

**Australia (Sydney/Melbourne)**  
May is low season (autumn/winter), so prices are low. Book **6–8 weeks ahead** for the best deals. Cheapest: **Jetstar** (via Osaka or Manila) or **Scoot** (via Singapore) from TPE; **China Airlines** direct to SYD/MEL is a solid mid-range option. Look for **Jetstar’s “Friday Fare Frenzy”** and **Scoot’s** “Scoot-a-Week”

### 🗺️ Travel Deals
> `2026-05-05 08:20:08`

#### r/solotravel
- [First time in Japan (11 Days Solo) - Golden Route! (Am i doing it right)](https://www.reddit.com/r/solotravel/comments/1t3ad6s/first_time_in_japan_11_days_solo_golden_route_am/)
- [Tokyo layover, solo female, what I learnt](https://www.reddit.com/r/solotravel/comments/1t29u5l/tokyo_layover_solo_female_what_i_learnt/)

## 📚 Learning

### 📚 Learning — Finance
> `2026-05-05 08:30:04`

#### 📚 Today's Concept: Revenue vs. Net Income

What it is: Revenue is the total money a company brings in from sales of its products or services, before any costs are subtracted. Net income is what remains after deducting all expenses—like cost of goods sold, salaries, taxes, and interest—from revenue.

Why it matters: A company can have soaring revenue but still lose money if costs are too high, which is a red flag for unsustainable growth. For stock analysis, comparing revenue growth to net income growth reveals whether a company is scaling efficiently or burning cash.

Example: Imagine a software company reports $100M in revenue for the year. After paying $60M in server costs, $30M in salaries, and $10M in taxes, its net income is $0. Revenue grew 50% from last year, but net income stayed flat—indicating costs are eating all the gains.

Rule of thumb: If revenue grows faster than net income for several quarters, investigate rising expenses; if net income grows faster than revenue, the company may be cutting costs unsustainably.

### 🧩 LeetCode Blind 100
> `2026-05-05 08:30:12`

#### 🧩 Blind 100 — 312. Burst Balloons [2D DP]
**連結:** https://leetcode.com/problems/burst-balloons/
> 📅 **Today's Daily Challenge:** #61 Rotate List [Medium] — Tags: Linked List, Two Pointers — https://leetcode.com/problems/rotate-list/

## 312. Burst Balloons [2D DP]

**Problem Type:** Interval DP / 2D DP  
**Key Insight:** Instead of picking which balloon to burst first, think backwards — pick the *last* balloon to burst in a range. This fixes the subproblems because the last balloon's neighbors are the boundaries of the range.

**Approach:**
1. Add `1` at both ends of `nums` to handle edge cases uniformly (new array `arr`).
2. Define `dp[i][j]` = max coins from bursting all balloons strictly between `i` and `j` (exclusive).
3. For each interval length from 2 to n+1:
   - For each start `i`, let `j = i + len`.
   - Try each `k` in `(i+1 ... j-1)` as the *last* balloon burst in this range.
   - Coins = `dp[i][k] + dp[k][j] + arr[i] * arr[k] * arr[j]`
4. Return `dp[0][n+1]`.

**Python3 Solution:**
```python
def maxCoins(nums: List[int]) -> int:
    arr = [1] + nums + [1]
    n = len(nums)
    dp = [[0] * (n + 2) for _ in range(n + 2)]
    
    for length in range(2, n + 2):          # interval length
        for i in range(0, n + 2 - length):  # left boundary
            j = i + length                  # right boundary
            for k in range(i + 1, j):       # last balloon to burst
                dp[i][j] = max(dp[i][j],
                               dp[i][k] + dp[k][j] + arr[i] * arr[k] * arr[j])
    return dp[0][n + 1]
```

**Complexity:** Time O(n³) | Space O(n²)

**Blind 100 Note:** Classic interval DP — the "reverse thinking" trick (last balloon instead of first) is the key pattern. Similar problems: *Minimum Cost to Merge Stones*, *Burst Balloons*, *Remove Boxes*. Essential for mastering 2D DP on intervals.

**Contest Tips:**
- **Edge case:** `nums = []` → returns 0 (handled by padding).
- **Python trick:** Use `arr = [1] + nums + [1]` to avoid bounds checking.
- **Common mistake:** Forgetting that `i` and `j` are *exclusive* boundaries — the actual balloons are between them.
- **Optimization:** Precompute `arr[i] * arr[k] * arr[j]` or use local variables for speed.
- **Memory:** Can be reduced to O(n) with 1D DP, but O(n²) is fine for n ≤ 300.

### 📷 Learning — Photography
> `2026-05-05 08:30:22`

#### 📷 Today's Concept: Special — Underwater Housing and Wet Lenses Basics

**What it is:** An underwater housing is a waterproof case that seals your Sony A7C for submerged shooting, while wet lenses are interchangeable glass elements attached to the housing’s dome port to change focal length or magnification underwater. This setup lets you capture sharp, distortion-free images from the surface down to depths of 30–60 meters.

**Why it matters:** It unlocks a hidden world—crystal-clear portraits with floating hair, dramatic street-like scenes of coral cities, and cinematic video with ethereal light rays. The visual impact is immediate: water adds depth, color, and motion impossible on land.

**How to apply it:**
1. **Choose a housing** rated for your A7C (e.g., Nauticam or Ikelite) and test the seal with a pressure check before each dive.
2. **Attach a dome port** (e.g., 6-inch dome) for wide-angle landscape or street shots—this corrects refraction and keeps edges sharp.
3. **Use a wet lens** like a +5 diopter for macro portraits of small subjects (e.g., nudibranchs); screw it onto the housing port underwater.
4. **Set white balance manually** to “Cloudy” or use a gray card at depth—auto WB turns everything blue-green.
5. **Shoot in manual mode** with shutter speed 1/125s or faster to freeze water movement; aperture f/8–f/11 for depth of field.

**Sony A7C tip:** Enable **Focus Magnifier** (Menu > Camera Settings 2 > Focus Assist > Focus Magnifier) and assign it to a custom button—it’s critical for nailing focus through a dome port, especially with wet lenses.

**Common mistake:** Forgetting to **remove the lens hood** before sealing the housing. The hood traps bubbles and blocks the dome’s field of view, causing vignetting. Always pack a flat port for hood-free lenses.

### 📚 Learning — Tech
> `2026-05-05 08:30:17`

#### 📚 Today's Concept: Kubernetes Pod Scheduling

**What it is:**  
Kubernetes Pod Scheduling is the process by which the kube-scheduler assigns a pod to a specific node in a cluster based on resource requirements, constraints, and policies. It evaluates node resources (CPU, memory), affinity rules, and taints/tolerations to make placement decisions.

**When to use it:**  
Use scheduling to ensure workloads run on appropriate nodes—e.g., placing GPU-intensive ML training pods only on nodes with GPUs, or spreading replicas across availability zones for high availability.

**Example:**  
```yaml
apiVersion: v1
kind: Pod
metadata:
  name: gpu-pod
spec:
  containers:
  - name: cuda
    image: nvidia/cuda
    resources:
      requests:
        nvidia.com/gpu: 1
  nodeSelector:
    gpu-type: a100
```
This pod will only schedule on nodes labeled `gpu-type: a100`.

**Gotcha:**  
A common mistake is assuming `nodeSelector` is the only way to constrain scheduling—it’s simple but inflexible. For complex rules (e.g., “prefer node X but fallback to Y”), use **node affinity** and **pod anti-affinity** instead, or you’ll get unschedulable pods if no matching node exists.

### 🎬 Learning — YouTube
> `2026-05-05 08:30:27`

#### 🎬 今日主題：策略 — Shorts 與長影片的搭配策略
**類別：** 策略

**是什麼：**  
Shorts 是短影音（60 秒內），長影片是深度內容。兩者搭配能互相導流，Shorts 負責曝光，長影片負責留存與訂閱。

**為什麼重要：**  
新手頻道缺乏流量，Shorts 能快速測試主題熱度，並將觀眾導向長影片，加速頻道成長。

**怎麼做：**  
1. 每週發 3-5 支 Shorts，從長影片剪出「精華片段」或「幕後花絮」。  
2. 在 Shorts 結尾加上「完整版連結」或引導文字。  
3. 長影片開頭用 15 秒預告 Shorts 的爆點。  
4. 用 AI 工具（如 Opus Clip）自動將長影片拆成多支 Shorts。  
5. 觀察 Shorts 數據，選高互動主題拍成完整長片。

**新手常犯的錯：**  
只做 Shorts 不做長影片，導致訂閱數高但觀看時長低，無法開啟收益。  
→ 解法：每 3 支 Shorts 搭配 1 支長影片，維持內容深度。

**延伸 idea：**  
【攝影 Vlog】用 Shorts 展示「A7C 一鍵拍出電影感」的 3 個設定，長影片則完整教學如何調整參數與後製。

## 🛂 Immigration

### 🇦🇺 Australia Immigration
> `2026-05-05 08:40:09`

- [PSA Reddit Mod Account Compromised](https://www.reddit.com/r/AusVisa/comments/1sp17tm/psa_reddit_mod_account_compromised/)
- [April 2026 Mega Thread](https://www.reddit.com/r/AusVisa/comments/1s9xabb/april_2026_mega_thread/)
- [VIC SC 190 Granted - ICT Security Specialist](https://www.reddit.com/r/AusVisa/comments/1t3emhm/vic_sc_190_granted_ict_security_specialist/)
- [Need help! 485 visa to PR (law background) and completely lost!](https://www.reddit.com/r/AusVisa/comments/1t3vqqh/need_help_485_visa_to_pr_law_background_and/)
- [DIY 491](https://www.reddit.com/r/AusVisa/comments/1t3y4yl/diy_491/)
