---
date: 2026-09-15
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "savings_travel", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-09-15

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

- **AI 硬體殺聲隆隆、軟體接棒**：AMD −4.40%、Broadcom −4.46%、Arm −5.97%、NVDA −3.36% 全面回檔，但 Google +3.22%、Meta +2.71%、Microsoft +1.97%、PLTR +3.64% 逆勢上漲 — 資金明顯從 AI 硬體輪動到 AI 應用/平台，值得檢查你的持股結構。
- **eBPF CPU 成本砍 90%**：memoization 技巧對做 observability / networking / kernel tooling 的人是立即可用的優化 → [link](https://nathannaveen.dev/posts/dropping-ebpf-cpu-cost-by-90/)
- **AI 找到真實世界的安全漏洞**：OpenAI bots 比人類早發現 RubyGems caching 漏洞，dependency supply-chain 風險 + AI 輔助安全研究的重要訊號 → [link](https://tenderlovemaking.com/2026/09/11/what-a-time-to-be-alive/)
- **Google ADK for Kotlin 1.0 發布**：與 Python / Java 核心功能對齊，可在 Kotlin / Android 上開發 production-ready multi-agent AI → [link](https://developers.googleblog.com/announcing-adk-for-kotlin-10-building-production-ready-ai-agents-in-kotlin-android-and-beyond/)
- **相機採購時機**：9 月是水貨/二手好時機（新機上市壓低舊款價），公司貨則等 9/25 後中秋＋週年慶預購；momo 會員日就在今天前後，可留意鏡頭/配件回饋。

---

- 💻 **Tech**: Agentic AI 走向企業級、AI 抓漏、eBPF 大優化、GPT-5.6 Luna vs GPT-6 Astra 的 code review 成本戰、embodied AI 論文齊發。
- 🤖 **AI 公司動態**: 全是 Tesla（robotaxi 恐懼被分析師反駁、Roadster 發表、TSLA 一年報酬回顧）；OpenAI / Anthropic 今日無更新。
- 🔵 **Google 動態**: ADK for Kotlin 1.0、Tunix on TPUs 自動化 post-training、harness engineering 評估 AI coding agents、DevFest 2026 開放報名。
- 📈 **Markets**: 美股 S&P 500 +0.37% 領漲，日經 +0.75% 強於台股 TAIEX +0.11%，低波動樂觀但台股動能落後。
- 🏠 **台灣房市**: 央行信用管制下買方市場成形，蛋黃區大樓仍有接手力道，自備款備足 3 成再進場。
- 📊 **Watchlist**: 半導體全面重挫、hyperscaler 軟體/雲端與 PLTR 逆勢上漲；估值欄位全 N/A，今日只有價格訊號。
- 🌍 **World News**: 中國反駁 AI 惡性競爭說、俄羅斯襲擊烏克蘭列車、瑞典大選難分軒輊、尚比亞野犬創紀錄遷徙、墨西哥反毒梟暴力抗議。
- 📷 **Camera Deals**: 9 月通路比價攻略（PChome/momo/光華/日本代購/二手），減法構圖技巧，Reddit 出現 Sigma DP lot、Ricoh GR III HDF 等二手釋出。
- 🤿 **Dive Gear Deals**: 台灣實體店與 FB 社團採購管道整理，9 月潛季尾聲店家出清夏季庫存，調節器/電腦錶建議買有保固新品。
- ✈️ **Flight Tips**: 9 月全線便宜（日本 −20~30%、泰國最低、歐洲 shoulder season），埃及/澳洲約 NT$25,000–40,000 來回，建議設 Google Flights 警報。
- 🗺️ **Travel Deals**: 泰寮柬 25 天行程偏緊建議砍一國、東南亞簽證與延簽資訊、Oktoberfest 約 $700–800 值得與否的討論。
- 📚 **Learning — Finance**: ROE = 淨利 / 股東權益，>15% 且持續 5 年為篩選標準，但先檢查

---

## 💻 Tech

### 💻 Tech & AI
> `2026-09-15 09:40:47`

#### Hacker News
- [Pion, an agent designed to run any company autonomously](https://andonlabs.com/blog/why-we-built-pion) ⭐283
- [OpenAI bots knew about the RubyGems caching vulnerability](https://tenderlovemaking.com/2026/09/11/what-a-time-to-be-alive/) ⭐374
- [Dropping eBPF CPU Cost by About 90% with Memoization (Not AI Gen)](https://nathannaveen.dev/posts/dropping-ebpf-cpu-cost-by-90/) ⭐26
- [Why don't machine learning research agents overfit?](https://www.amazon.science/blog/why-dont-machine-learning-research-agents-overfit) ⭐105
- [GPT-5.6 Luna vs. GPT-6 Astra: Is a $1.20 Model Good Enough for Code Review?](https://entelligence.ai/blogs/gpt-5.6-luna-vs-gpt-6-astra-is-a-1.20-model-good-enough-for-code-review) ⭐108
- [Largest known Roman mosaic, beneath Baths of Trajan, opens to the public](https://www.theartnewspaper.com/2026/09/14/largest-roman-mosaic-opens-to-the-public) ⭐47
- [Adversarial Fashion Makes a Statement on AI Panopticon](https://spectrum.ieee.org/adversarial-fashion) ⭐94
- [Anthropic is in regulatory-capture financial loop](https://twitter.com/kevinnbass/status/2099626156660043891) ⭐18
- [Ex-FTC boss Khan: break out the handcuffs for AI CEOs, citing 1934 precedent](https://www.theregister.com/ai-and-ml/2026/09/14/ex-ftc-boss-khan-urges-uncle-sam-to-break-out-the-handcuffs-for-ai-ceos-citing-1934-precedent/5296325) ⭐9
- [Show HN: Kinesis – Control your Mac with the Meta Neural Band](https://github.com/callbacked/kinesis) ⭐108

#### HuggingFace
- [ReMoMask-2: Latent Retrieval-Augmented Masked Motion Generation](https://huggingface.co/papers/2609.08365)
- [MobileVLA-R1 2.0: RL-Enhanced Reasoning for Mobile Robot Control](https://huggingface.co/papers/2609.06251)
- [Occamy-1.0: Open Pareto-frontier 35B Intelligence for Co-work](https://huggingface.co/papers/2609.11977)
- [Pelican-Sim 1.0: A General World Model Simulator for Embodied Intelligence](https://huggingface.co/papers/2609.12036)
- [ReactHuman: A Physics-Grounded Benchmark for Human-Like Reactive Decision-Making in Embodied Multimodal LLMs](https://huggingface.co/papers/2609.10895)
- [Competence-Gated Pooling of Language Models and Priors for Event Forecasting](https://huggingface.co/papers/2609.12101)

#### ArXiv


### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-09-15 09:40:53`

#### Tesla
- [Analyst calls robotaxi fears completely ridiculous](https://finance.yahoo.com/markets/stocks/articles/analyst-calls-robotaxi-fears-completely-235057488.html)
- [Musk offers radical fix to welfare state bankruptcy](https://finance.yahoo.com/markets/crypto/articles/musk-offers-radical-fix-welfare-224746389.html)
- [If You'd Invested $1,000 in Tesla Stock 1 Year Ago, Here's How Much You'd Have Today](https://finance.yahoo.com/markets/stocks/articles/youd-invested-1-000-tesla-215300976.html)
- [Tesla Roadster Reveal Could Be Musk's Biggest Test Yet](https://finance.yahoo.com/markets/stocks/articles/tesla-roadster-reveal-could-musks-212248792.html)

### 🔵 Google 動態
> `2026-09-15 09:40:50`

#### Google AI Blog
- [Watch astronaut Christina Koch and Google’s James Manyika discuss space, technology, and discovery.](https://blog.google/innovation-and-ai/technology/ai/dialogues-christina-koch/)
- [DevFest is back](https://blog.google/innovation-and-ai/technology/developers-tools/devfest2026/)
- [3 ways to prep for your next big race with Search](https://blog.google/products-and-platforms/products/search/running-race-training-tips/)
- [Get ready for the game with new football features in Search](https://blog.google/products-and-platforms/products/search/football-features-google-search/)
- [Recreating a 70-year love story frame by frame](https://blog.google/innovation-and-ai/technology/ai/love-rendered-film/)
#### Google Blog
- [Watch astronaut Christina Koch and Google’s James Manyika discuss space, technology, and discovery.](https://blog.google/innovation-and-ai/technology/ai/dialogues-christina-koch/)
- [DevFest is back](https://blog.google/innovation-and-ai/technology/developers-tools/devfest2026/)
- [We’re exploring a potential data center in Lea County, New Mexico.](https://blog.google/innovation-and-ai/infrastructure-and-cloud/global-network/lea-county-new-mexico/)
- [Three Google supported projects premiere during the 83rd Venice International Film Festival.](https://blog.google/innovation-and-ai/technology/xr-ar/three-google-supported-projects-premiere-during-the-83rd-venice-international-film-festival/)
- [Dreambeans: Daily stories, brewed just for you, now available to all accounts in the U.S.](https://blog.google/innovation-and-ai/models-and-research/google-labs/dreambeans-expansion-september-2026/)
#### Google Developers
- [Autonomous LLM post-training with Tunix on TPUs](https://developers.googleblog.com/autonomous-llm-post-training-with-tunix-on-tpus/)
- [The Anatomy of Harness Engineering: How to Evaluate, Iterate, and Guard AI Coding Agents](https://developers.googleblog.com/the-anatomy-of-harness-engineering-how-to-evaluate-iterate-and-guard-ai-coding-agents/)
- [Announcing ADK for Kotlin 1.0: Building Production-Ready AI Agents in Kotlin, Android, and Beyond](https://developers.googleblog.com/announcing-adk-for-kotlin-10-building-production-ready-ai-agents-in-kotlin-android-and-beyond/)
- [Driving Developer Excellence: Inside the Program Sprints](https://developers.googleblog.com/driving-developer-excellence-inside-the-program-sprints/)
- [4 engineering patterns behind the strongest AI Agents Challenge submissions](https://developers.googleblog.com/4-engineering-patterns-behind-the-strongest-ai-agents-challenge-submissions/)

## 📈 Finance

### 📈 Markets Overview
> `2026-09-15 09:40:55`

#### Indices
- S&P 500: 7,619.98 ▲0.37%
- 台股加權: 45,913.96 ▲0.11%
- 日經 225: 63,967.83 ▲0.75%

### 🏠 台灣房市
> `2026-09-15 09:41:49`

#### AI 分析
# 台灣房市快評（2026-09-15）

**1. 整體趨勢**
央行選擇性信用管制持續發酵，投資買盤退場，市場以自住剛需為主軸，成交量能偏弱、價格呈現「高檔盤整、區域分化」。高總價產品去化期拉長，賣方讓利意願逐漸提高，議價空間較去年明顯擴大。

**2. 值得注意的訊號**
- 近期實價登錄高總價成交集中在**住宅大樓（11層以上）**，單價落在 28–37 萬/㎡（約 92–122 萬/坪），顯示蛋黃區大樓仍有一定接手力道。
- 一筆華廈成交單價達 52 萬/㎡（約 172 萬/坪），屬特殊地段/產品，不宜視為通案行情。
- 出現「其他」類別 0 坪、總價 9,369 萬的成交，多為**土地、店面或持分交易**，與住宅行情脫鉤，勿誤讀。

**3. 對自住者建議**
- 現在是**買方市場**，可積極議價，優先鎖定生活機能成熟、屋齡 10–20 年的大樓，避開供給量大的新興重劃區。
- 貸款成數受管制影響，自備款需備足 3 成以上再進場。

**4. 對投資者建議**
- 短期價差空間有限，**收租型產品**（捷運周邊、學區小宅）較穩健；高總價豪宅流動性差，不建議追高。
- 關注央行信用管制是否鬆綁，將是下一波量能回溫的關鍵訊號。

**5. 風險提醒**
利率與政策仍偏緊，若持有成本上升，部分槓桿型賣壓可能釋出，進場前務必試算現金流與持有期間。

#### 591 最新


#### 實價登錄 (115S2) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 華廈(10層含以下有電梯) | 342.6㎡ | 17800萬 | 519496元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 675.5㎡ | 17000萬 | 279512元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 294.7㎡ | 10848萬 | 368078元/㎡ |
|  | 其他 | 0.0㎡ | 9369萬 | 36623元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 261.6㎡ | 8350萬 | 357414元/㎡ |

### 📊 Watchlist
> `2026-09-15 09:41:22`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 210.96 ▼3.36% |
| Market Cap | $5.11T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.7% / 65.2% / 63.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 22.29 |
| Beta | 2.22 |
| 52-Week | 164.27 – 236.54 |
| Div. Yield | — |

**Recent News:**
- [SpaceX Spent $15.8 Billion on AI in a Quarter. Here's What Happens to the Stock if Orbital Data Centers Don't Work.](https://finance.yahoo.com/m/48d929f1-a7e5-37d7-baca-cd90a3c146ea/spacex-spent-%2415.8-billion-on.html) — Motley Fool
- [Prediction: Interactive Brokers Ends 2026 With More Than 6 Million Customer Accounts](https://finance.yahoo.com/m/69b2ac26-3767-3b50-bbb8-54ee3503ff97/prediction%3A-interactive.html) — Motley Fool
- [IREN Stock Slips, But A Top Wall Street Bank Is Bullish With Double-Upgrade And 50% Upside](https://finance.yahoo.com/m/baee9207-8489-367e-8518-2114e0f7a909/iren-stock-slips%2C-but-a-top.html) — Stocktwits

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 493.41 ▼4.40% |
| Market Cap | $804.55B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.2% / 15.7% / 15.6% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 11.97 |
| Beta | 2.48 |
| 52-Week | 149.85 – 584.73 |
| Div. Yield | — |

**Recent News:**
- [AI-linked stocks slide after tech bosses call for slowdown in ‘reckless’ development](https://finance.yahoo.com/technology/ai/articles/ai-linked-stocks-slide-tech-181747255.html) — The Guardian
- [Talk of AI pause slams Nvidia, AMD and Intel as fears of doomsday scenarios spread](https://finance.yahoo.com/technology/ai/articles/talk-ai-pause-slams-nvidia-214716918.html) — LA Times
- [Update: Wall Street Dips as AI Warnings Weigh on Tech Sector](https://finance.yahoo.com/technology/ai/articles/wall-street-dips-ai-warnings-204112098.html) — MT Newswires

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 505.41 ▲1.97% |
| Market Cap | $3.75T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.9% / 46.8% / 40.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 8.49 |
| Beta | 1.11 |
| 52-Week | 349.20 – 553.72 |
| Div. Yield | — |

**Recent News:**
- [Microsoft Just Made a Move That Could Put More Pressure on Its Azure Business. Here's Why It Could Turn Out Great for the Stock](https://finance.yahoo.com/m/bce0c7c7-b0ee-3152-a73b-9ed20219664e/microsoft-just-made-a-move.html) — Motley Fool
- [S&P 500, Nasdaq, Dow Drop On Chipmaker Weakness, Treasury Yield Pressure — MSFT, NFLX, ORCL, CRWD, RBLX In Focus](https://finance.yahoo.com/m/c03e7abf-3f31-3de5-9594-2b699d67d8e9/s%26p-500%2C-nasdaq%2C-dow-drop-on.html) — Stocktwits
- [Talk of AI pause slams Nvidia, AMD and Intel as fears of doomsday scenarios spread](https://finance.yahoo.com/technology/ai/articles/talk-ai-pause-slams-nvidia-214716918.html) — LA Times

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 349.39 ▲3.22% |
| Market Cap | $4.23T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.1% / 54.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.56 |
| Beta | 1.23 |
| 52-Week | 235.84 – 408.61 |
| Div. Yield | — |

**Recent News:**
- ['We owe it to humanity to try': Anthropic's CEO Just Called For Global AI Slowdown. Elon Musk, Sam Altman, and Google’s AI Chief Agree.](https://finance.yahoo.com/technology/ai/articles/owe-humanity-try-anthropics-ceo-221601409.html) — Motley Fool
- [Big Tech Issued About $220 Billion of Bonds. Alphabet and Meta Show How AI Is Warping the Credit Market](https://finance.yahoo.com/markets/stocks/articles/big-tech-issued-220-billion-212946047.html) — Insider Monkey
- [Maryland Seeks To Reinstate Digital Ad Tax](https://finance.yahoo.com/media-advertising/articles/maryland-seeks-reinstate-digital-ad-210454125.html) — MediaPost

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 253.54 ▼1.26% |
| Market Cap | $2.73T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 50.8% / 12.1% / 17.4% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.94 |
| Beta | 1.44 |
| 52-Week | 196.00 – 287.20 |
| Div. Yield | — |

**Recent News:**
- [Amazon Partners with Wiwynn to Expand U.S. AI Infrastructure Capacity](https://finance.yahoo.com/technology/ai/articles/amazon-partners-wiwynn-expand-u-012223093.html) — Insider Monkey
- [AMAZON TEAMSTERS RALLY FOR DELIVERY PROTECTION ACT](https://finance.yahoo.com/small-business/articles/amazon-teamsters-rally-delivery-protection-230500185.html) — PR Newswire
- [The Gulf’s AI Nightmare Came Courtesy of an Iranian Drone](https://finance.yahoo.com/m/06d71b1e-17ed-3541-b91d-f920b5810530/the-gulf%E2%80%99s-ai-nightmare-came.html) — The Wall Street Journal

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 665.60 ▲2.71% |
| Market Cap | $1.70T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.7% / 38.1% / 29.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.48 |
| Beta | 1.24 |
| 52-Week | 520.26 – 790.80 |
| Div. Yield | — |

**Recent News:**
- [Big Tech Issued About $220 Billion of Bonds. Alphabet and Meta Show How AI Is Warping the Credit Market](https://finance.yahoo.com/markets/stocks/articles/big-tech-issued-220-billion-212946047.html) — Insider Monkey
- [Meta’s AI Agents Are Coming for Your Shopping Cart. These ETFs Could Cash In](https://finance.yahoo.com/technology/ai/articles/meta-ai-agents-coming-shopping-203040358.html) — Benzinga
- [Is META Stock’s $130B AI Buildout Your Ticket to an 8.7% Yield?](https://finance.yahoo.com/m/e91f8041-f74e-3861-b989-8a722db0ede0/is-meta-stock%E2%80%99s-%24130b-ai.html) — Trefis

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 344.72 ▼4.46% |
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
- [3 Stocks That Offer AI Exposure and Dividends](https://finance.yahoo.com/markets/stocks/articles/3-stocks-offer-ai-exposure-232700797.html) — Zacks
- [Broadcom Drops Over 4% as $21.7 Billion AI Forecast Meets Slowdown Fears](https://finance.yahoo.com/technology/ai/articles/broadcom-drops-over-4-21-210015158.html) — GuruFocus.com
- [Wall Street ends down, calls for AI slowdown pummel chipmakers](https://finance.yahoo.com/technology/ai/articles/ai-warnings-knock-nasdaq-futures-092329455.html) — Reuters

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 239.01 ▼5.97% |
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
- [Netflix Stock Rose 4% While the AI Trade Sold Off on Monday. Its Capital Goes Into Shows, Not Silicon.](https://finance.yahoo.com/m/003bb504-9f0a-3146-a5b8-578bd0fcdadd/netflix-stock-rose-4%25-while.html) — Motley Fool
- [Prediction: Arm Could Be the Picks-and-Shovels Winner of the AI Boom](https://finance.yahoo.com/m/72b2efac-268c-318e-92aa-f87afe5f02aa/prediction%3A-arm-could-be-the.html) — 24/7 Wall St.
- [Wall Street Analyst Sees Between 19% to 37% Upside in These 5 AI Chip Stocks](https://finance.yahoo.com/m/267d424a-db40-3248-ae9c-f0eeee6ac9f9/wall-street-analyst-sees.html) — Motley Fool

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 173.31 ▲3.64% |
| Market Cap | $397.93B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.8% / 42.8% / 49.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 42.50 |
| Beta | 1.62 |
| 52-Week | 106.37 – 207.52 |
| Div. Yield | — |

**Recent News:**
- [Oklo Has Massive Potential Due to Artificial Intelligence, but the Stock Is Sinking. Here's What I'd Do](https://finance.yahoo.com/markets/stocks/articles/oklo-massive-potential-due-artificial-213201743.html) — Motley Fool
- [Sector Update: Tech](https://finance.yahoo.com/technology/articles/sector-tech-194005500.html) — MT Newswires
- [Palantir and Nvidia rethink AI use over a growing data risk](https://finance.yahoo.com/news/palantir-nvidia-rethink-ai-over-190043439.html) — GuruFocus.com

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 36.74 ▼1.71% |
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
- [Which Tech Stocks Are Getting Hit Hardest Today](https://finance.yahoo.com/m/b4ef8b18-9650-3d18-8f87-584b47727065/which-tech-stocks-are-getting.html) — The Wall Street Journal
- [5 Top AI Stocks to Buy on the Dip as Slowdown Fears Hit Markets](https://finance.yahoo.com/technology/ai/articles/5-top-ai-stocks-buy-203700535.html) — Zacks
- [Is HPE Stock Now A Bet On Memory Prices?](https://finance.yahoo.com/markets/stocks/articles/hpe-stock-now-bet-memory-174916864.html) — Trefis

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 358.97 ▼1.77% |
| Market Cap | $1.42T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 18.9% / 4.2% / 3.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.38 |
| Beta | 1.84 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Analyst calls robotaxi fears completely ridiculous](https://finance.yahoo.com/markets/stocks/articles/analyst-calls-robotaxi-fears-completely-235057488.html) — TheStreet
- [Musk offers radical fix to welfare state bankruptcy](https://finance.yahoo.com/markets/crypto/articles/musk-offers-radical-fix-welfare-224746389.html) — TheStreet
- [If You'd Invested $1,000 in Tesla Stock 1 Year Ago, Here's How Much You'd Have Today](https://finance.yahoo.com/markets/stocks/articles/youd-invested-1-000-tesla-215300976.html) — Motley Fool

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 699.30 ▲0.38% |
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
- [Bond Yields Near 5% as ETF Investors Keep Buying](https://finance.yahoo.com/m/d658fd86-da31-37e3-9f7b-cd6e6f2fd283/bond-yields-near-5%25-as-etf.html) — etf.com
- [VOO vs. IVV: Same S&P 500, Same Fee, So Does It Even Matter Which One You Buy?](https://finance.yahoo.com/m/bc3b84ea-6152-3fcd-ab4e-da7fc6426cf4/voo-vs.-ivv%3A-same-s%26p-500%2C.html) — 24/7 Wall St.
- [Investors Just Pulled $32 Billion From U.S. Stocks. Should You Be Selling, Too?](https://finance.yahoo.com/m/bb196f1f-70b0-3fcb-a4fd-ff7a1aef8f0c/investors-just-pulled-%2432.html) — Motley Fool

## 🌍 News

### 🌍 World News
> `2026-09-15 09:41:52`

- [China criticises idea it is in 'malicious competition' over AI](https://www.bbc.co.uk/news/articles/cn8me133119o?at_medium=RSS&at_campaign=rss)
- [Russia hits Ukrainian train shortly after Boris Johnson and top European officials leave station](https://www.bbc.co.uk/news/articles/cy5zg41dkqwo?at_medium=RSS&at_campaign=rss)
- [Swedish left-wing bloc narrowly ahead with election too close to call](https://www.bbc.co.uk/news/articles/c0qx5d79kdeo?at_medium=RSS&at_campaign=rss)
- [Wild dogs record 2,500-mile trek across Zambia in search of a mate](https://www.bbc.co.uk/news/articles/cy459y5y9yxo?at_medium=RSS&at_campaign=rss)
- [Thousands demand end to violence in Mexican cartel hotspot](https://www.bbc.co.uk/news/articles/cde06rxw5g6o?at_medium=RSS&at_campaign=rss)
- [Legendary costume designer Bob Mackie dies aged 87](https://www.bbc.co.uk/news/articles/cmpq04wx8l4eo?at_medium=RSS&at_campaign=rss)
- [Malaysian boy acquitted for murder of schoolgirl on grounds of insanity](https://www.bbc.co.uk/news/articles/ce87qzrz7p8o?at_medium=RSS&at_campaign=rss)
- [Immigrants held in small outdoor cages at 'Alligator Alcatraz' in Florida, investigators find](https://www.bbc.co.uk/news/articles/cqrk37rrpk23o?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-09-15 09:42:05`

#### AI Tips
# 📸 台灣攝影採購 & 技巧日報 — 2026/09/15

## 【購買優惠】九月買相機鏡頭攻略

**通路比一比（2026 現況）**

| 通路 | 適合買什麼 | 注意事項 |
|---|---|---|
| **PChome 24h** | 公司貨機身、記憶卡、電池 | 常有「刷卡回饋 + 折價券」疊加，9 月週年慶前哨戰已開跑 |
| **momo** | 鏡頭、腳架、配件 | 會員日（每月 15 號前後）回饋最高，今天正好可留意 |
| **光華商場 / 相機街** | 議價空間大、可試機 | 現金價通常比標價低 3–8%，記得先查公司貨建議售價 |
| **日本代購** | 日系鏡頭、機身 | 日圓弱勢時價差可達 15–25%，但**無台灣保固**，送修要寄回日本 |
| **二手（DCView、旋轉、蝦皮）** | 高階鏡頭、停產機 | 快門數、公司貨保卡、有無入塵是三大檢查點 |

**九月季節性重點**
- **中秋連假（9 月底）**：各大電商會推「秋節加碼」，是撿機身優惠的好時機。
- **週年慶前哨**：百貨（新光、SOGO）10 月週年慶，9 月底常先釋出「預購優惠」，滿額贈 + 信用卡回饋可疊到 10–15%。
- **策略**：想買**公司貨**→ 等 9/25 後的中秋＋週年慶預購；想買**水貨/二手**→ 現在就是好時機，因為新機（如各家秋季發表）上市會壓低舊款二手價。

**一句話建議**：先鎖定型號 → 用「比價網站 + 信用卡回饋網」算出實付價 → 光華現金價當談判底線。

---

## 【今日攝影技巧】用「減法構圖

#### r/photomarket
- [Universal Scammer List — Lookup](https://www.reddit.com/r/photomarket/comments/1vk7dhy/universal_scammer_list_lookup/)
- [PSA: AI timestamp photos and how not to get scammed](https://www.reddit.com/r/photomarket/comments/1nkg9v6/psa_ai_timestamp_photos_and_how_not_to_get_scammed/)
- [[S] [USA-WA] Sigma DP lot-](https://www.reddit.com/r/photomarket/comments/1wgisv6/s_usawa_sigma_dp_lot/)
- [[B] [USA-TX] Sigma 10-18mm f2.8 AND Sigma 16-300mm for Fuji X Mount](https://www.reddit.com/r/photomarket/comments/1wgm20q/b_usatx_sigma_1018mm_f28_and_sigma_16300mm_for/)
- [[B] [USA-NJ] Ricoh GR III HDF](https://www.reddit.com/r/photomarket/comments/1wglymx/b_usanj_ricoh_gr_iii_hdf/)

### 🤿 Dive Gear Deals
> `2026-09-15 09:42:09`

#### AI Tips
# 台灣潛水裝備採購 & 9月裝備提醒（2026-09-15）

## 【購買優惠】台灣買潛水裝備的實用管道

**實體店（可試穿、可議價、售後最穩）**
- **台北**：潛水貨倉、海人潛水、BlueTrend 藍色趨勢（東北角/台北皆有）
- **東北角（龍洞、鼻頭角一帶）**：店家密集，適合週末潛水順便試裝，常有現貨促銷
- **墾丁**：潛水店多，套裝（BCD+調節器+電腦錶）常給「整組價」
- **台中/高雄**：海洋先生、潛水主義等，南部的調節器維修資源也不錯

**線上 / 社團（撿便宜但要看評價）**
- **Facebook 社團**：「台灣潛水二手交流」「潛水裝備買賣」— 二手 BCD、蛙鞋、防寒衣流動快，**調節器、電腦錶建議買有保固卡的新品或原廠可查序號的**
- **蝦皮 / momo / PChome**：適合買配件（面鏡、呼吸管、手套、防水袋、燈具）
- **國外網購（Amazon JP、Diveinn、Scuba.com）**：調節器/電腦錶價差可達 2–3 成，但**注意保固是否跨國、關稅（超過 NT$2,000 可能課稅）**

**9月採購時機提示**
- 9月是**台灣潛季尾聲（東北角約到10–11月，墾丁/小琉球全年）**，店家開始**出清夏季庫存**

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-09-15 09:42:00`

#### AI Flight Tips — September
# September Flight Deals from Taiwan (TPE/TSA)

**Japan (Tokyo/Osaka/Sapporo)**
- September is post-summer off-peak (typhoon season), so fares drop ~20-30% vs August. Book 6-8 weeks out for the sweet spot.
- Cheapest: Peach, Scoot, Tigerair Taiwan to NRT/KIX; ~NT$5,000-8,000 round-trip. Sapporo via CTS on Peach/Thai Vietjet is priciest—book 10-12 weeks ahead.
- Watch: Budget carriers' "early bird" autumn sales in late September for Oct-Nov travel.

**Thailand (Bangkok/Chiang Mai)**
- September is low season (rainy), so it's the cheapest month—fares can hit NT$4,000-6,000 round-trip.
- Cheapest: Thai Vietjet, AirAsia, Tigerair Taiwan direct to BKK/DMK; Chiang Mai usually requires a connection via BKK.
- Watch: AirAsia and Vietjet flash sales; book 4-6 weeks out for best pricing.

**Europe (any major city)**
- September is shoulder season—still popular but cheaper than summer peak. Book 8-12 weeks ahead.
- Cheapest: China Airlines/EVA Air direct to LHR/AMS/CDG, or connect via BKK/DXB on Emirates/Qatar for lower fares (~NT$25,000-35,000 RT).
- Watch: EVA Air and China Airlines autumn promos; Middle East carriers' stopover deals.

**USA (West/East Coast)**
- September is off-peak post-summer—good value. Book 10-14 weeks ahead for best fares.
- Cheapest: EVA Air/China Airlines direct to LAX/SFO/SEA (~NT$28,000-38,000 RT); East Coast via connection or United/Delta.
- Watch: EVA Air's "Early Bird" promos and Starlux launch fares to LAX/SFO.

**Egypt (Cairo)**
- September is shoulder season—hot but fewer crowds. Book 10-14 weeks ahead.
- Cheapest: Connect via Istanbul (Turkish), Doha (Qatar), or Dubai (Emirates); ~NT$30,000-40,000 RT. No direct flights from TPE.
- Watch: Turkish Airlines and Qatar Airways stopover packages; EgyptAir via BKK.

**Australia (Sydney/Melbourne)**
- September is early spring—shoulder season, moderate prices. Book 8-12 weeks ahead.
- Cheapest: China Airlines/EVA Air direct to SYD/MEL (~NT$25,000-35,000 RT); Scoot via SIN for budget option.
- Watch: China Airlines and EVA Air spring sales; Scoot's Singapore stopover deals.

**General tip:** Set Google Flights alerts now; Tuesday/Wednesday departures are typically cheapest, and Taiwan's September typhoon season means flexible tickets are worth the small premium.

### 🗺️ Travel Deals
> `2026-09-15 09:41:55`

#### r/solotravel
- [~25 days solo travel Thailand, Laos, Cambodia. Any advice on split?](https://www.reddit.com/r/solotravel/comments/1wg68ss/25_days_solo_travel_thailand_laos_cambodia_any/)
- [Is Oktoberfest worth ~$700–800 solo, or should I do a cheaper German beer festival instead?](https://www.reddit.com/r/solotravel/comments/1weboko/is_oktoberfest_worth_700800_solo_or_should_i_do_a/)
- [Visa Exemption, 30 day Extension question .](https://www.reddit.com/r/solotravel/comments/1wf89r1/visa_exemption_30_day_extension_question/)

## 📚 Learning

### 📚 Learning — Finance
> `2026-09-15 09:42:11`

#### 📚 Today's Concept: Return on Equity (ROE)

What it is: Return on Equity measures how much profit a company generates for every dollar of shareholder equity, calculated as Net Income divided by Shareholders' Equity. It's essentially the efficiency metric for how well management turns investor capital into earnings.

Why it matters: ROE lets you compare profitability across companies regardless of size, and a consistently high ROE often signals a durable competitive advantage. It's a core input for valuation models and a quick filter for quality businesses.

Example: Suppose Company X earns $50 million in net income with $250 million in shareholder equity. ROE = 50 / 250 = 20%. That means for every $1 investors have put in (retained earnings plus paid-in capital), the company generates $0.20 in annual profit. If a competitor earns the same $50 million but holds $500 million in equity, its ROE is only 10% — half as efficient.

Rule of thumb: Look for ROE above 15% sustained over 5+ years, but check the debt level first — heavy borrowing shrinks the equity denominator and can inflate ROE artificially.

### 🧩 LeetCode Blind 100
> `2026-09-15 09:42:15`

#### 🧩 Blind 100 — 684. Redundant Connection [Graphs]
**連結:** https://leetcode.com/problems/redundant-connection/
> 📅 **Today's Daily Challenge:** #2559 Maximum Number of Non-overlapping Palindrome Substrings [Hard] — Tags: Two Pointers, String, Dynamic Programming, Greedy — https://leetcode.com/problems/maximum-number-of-non-overlapping-palindrome-substrings/

# 684. Redundant Connection

**Problem Type:** Union-Find (Disjoint Set Union) / Cycle Detection in Undirected Graph

**Key Insight:** In a tree with one extra edge, the redundant edge is exactly the first edge that connects two nodes already in the same component. Process edges in order with DSU — the first one that fails to union is the answer.

**Approach:**
1. Initialize DSU with `n+1` parents (1-indexed), each pointing to itself.
2. For each edge `(u, v)` in order:
   - Find roots of `u` and `v`.
   - If roots are equal → this edge creates a cycle → return `[u, v]`.
   - Otherwise, union them (attach one root to the other).
3. Return `[]` (never reached given problem guarantees).

**Python3 Solution:**
```python
class Solution:
    def findRedundantConnection(self, edges: List[List[int]]) -> List[int]:
        n = len(edges)
        parent = list(range(n + 1))
        rank = [0] * (n + 1)

        def find(x):
            while parent[x] != x:
                parent[x] = parent[parent[x]]  # path compression
                x = parent[x]
            return x

        for u, v in edges:
            ru, rv = find(u), find(v)
            if ru == rv:
                return [u, v]
            if rank[ru] < rank[rv]:
                ru, rv = rv, ru
            parent[rv] = ru
            if rank[ru] == rank[rv]:
                rank[ru] += 1
        return []
```

**Complexity:** Time O(n · α(n)) ≈ O(n) | Space O(n)

**Blind 100 Note:** This is the canonical **Union-Find** problem — teaches DSU with path compression + union by rank, the foundation for Kruskal's MST, "Number of Connected Components," and "Accounts Merge." Practice next: **547. Number of Provinces**, **261. Graph Valid Tree**, **721. Accounts Merge**, **128. Longest Consecutive Sequence** (DSU variant).

**Contest Tips:**
- **1-indexed nodes** — size array as `n+1`, not `n`.
- **Iterative `find`** avoids recursion limit issues on large inputs (LeetCode n ≤ 1000 here, but habit matters).
- **Path compression alone** is enough; union by rank is a bonus for interview polish.
- **Don't sort edges** — the problem asks for the edge appearing *last* in the input that could be removed, which equals the first cycle-forming edge in input order.
- Alternative: DFS cycle detection works but is O(n²) — DSU is the intended O(n·α(n)) solution.
- Common mistake: returning the edge that *closes* the cycle vs. the one that *would be removed* — they're the same edge here, so just return on first `ru == rv`.

### 📷 Learning — Photography
> `2026-09-15 09:42:20`

#### 📷 Today's Concept: Light — Hard Light vs Soft Light Characteristics

**What it is:** Hard light comes from a small or distant source, creating sharp-edged, high-contrast shadows. Soft light comes from a large source relative to your subject, producing gradual, feathered shadow transitions.

**Why it matters:** Hard light adds drama, texture, and mood; soft light flatters skin and hides flaws. Knowing which you're getting — and how to change it — is the fastest way to control the look of any photo or video.

**How to apply it:**
1. **Read the shadow edge.** Sharp line = hard. Fuzzy gradient = soft. This is your only reliable test.
2. **Change source size, not power.** Move a light closer or add a diffuser/scrim to soften. Move it farther or remove diffusion to harden.
3. **Use the sun as your key.** Midday sun = hard. Overcast or open shade = soft. Golden hour sits in between.
4. **Bounce for instant softness.** White wall, foam board, or reflector fills shadows and widens your effective source.
5. **Match mood to subject.** Hard for street, editorial, and cinematic contrast; soft for beauty, family, and gentle portraits.

**Sony A7C tip:** Enable **Zebra** (Menu → Exposure/Color → Zebra Display) to protect highlights when shooting hard light, and pair with the compact **Sony 35mm f/1.8** for street — its close focus and fast aperture let you shoot in shade and backlight.

**Common mistake:** Assuming "more light" means "better light." Beginners blast a bare speedlight and get raccoon shadows. Instead, diffuse or bounce first — then adjust power.

### 📚 Learning — Tech
> `2026-09-15 09:42:17`

#### 📚 Today's Concept: API Versioning Strategies

**What it is:** API versioning is the practice of managing breaking changes to an API without disrupting existing consumers. It lets you evolve endpoints while old clients keep working against a stable contract.

**When to use it:** Use it when a change would break existing clients—renamed fields, changed types, removed endpoints. E.g., a payments API needs to switch `amount` from float to integer cents; existing mobile apps still send floats, so you expose `/v2/` while `/v1/` keeps the old behavior.

**Example:**
```
GET /v1/charges/123   → { "amount": 10.50 }
GET /v2/charges/123   → { "amount_cents": 1050 }
```
Common strategies: URI path (`/v2/`), header (`Accept: application/vnd.api.v2+json`), or query param (`?version=2`).

**Gotcha:** Versioning isn't a substitute for backward compatibility. Teams often bump versions for every change, fragmenting the API and multiplying maintenance. Only version on *breaking* changes; make additive changes (new optional fields) in place. Also, never silently change `/v1` behavior—that defeats the purpose.

### 🎬 Learning — YouTube
> `2026-09-15 09:42:23`

#### 🎬 今日主題：AI 剪輯 — Runway Gen-2：AI 生成 B-Roll 補足畫面
**類別：** AI剪輯

**是什麼：** Runway Gen-2 是一款文字或圖片轉影片的 AI 工具，輸入描述就能生成數秒的動態片段。適合用來補拍你當下沒拍到、或拍不好的 B-Roll。

**為什麼重要：** 對剛起步的你來說，不用為了一個空鏡頭重跑一趟外拍，省時省錢，還能讓影片節奏更完整。

**怎麼做：**
1. 先寫好腳本，標記哪些段落缺 B-Roll（例如「咖啡杯特寫」「街景空拍」）。
2. 用一句話描述畫面：主體＋動作＋場景＋光線，例如「手持咖啡杯，窗邊晨光，淺景深」。
3. 生成 3-5 秒短片，下載後放進剪輯軟體，調色對齊 A7C 的畫面。
4. 只當「過場或補充」，主畫面仍用你拍的實景，避免風格突兀。

**新手常犯的錯：** 生成太長或太複雜的畫面，導致 AI 感重、與實拍不搭。建議每次只生成 3 秒內、單一動作的鏡頭。

**延伸 idea：** 拍一支「我用 AI 補拍遺漏鏡頭」的旅遊 Vlog，對比實拍與 AI 生成畫面，分享哪種情境適合用 AI。
