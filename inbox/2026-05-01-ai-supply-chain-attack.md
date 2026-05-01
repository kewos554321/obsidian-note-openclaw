---
date: 2026-05-01
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "savings_travel", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube", "immigration_au"]
---

# Daily Digest — 2026-05-01

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

1. **⚠️ Critical PyTorch Lightning supply chain attack** — Malicious dependency "Shai-Hulud" found targeting AI/ML pipelines. **Immediately audit your ML project dependencies.** ([source](https://semgrep.dev/blog/2026/malicious-dependency-in-pytorch-lightning-used-for-ai-training/))
2. **📈 Google (GOOGL) surged +9.96% to $384.80** — Standout AI/cloud earnings mover. Meanwhile Meta dropped -8.55% and NVDA fell -4.63%. Rotation happening.
3. **🛡️ LLM fine-tuning can reactivate copyrighted book memorization** — "Alignment Whack-a-Mole" research shows safety alignment can be undone. Critical for anyone fine-tuning on proprietary data. ([source](https://github.com/cauchy221/Alignment-Whack-a-Mole-Code))
4. **🌍 Oil prices surge on potential US strikes on Iran** — Crude hit highest since 2022. Watch for inflation ripple effects on tech stocks and travel costs. ([BBC](https://www.bbc.com/news/articles/cx21m88rd14o))
5. **✈️ May flight deals active** — Japan mid-May cheapest post-Golden Week (NT$3,000-5,000 one-way); Australia off-peak (NT$8,000-10,000 round-trip); Egypt low season (under NT$20,000).

---

- 💻 Tech: PyTorch Lightning supply chain attack + LLM alignment vulnerability + Claude Code pricing quirk on "OpenClaw" commits
- 🤖 AI 公司動態: Tesla mixed — Aurora autonomous freight deal positive, but Tesla worst S&P 500 performer in April
- 🔵 Google 動態: Gemini Embedding 2 GA (multimodal RAG), Agents CLI launched, LiteRT + NPU on-device AI guide
- 📈 Markets: US bullish (+0.98% S&P 500) but Taiwan (-0.96%) and Japan (-1.06%) under pressure
- 🏠 台灣房市: 兩極化格局 — 高總價冷、低總價熱；建議鎖定新北淡水、桃園龍潭低總價區
- 📊 Watchlist: GOOGL +9.96% standout; META -8.55% worst; AMD +5.16%, Arm +5.87% strong
- 🌍 World News: Suu Kyi house arrest, oil surge on Iran strike reports, Israeli strikes on Lebanon, Gaza flotilla intercepted
- 📷 Camera Deals: 母親節檔期開跑 — Sony A7C II / Canon R8 combo deals on PChome; vlogging cameras 10-15% off
- 🤿 Dive Gear: 母親節潛水特惠 (May 5-12) — buy dive computer get free service; check 墾丁潛水器材行
- ✈️ Flight Tips: Japan mid-May cheapest; Thailand low season under NT$4,000; Australia off-peak NT$8,000-10,000
- 🗺️ Travel Deals: Thailand & Vietnam first-timer friendly ($40-60/day); Eastern Europe safe for solo ($50-70/day)
- 📚 Learning — Finance: P/B ratio explained — below 1.0 signals potential undervaluation but investigate risks
- 🧩 LeetCode Blind 100: Reverse Nodes in K-Group — classic linked list reversal with recursion; O(n) time
- 📷 Learning — Photography: Sony A7C custom button setup — map C1 to Focus Mode, C2 to ISO for faster shooting
- 📚 Learning — Tech: Observability (metrics + logs + traces) vs monitoring — traces tell you *why* something is wrong
- 🎬 Learning — YouTube: Descript AI video editing — delete text = delete video; keep 0.5-1s pauses for natural flow
- 🇦🇺 Australia Immigration: VIC 190 round active; 462 visa strict age limit (under 31); check April 2026 mega thread for processing times

---

## 💻 Tech

### 💻 Tech & AI
> `2026-05-01 07:50:22`

#### Hacker News
- [CopyFail was not disclosed to distro developers?](https://www.openwall.com/lists/oss-security/2026/04/30/10) ⭐320
- [Shai-Hulud Themed Malware Found in the PyTorch Lightning AI Training Library](https://semgrep.dev/blog/2026/malicious-dependency-in-pytorch-lightning-used-for-ai-training/) ⭐302
- [Claude Code refuses requests or charges extra if your commits mention "OpenClaw"](https://twitter.com/theo/status/2049645973350363168) ⭐891
- [Show HN: Pu.sh – a full coding-agent harness in 400 lines of shell](https://pu.dev/) ⭐56
- [Spain's parliament will act against massive IP blockages by LaLiga](https://www.democrata.es/en/politics/congress-and-senate/congress-will-act-against-massive-ip-blockages-by-laliga/) ⭐386
- [AI discovery reveals DNA isn’t locked away in cells after all](https://gladstone.org/news/ai-discovery-reveals-dna-isnt-locked-away-cells-after-all) ⭐4
- [1.4 GW: battery storage at former Grohnde nuclear power plant](https://www.heise.de/en/news/1-4-GW-Huge-battery-storage-at-former-Grohnde-nuclear-power-plant-11277367.html) ⭐49
- [The Human Creativity Benchmark – Evaluating Generative AI in Creative Work](https://contralabs.com/research/human-creativity-benchmark) ⭐16
- [What can we gain by losing infinity?](https://www.quantamagazine.org/what-can-we-gain-by-losing-infinity-20260429/) ⭐94
- [Alignment whack-a-mole: Finetuning activates recall of copyrighted books in LLMs](https://github.com/cauchy221/Alignment-Whack-a-Mole-Code) ⭐187

#### HuggingFace
- [Sample Selection Using Multi-Task Autoencoders in Federated Learning with Non-IID Data](https://huggingface.co/papers/2604.26116)
- [Enhanced Privacy and Communication Efficiency in Non-IID Federated Learning with Adaptive Quantization and Differential Privacy](https://huggingface.co/papers/2604.23426)
- [FAMA: Failure-Aware Meta-Agentic Framework for Open-Source LLMs in Interactive Tool Use Environments](https://huggingface.co/papers/2604.25135)
- [Operating-Layer Controls for Onchain Language-Model Agents Under Real Capital](https://huggingface.co/papers/2604.26091)
- [Praxy Voice: Voice-Prompt Recovery + BUPS for Commercial-Class Indic TTS from a Frozen Non-Indic Base at Zero Commercial-Training-Data Cost](https://huggingface.co/papers/2604.25441)
- [PSP: An Interpretable Per-Dimension Accent Benchmark for Indic Text-to-Speech](https://huggingface.co/papers/2604.25476)

#### ArXiv
- [Turning the TIDE: Cross-Architecture Distillation for Diffusion Large Language Models](http://arxiv.org/abs/2604.26951v1)
- [Hyper Input Convex Neural Networks for Shape Constrained Learning and Optimal Transport](http://arxiv.org/abs/2604.26942v1)
- [Select to Think: Unlocking SLM Potential with Local Sufficiency](http://arxiv.org/abs/2604.26940v1)
- [Learning Over-Relaxation Policies for ADMM with Convergence Guarantees](http://arxiv.org/abs/2604.26932v1)
- [A Note on How to Remove the $\ln\ln T$ Term from the Squint Bound](http://arxiv.org/abs/2604.26926v1)
- [ClassEval-Pro: A Cross-Domain Benchmark for Class-Level Code Generation](http://arxiv.org/abs/2604.26923v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-05-01 07:50:38`

#### Tesla
- [Stock Market Today, April 30: Aurora Innovation Jumps on Hirschbach’s 500-Truck Autonomous Freight Plan](https://finance.yahoo.com/m/3c0bb778-2f5a-3823-9b19-4e8ca566f4e4/stock-market-today%2C-april-30%3A.html)
- [Elon Musk reportedly labels most cryptocurrencies as 'scams'](https://finance.yahoo.com/m/a772ee5c-4d42-3554-aa45-8cc54fb1fe35/elon-musk-reportedly-labels.html)
- [Tesla Stock Is Outrageously Cheap. Here's Why There Could Be Another 100% in Upside Potential.](https://finance.yahoo.com/m/a4006a89-892f-32d6-9895-cc14902731ce/tesla-stock-is-outrageously.html)
- [These Were the Best and Worst S&P 500 Stocks in April](https://finance.yahoo.com/m/082e2a57-2300-3196-8e65-10b3a98017d4/these-were-the-best-and-worst.html)

### 🔵 Google 動態
> `2026-05-01 07:50:30`

#### Google AI Blog
- [Celebrating 20 years of Google Translate: Fun facts, tips and new features to try](https://blog.google/products-and-platforms/products/translate/fun-facts-google-translate-20-years/)
- [Join the new AI Agents Vibe Coding Course from Google and Kaggle](https://blog.google/innovation-and-ai/technology/developers-tools/kaggle-genai-intensive-course-vibe-coding-june-2026/)
- [8 Gemini tips for organizing your space (and life)](https://blog.google/products-and-platforms/products/gemini/gemini-spring-cleaning-tips/)
- [Here’s how our TPUs power increasingly demanding AI workloads.](https://blog.google/innovation-and-ai/infrastructure-and-cloud/google-cloud/what-is-a-tpu/)
- [Elevating Austria: Google invests in its first data center in the Alps.](https://blog.google/innovation-and-ai/infrastructure-and-cloud/global-network/google-data-center-austria/)
#### Google Blog
- [Your car with Google built-in is about to get smarter, thanks to Gemini](https://blog.google/products-and-platforms/platforms/android/cars-with-google-built-in-gemini-tips-2026/)
- [Check out the new ways to explore Route 66 on Google Maps.](https://blog.google/products-and-platforms/products/maps/route-66/)
- [Preferred Sources is now available in all languages.](https://blog.google/products-and-platforms/products/search/preferred-sources-language-expansion/)
- [Adapt your Shopping campaigns to modern Search with AI Max.](https://blog.google/products/ads-commerce/ai-max-for-shopping/)
- [Meet travelers in the moments that matter with Search Campaigns for Travel.](https://blog.google/products/ads-commerce/ai-max-for-travel/)
#### Google Developers
- [Building with Gemini Embedding 2: Agentic multimodal RAG and beyond](https://developers.googleblog.com/building-with-gemini-embedding-2/)
- [Speeding Up AI: Bringing Google Colossus to PyTorch via GCSFS and Rapid Bucket](https://developers.googleblog.com/speeding-up-ai-bringing-google-colossus-to-pytorch-via-gcsfs-and-rapid-bucket/)
- [Building real-world on-device AI with LiteRT and NPU](https://developers.googleblog.com/building-real-world-on-device-ai-with-litert-and-npu/)
- [Agents CLI in Agent Platform:  create to production in one CLI](https://developers.googleblog.com/agents-cli-in-agent-platform-create-to-production-in-one-cli/)
- [Production-Ready AI Agents: 5 Lessons from Refactoring a Monolith](https://developers.googleblog.com/production-ready-ai-agents-5-lessons-from-refactoring-a-monolith/)

## 📈 Finance

### 📈 Markets Overview
> `2026-05-01 08:00:04`

#### Indices
- S&P 500: 7,209.01 ▲0.98%
- 台股加權: 38,926.63 ▼0.96%
- 日經 225: 59,284.92 ▼1.06%

### 🏠 台灣房市
> `2026-05-01 08:01:25`

#### AI 分析
#### 台灣房市分析報告 (2026-05-01)

1. **整體趨勢**：市場呈現「高總價冷、低總價熱」的兩極化格局。高總價住宅成交單價持續創高（如台北市住宅大樓單價達54.8萬/坪），但交易量縮；低總價小套房及中南部物件掛牌活躍，反映自住與收租需求仍穩健。

2. **值得注意的地區與物件**：
   - **台北市大同區**：延平北路、重慶北路一帶套房與住家釋出，鄰近商圈與捷運，具都更題材，適合長期持有。
   - **高雄仁武、鳳山**：套房租金投報率相對北部高（約3-4%），且可寵物物件增加，吸引年輕租客。
   - **台中太平、北區**：平房式套房與可租補物件增多，反映首購族與學生租屋需求強勁。

3. **自住建議**：優先鎖定**新北淡水、桃園龍潭**等低總價區（如摩天31套房），通勤時間可接受且生活機能成熟，議價空間約5-10%。

4. **投資建議**：避開高總價豪宅（單價>40萬/坪），轉向**中南部低總價套房**（總價300-600萬），搭配可寵、可租補等條件提升出租率，年化報酬率可達3.5%以上。

5. **風險提示**：注意央行選擇性信用管制對多戶貸款成數限制，以及營建成本高漲可能壓縮新案利潤，建議避開預售屋轉約物件。

#### 591 最新
- [台北市大同區延平北路四段73巷近民族西路溫馨住家首選](https://rent.591.com.tw/rent-detail-19283015.html)
- [桃園市龍潭區中興路63巷804旁独立美大套房](https://rent.591.com.tw/rent-detail-21167005.html)
- [台中市太平區光德路390巷平房式獨立套房](https://rent.591.com.tw/rent-detail-21167003.html)
- [台北市大同區重慶北路二段6巷☀️寧夏夜市💕全新套房🐈獨洗可寵✅可租補](https://rent.591.com.tw/rent-detail-21167001.html)
- [新北市淡水區中山北路一段鋼骨結構－摩天31獨立套房含管理費](https://rent.591.com.tw/rent-detail-21166999.html)
- [高雄市仁武區八德中路仁武八德中路3樓套房（可寵物）](https://rent.591.com.tw/rent-detail-21167000.html)
- [台中市北區五權路❤台電❤可租補❤可寵❤多間可選❤近一中商圈](https://rent.591.com.tw/rent-detail-21166998.html)
- [高雄市鳳山區過勇路《鳳山套房出租》](https://rent.591.com.tw/rent-detail-21166996.html)

#### 實價登錄 (115S1) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 住宅大樓(11層含以上有電梯) | 382.2㎡ | 18305萬 | 548016元/㎡ |
|  | 透天厝 | 338.8㎡ | 10600萬 | 312848元/㎡ |
|  | 其他 | 0.0㎡ | 9954萬 | 1480149元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 222.3㎡ | 9028萬 | 406100元/㎡ |
|  | 其他 | 0.0㎡ | 8300萬 | 360870元/㎡ |

### 📊 Watchlist
> `2026-05-01 08:00:45`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 199.57 ▼4.63% |
| Market Cap | $4.85T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 71.1% / 60.4% / 55.6% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 30.84 |
| Beta | 2.33 |
| 52-Week | 110.82 – 216.83 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures Rise As Apple Jumps On Earnings, Sandisk Skids; Stock Market At High](https://finance.yahoo.com/m/c0df32c8-866d-379a-9315-203c3bff518e/dow-jones-futures-rise-as.html) — Investor's Business Daily
- [Is NVIDIA Corporation (NVDA) Among the Best Data Center Hardware Stocks?](https://finance.yahoo.com/markets/stocks/articles/nvidia-corporation-nvda-among-best-234753823.html) — Insider Monkey
- [1 Reason Apple Is Still My Favorite Stock I'd Hand Down to My Grandkids](https://finance.yahoo.com/m/b9959b93-0d32-3ee3-a9e1-450539dc8531/1-reason-apple-is-still-my.html) — Motley Fool

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 354.49 ▲5.16% |
| Market Cap | $577.96B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 49.5% / 10.7% / 12.5% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 9.17 |
| Beta | 1.96 |
| 52-Week | 96.45 – 354.96 |
| Div. Yield | — |

**Recent News:**
- [Is Advanced Micro Devices, Inc. (AMD) one of the Best Data Center Hardware Stocks?](https://finance.yahoo.com/markets/stocks/articles/advanced-micro-devices-inc-amd-234740206.html) — Insider Monkey
- [CHAI AI, Backed by CoreWeave and AMD, Hits $80M ARR with talks of $2.4B Valuation](https://finance.yahoo.com/sectors/technology/articles/chai-ai-backed-coreweave-amd-232800936.html) — PR Newswire
- [These Were the Best and Worst S&P 500 Stocks in April](https://finance.yahoo.com/m/082e2a57-2300-3196-8e65-10b3a98017d4/these-were-the-best-and-worst.html) — Barrons.com

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 407.78 ▼3.93% |
| Market Cap | $3.03T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 68.3% / 46.8% / 39.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 7.31 |
| Beta | 1.11 |
| 52-Week | 356.28 – 555.45 |
| Div. Yield | — |

**Recent News:**
- [Five9 Q1 Earnings Call Highlights](https://finance.yahoo.com/m/d0014e5a-333c-3b61-8264-2fec42941b74/five9-q1-earnings-call.html) — MarketBeat
- [Microsoft's CEO Satya Nadella Signals AI Boom Must Prove Its Value — and Healthcare Could be the Ultimate Test Case](https://finance.yahoo.com/sectors/healthcare/articles/microsofts-ceo-satya-nadella-signals-230107764.html) — Benzinga
- [Microsoft (MSFT) – Among the 10 Innovative Dividend Stocks to Buy Right Now](https://finance.yahoo.com/markets/stocks/articles/microsoft-msft-among-10-innovative-224320892.html) — Insider Monkey

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 384.80 ▲9.96% |
| Market Cap | $4.66T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.4% / 32.7% / 37.9% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 9.72 |
| Beta | 1.13 |
| 52-Week | 147.84 – 385.83 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures Rise As Apple Jumps On Earnings, Sandisk Skids; Stock Market At High](https://finance.yahoo.com/m/c0df32c8-866d-379a-9315-203c3bff518e/dow-jones-futures-rise-as.html) — Investor's Business Daily
- [FIDO Alliance Announces Agenda for Authenticate APAC 2026](https://finance.yahoo.com/sectors/technology/articles/fido-alliance-announces-agenda-authenticate-234300485.html) — Business Wire
- [Stock Market Today, April 30: Aurora Innovation Jumps on Hirschbach’s 500-Truck Autonomous Freight Plan](https://finance.yahoo.com/m/3c0bb778-2f5a-3823-9b19-4e8ca566f4e4/stock-market-today%2C-april-30%3A.html) — Motley Fool

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 265.06 ▲0.77% |
| Market Cap | $2.85T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 50.6% / 11.5% / 12.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.44 |
| Beta | 1.38 |
| 52-Week | 183.85 – 273.87 |
| Div. Yield | — |

**Recent News:**
- [Trump Says Amazon Considering 'Apprentice' Reboot, With Son as Host](https://finance.yahoo.com/markets/stocks/articles/trump-says-amazon-considering-apos-230357496.html) — MT Newswires
- [Everyone's Wondering What's Next for Nvidia. This News From Amazon and Alphabet Offers Us an Idea That's Strikingly Clear](https://finance.yahoo.com/m/edd13638-d9e2-33b5-92c5-067df248a788/everyone%27s-wondering-what%27s.html) — Motley Fool
- [Constellation Energy Stock Jumps on AI Boom. Why Power Producers Will Gain.](https://finance.yahoo.com/m/e36aafc1-e5a4-3930-b1db-7326d5768a77/constellation-energy-stock.html) — Barrons.com

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 611.91 ▼8.55% |
| Market Cap | $1.55T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.9% / 41.2% / 32.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.36 |
| Beta | 1.31 |
| 52-Week | 520.26 – 796.25 |
| Div. Yield | — |

**Recent News:**
- [Ex-PayPal president unveils bullish Bitcoin target](https://finance.yahoo.com/m/36523b3c-3cde-34d1-ac52-c9a9f5df269f/ex-paypal-president-unveils.html) — TheStreet
- [Coastal Pay Launches SignUp Link—Two-Minute, Friction-Free Merchant Onboarding for Retail and E-Commerce](https://finance.yahoo.com/markets/stocks/articles/coastal-pay-launches-signup-two-230600253.html) — GlobeNewswire
- [Everyone's Wondering What's Next for Nvidia. This News From Amazon and Alphabet Offers Us an Idea That's Strikingly Clear](https://finance.yahoo.com/m/edd13638-d9e2-33b5-92c5-067df248a788/everyone%27s-wondering-what%27s.html) — Motley Fool

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 417.43 ▲4.40% |
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
- [Meta Sells $25 Billion of Debt as Investor Worry, Fatigue Builds](https://finance.yahoo.com/markets/stocks/articles/meta-looks-raise-much-25-140755006.html) — Bloomberg
- [Data-Center Capex Hikes Positive For These AI Stocks](https://finance.yahoo.com/m/0ca0ccde-957d-3768-be5f-0e38b3311280/data-center-capex-hikes.html) — Investor's Business Daily
- [Buy AMD Stock Before Q1 Earnings: Here's What You Should Know](https://finance.yahoo.com/markets/stocks/articles/buy-amd-stock-q1-earnings-172100590.html) — Zacks

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 210.32 ▲5.87% |
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
- [Jim Cramer Says “Corning Flew Too Close and Had Its Icarus Moment”](https://finance.yahoo.com/markets/stocks/articles/jim-cramer-says-corning-flew-191750330.html) — Insider Monkey
- [Arm’s May 6 Earnings Could Unlock $250 as AI Workloads Accelerate](https://finance.yahoo.com/m/ac8ed2bc-4028-3770-92da-fb5d825b74f8/arm%E2%80%99s-may-6-earnings-could.html) — 24/7 Wall St.
- [TSMC Exit And OpenAI Concerns Test Arm’s AI Valuation Story](https://finance.yahoo.com/markets/stocks/articles/tsmc-exit-openai-concerns-test-110639062.html) — Simply Wall St.

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 139.11 ▲0.83% |
| Market Cap | $318.77B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 82.4% / 31.6% / 36.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 44.95 |
| Beta | 1.67 |
| 52-Week | 105.32 – 207.52 |
| Div. Yield | — |

**Recent News:**
- [With Trump's $1.5 Trillion Defense Budget, Palantir Looks Less Like a "Story Stock" and More Like a Strategic Vendor](https://finance.yahoo.com/m/eead434a-20fd-3c9f-a453-9f660fc8d8d8/with-trump%27s-%241.5-trillion.html) — Motley Fool
- [Will Top-Line Improvement Benefit Palantir in Q1 Earnings?](https://finance.yahoo.com/markets/stocks/articles/top-line-improvement-benefit-palantir-181100810.html) — Zacks
- [Palantir Seen Benefiting From AI Platform Strength, Defense Spending, Commercial Growth, Oppenheimer Says](https://finance.yahoo.com/sectors/technology/articles/palantir-seen-benefiting-ai-platform-175850335.html) — MT Newswires

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 27.40 ▲0.55% |
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
- [JPMorgan Maintains a Neutral Rating on Super Micro Computer, Inc. (SMCI)](https://finance.yahoo.com/markets/stocks/articles/jpmorgan-maintains-neutral-rating-super-234733865.html) — Insider Monkey
- [Super Micro Computer Climbs 25% in April: 3 Reasons SMCI Is the Tech Sector’s Comeback Kid](https://finance.yahoo.com/m/09cbb55d-bcb5-3585-90b2-59f31c84b22e/super-micro-computer-climbs.html) — 24/7 Wall St.
- [Nvidia Stock Investors Just Got Major News From China](https://finance.yahoo.com/markets/stocks/articles/nvidia-stock-investors-just-got-141720598.html) — GuruFocus.com

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 381.63 ▲2.37% |
| Market Cap | $1.43T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.1% / 5.0% / 4.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 14.67 |
| Beta | 1.92 |
| 52-Week | 271.00 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Stock Market Today, April 30: Aurora Innovation Jumps on Hirschbach’s 500-Truck Autonomous Freight Plan](https://finance.yahoo.com/m/3c0bb778-2f5a-3823-9b19-4e8ca566f4e4/stock-market-today%2C-april-30%3A.html) — Motley Fool
- [Elon Musk reportedly labels most cryptocurrencies as 'scams'](https://finance.yahoo.com/m/a772ee5c-4d42-3554-aa45-8cc54fb1fe35/elon-musk-reportedly-labels.html) — TheStreet
- [Tesla Stock Is Outrageously Cheap. Here's Why There Could Be Another 100% in Upside Potential.](https://finance.yahoo.com/m/a4006a89-892f-32d6-9895-cc14902731ce/tesla-stock-is-outrageously.html) — Motley Fool

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 660.58 ▲0.97% |
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
- [1 Vanguard ETF to Buy Every Time the Market Dips](https://finance.yahoo.com/m/ee8a4693-7118-30fd-9325-729c895d9a85/1-vanguard-etf-to-buy-every.html) — Motley Fool
- [8 Microcap Stocks Pick Up A Head Of Steam For Enormous Gains](https://finance.yahoo.com/m/ad2bed74-a89a-3ddc-ba3f-f2099c506e24/8-microcap-stocks-pick-up-a.html) — Investor's Business Daily
- [VTI or VOO: Which Vanguard ETF Should You Buy During a Market Sell-Off?](https://finance.yahoo.com/m/b53f45ba-3389-3eaa-9d11-122856f4799e/vti-or-voo%3A-which-vanguard.html) — Motley Fool

## 🌍 News

### 🌍 World News
> `2026-05-01 08:10:06`

- [Myanmar ex-leader Aung San Suu Kyi moved to house arrest, military says](https://www.bbc.com/news/articles/cz72j8eex4eo?at_medium=RSS&at_campaign=rss)
- [Oil price hits highest since 2022 after report Trump to be briefed on new Iran options](https://www.bbc.com/news/articles/cx21m88rd14o?at_medium=RSS&at_campaign=rss)
- [US House votes to end record shutdown over immigration enforcement](https://www.bbc.com/news/articles/ce3pw5x3z54o?at_medium=RSS&at_campaign=rss)
- [Deadly Israeli strikes on southern Lebanon despite ceasefire](https://www.bbc.com/news/articles/cq5pepj21g8o?at_medium=RSS&at_campaign=rss)
- [Trump says US studying troop cuts in Germany, as spat with Merz intensifies](https://www.bbc.com/news/articles/clyplg23l30o?at_medium=RSS&at_campaign=rss)
- [Belgium plans to nationalise nuclear power plants](https://www.bbc.com/news/articles/c4g05jg87wko?at_medium=RSS&at_campaign=rss)
- [Britney Spears charged in California with driving under influence](https://www.bbc.com/news/articles/clyp6r9dzedo?at_medium=RSS&at_campaign=rss)
- [Israel intercepts Gaza flotilla near Crete and detains 175 activists](https://www.bbc.com/news/articles/c4g4lk9m77vo?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-05-01 08:20:24`

#### AI Tips
Here’s your **Taiwan photography expert & deals advisor** briefing for **2026-05-01**.

---

## 🛒 購買優惠 (Deals & Shopping Advice)

#### Best places to buy camera gear in Taiwan right now

| Channel | Best for | Note |
|---------|----------|------|
| **PChome 24h** | New gear, fast delivery, credit card rebates | Today (5/1) is **勞動節** – many stores run **限時加碼回饋** (extra 5–8% P幣). Check for **Sony A7C II / Canon R8** combo deals. |
| **momo購物** | Lenses, tripods, bags | Often has **滿萬送千** (NT$1,000 off every NT$10,000) on camera accessories. Use **momo卡** for 5% back. |
| **光華商場 (Guanghua Digital Plaza)** | Used / grey market / cash price | Go **in person** – negotiate hard. Today many shops open but quieter (holiday). Good for **Sony FE 24-70 GM II** or **Fujifilm X100VI** (if you can find stock). |
| **日本代購 (Japan proxy)** | High-end lenses, limited editions | Yen is weak. **Map Camera / Yodobashi** online + Buyee/Tenso. Shipping 7–10 days. Best for **Nikon Z 28-400mm** or **Leica Q3**. |
| **二手 (Used)** | Budget bodies, vintage glass | Check **DCView二手市集** & **蝦皮拍賣** (filter by 評價>100). Today many sellers offer 5/1 holiday discounts. |

#### 🎯 Seasonal Sale Tip for May

**May is “母親節檔期” (Mother’s Day campaign)** – the biggest camera sale window before 618/雙11.

- **PChome & momo** will have **“母親節禮物專區”** from now until mid-May.
- **Best bet**: Vlogging cameras (Sony ZV-E10 II, DJI Osmo Pocket 3) and **instant cameras** (Fujifilm Instax) are often discounted 10–15%.
- **Pro tip**: Don’t buy memory

#### r/photomarket
- [PSA: Turn on ‘Persistent Messaging’ when using Chats](https://www.reddit.com/r/photomarket/comments/1mboakg/psa_turn_on_persistent_messaging_when_using_chats/)
- [PSA: AI timestamp photos and how not to get scammed](https://www.reddit.com/r/photomarket/comments/1nkg9v6/psa_ai_timestamp_photos_and_how_not_to_get_scammed/)
- [[S] [USA-OR] Fujifilm GF670](https://www.reddit.com/r/photomarket/comments/1t03za8/s_usaor_fujifilm_gf670/)
- [[S] [USA-CA] Leica M262 + Voigtlander 28mm 2.8](https://www.reddit.com/r/photomarket/comments/1t08j7c/s_usaca_leica_m262_voigtlander_28mm_28/)
- [[S][USA-HI] REDUCED PRICED!! Lumix S1ii, S9, Sigma 16-28mm f2.8](https://www.reddit.com/r/photomarket/comments/1t07ymi/susahi_reduced_priced_lumix_s1ii_s9_sigma_1628mm/)

### 🤿 Dive Gear Deals
> `2026-05-01 08:20:31`

#### AI Tips
Here’s a specific, actionable guide tailored for Taiwan divers in **May 2026**.

---

#### 【購買優惠】Best Places & May Seasonal Tips

**1. Top 3 Places to Buy in Taiwan (May 2026)**
- **實體店 (Dive Shops):**  
  *台北*: **內湖潛水** (Neihu) – Great for high-end regulators & computers.  
  *墾丁*: **墾丁潛水器材行** (Kenting) – Best for masks, fins, and wetsuits if you’re heading south.  
  *台中*: **潛水者之家** (Diver’s Home) – Solid for BCDs and tanks.
- **Online (Taiwan):**  
  **PChome 24h / 蝦皮商城** – Search for “潛水裝備 2026新款”. Filter by “商城” (official stores) to avoid counterfeits.  
- **Facebook 社團 (Groups):**  
  Join **「台灣潛水裝備二手交流」** and **「潛水人跳蚤市場」**. May is when divers upgrade gear before summer peak – you can find barely-used gear at 50-60% retail.

**2. May Seasonal Sale Tips & Diving Notes**
- **May Sale Tip:**  
  Many shops run **「母親節潛水特惠」** (Mother’s Day Dive Sale) around the 2nd week of May. Look for **“買電腦錶送保養”** (buy a dive computer, get free service) or **“防寒衣第二件半價”** (2nd wetsuit half off).  
  *Action:* Check **墾丁潛水器材行** and **台北潛水倉庫** websites on **May 5–12**.
- **Diving Season Note (Tai

#### r/scuba
- [BCD Sizing Question](https://www.reddit.com/r/scuba/comments/1szvzp9/bcd_sizing_question/)
- [Thanks for making me choose BPW instead of regular bcd](https://www.reddit.com/r/scuba/comments/1syxte3/thanks_for_making_me_choose_bpw_instead_of/)
- [Alternate JJCCR regulators](https://www.reddit.com/r/scuba/comments/1szbmad/alternate_jjccr_regulators/)
- [Need help with buying Apex regulator](https://www.reddit.com/r/scuba/comments/1syufcf/need_help_with_buying_apex_regulator/)

### ✈️ Flight Tips
> `2026-05-01 08:20:16`

#### AI Flight Tips — May
Here’s your May 2026 flight deal guide from Taiwan (TPE/TSA):

**Japan (Tokyo/Osaka/Sapporo)**  
- **May is shoulder season** (post-Golden Week, pre-summer); mid-May is cheapest.  
- **Book 6–8 weeks ahead**; low-cost carriers like **Peach, Jetstar Japan, or AirAsia X** (via KIX) often have NT$3,000–5,000 one-way deals.  
- **Watch for “Happy Peach” sales** (every Tuesday/Wednesday) and **Scoot’s “Flash Sale”** — Sapporo routes sometimes drop to NT$4,500 round-trip.

**Thailand (Bangkok/Chiang Mai)**  
- **May is low season** (rainy start) — excellent for deals.  
- **Book 4–6 weeks out**; **Thai Lion Air, NokScoot, or AirAsia** routinely offer TPE–BKK round-trip under NT$4,000.  
- **Check AirAsia’s “Big Sale”** (usually mid-month) and **Thai Vietjet’s “0 Baht base fare”** promotions for Chiang Mai.

**Europe (any major city)**  
- **May is peak spring season** — prices high; aim for late May departures.  
- **Book 10–12 weeks ahead**; **China Airlines or EVA via Taipei** with a stop in Bangkok or Dubai can undercut direct flights.  
- **Look for “Turkish Airlines” or “Emirates” flash sales** (often 20–30% off) and **Scoot’s “Europe Sale”** (via Berlin/Athens) for sub-NT$18,000 round-trip.

**USA (West Coast / East Coast)**  
- **May is shoulder season** (pre-summer rush); West Coast cheaper than East.  
- **Book 8–10 weeks out**; **EVA Air or China Airlines** often have TPE–LAX round-trip for NT$18,000–22,000.  
- **Watch for “Cathay Pacific” or “United” stopover deals** (e.g., TPE–HKG–SFO) and **Starlux’s introductory fares** to LAX (sometimes NT$15,000).

**Egypt (Cairo)**  
- **May is low season** (hot but fewer tourists) — good deals.  
- **Book 6–8 weeks ahead**; **Turkish Airlines** (via Istanbul) or **Emirates** (via Dubai) often have round-trip under NT$20,000.  
- **Check “EgyptAir” direct from TPE?** (rare) — instead, search **“Air Arabia”** via Sharjah for budget options (NT$14,000–16,000).

**Australia (Sydney/Melbourne)**  
- **May is off-peak** (autumn/winter) — excellent value.  
- **Book 6–8 weeks out**; **Jetstar, Scoot, or AirAsia X** via KL/GC often have TPE–SYD round-trip for NT$8,000–10,000.  
- **Watch for “Scoot’s “

### 🗺️ Travel Deals
> `2026-05-01 08:20:08`

#### r/solotravel
- [Flights keep getting canceled](https://www.reddit.com/r/solotravel/comments/1syrgl7/flights_keep_getting_canceled/)
- [Thailand and Vietnam in 20 Days – Worth It for a First Solo Trip to Asia?](https://www.reddit.com/r/solotravel/comments/1syvfbh/thailand_and_vietnam_in_20_days_worth_it_for_a/)
- [Solo Travel eastern europe as a Woman - ideas, tips?](https://www.reddit.com/r/solotravel/comments/1sxtc03/solo_travel_eastern_europe_as_a_woman_ideas_tips/)

## 📚 Learning

### 📚 Learning — Finance
> `2026-05-01 08:30:04`

#### 📚 Today's Concept: Price-to-Book (P/B) Ratio

What it is: The Price-to-Book (P/B) ratio compares a company’s stock price to its net asset value per share (assets minus liabilities, divided by shares outstanding). It tells you how much investors are paying for each dollar of the company’s tangible equity on the balance sheet.

Why it matters: It helps identify undervalued stocks, especially in asset-heavy industries like banks, insurance, or real estate. A low P/B can signal a bargain, while a high P/B may indicate overvaluation or reliance on intangible assets.

Example: A bank has $50 billion in assets, $40 billion in liabilities, and 1 billion shares outstanding. Book value per share = ($50B - $40B) / 1B = $10. If the stock trades at $8, P/B = 0.8. Investors pay 80 cents for each dollar of net assets.

Rule of thumb: A P/B below 1.0 often means the market thinks the company’s assets are overstated or its future is poor—investigate for hidden risks like bad loans or obsolete inventory.

### 🧩 LeetCode Blind 100
> `2026-05-01 08:30:10`

#### 🧩 Blind 100 — 25. Reverse Nodes in K-Group [Linked List]
**連結:** https://leetcode.com/problems/reverse-nodes-in-k-group/
> 📅 **Today's Daily Challenge:** #396 Rotate Function [Medium] — Tags: Array, Math, Dynamic Programming — https://leetcode.com/problems/rotate-function/

## 25. Reverse Nodes in K-Group

**Problem Type:** Linked List Manipulation / Recursion

**Key Insight:** Reverse k nodes at a time using pointer manipulation; after reversing a group, the original head becomes the tail, and we need to connect it to the result of recursively reversing the next group.

**Approach:**
1. Count k nodes ahead; if fewer than k remain, return head unchanged
2. Reverse the first k nodes using standard iterative reversal (prev/curr/next pointers)
3. After reversal, original head is now the tail — connect its `next` to recursive result on remaining list
4. Return the new head (which was the kth node before reversal)

**Python3 Solution:**
```python
class Solution:
    def reverseKGroup(self, head: Optional[ListNode], k: int) -> Optional[ListNode]:
        # Check if we have k nodes
        curr = head
        for _ in range(k):
            if not curr:
                return head
            curr = curr.next
        
        # Reverse first k nodes
        prev, curr = None, head
        for _ in range(k):
            nxt = curr.next
            curr.next = prev
            prev = curr
            curr = nxt
        
        # Connect original head (now tail) to next reversed group
        head.next = self.reverseKGroup(curr, k)
        return prev
```

**Complexity:** Time O(n) | Space O(n/k) recursion stack → O(n) worst case

**Blind 100 Note:** Classic linked list reversal pattern with recursion. Tests ability to manipulate pointers under constraints. Similar problems: Reverse Linked List II, Swap Nodes in Pairs, Reverse Nodes in Even Length Groups.

**Contest Tips:**
- **Edge case:** k=1 → no reversal; k > list length → return as-is
- **Python trick:** Use `Optional[ListNode]` type hint for clarity
- **Common mistake:** Forgetting to reconnect the tail (original head) to the next group
- **Optimization:** Can be done iteratively with O(1) space, but recursion is cleaner for contests
- **Dummy node alternative:** Not needed here since we return the new head directly

### 📷 Learning — Photography
> `2026-05-01 08:30:18`

#### 📷 Today's Concept: Sony A7C — Custom Button Setup for Efficient Shooting

**What it is:** Custom button setup remaps the A7C’s programmable buttons (C1, C2, and the trash/delete button) to instantly access your most-used functions. This eliminates menu diving and keeps your eye on the subject.

**Why it matters:** In fast-paced street and portrait work, missing a moment while scrolling menus costs you the shot. A tailored setup speeds up exposure, focus, and white balance adjustments, letting you react instantly.

**How to apply it:**
1. Go to Menu → Camera Settings 2 → Custom Key (shoot mode) → assign C1 to **Focus Mode** (toggle between AF-S and AF-C for portraits vs. street).
2. Assign C2 to **ISO** (hold and scroll front dial) for quick exposure changes in changing light.
3. Set the trash button (bottom left) to **APS-C/Super 35mm** toggle—instantly crop for extra reach in landscapes or street.
4. For video, assign the Movie button’s custom setting to **Picture Profile** (e.g., S-Log3) for cinematic grading.
5. Map the control wheel’s center button to **Focus Area** (spot vs. wide) for precise portrait eye-AF.

**Sony A7C tip:** In Menu → Camera Settings 1 → *DISP Button*, enable “Histogram” and “Level” for real-time exposure and horizon checks in landscape and street.

**Common mistake:** Overloading buttons with rarely used functions (e.g., “Silent Shooting”). *Fix:* Prioritize exposure triangle (ISO, aperture, shutter) and focus—test in a single walk to confirm muscle memory.

### 📚 Learning — Tech
> `2026-05-01 08:30:13`

#### 📚 Today's Concept: Observability: Metrics, Logs, Traces

**What it is:** Observability is the ability to understand a system’s internal state by analyzing its external outputs—specifically metrics, logs, and traces. Metrics are numeric aggregations (e.g., request latency), logs are discrete events (e.g., error messages), and traces follow a request’s path across services.

**When to use it:** Use observability in distributed systems (e.g., microservices) to debug performance bottlenecks or failures. *Real-world scenario:* A user reports slow checkout; you query traces to find a payment service timeout, check metrics for CPU spikes, and read logs for database connection errors.

**Example:**  
```python
# Trace a request with OpenTelemetry
with tracer.start_as_current_span("checkout") as span:
    span.set_attribute("user.id", user_id)
    log.info("Processing payment for user %s", user_id)
    metrics.counter("checkout.attempts").add(1)
```

**Gotcha:** Confusing observability with monitoring—monitoring tells you *if* something is wrong (e.g., alert on high latency), but observability (via traces + logs) tells you *why* it’s wrong. Without distributed tracing, you cannot pinpoint the failing service in a chain.

### 🎬 Learning — YouTube
> `2026-05-01 08:30:22`

#### 🎬 今日主題：AI 剪輯 — Descript：用文字編輯影片的工作流程
**類別：** AI剪輯

**是什麼：**  
Descript 是一款以「文字編輯影片」為核心的 AI 剪輯工具，能自動將語音轉成逐字稿。你只要刪除或修改文字，對應的影片片段就會同步剪掉或調整。

**為什麼重要：**  
對不熟悉剪輯軟體的初學者來說，Descript 大幅降低學習曲線，省去手動對時間軸的繁瑣步驟，讓你專注在內容而非技術。

**怎麼做：**  
1. 上傳影片至 Descript，等待 AI 自動生成逐字稿。  
2. 瀏覽文字稿，直接刪除口頭禪、停頓或錯誤段落，影片會自動剪掉對應畫面。  
3. 使用「Fill in Silence」功能自動移除空白片段，讓節奏更緊湊。  
4. 加入標題、字幕樣式與過場，輸出前用「Export」選擇適合 YouTube 的格式。

**新手常犯的錯：**  
過度依賴 AI 刪除所有停頓，導致影片聽起來不自然。建議保留 0.5-1 秒的呼吸節奏，維持對話流暢感。

**延伸 idea：**  
【攝影 Vlog】用 Descript 剪一支「Sony A7C 一週實拍心得」，先錄製口白介紹優缺點，再用文字稿快速刪除廢話，搭配實拍畫面，輕鬆產出專業感影片。

## 🛂 Immigration

### 🇦🇺 Australia Immigration
> `2026-05-01 08:40:07`

- [PSA Reddit Mod Account Compromised](https://www.reddit.com/r/AusVisa/comments/1sp17tm/psa_reddit_mod_account_compromised/)
- [April 2026 Mega Thread](https://www.reddit.com/r/AusVisa/comments/1s9xabb/april_2026_mega_thread/)
- [VIC 190 round happening today](https://www.reddit.com/r/AusVisa/comments/1t0dzqm/vic_190_round_happening_today/)
- [Visa 190 (VIC, Marketing Specialist) - Granted](https://www.reddit.com/r/AusVisa/comments/1szmvtz/visa_190_vic_marketing_specialist_granted/)
- [Subclass 462 refused due to missed RFI while overseas (now over 31, SG citizen) – any chance of reconsideration?](https://www.reddit.com/r/AusVisa/comments/1t0csdq/subclass_462_refused_due_to_missed_rfi_while/)
