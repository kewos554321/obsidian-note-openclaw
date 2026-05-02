---
date: 2026-05-02
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "savings_travel", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube", "immigration_au"]
---

# Daily Digest — 2026-05-02

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

1. **⚠️ 供應鏈攻擊警報：PyTorch Lightning 發現惡意依賴 "Shai-Hulud"** — 立即審查你的 `requirements.txt` 和 lock files！[詳情](https://semgrep.dev/blog/2026/malicious-dependency-in-pytorch-lightning-used-for-ai-training/)
2. **🚨 Ubuntu 伺服器遭跨國攻擊，已中斷超過一天** — 若依賴 `apt` mirrors 或 Launchpad，請注意服務中斷。[詳情](https://arstechnica.com/security/2026/05/ubuntu-infrastructure-has-been-down-for-more-than-a-day/)
3. **📈 美股強勢上漲，台股逆勢下跌 0.96%** — S&P 500 漲 1.32% 至 7,230，但台股加權指數跌至 38,926，留意國內獲利了結壓力。
4. **🤖 Google Gemini Embedding 2 正式上線** — 支援文字/圖片/影片/音訊多模態 RAG，適合打造智慧搜尋與代理系統。[了解更多](https://developers.googleblog.com/building-with-gemini-embedding-2/)
5. **🇦🇺 澳洲移民新規：收到邀請後不得更新 PTE 成績** — 申請前務必取得最終有效成績，否則將被忽略。[詳情](https://www.reddit.com/r/AusVisa/comments/1t1au8o/can_should_i_update_pte_scores_after_getting/)

---

- 💻 Tech: PyTorch Lightning 供應鏈攻擊、Ubuntu 中斷、Intel AutoRound 量化、NVIDIA 多模態模型、Spotify 驗證徽章
- 🤖 AI 公司動態：Tesla 股價週漲近 4%，FSD 與 Robotaxi 題材帶動；OpenAI/Anthropic 無重大更新
- 🔵 Google 動態：Gemini Embedding 2 GA、Agents CLI、LiteRT 邊緣 AI、Colossus + PyTorch 效能優化、生產級代理架構教戰
- 📈 市場概覽：美股領漲 (S&P +1.32%)，台股逆勢跌 0.96%，日經微漲 0.38%
- 🏠 台灣房市：北溫中南熱，內湖頂加投報 4%、中南部科技園區租賃強勁
- 📊 Watchlist：AVGO (+3.9%)、ARM (+4.71%) 領漲 AI 硬體，NVDA 微跌 0.56%
- 🌍 世界新聞：美削減駐德兵力 5,000、川普稱停火即不需國會授權對伊戰爭、肥料短缺恐影響數十億餐食、澳洲有望首個消滅子宮頸癌、美法院限縮墮胎藥郵購
- 📷 相機優惠：5月母親節檔期 PChome/momo 有銀行加碼，日本黃金週後二手店出清，光華現金價 5-10% off
- 🤿 潛水裝備：5月季前折扣，內湖潛水街出清去年款，墾丁展示品折扣，蝦皮母親節滿額折價
- ✈️ 機票攻略：日本黃金週後價格回落、泰國淡季低價、歐洲旺季需早訂、美西便宜於美東、埃及土耳其航空促銷、澳洲淡季好價
- 🗺️ 旅遊資訊：泰越免簽、每日預算 $30-50 USD、11-2月最佳旅遊季節
- 📚 學習—理財：Short Interest 與 Days to Cover — 高於 10 天可能醞釀軋空
- 🧩 LeetCode：98. Validate Binary Search Tree — 遞迴傳遞 min/max 邊界，O(n) 時間
- 📷 學習—攝影：街拍光影 — 黃金時刻、硬邊光線、點測光、低角度拍攝
- 📚 學習—技術：Vector Database 與 Embeddings — FAISS 範例、RAG 應用、注意語義偏差
- 🎬 學習—YouTube：英雄旅程結構套用 Vlog — 從平凡世界到回歸分享，記錄掙扎才是關鍵
- 🇦🇺

---

## 💻 Tech

### 💻 Tech & AI
> `2026-05-02 07:50:28`

#### Hacker News
- [Eka’s robotic claw feels like we're approaching a ChatGPT moment](https://www.wired.com/story/when-robots-have-their-chatgpt-moment-remember-these-pincers/) ⭐67
- [Show HN: AI CAD Harness](https://fusion.adam.new/install) ⭐54
- [The gay jailbreak technique](https://github.com/Exocija/ZetaLib/blob/main/The%20Gay%20Jailbreak/The%20Gay%20Jailbreak.md) ⭐321
- [AI uses less water than the public thinks](https://californiawaterblog.com/2026/04/26/ai-water-use-distractions-and-lessons-for-california/) ⭐314
- [Spotify adds 'Verified' badges to distinguish human artists from AI](https://www.bbc.com/news/articles/c5yerr4m1yno) ⭐185
- [Ubuntu servers taken offline by "sustained, cross-border attack"](https://arstechnica.com/security/2026/05/ubuntu-infrastructure-has-been-down-for-more-than-a-day/) ⭐91
- [AWS stops billing Middle East cloud customers as repairs to war damage drag on](https://arstechnica.com/gadgets/2026/05/amazon-stuck-with-months-of-repairs-after-drone-strikes-on-data-centers/) ⭐126
- [Advanced Quantization Algorithm for LLMs](https://github.com/intel/auto-round) ⭐115
- [Show HN: Loopsy, a way for terminals and AI agents on different machines to talk](https://github.com/leox255/loopsy) ⭐38
- [Shai-Hulud Themed Malware Found in the PyTorch Lightning AI Training Library](https://semgrep.dev/blog/2026/malicious-dependency-in-pytorch-lightning-used-for-ai-training/) ⭐455

#### HuggingFace
- [Nemotron 3 Nano Omni: Efficient and Open Multimodal Intelligence](https://huggingface.co/papers/2604.24954)
- [Step-level Optimization for Efficient Computer-use Agents](https://huggingface.co/papers/2604.27151)
- [ViPO: Visual Preference Optimization at Scale](https://huggingface.co/papers/2604.24953)
- [Learning from Noisy Preferences: A Semi-Supervised Learning Approach to Direct Preference Optimization](https://huggingface.co/papers/2604.24952)
- [FlashRT: Towards Computationally and Memory Efficient Red-Teaming for Prompt Injection and Knowledge Corruption](https://huggingface.co/papers/2604.28157)
- [Safety Drift After Fine-Tuning: Evidence from High-Stakes Domains](https://huggingface.co/papers/2604.24902)

#### ArXiv
- [Computing Equilibrium beyond Unilateral Deviation](http://arxiv.org/abs/2604.28186v1)
- [Exploration Hacking: Can LLMs Learn to Resist RL Training?](http://arxiv.org/abs/2604.28182v1)
- [Synthetic Computers at Scale for Long-Horizon Productivity Simulation](http://arxiv.org/abs/2604.28181v1)
- [An adaptive wavelet-based PINN for problems with localized high-magnitude source](http://arxiv.org/abs/2604.28180v1)
- [LLM as Clinical Graph Structure Refiner: Enhancing Representation Learning in EEG Seizure Diagnosis](http://arxiv.org/abs/2604.28178v1)
- [Defending Quantum Classifiers against Adversarial Perturbations through Quantum Autoencoders](http://arxiv.org/abs/2604.28176v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-05-02 07:50:41`

#### Tesla
- [Stock Market Today, May 1: Rivian Falls After Investors Focus on Cash Burn Despite Beating Q1 Expectations](https://finance.yahoo.com/m/04799337-4272-3d00-aab1-efc014c812a5/stock-market-today%2C-may-1%3A.html)
- [Tesla ends week nearly 4% higher. What's driving the EV stock?](https://finance.yahoo.com/video/tesla-ends-week-nearly-4-higher-whats-driving-the-ev-stock-210623745.html)
- [NIO Stock Drops. The U.S. Isn’t the Only Country With an EV Problem.](https://finance.yahoo.com/m/5a94db5c-b9f9-3d4d-a546-d8b2a58ed998/nio-stock-drops.-the-u.s..html)
- [What's Going On With Tesla Stock Friday](https://finance.yahoo.com/markets/stocks/articles/whats-going-tesla-stock-friday-202055668.html)

### 🔵 Google 動態
> `2026-05-02 07:50:35`

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
> `2026-05-02 08:00:05`

#### Indices
- S&P 500: 7,230.12 ▲1.32%
- 台股加權: 38,926.63 ▼0.96%
- 日經 225: 59,513.12 ▲0.38%

### 🏠 台灣房市
> `2026-05-02 08:01:24`

#### AI 分析
#### 台灣房市分析 (截至2026-05-02)

1. **整體趨勢**：市場呈現「北溫中南熱」格局，台北市高總價住宅成交動能穩定，但租賃市場以精緻小宅為主；中南部如台中、台南、高雄受惠於科技園區與交通建設，租賃需求強勁，租金補貼物件增多，顯示年輕族群與就業人口外溢效應明顯。

2. **值得注意地區與物件**：
   - **台北市**：信義區永春站旁全新裝修套房、內湖區西湖國小頂加6房（投報率4%），顯示精華地段小坪數與高投報物件仍具吸引力。
   - **新北市**：永和永安捷運旁寧靜套房、三重可申請補助精裝房，反映捷運沿線與補助政策支撐租屋市場。
   - **中南部**：台中清水（近61快速道路）、台南善化（南科LM區）、高雄左營（高鐵特區）均為就業熱區，全新家具家電物件搶手，租金補貼申請率高。

3. **自住建議**：優先選擇捷運沿線、科學園區周邊（如南科、中科）或高鐵特區，可善用租金補貼降低負擔；台北市可鎖定總價2000萬內、有裝修套房，避開高公設比物件。

4. **投資建議**：關注內湖頂加（投報4%）、台中清水與高雄左營新成屋，租金報酬率優於北市；高總價住宅（如實價登錄中1.8億豪宅）流動性較低，建議以長期持有為主，避免短期套利。

5. **風險提醒**：央行選擇性信用管制與升息壓力仍在，高總價物件貸款成數可能受限；中南部租屋市場競爭激烈，需確認區域就業人口成長是否可持續。

#### 591 最新
- [台北市信義區忠孝東路五段423巷近永春站🚈全新裝修☀️採光套房](https://rent.591.com.tw/rent-detail-21173029.html)
- [台北市內湖區環山路一段60巷專約:西湖國小頂加.6房.高投報4%](https://sale.591.com.tw/sale-detail-20128163.html)
- [新北市永和區中和路永安捷運旁寧靜套房](https://rent.591.com.tw/rent-detail-21173024.html)
- [新北市三重區自強路一段可申請補助、可報稅~精緻裝潢有窗戶](https://rent.591.com.tw/rent-detail-21173028.html)
- [台中市清水區港新三路可申請租補@全新家具家電齊全@鄰61快速道路](https://rent.591.com.tw/rent-detail-21173027.html)
- [彰化縣彰化市華山路可租補一房兩房一廳，8500-12600、變頻冷氣近火車站獨](https://rent.591.com.tw/rent-detail-21173022.html)
- [高雄市左營區博愛四路左營高鐵全新層質感三改二房平車美宅-可立即入住](https://rent.591.com.tw/rent-detail-21173023.html)
- [台南市善化區龍目井路善化南科LM春池大樓獨立套房](https://rent.591.com.tw/rent-detail-21173021.html)

#### 實價登錄 (115S1) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 住宅大樓(11層含以上有電梯) | 382.2㎡ | 18305萬 | 548016元/㎡ |
|  | 透天厝 | 338.8㎡ | 10600萬 | 312848元/㎡ |
|  | 其他 | 0.0㎡ | 9954萬 | 1480149元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 222.3㎡ | 9028萬 | 406100元/㎡ |
|  | 其他 | 0.0㎡ | 8300萬 | 360870元/㎡ |

### 📊 Watchlist
> `2026-05-02 08:00:46`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 198.45 ▼0.56% |
| Market Cap | $4.82T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 71.1% / 60.4% / 55.6% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 30.66 |
| Beta | 2.33 |
| 52-Week | 110.82 – 216.83 |
| Div. Yield | — |

**Recent News:**
- [Data Center Demand Drove Vertiv's Earnings up 83%, but Is This AI Infrastructure Play Worth its Lofy Valuation?](https://finance.yahoo.com/m/f4aae1a1-24ec-3835-9382-6bb52206e19a/data-center-demand-drove.html) — Motley Fool
- [The Memory Supercycle Is Back in Motion — and Samsung and SK Hynix May Be the Stocks With the Most Torque](https://finance.yahoo.com/m/df75acef-c42f-3234-9f69-4943a906f672/the-memory-supercycle-is-back.html) — 24/7 Wall St.
- [1 Overlooked Detail to Watch as NuScale's SMR Project Moves Forward](https://finance.yahoo.com/m/d2c82bcb-cc93-3e07-988f-b1e538e96b69/1-overlooked-detail-to-watch.html) — Motley Fool

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 360.54 ▲1.71% |
| Market Cap | $587.83B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 49.5% / 10.7% / 12.5% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 9.33 |
| Beta | 1.96 |
| 52-Week | 96.88 – 362.79 |
| Div. Yield | — |

**Recent News:**
- [AMD earnings, Fed commentary, April jobs report: What to Watch](https://finance.yahoo.com/video/amd-earnings-fed-commentary-april-230000206.html) — Yahoo Finance Video
- [Dow Jones Futures: Stock Market Hits Highs After Bullish Pause; Apple, Broadcom In Buy Zones](https://finance.yahoo.com/m/cfdf164e-e24a-366b-9d8b-b0274f05ba94/dow-jones-futures%3A-stock.html) — Investor's Business Daily
- [Jobs Report, Berkshire Annual Meeting: What to Watch in the Next Week](https://finance.yahoo.com/m/2307a382-5e3f-31c9-86be-bdae1b2f5aae/jobs-report%2C-berkshire-annual.html) — The Wall Street Journal

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 414.44 ▲1.63% |
| Market Cap | $3.08T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 68.3% / 46.8% / 39.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 7.43 |
| Beta | 1.11 |
| 52-Week | 356.28 – 555.45 |
| Div. Yield | — |

**Recent News:**
- [Stock Market Today, May 1: Apple Jumps After Record Quarter and $100 Billion Share Buyback](https://finance.yahoo.com/m/37c8d4bb-9f6b-3d9b-aaad-cb887e9cb473/stock-market-today%2C-may-1%3A.html) — Motley Fool
- [PayPal Store Sync Links BigCommerce Merchants To AI Shopping And Valuation Story](https://finance.yahoo.com/markets/stocks/articles/paypal-store-sync-links-bigcommerce-221747770.html) — Simply Wall St.
- [U.S. Dips Into Oil Reserves as Iran War Enters Its Third Month](https://finance.yahoo.com/m/ce9ec5a4-6d23-3352-a419-cc941f794791/u.s.-dips-into-oil-reserves.html) — Barrons.com

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 385.69 ▲0.23% |
| Market Cap | $4.67T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.4% / 32.7% / 37.9% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 9.75 |
| Beta | 1.13 |
| 52-Week | 147.84 – 386.75 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures: Stock Market Hits Highs After Bullish Pause; Apple, Broadcom In Buy Zones](https://finance.yahoo.com/m/cfdf164e-e24a-366b-9d8b-b0274f05ba94/dow-jones-futures%3A-stock.html) — Investor's Business Daily
- [Alphabet Takes the Spotlight Among Mag 7 Hyperscalers](https://finance.yahoo.com/markets/stocks/articles/alphabet-takes-spotlight-among-mag-212300312.html) — Zacks
- [Why These 3 Red Hot Tech Stocks Keep Climbing](https://finance.yahoo.com/markets/stocks/articles/why-3-red-hot-tech-212100459.html) — Zacks

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 268.26 ▲1.21% |
| Market Cap | $2.88T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 50.6% / 11.5% / 12.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.52 |
| Beta | 1.38 |
| 52-Week | 183.85 – 273.88 |
| Div. Yield | — |

**Recent News:**
- [Alphabet Takes the Spotlight Among Mag 7 Hyperscalers](https://finance.yahoo.com/markets/stocks/articles/alphabet-takes-spotlight-among-mag-212300312.html) — Zacks
- [Vanguard partners with Amazon Alexa for voice-activated proxy voting](https://finance.yahoo.com/video/vanguard-partners-with-amazon-alexa-for-voice-activated-proxy-voting-211911272.html) — Yahoo Finance Video
- [Nasdaq, S&P 500 Log Record Finish, Extend Streak of Weekly Gains](https://finance.yahoo.com/markets/stocks/articles/nasdaq-p-500-log-record-210415219.html) — MT Newswires

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 608.75 ▼0.52% |
| Market Cap | $1.54T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.9% / 41.2% / 32.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.33 |
| Beta | 1.31 |
| 52-Week | 520.26 – 796.25 |
| Div. Yield | — |

**Recent News:**
- [Assessing Entergy (ETR) After Meta Data Center Deal And Expanded US$40b Capital Plan](https://finance.yahoo.com/markets/stocks/articles/assessing-entergy-etr-meta-data-231120619.html) — Simply Wall St.
- [IDACORP Q1 Earnings Call Highlights](https://finance.yahoo.com/m/9f1a2d3a-57e5-3699-b6e1-1a45a7626f99/idacorp-q1-earnings-call.html) — MarketBeat
- [Meta buys robotics startup to bolster its humanoid AI ambitions](https://finance.yahoo.com/sectors/technology/articles/meta-buys-robotic-startup-bolster-221327678.html) — TechCrunch

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 421.28 ▲3.90% |
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
- [Dow Jones Futures: Stock Market Hits Highs After Bullish Pause; Apple, Broadcom In Buy Zones](https://finance.yahoo.com/m/cfdf164e-e24a-366b-9d8b-b0274f05ba94/dow-jones-futures%3A-stock.html) — Investor's Business Daily
- [Stocks Recover From Tuesday OpenAI Selloff](https://finance.yahoo.com/m/b4a8721b-c320-3e32-99d5-db4bbf437fdb/stocks-recover-from-tuesday.html) — The Wall Street Journal
- [The First $6 Trillion Company May Not Be Nvidia](https://finance.yahoo.com/m/b246014e-b62f-3722-8a0b-f30af3a07666/the-first-%246-trillion-company.html) — Barrons.com

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 211.18 ▲4.71% |
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
- [ARM, Marvell, or Vertiv: Which AI Infrastructure Stock Crushed It in April?](https://finance.yahoo.com/m/7d8d154d-4b50-361b-adca-69a7536ad59d/arm%2C-marvell%2C-or-vertiv%3A.html) — 24/7 Wall St.
- [Palantir, Nvidia Partner CoreWeave Headline Earnings Calendar; Lithium Play In Spotlight](https://finance.yahoo.com/m/39f46054-2ad2-3b80-a2a4-87a699205a9a/palantir%2C-nvidia-partner.html) — Investor's Business Daily
- [Jim Cramer Says “Corning Flew Too Close and Had Its Icarus Moment”](https://finance.yahoo.com/markets/stocks/articles/jim-cramer-says-corning-flew-191750330.html) — Insider Monkey

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 144.07 ▲3.57% |
| Market Cap | $330.13B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 82.4% / 31.6% / 36.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 46.55 |
| Beta | 1.67 |
| 52-Week | 105.32 – 207.52 |
| Div. Yield | — |

**Recent News:**
- [Jobs Report, Berkshire Annual Meeting: What to Watch in the Next Week](https://finance.yahoo.com/m/2307a382-5e3f-31c9-86be-bdae1b2f5aae/jobs-report%2C-berkshire-annual.html) — The Wall Street Journal
- [Nasdaq Tops 25,000. Tech Is Back In Control.](https://finance.yahoo.com/m/800fe5c4-ed3b-3499-989a-deb0e50c256a/nasdaq-tops-25%2C000.-tech-is.html) — Barrons.com
- [SoundHound, Palantir, or C3.ai: Which AI Stock Won April? The Answer Will Surprise You](https://finance.yahoo.com/m/788f9c77-a556-3569-a35c-dbe99c100518/soundhound%2C-palantir%2C-or.html) — 24/7 Wall St.

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 27.09 ▲2.93% |
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
- [Dell, Super Micro, or HPE: Which AI Server Stock Crushed It in April?](https://finance.yahoo.com/m/5f8bcdee-6411-3d43-bd42-895fac5e84e8/dell%2C-super-micro%2C-or-hpe%3A.html) — 24/7 Wall St.
- [3 Growth Stocks With High Insider Ownership Achieving 19% Revenue Growth](https://finance.yahoo.com/markets/stocks/articles/3-growth-stocks-high-insider-173611753.html) — Simply Wall St.
- [Should You Hold or Fold Super Micro Computer Stock Before Q3 Earnings?](https://finance.yahoo.com/markets/stocks/articles/hold-fold-super-micro-computer-163600098.html) — Zacks

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 390.82 ▲2.41% |
| Market Cap | $1.47T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.1% / 5.0% / 4.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 15.03 |
| Beta | 1.92 |
| 52-Week | 271.00 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Stock Market Today, May 1: Rivian Falls After Investors Focus on Cash Burn Despite Beating Q1 Expectations](https://finance.yahoo.com/m/04799337-4272-3d00-aab1-efc014c812a5/stock-market-today%2C-may-1%3A.html) — Motley Fool
- [Tesla ends week nearly 4% higher. What's driving the EV stock?](https://finance.yahoo.com/video/tesla-ends-week-nearly-4-higher-whats-driving-the-ev-stock-210623745.html) — Yahoo Finance Video
- [NIO Stock Drops. The U.S. Isn’t the Only Country With an EV Problem.](https://finance.yahoo.com/m/5a94db5c-b9f9-3d4d-a546-d8b2a58ed998/nio-stock-drops.-the-u.s..html) — Barrons.com

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 662.52 ▲1.27% |
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
- [4 S&P 500 Stocks Turn $10,000 To $109,607 In Four Months](https://finance.yahoo.com/m/411bce67-9920-3964-8ee1-760d16f92613/4-s%26p-500-stocks-turn-%2410%2C000.html) — Investor's Business Daily
- [S&P 500 vs. Gold: Warren Buffett Said Buy One and Forget the Other](https://finance.yahoo.com/m/9958d16c-95de-3814-8d7c-cd5f80ab068b/s%26p-500-vs.-gold%3A-warren.html) — Motley Fool
- [Tech ETFs Dominate as $11.4B Floods Into U.S. Equity Funds](https://finance.yahoo.com/m/ac422c8a-6b76-3d34-ab61-8dc76605407c/tech-etfs-dominate-as-%2411.4b.html) — etf.com

## 🌍 News

### 🌍 World News
> `2026-05-02 08:10:06`

- [US to cut troop levels in Germany by 5,000 amid Trump spat with Merz](https://www.bbc.com/news/articles/c0729d374mxo?at_medium=RSS&at_campaign=rss)
- [Trump tells Congress ceasefire means he does not need their approval for Iran war](https://www.bbc.com/news/articles/c4g4xexy4w7o?at_medium=RSS&at_campaign=rss)
- [Billions of meals at risk due to Iran war, says fertiliser boss](https://www.bbc.com/news/articles/cpwp50v4ye7o?at_medium=RSS&at_campaign=rss)
- [Australia wants to be first nation in the world to eliminate a cancer - can it?](https://www.bbc.com/news/articles/cd6w15vgp7lo?at_medium=RSS&at_campaign=rss)
- [Who shot a Secret Service officer at the Trump press dinner?](https://www.bbc.com/news/articles/cm2pmk0r3pjo?at_medium=RSS&at_campaign=rss)
- [French PM fuels row with trip to buy baguettes](https://www.bbc.com/news/articles/czx2rnk9y9go?at_medium=RSS&at_campaign=rss)
- [US court limits mail-order access to abortion pill mifepristone](https://www.bbc.com/news/articles/c2k20z5yj3wo?at_medium=RSS&at_campaign=rss)
- [War criminal Mladic close to death, say lawyers asking judge for jail release](https://www.bbc.com/news/articles/c3e283g80n4o?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-05-02 08:20:26`

#### AI Tips
Here’s your tailored photography expert and deals advice for Taiwan consumers on **2026-05-02**.

---

## 【購買優惠】— Best Places & May Sale Tips

#### 1. Best places to buy camera gear in Taiwan (ranked for value)

| Channel | Best for | Notes |
|---------|----------|-------|
| **PChome 24h** | New gear, fast delivery, easy returns | Often has **銀行加碼回饋** (bank rebates) on Wednesdays. Check for **5月母親節檔期** deals now. |
| **momo購物** | Bundles (body + lens + accessories) | Strong **折價券** (coupon) system. Look for “限時特賣” in the afternoon. |
| **光華商場** (Guanghua Digital Plaza) | Bargaining, used gear, niche accessories | Go on a weekday morning. Ask for “現金價” (cash price) — usually 5–10% off listed. |
| **日本代購** (e.g., Buyee, ZenMarket, or 代購社團) | High-end lenses, limited editions | **Yen is weak** in 2026. Add 10% Taiwan import tax + shipping. Still cheaper for Sony GM / Nikon Z lenses. |
| **二手** (DCView二手市集, 蝦皮, 臉書社團) | Budget bodies, vintage lenses | **May is good** — students sell gear before graduation. Check shutter count and mold carefully. |

#### 2. Seasonal sale tips for May

- **母親節檔期 (Mother’s Day campaign)** — now through mid-May. PChome & momo have **全站折價券** (site-wide coupons) + **銀行滿額禮** (bank gift). Example: 花旗/國泰 often give NT$1,200–2,000 back on NT$30,000+.
- **春季電腦展 leftovers** — some 光華 shops still have “展場價” from April. Ask directly.
- **日本黃金週 (Golden Week) 結束** — Japanese used camera shops (e.g., Map Camera, Kitamura) often clear inventory in early May. Use a proxy to snag deals.
- **Avoid buying new flagship bodies now** — Canon/Nikon/Sony usually

#### r/photomarket
- [PSA: Turn on ‘Persistent Messaging’ when using Chats](https://www.reddit.com/r/photomarket/comments/1mboakg/psa_turn_on_persistent_messaging_when_using_chats/)
- [PSA: AI timestamp photos and how not to get scammed](https://www.reddit.com/r/photomarket/comments/1nkg9v6/psa_ai_timestamp_photos_and_how_not_to_get_scammed/)
- [[B][USA-CA] Leica MP .72x Black Paint](https://www.reddit.com/r/photomarket/comments/1t19hxh/busaca_leica_mp_72x_black_paint/)
- [[S] [USA-IL] Repost + lowered price. Wotancraft Pilot 18L Backpack Khaki with Waist Strap and Armor 06 Module.](https://www.reddit.com/r/photomarket/comments/1t18n24/s_usail_repost_lowered_price_wotancraft_pilot_18l/)
- [[S][USA-CA] Nikon D3100 with 35/1.8G and 40/2.8G (Micro-Nikkor)](https://www.reddit.com/r/photomarket/comments/1t124id/susaca_nikon_d3100_with_3518g_and_4028g/)

### 🤿 Dive Gear Deals
> `2026-05-02 08:20:33`

#### AI Tips
Here’s a practical, Taiwan-focused guide for recreational divers looking to buy gear or maintain it this May 2026.

---

#### 【購買優惠】Best Places & May Seasonal Tips

**Top 3 places to buy in Taiwan (May 2026):**

1.  **實體店 – 台北「內湖潛水街」& 墾丁大街**  
    - **內湖 (Taipei):** 集中多家老牌店 (如「海人潛水」、「台灣潛水」)。5月是季前最後折扣期，很多店會出清去年款式的面鏡、蛙鞋、電腦錶。  
    - **墾丁 (Kenting):** 5月水溫約26-28°C，能見度佳，但尚未進入暑假人潮高峰。店家有機會給「試穿套裝」的展示品折扣 (如4mm防寒衣、調節器)。  
2.  **線上 – 蝦皮商城 & 「潛水裝備二手交流」Facebook社團**  
    - **蝦皮:** 5月有「母親節檔期」(5/1-5/10)，部分潛水品牌 (如Suunto、Garmin、Mares) 會有滿額折價券。注意：只買有「商城」標籤的，避免水貨無保固。  
    - **Facebook社團:** 搜尋「台灣潛水裝備二手買賣」。5月很多人剛從帛琉、沖繩回來，會拋售「只穿過一次」的輕裝 (如面鏡、防寒衣)。**建議面交檢查矽膠邊條有無硬化。**  
3.  **品牌官網直購 – 如「AROPEC」、「TUSA Taiwan」**  
    - 5月常有「早鳥潛水季」活動：買調

#### r/scuba
- [Semi-dry wetsuit zipper slider came off one side of the zip](https://www.reddit.com/r/scuba/comments/1t0r4sg/semidry_wetsuit_zipper_slider_came_off_one_side/)
- [BCD Sizing Question](https://www.reddit.com/r/scuba/comments/1szvzp9/bcd_sizing_question/)

### ✈️ Flight Tips
> `2026-05-02 08:20:17`

#### AI Flight Tips — May
Here’s your actionable flight deal guide for May 2026, departing from Taipei (TPE/TSA):

**Japan (Tokyo, Osaka, Sapporo)**  
- **May is shoulder season** (post-Golden Week, pre-summer); prices dip after May 7.  
- **Book 4–6 weeks ahead** for best rates; last-minute deals possible mid-month.  
- **Cheapest route:** Peach Aviation or Jetstar from TPE to Tokyo (NRT) or Osaka (KIX); for Sapporo, fly Peach via KIX or direct Tigerair Taiwan.  
- **Watch for:** Peach’s “Happy Peach” flash sales (often Wednesdays) and Tigerair’s monthly promo codes.

**Thailand (Bangkok, Chiang Mai)**  
- **Off-peak** (rainy season starts mid-May); low demand keeps fares down.  
- **Book 3–5 weeks ahead**; last-minute deals common for Bangkok.  
- **Cheapest route:** Thai Lion Air or Nok Air from TPE to DMK (Bangkok); for Chiang Mai, fly Air Asia via DMK or direct Thai Vietjet.  
- **Watch for:** AirAsia’s “Big Sale” (usually early May) and Vietjet’s “Fly Now” flash sales.

**Europe (any major city)**  
- **Peak season** (spring travel surge); prices high, especially for London, Paris, Amsterdam.  
- **Book 8–12 weeks ahead**; avoid waiting past mid-May.  
- **Cheapest route:** China Airlines or EVA Air via Taipei to London (LHR) or Paris (CDG); consider Turkish Airlines via Istanbul for lower fares to secondary cities.  
- **Watch for:** EVA Air’s “Hello Spring” promo (ends May 15) and Turkish Airlines’ “Europe Sale” (often 20–30% off in May).

**USA (West Coast or East Coast)**  
- **Shoulder season** (post-spring break, pre-summer); West Coast cheaper than East Coast.  
- **Book 6–8 weeks ahead**; West Coast deals pop up 4 weeks out.  
- **Cheapest route:** Starlux or EVA Air to LAX/SFO (West Coast); for East Coast, China Airlines to JFK or EVA to ORD (Chicago) with a connection.  
- **Watch for:** Starlux’s “May Madness” sale (up to 25% off) and EVA’s “USA Flash Sale” (often mid-May).

**Egypt (Cairo)**  
- **Off-peak** (hot season begins); low demand, but limited direct options.  
- **Book 5–7 weeks ahead**; last-minute deals rare due to limited routes.  
- **Cheapest route:** Turkish Airlines via Istanbul (IST) to CAI; or EgyptAir via Bangkok (BKK) with a stop.  
- **Watch for:** Turkish Airlines’ “Middle East & Africa” promo (usually 15–20% off in May) and EgyptAir’s occasional “Summer Sale.”

**Australia (Sydney, Melbourne)**  
- **Off-peak** (autumn in Australia, pre-winter); good deals available.  
- **Book 4–6 weeks ahead**;

### 🗺️ Travel Deals
> `2026-05-02 08:20:08`

#### r/solotravel
- [How do you deal with the excitement of planning a trip with no one to talk to about it](https://www.reddit.com/r/solotravel/comments/1t1a92d/how_do_you_deal_with_the_excitement_of_planning_a/)
- [Flights keep getting canceled](https://www.reddit.com/r/solotravel/comments/1syrgl7/flights_keep_getting_canceled/)
- [Thailand and Vietnam in 20 Days – Worth It for a First Solo Trip to Asia?](https://www.reddit.com/r/solotravel/comments/1syvfbh/thailand_and_vietnam_in_20_days_worth_it_for_a/)

## 📚 Learning

### 📚 Learning — Finance
> `2026-05-02 08:30:05`

#### 📚 Today's Concept: Short Interest and Days to Cover

What it is: Short interest is the total number of shares that have been sold short but not yet covered, expressed as a percentage of total shares outstanding. Days to Cover (also called “short ratio”) divides that short interest by the average daily trading volume, estimating how many days it would take all short sellers to buy back those shares.

Why it matters: High days to cover (e.g., above 10) signals potential for a “short squeeze” if positive news hits, because shorts must scramble to buy shares, driving the price up rapidly. For a software engineer, think of it as a measure of “pending demand” that can amplify price moves.

Example: Stock XYZ has 10 million shares outstanding. Short interest is 2 million shares (20%). Average daily volume is 500,000 shares. Days to Cover = 2,000,000 / 500,000 = 4 days. If a surprise earnings beat occurs, shorts covering over 4 days could push the stock up 15-30% in a week.

Rule of thumb: Days to Cover above 10 is a warning sign of extreme bearish sentiment; combined with low volume, it’s a high-risk, high-reward setup. Avoid buying into a stock with high short interest if the company has weak fundamentals—it’s often shorted for a reason.

### 🧩 LeetCode Blind 100
> `2026-05-02 08:30:12`

#### 🧩 Blind 100 — 98. Validate Binary Search Tree [Trees]
**連結:** https://leetcode.com/problems/validate-binary-search-tree/
> 📅 **Today's Daily Challenge:** #804 Rotated Digits [Medium] — Tags: Math, Dynamic Programming — https://leetcode.com/problems/rotated-digits/

## 98. Validate Binary Search Tree [Trees]

**Problem Type:** BST validation / recursion with bounds

**Key Insight:** A BST requires that *all* left subtree values are less than the root, and *all* right subtree values are greater — not just immediate children. Pass down valid ranges (min/max) to each node.

**Approach:**
1. Define a recursive helper that takes a node, a lower bound, and an upper bound
2. For the root, bounds are `-inf` and `+inf`
3. At each node: check if `node.val` is strictly between bounds
4. Recurse left with updated upper bound = `node.val`
5. Recurse right with updated lower bound = `node.val`
6. Return `False` immediately on any violation (pruning)

**Python3 Solution:**
```python
class Solution:
    def isValidBST(self, root: Optional[TreeNode]) -> bool:
        def dfs(node, lo, hi):
            if not node:
                return True
            if not (lo < node.val < hi):
                return False
            return dfs(node.left, lo, node.val) and dfs(node.right, node.val, hi)
        
        return dfs(root, float('-inf'), float('inf'))
```

**Complexity:** Time O(n) | Space O(h) — recursion stack, h = tree height

**Blind 100 Note:** Core tree validation pattern — demonstrates the critical concept of propagating constraints down the tree. Similar problems: *Kth Smallest Element in a BST*, *Recover Binary Search Tree*, *Lowest Common Ancestor of BST*.

**Contest Tips:**
- **Edge case:** Single node → `True`
- **Edge case:** Duplicate values → must be `False` (BST requires strict inequality)
- **Common mistake:** Only checking immediate children (fails for `[5,4,6,null,null,3,7]`)
- **Python trick:** Use `float('-inf')` / `float('inf')` for clean initial bounds
- **Optimization:** Return early on `False` — don't explore both subtrees if left already fails

### 📷 Learning — Photography
> `2026-05-02 08:30:21`

#### 📷 Today's Concept: Street — Reading Urban Light and Shadows

**What it is:** Street photography is about reading urban light and shadows as compositional tools, not just recording scenes. It’s the practice of anticipating how light falls on architecture, streets, and people to create mood, depth, and contrast.

**Why it matters:** Light defines shape and texture, while shadows add mystery and guide the viewer’s eye. Mastering this turns ordinary streets into dynamic, cinematic frames.

**How to apply it:**
1. **Walk at golden hours** (early morning or late afternoon) when light is directional and shadows are long.
2. **Look for hard edges**—sunlight slicing through alleys, under awnings, or between buildings. Position yourself to catch subjects stepping into or out of these light pools.
3. **Use spot metering** on the brightest part of the frame to expose for highlights, letting shadows go dark for contrast.
4. **Wait for a subject** to enter your pre-visualized light patch. Patience turns a good shadow into a great story.
5. **Shoot from low angles** to emphasize shadow length and scale against the urban backdrop.

**Sony A7C tip:** Set your *Silent Shooting* mode (Menu → Camera → Shutter/Silent) to avoid drawing attention. Pair with a compact 35mm f/2.8 lens for discreet, fast street work.

**Common mistake:** Overexposing to see shadow detail. Instead, embrace deep blacks—they create drama and hide clutter. Expose for the highlights and let shadows fall where they may.

### 📚 Learning — Tech
> `2026-05-02 08:30:16`

#### 📚 Today's Concept: Vector Databases and Embeddings

**What it is:**  
A vector database stores and indexes data as high-dimensional numerical vectors (embeddings), enabling similarity search rather than exact keyword matching. Embeddings are generated by AI models to capture semantic meaning, so “dog” and “puppy” are close in vector space.

**When to use it:**  
Use for semantic search, recommendation systems, or RAG (Retrieval-Augmented Generation). Real-world scenario: a customer support chatbot retrieves the most relevant FAQ answers by embedding user queries and comparing them to stored FAQ embeddings.

**Example (Python with FAISS):**  
```python
import faiss
import numpy as np

# Embeddings: 3 items, each 4-dimensional
embeddings = np.array([[0.1, 0.2, 0.3, 0.4],
                       [0.5, 0.6, 0.7, 0.8],
                       [0.9, 0.1, 0.2, 0.3]]).astype('float32')
index = faiss.IndexFlatL2(4)  # L2 distance
index.add(embeddings)

query = np.array([[0.2, 0.3, 0.4, 0.5]]).astype('float32')
distances, indices = index.search(query, k=2)  # returns nearest items
```

**Gotcha:**  
Assuming embeddings capture all semantics perfectly—they don’t. Two unrelated concepts can be close in vector space due to training data bias or poor model choice. Always test with domain-specific data.

### 🎬 Learning — YouTube
> `2026-05-02 08:30:26`

#### 🎬 今日主題：Script — 說故事結構：英雄旅程套用在 Vlog
**類別：** 腳本

**是什麼：**  
英雄旅程是將 Vlog 包裝成「主角（你）經歷挑戰、獲得成長」的故事結構。它能讓日常片段變成有起承轉合的冒險，而非流水帳。

**為什麼重要：**  
初學者常因影片缺乏焦點而流失觀眾。英雄旅程能幫你快速抓住觀眾注意力，讓他們想看完你的旅程。

**怎麼做：**  
1. **平凡世界**：開頭 10 秒展示日常（如在家整理背包）。  
2. **冒險召喚**：出現一個目標或問題（如「今天要去拍銀河，但天氣預報說會下雨」）。  
3. **挑戰與轉折**：記錄過程中的困難（如雲層突然變厚、器材沒電）。  
4. **獲得寶藏**：解決問題後的收穫（如拍到絕美星空、學到應變技巧）。  
5. **回歸分享**：結尾總結心得，並預告下一支影片。

**新手常犯的錯：**  
只拍「成功」畫面，忽略掙扎過程。觀眾更想看真實的挫折與解決，這才是英雄旅程的核心。

**延伸 idea：**  
【科技開箱】「用 Sony A7C 挑戰拍出人生第一支銀河縮時」——從找不到拍攝點、對焦失敗，到成功捕捉流動星空的完整旅程，最後分享 3 個新手必學設定。

## 🛂 Immigration

### 🇦🇺 Australia Immigration
> `2026-05-02 08:40:08`

- [PSA Reddit Mod Account Compromised](https://www.reddit.com/r/AusVisa/comments/1sp17tm/psa_reddit_mod_account_compromised/)
- [April 2026 Mega Thread](https://www.reddit.com/r/AusVisa/comments/1s9xabb/april_2026_mega_thread/)
- [VISA GRANTED](https://www.reddit.com/r/AusVisa/comments/1t156d4/visa_granted/)
- [Can/ Should I update PTE scores after getting invitation to apply?](https://www.reddit.com/r/AusVisa/comments/1t1au8o/can_should_i_update_pte_scores_after_getting/)
- [Student visa (subclass 500)](https://www.reddit.com/r/AusVisa/comments/1t161h0/student_visa_subclass_500/)
