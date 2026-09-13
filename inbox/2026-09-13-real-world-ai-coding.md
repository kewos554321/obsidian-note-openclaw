---
date: 2026-09-13
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "savings_travel", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-09-13

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

- **AI 評測走向「真實企業場景」**：Real-SWE 用私有企業 codebase 測 coding agent，比 toy repo 更能反映實戰能力；Google 同時發表 harness engineering 方法論，教你如何評估、迭代、守護 AI coding agent。[Real-SWE](https://withspecific.com/benchmarks/real-swe) · [Harness Engineering](https://developers.googleblog.com/the-anatomy-of-harness-engineering-how-to-evaluate-iterate-and-guard-ai-coding-agents/)
- **台股重挫、美股獨強**：TAIEX 跌 1.61% 至 46,184.85，日經跌 1.93%，但 S&P 500 小漲 0.27% — 亞洲 risk-off 明顯，台股投資人今天心情不會太好。
- **Anthropic CEO 呼籲放慢 AI 發展**：Dario Amodei 公開警告模型可能造成嚴重全球危害，與自家商業利益相悖的表態值得關注。[BBC](https://www.bbc.co.uk/news/articles/c14dpgm0rg4o)
- **ADK for Kotlin 1.0 正式發布**：Google Agent Development Kit 在 Kotlin/Android 上達到與 Python/Java 同等功能，Android 工程師做 multi-agent AI 的門檻大幅降低。[Link](https://developers.googleblog.com/announcing-adk-for-kotlin-10-building-production-ready-ai-agents-in-kotlin-android-and-beyond/)
- **9 月是旅遊黃金窗口**：日本/泰國/歐洲/埃及/澳洲全部進入 off-peak 或 shoulder season，機票比旺季便宜 20–30%；同時也是潛水裝備換季出清與相機前代旗艦跳水的高峰期。

---

- 💻 **Tech**: Real-SWE 企業級評測、ANE DMA 逆向工程、async/await 設計空間、多語推理仍以英文思考、ROS 2 backpressure 修法。
- 🤖 **AI 公司動態**: Tesla 收復美國 EV 市佔但長期投資報酬落後大盤；OpenAI/Anthropic 今日無產品更新。
- 🔵 **Google 動態**: ADK for Kotlin 1.0、Tunix 自動化 TPU 後訓練、harness engineering、Gemini Windows 原生 App、Fairwind 資安計畫。
- 📈 **Markets**: 台股 -1.61%、日經 -1.93%、S&P 500 +0.27%，亞洲明顯弱於美國。
- 🏠 **台灣房市**: 量縮價盤整，自住為王；避開高總價與重劃區賣壓，投資轉長線收租。
- 📊 **Watchlist**: AI 大型股普遍收紅（AMD +2.49% 領漲、SMCI +3.01% 最強），半導體分歧（NVDA 持平、AVGO -0.66%）；估值欄位全 N/A。
- 🌍 **World News**: Anthropic CEO 籲放慢 AI、沙烏地油管遭無人機攻擊關閉、烏克蘭迎最嚴峻冬天、智利養老院火災 16 死、菲律賓渡輪火災 76 死。
- 📷 **Camera Deals**: 9 月開學季尾聲＋新機發表連動，前代旗艦最划算；光華現金價可再省 2–3%。
- 🤿 **Dive Gear Deals**: 9 月換季出清高峰，FB 社團整套裝備議價空間大；調節器/電腦錶務必要求原廠保養紀錄。
- ✈️ **Flight Tips**: 各航線 9 月皆為 off-peak/shoulder，日本 LCC 單程 NT$4,000–7,000、泰國來回 NT$3,500–6,000、歐洲來回 NT$28,000–35,000。
- 🗺️ **Travel Deals**: Oktoberfest 單人 $700–800 偏貴，可考慮 Stuttgart 等替代啤酒節；日本+韓國 12 天行程易過勞，建議拆兩趟。
- 📚 **Learning — Finance**: P/E 比率 = 股價 ÷ EPS，高 P/E 代表預期已反映，同產業內比較才有意義。
- 🧩 **LeetCode Blind 100**:

---

## 💻 Tech

### 💻 Tech & AI
> `2026-09-13 09:16:03`

#### Hacker News
- [Real-SWE: Benchmarking AI models on private, real-world, enterprise codebases](https://withspecific.com/benchmarks/real-swe) ⭐108
- [Nvidia is the central bank of AI](https://www.economist.com/interactive/briefing/2026/09/03/nvidia-is-the-central-bank-of-ai) ⭐386
- [Getting 50 GB/S Back from the Apple Neural Engine](https://eiln.github.io/posts/ane-dma.html) ⭐67
- [LG denies TV spying claims, says tracking and snooping concerns 'not true'](https://www.tomshardware.com/tech-industry/big-tech/lg-strongly-denies-tv-security-claims-says-tracking-and-snooping-concerns-not-true-online-investigation-claims-216-000-000-spy-tvs-record-audio) ⭐431
- [How Trail of Bits helps verify the integrity of Signal chats](https://blog.trailofbits.com/2026/08/11/how-trail-of-bits-helps-verify-the-integrity-of-your-signal-chats/) ⭐52
- [I fixed a tractor using John Deere's self-repair service. Farmers aren't sold](https://www.wired.com/story/i-fixed-a-tractor-john-deere-self-repair-service/) ⭐102
- [Retrospectively Reverse-Engineering Apple's Neural Engine](https://eiln.github.io/posts/ane.html) ⭐222
- [A Mathematical Framework for Transformer Circuits (2021)](https://transformer-circuits.pub/2021/framework/index.html) ⭐83
- [A Design Space Exploration of Async/Await](https://cel.cs.brown.edu/blog/design-space-async-await/) ⭐423
- [The worst spam emails: iLands AI agent hustle](https://tedium.co/2026/09/11/ilands-agents-email-spam-kaixin-tang/) ⭐103

#### HuggingFace
- [Studying Image Tokenizers as Visual Languages in Unified Multimodal Models](https://huggingface.co/papers/2609.09143)
- [Think Before You Link: Rarity, Reasoning, and Retrieval in Multilingual Entity Linking](https://huggingface.co/papers/2609.10745)
- [Building Multilingual Bridges: Data Mixing as the Pillar of Generalization for In-Language Reasoning](https://huggingface.co/papers/2609.10445)
- [Adaptive Bridge: A Proxy-Based Decoupling Layer for Mitigating DDS Backpressure in ROS 2](https://huggingface.co/papers/2608.15380)
- [Beyond Solver Verdicts: Generative Reward Models for Autoformalization](https://huggingface.co/papers/2609.11085)
- [ActReview: Rebuttal-Guided Training Data and Rubric Rewards for Actionable Peer Review Generation](https://huggingface.co/papers/2609.09076)

#### ArXiv


### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-09-13 09:16:09`

#### Tesla
- [Tesla Is Reclaiming the U.S. EV Market as Legacy Automakers Retreat](https://finance.yahoo.com/m/140824c4-c177-3a2a-900f-645f34bf465d/tesla-is-reclaiming-the-u.s..html)
- [Longevity Entrepreneur Peter Diamandis Says He’s Not Trying to Live Longer Because He’s Afraid of Dying — He’s Just Not Done Being ‘Curious’](https://finance.yahoo.com/healthcare/articles/longevity-entrepreneur-peter-diamandis-says-230019533.html)
- [$10,000 in Tesla When It Joined the S&P 500 Would Be About $15,700 Today. An Index Fund Would Have Done Better.](https://finance.yahoo.com/m/4f544e18-54eb-31ad-b771-06f8b67187c8/%2410%2C000-in-tesla-when-it.html)
- [Ted Lieu Cites Poll, Says 'Blue Tsunami' Could Be Coming as Democrats Hold 11-Point Lead Over Republicans in 2026 House Election Poll](https://finance.yahoo.com/m/7e033e0f-9876-3e73-9d59-2f48fa6bfebb/ted-lieu-cites-poll%2C-says.html)

### 🔵 Google 動態
> `2026-09-13 09:16:06`

#### Google AI Blog
- [3 ways to prep for your next big race with Search](https://blog.google/products-and-platforms/products/search/running-race-training-tips/)
- [Get ready for the game with new football features in Search](https://blog.google/products-and-platforms/products/search/football-features-google-search/)
- [Recreating a 70-year love story frame by frame](https://blog.google/innovation-and-ai/technology/ai/love-rendered-film/)
- [Proactive cyber defense for governments and enterprises](https://blog.google/innovation-and-ai/technology/safety-security/fairwind-program/)
- [The latest AI news we announced in August 2026](https://blog.google/innovation-and-ai/technology/google-ai-updates-august-2026/)
#### Google Blog
- [Three Google supported projects premiere during the 83rd Venice International Film Festival.](https://blog.google/innovation-and-ai/technology/xr-ar/three-google-supported-projects-premiere-during-the-83rd-venice-international-film-festival/)
- [Dreambeans: Daily stories, brewed just for you, now available to all accounts in the U.S.](https://blog.google/innovation-and-ai/models-and-research/google-labs/dreambeans-expansion-september-2026/)
- [3 ways to prep for your next big race with Search](https://blog.google/products-and-platforms/products/search/running-race-training-tips/)
- [The Gemini app is now available for Windows](https://blog.google/innovation-and-ai/products/gemini-app/gemini-app-now-on-windows/)
- [Switching password managers is easy and safe on Android](https://blog.google/products-and-platforms/platforms/android/switch-password-managers/)
#### Google Developers
- [Autonomous LLM post-training with Tunix on TPUs](https://developers.googleblog.com/autonomous-llm-post-training-with-tunix-on-tpus/)
- [The Anatomy of Harness Engineering: How to Evaluate, Iterate, and Guard AI Coding Agents](https://developers.googleblog.com/the-anatomy-of-harness-engineering-how-to-evaluate-iterate-and-guard-ai-coding-agents/)
- [Announcing ADK for Kotlin 1.0: Building Production-Ready AI Agents in Kotlin, Android, and Beyond](https://developers.googleblog.com/announcing-adk-for-kotlin-10-building-production-ready-ai-agents-in-kotlin-android-and-beyond/)
- [Driving Developer Excellence: Inside the Program Sprints](https://developers.googleblog.com/driving-developer-excellence-inside-the-program-sprints/)
- [4 engineering patterns behind the strongest AI Agents Challenge submissions](https://developers.googleblog.com/4-engineering-patterns-behind-the-strongest-ai-agents-challenge-submissions/)

## 📈 Finance

### 📈 Markets Overview
> `2026-09-13 09:16:11`

#### Indices
- S&P 500: 7,656.98 ▲0.27%
- 台股加權: 46,184.85 ▼1.61%
- 日經 225: 64,011.34 ▼1.93%

### 🏠 台灣房市
> `2026-09-13 09:17:03`

#### AI 分析
# 台灣房市快評（2026-09-13）

**1. 整體趨勢**
央行選擇性信用管制持續發酵，投資買盤退場，市場呈「量縮價盤整」格局；高總價產品去化明顯放緩，買方議價空間擴大。整體而言，自住剛需仍是唯一穩定支撐，投機氛圍已大幅降溫。

**2. 高總價成交觀察**
115S2 揭露的高總價物件集中在住宅大樓（11層以上），單價落在 28～52 萬/㎡，總價 8,350 萬～1.78 億。值得注意的是，高總價交易多為大坪數（260㎡以上）產品，單價落差大，反映地段與屋況分化明顯；蛋黃區大樓仍具撐價力，但非核心區高總價物件已有讓利跡象。

**3. 值得注意的地區與物件**
- **核心都會蛋黃區**：大坪數電梯大樓仍有高資產自住客接手，抗跌性較佳。
- **新興重劃區**：供給量大、投資客比重高，需留意交屋潮帶來的賣壓。
- **老華廈/公寓**：若無都更或危老題材，流動性轉差，不建議追高。

**4. 對自住者建議**
自住可趁量縮期進場，優先選擇生活機能成熟、交通便利的蛋黃區中古大樓，議價空間約 5～10%，不必追高預售。

**5. 對投資者建議**
短線炒作空間已封閉，建議轉向長期收租型產品（捷運沿線、學區小宅），並嚴控槓桿；高總價物件除非有明確都更或租金收益支撐，否則不宜貿然進場。

---
**一句話總結**：量縮價盤、自住為王，投資轉長線、避開高總價與重劃區賣壓。

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
> `2026-09-13 09:16:38`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 218.29 ▼0.03% |
| Market Cap | $5.29T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.7% / 65.2% / 63.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 23.06 |
| Beta | 2.22 |
| 52-Week | 164.27 – 236.54 |
| Div. Yield | — |

**Recent News:**
- [Dell Booked More AI Server Orders in 3 Months Than It Recorded in Total Revenue](https://finance.yahoo.com/m/28ca79c0-b2a7-3c4a-aefa-979eef81a894/dell-booked-more-ai-server.html) — Motley Fool
- [Is Nu Holdings Stock a Buy, Sell, or Hold With Shares 20% Below Their 52-Week High?](https://finance.yahoo.com/m/f819b488-5cb9-3535-bd48-c7e791599ef7/is-nu-holdings-stock-a-buy%2C.html) — Motley Fool
- [Hyundai Motor Group Accelerates Autonomous Driving Innovation with AI-Powered Data Flywheel](https://finance.yahoo.com/technology/ai/articles/hyundai-motor-group-accelerates-autonomous-000000032.html) — CNW Group

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 516.13 ▲2.49% |
| Market Cap | $841.60B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.2% / 15.7% / 15.6% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 12.52 |
| Beta | 2.48 |
| 52-Week | 149.85 – 584.73 |
| Div. Yield | — |

**Recent News:**
- [Advanced Micro Devices, Inc. (AMD)’s Halo Station Could Strengthen Its AI Position, but Near-Term Revenue Impact May Be Limited](https://finance.yahoo.com/technology/ai/articles/advanced-micro-devices-inc-amd-235430291.html) — Insider Monkey
- [Nvidia vs. AMD: Elon Musk Picked a Side on the SpaceX Earnings Call](https://finance.yahoo.com/m/e61254d9-56d2-3272-8d44-3050272e6898/nvidia-vs.-amd%3A-elon-musk.html) — Motley Fool
- [Cramer Asked Who Was Buying Gigantic Bloom Energy Calls. A Pelosi Filing Named Two of the Same Stocks Weeks Earlier.](https://finance.yahoo.com/m/3c92812f-f806-3fe2-935f-3de7cfea9aad/cramer-asked-who-was-buying.html) — 24/7 Wall St.

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 495.63 ▲0.65% |
| Market Cap | $3.68T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.9% / 46.8% / 40.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 8.32 |
| Beta | 1.11 |
| 52-Week | 349.20 – 553.72 |
| Div. Yield | — |

**Recent News:**
- [Nvidia vs. AMD: Elon Musk Picked a Side on the SpaceX Earnings Call](https://finance.yahoo.com/m/e61254d9-56d2-3272-8d44-3050272e6898/nvidia-vs.-amd%3A-elon-musk.html) — Motley Fool
- [Zscaler Conference: AI Agents, Agentic SOC Fuel Zero-Trust Growth Ambitions](https://finance.yahoo.com/m/c3ec876a-6501-3000-8f8c-ccd6b7e9f7ce/zscaler-conference%3A-ai.html) — MarketBeat
- [Anthropic’s Prisoner’s Dilemma: Dario Amodei Hits the Brakes on AI While Begging Everyone Else to Do the Same](https://finance.yahoo.com/m/909f9bc5-e3c3-32a6-8a37-941842531427/anthropic%E2%80%99s-prisoner%E2%80%99s.html) — 24/7 Wall St.

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 338.50 ▲1.77% |
| Market Cap | $4.10T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.1% / 54.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.36 |
| Beta | 1.23 |
| 52-Week | 235.84 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [Agentic commerce: Is Payments the winner this time?](https://finance.yahoo.com/technology/ai/articles/agentic-commerce-payments-winner-time-213309351.html) — Investing.com
- [Nvidia vs. AMD: Elon Musk Picked a Side on the SpaceX Earnings Call](https://finance.yahoo.com/m/e61254d9-56d2-3272-8d44-3050272e6898/nvidia-vs.-amd%3A-elon-musk.html) — Motley Fool
- [Google's Historic 396 MW Clean Energy Deal Just Changed the Game for 1 AI Power Play](https://finance.yahoo.com/m/1b044c3d-e233-30b0-bef8-5a841dbcd8fb/google%27s-historic-396-mw.html) — Motley Fool

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 256.78 ▲1.94% |
| Market Cap | $2.76T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 50.8% / 12.1% / 17.4% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 5.01 |
| Beta | 1.44 |
| 52-Week | 196.00 – 287.20 |
| Div. Yield | — |

**Recent News:**
- [Nvidia vs. AMD: Elon Musk Picked a Side on the SpaceX Earnings Call](https://finance.yahoo.com/m/e61254d9-56d2-3272-8d44-3050272e6898/nvidia-vs.-amd%3A-elon-musk.html) — Motley Fool
- [Sirius XM CEO Highlights Cash Flow Growth, New Sports Plans and Ad Expansion at Conference](https://finance.yahoo.com/m/b0822a02-9ec8-3ce1-bb1e-f9b2b354900c/sirius-xm-ceo-highlights-cash.html) — MarketBeat
- [Anthropic’s Prisoner’s Dilemma: Dario Amodei Hits the Brakes on AI While Begging Everyone Else to Do the Same](https://finance.yahoo.com/m/909f9bc5-e3c3-32a6-8a37-941842531427/anthropic%E2%80%99s-prisoner%E2%80%99s.html) — 24/7 Wall St.

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 648.03 ▲0.57% |
| Market Cap | $1.65T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.7% / 38.1% / 29.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 6.31 |
| Beta | 1.24 |
| 52-Week | 520.26 – 790.80 |
| Div. Yield | — |

**Recent News:**
- [Bill Ackman Calls Anthropic Researcher's Exit 'Interesting' Amid Claims of 'Well-Funded PR Operation' Aimed at Democrats](https://finance.yahoo.com/m/a6c56873-d706-3170-85d7-10892ff5c035/bill-ackman-calls-anthropic.html) — Benzinga
- [Agentic commerce: Is Payments the winner this time?](https://finance.yahoo.com/technology/ai/articles/agentic-commerce-payments-winner-time-213309351.html) — Investing.com
- [Nvidia vs. AMD: Elon Musk Picked a Side on the SpaceX Earnings Call](https://finance.yahoo.com/m/e61254d9-56d2-3272-8d44-3050272e6898/nvidia-vs.-amd%3A-elon-musk.html) — Motley Fool

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 361.99 ▼0.66% |
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
- [Broadcom vs. Micron Technology: Which Technology Stock Is a Better Buy in 2026?](https://finance.yahoo.com/m/8c025786-2f35-38af-9455-0063c6cb65fc/broadcom-vs.-micron.html) — Motley Fool
- [Better AI Chip Stock: Broadcom vs. Nvidia](https://finance.yahoo.com/m/f0c445a2-dcab-353a-a837-29096be9dcc4/better-ai-chip-stock%3A.html) — Motley Fool
- [Nvidia takes new role as AI’s $5 trillion bill comes due](https://finance.yahoo.com/m/17389bb9-2f1c-39e6-9072-70e1317d940f/nvidia-takes-new-role-as-ai%E2%80%99s.html) — TheStreet

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 264.79 ▲0.21% |
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
- [Arm vs. Credo Technology Group: Which Semiconductor Stock Is a Better Buy in 2026?](https://finance.yahoo.com/m/6933b569-091d-355f-b929-103354e3184e/arm-vs.-credo-technology.html) — Motley Fool
- [Arm vs. Sandisk: Which Technology Stock Is a Better Buy in 2026?](https://finance.yahoo.com/m/0b73c600-052d-3d93-a892-2c095d73f3ea/arm-vs.-sandisk%3A-which.html) — Motley Fool
- [SoftBank Just Freed Up $25.9 Billion and Its Next AI Move Could Be Huge](https://finance.yahoo.com/technology/ai/articles/softbanks-25-9-billion-move-160001302.html) — GuruFocus.com

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 167.23 ▲0.83% |
| Market Cap | $383.97B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.8% / 42.8% / 49.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 41.01 |
| Beta | 1.62 |
| 52-Week | 106.37 – 207.52 |
| Div. Yield | — |

**Recent News:**
- [Palantir's Growth Has Kept Accelerating, but Can the Rally Continue?](https://finance.yahoo.com/m/fd139d06-77d3-3032-a830-e19b8356c514/palantir%27s-growth-has-kept.html) — Motley Fool
- [Palantir and Nvidia Are Building a Sovereign AI Stack. Who Captures More of the Economics?](https://finance.yahoo.com/technology/ai/articles/palantir-nvidia-building-sovereign-ai-085205506.html) — Insider Monkey
- [Michael Burry Is Staying Short Nvidia, Palantir, and Tesla, Warning of a Possible "1987-Type Fall" for AI Stocks. Should Investors Take the Bet Seriously?](https://finance.yahoo.com/m/f826923c-2137-31af-ba47-7dbd53851f43/michael-burry-is-staying.html) — Motley Fool

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 40.10 ▲3.01% |
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
- [Jim Cramer Turned Out Right For This Particular AI Stock That’s Up Since Earnings](https://finance.yahoo.com/markets/stocks/articles/jim-cramer-turned-particular-ai-105648990.html) — Insider Monkey
- [Jim Cramer Favors Dell (DELL) Over Super Micro (SMCI) as AI Server Demand Surges](https://finance.yahoo.com/markets/stocks/articles/jim-cramer-favors-dell-dell-093723056.html) — Insider Monkey
- [3 Market-Beating Stocks with Promising Prospects](https://finance.yahoo.com/markets/stocks/articles/3-market-beating-stocks-promising-023505827.html) — StockStory

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 365.44 ▲0.52% |
| Market Cap | $1.44T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 18.9% / 4.2% / 3.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.62 |
| Beta | 1.84 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Tesla Is Reclaiming the U.S. EV Market as Legacy Automakers Retreat](https://finance.yahoo.com/m/140824c4-c177-3a2a-900f-645f34bf465d/tesla-is-reclaiming-the-u.s..html) — The Wall Street Journal
- [Longevity Entrepreneur Peter Diamandis Says He’s Not Trying to Live Longer Because He’s Afraid of Dying — He’s Just Not Done Being ‘Curious’](https://finance.yahoo.com/healthcare/articles/longevity-entrepreneur-peter-diamandis-says-230019533.html) — Benzinga
- [$10,000 in Tesla When It Joined the S&P 500 Would Be About $15,700 Today. An Index Fund Would Have Done Better.](https://finance.yahoo.com/m/4f544e18-54eb-31ad-b771-06f8b67187c8/%2410%2C000-in-tesla-when-it.html) — Motley Fool

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 702.56 ▲0.24% |
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
- [Investing in the Vanguard S&P 500 ETF (VOO)? Beware of This 1 Sneaky Risk.](https://finance.yahoo.com/m/9d8eefcc-5e78-3b93-89e4-2286c8594501/investing-in-the-vanguard-s%26p.html) — Motley Fool
- [4 Vanguard Funds With Rock-Bottom Fees That Do Most of the Work for You](https://finance.yahoo.com/m/d2822f30-2827-34bc-a6ac-ea762c6a695a/4-vanguard-funds-with.html) — 24/7 Wall St.
- [SCHD’s 3% Yield Hides a $216,000 Decade-Long Performance Gap Investors Miss](https://finance.yahoo.com/m/40f4e3bf-9f7e-3642-92f0-438a9539eed1/schd%E2%80%99s-3%25-yield-hides-a.html) — 24/7 Wall St.

## 🌍 News

### 🌍 World News
> `2026-09-13 09:17:06`

- [Anthropic boss Dario Amodei calls for AI development to slow down](https://www.bbc.co.uk/news/articles/c14dpgm0rg4o?at_medium=RSS&at_campaign=rss)
- [Saudi Arabia shuts key oil pipeline after drone attack launched from Iraq](https://www.bbc.co.uk/news/articles/c62m933465eo?at_medium=RSS&at_campaign=rss)
- [Trump's comments on a united Ireland may have targeted audience across the Atlantic](https://www.bbc.co.uk/news/articles/cwyzppd1d5lo?at_medium=RSS&at_campaign=rss)
- [Fire at nursing home in Chile kills 16 residents](https://www.bbc.co.uk/news/articles/cy4zpp20w77o?at_medium=RSS&at_campaign=rss)
- [French officials investigate if malicious act caused train derailment](https://www.bbc.co.uk/news/articles/c33kp533nn6o?at_medium=RSS&at_campaign=rss)
- [Uganda's King Oyo buried amid calls for unity over his successor](https://www.bbc.co.uk/news/articles/c0lr7k4k4zyo?at_medium=RSS&at_campaign=rss)
- [Ukraine faces 'toughest winter' since Russia's full-scale invasion, UN official tells BBC](https://www.bbc.co.uk/news/articles/cwyz59yyqk4o?at_medium=RSS&at_campaign=rss)
- [Death toll from Philippines ferry fire rises to 76, with more still missing](https://www.bbc.co.uk/news/articles/cwyz755yeg9o?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-09-13 09:17:19`

#### AI Tips
# 📸 台灣攝影採購 & 今日技巧快報（2026/09/13）

---

## 🛒 購買優惠：台灣相機器材哪裡買最划算

#### 各通路優劣分析

| 通路 | 適合買什麼 | 注意事項 |
|------|-----------|---------|
| **PChome 24h** | 公司貨機身、鏡頭、配件 | 常有「品牌日」折價券，可疊加信用卡回饋；到貨快但價格偏硬 |
| **momo購物** | 公司貨、組合包 | 9月常有「99購物節」餘溫，關注mo幣回饋；比價後再下單 |
| **蝦皮商城** | 公司貨+水貨混雜 | 認明「蝦皮優選」與原廠保固；9/9檔期後仍有零星折扣 |
| **光華商場** | 水貨、二手、議價空間大 | 博愛路/八德路店家可現場試機議價；水貨保固找店家 |
| **日本代購/Bic Camera** | 日系品牌水貨 | 日圓匯率是關鍵；注意保固需寄回日本、關稅風險 |
| **二手（DCView、旋轉拍賣、FB社團）** | 鏡頭、機身 | 面交驗快門數、感光元件入塵；9月畢業季後有學生拋售潮 |

#### 🎯 9月採購時機建議

1. **開學季尾聲（9月中下旬）**：學生機（入門DSLR/無反）降價出清，適合撿便宜。
2. **新機發表連動**：Canon/Nikon/Sony 通常 8–9 月發表新機，**上一代機型**會跳水，鎖定前代旗艦最划算。
3. **百貨週年慶前哨（9月底–10月）**：先觀望，10月週年慶「滿千送百」+ 信用卡回饋常比電商更低。
4. **議價技巧**：光華/博愛路現金價通常比刷卡便宜 2–3%，可問「現金

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-09-13 09:17:23`

#### AI Tips
# 台灣潛水裝備採購 & 9月保養指南（2026-09-13）

## 【購買優惠】台灣買潛水裝備的實用管道

**實體店（可試穿、可議價、售後最穩）**
- **台北**：潛水貨倉、海人潛水、BlueTrend 藍色趨勢（東北角/台北皆有）
- **台中**：潛水主義、海洋先生
- **高雄/墾丁**：墾丁在地潛店（如台灣潛水、水世界）——**9月墾丁仍旺季，現場常有裝備+潛旅套裝折扣**
- 建議：**先到店試尺寸（尤其防寒衣、BCD、面鏡），再比價線上**

**線上**
- **PChome / momo / 蝦皮**：適合買配件（蛙鞋扣、防水袋、O-ring、燈具）
- **蝦皮商城品牌旗艦店**：Cressi、Mares、Scubapro 官方代理常有**9月開學/秋季出清**
- **國外直送**：Diveinn、Amazon JP（注意關稅+保固問題，高單價裝備不建議）

**Facebook 社團（二手撿便宜首選）**
- 「台灣潛水二手裝備買賣」、「潛水裝備交流區」、「Dive Gear Taiwan」
- **9月是換季出清高峰**：許多人夏天結束後拋售整套裝備，**防寒衣、BCD、調節器**議價空間大
- ⚠️ 調節器、電腦錶務必要求**原廠保養紀錄**，否則省小錢賠大錢

**9月季節重點**
- 台灣潛季：**4–10月**，9月東北角水溫約

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-09-13 09:17:15`

#### AI Flight Tips — September
# Flight Deals from Taiwan — September 2026 Playbook

**Japan (Tokyo/Osaka/Sapporo)**
- September is *off-peak* (post-summer, pre-autumn leaves) — typhoon season though, so book flexible fares. Sapporo is cheapest now before ski season.
- Book 6–10 weeks out; LCCs (Peach, Tigerair Taiwan, Scoot) TPE–NRT/KIX run NT$4,000–7,000 one-way.
- Watch Peach's "Fly to Japan" flash sales and EVA/China Airlines early-bird promos; TSA–HND (松山–羽田) is worth the premium for central Tokyo.

**Thailand (Bangkok/Chiang Mai)**
- September = *low season* (rainy) — cheapest month of the year for flights and hotels.
- Book 4–8 weeks ahead; Thai Lion Air, AirAsia, and VietJet TPE–DMK/BKK often NT$3,500–6,000 round-trip.
- Chiang Mai is cheapest via Bangkok connection; watch AirAsia's "Free Seats" promo (usually March & September) and Thai VietJet's 0-baht base fare sales.

**Europe (any major city)**
- September is *shoulder/off-peak* — post-summer crowds gone, fares drop ~20–30% vs July–August.
- Book 8–14 weeks out; China Airlines & EVA Air direct TPE–VIE/AMS/LHR/MUC are the value plays vs. Middle East carriers.
- Watch EVA Air's "Early Bird" Europe fares and China Airlines' TPE–Prague/Vienna direct routes — often NT$28,000–35,000 round-trip if booked by early October.

**USA (West/East Coast)**
- September is *off-peak* (post-Labor Day) — best month for trans-Pacific deals before Thanksgiving.
- Book 8–12 weeks out; EVA Air, China Airlines, and Starlux direct TPE–LAX/SFO/SEA/ONT are competitive; JFK/ORD via connection.
- Watch Starlux's LAX/SFO launch fares and EVA's "Hello Kitty" promo cycles; East Coast often NT$32,000–40,000 round-trip, West Coast NT$25,000–32,000.

**Egypt (Cairo)**
- September is *shoulder* — still hot but pre-high-season (Oct–Apr); decent fares before winter rush.
- Book 10–14 weeks out; no direct TPE–CAI — route via Istanbul (Turkish), Doha (Qatar), or Dubai (Emirates).
- Watch Turkish Airlines' TPE–IST–CAI promo fares (often NT$28,000–35,000 round-trip) and Qatar Airways' "Stopover" packages; book by mid-October for winter travel.

**Australia (Sydney/Melbourne)**
- September is *shoulder* — spring in AU, pre-Christmas peak; good value before December.
- Book 8–12 weeks out; China Airlines & EVA Air direct TPE–SYD/BNE/MEL are the sweet spot; Scoot via Singapore is cheapest.
- Watch China Airlines'

### 🗺️ Travel Deals
> `2026-09-13 09:17:10`

#### r/solotravel
- [Is Oktoberfest worth ~$700–800 solo, or should I do a cheaper German beer festival instead?](https://www.reddit.com/r/solotravel/comments/1weboko/is_oktoberfest_worth_700800_solo_or_should_i_do_a/)
- [First solo trip, 6 weeks (Oct 10 – Nov 22): draft Nepal trek + Japan nature itinerary, looking for feedback](https://www.reddit.com/r/solotravel/comments/1wdjeto/first_solo_trip_6_weeks_oct_10_nov_22_draft_nepal/)
- [Exhausted from 12 day japan/korea trip](https://www.reddit.com/r/solotravel/comments/1wd6fmo/exhausted_from_12_day_japankorea_trip/)
- [Backpacking Europe with a snowboard](https://www.reddit.com/r/solotravel/comments/1wcdqlw/backpacking_europe_with_a_snowboard/)

## 📚 Learning

### 📚 Learning — Finance
> `2026-09-13 09:17:26`

#### 📚 Today's Concept: Price-to-Earnings (P/E) Ratio

What it is: The P/E ratio divides a company's stock price by its earnings per share (EPS), telling you how much investors pay for each dollar of profit. It's the market's shorthand for how expensive a stock is relative to what the company actually earns.

Why it matters: It lets you compare valuations across companies and against a stock's own history, so you can judge whether you're overpaying for growth or spotting a bargain.

Example: A stock trades at $150 and earned $5 per share last year. P/E = 150 / 5 = 30. A competitor at $60 with $4 EPS has a P/E of 15. Same industry, but you're paying twice as much per dollar of earnings for the first company, so the market expects faster growth from it.

Rule of thumb: A high P/E isn't automatically bad, but it means expectations are already priced in, so any earnings miss hits hard; compare P/E only within the same industry, and be wary when a stock's P/E is far above its own five-year average.

### 🧩 LeetCode Blind 100
> `2026-09-13 09:17:30`

#### 🧩 Blind 100 — 139. Word Break [1D DP]
**連結:** https://leetcode.com/problems/word-break/
> 📅 **Today's Daily Challenge:** #864 Image Overlap [Medium] — Tags: Array, Matrix — https://leetcode.com/problems/image-overlap/

## 139. Word Break

**Problem Type:** 1D DP / String Partitioning (can also be solved with BFS or Trie+DP)

**Key Insight:** `dp[i] = True` iff `s[:i]` can be segmented. Transition: `dp[i] = any(dp[j] and s[j:i] in wordSet for j < i)`. The substring `s[j:i]` must be a dictionary word, and everything before `j` must already be segmentable.

**Approach:**
1. Convert `wordDict` to a `set` for O(1) lookups.
2. `dp = [False] * (n+1)`, `dp[0] = True` (empty prefix is trivially segmentable).
3. For each end index `i` from 1 to n:
   - For each start `j` from 0 to i-1:
     - If `dp[j]` and `s[j:i] in wordSet`: set `dp[i] = True`, break.
4. Return `dp[n]`.

**Python3 Solution:**
```python
class Solution:
    def wordBreak(self, s: str, wordDict: List[str]) -> bool:
        words = set(wordDict)
        n = len(s)
        dp = [False] * (n + 1)
        dp[0] = True
        max_len = max(map(len, words))  # optimization: cap inner loop
        
        for i in range(1, n + 1):
            for j in range(max(0, i - max_len), i):
                if dp[j] and s[j:i] in words:
                    dp[i] = True
                    break
        return dp[n]
```

**Complexity:** Time O(n² · L) worst case (L = avg word length for slicing/hashing), often O(n · maxLen) with the cap | Space O(n)

**Blind 100 Note:** Classic 1D DP on strings — teaches "can we partition into valid pieces?" recurrence. Bridges to **Word Break II** (backtracking + memo), **Palindrome Partitioning** (same DP shape), and **Concatenated Words**. The `dp[i] = any(dp[j] and valid(j,i))` template reappears constantly.

**Contest Tips:**
- **Edge case:** empty string / empty dict → `dp[0]=True` handles it.
- **TLE trap:** naive O(n²) with slicing is fine for n≤300, but always add the `max_len` cap — it's free and often 5–10× faster.
- **Don't** try greedy/left-to-right matching — fails on cases like `s="cars", dict=["car","ca","rs"]`.
- **BFS alternative:** treat indices as nodes, edges = valid words from position `i`. Sometimes cleaner for Word Break II.
- **Common mistake:** forgetting `dp[0] = True` (base case) — everything collapses without it.
- **Python trick:** `set(wordDict)` once outside the loop; never check `in wordDict` (list) inside.

### 📷 Learning — Photography
> `2026-09-13 09:17:36`

#### 📷 Today's Concept: Special — Food and Product Still Life Lighting

**What it is:** Food and product still life lighting is the deliberate shaping of small, controllable light sources to reveal texture, shape, and freshness in inanimate subjects. It's studio-style lighting scaled down — often one light plus modifiers, placed with precision.

**Why it matters:** The right light makes food look appetizing and products look premium; the wrong light flattens them into dull, lifeless snapshots. It's the difference between "I want to eat/buy that" and scrolling past.

**How to apply it:**
1. **Start with one light.** Place a window or single LED panel to one side, at roughly 45° and slightly behind the subject (back-side light) to rake across texture.
2. **Diffuse it.** Put a scrim, white shower curtain, or softbox between light and subject for soft, even highlights.
3. **Add fill with a bounce.** Use white foam board opposite the light to lift shadows without killing contrast.
4. **Control reflections.** For glossy products, angle a black card to create crisp edge highlights; for matte food, keep light broad.
5. **Shoot low and close.** Get near table level for heroic angles; use a tripod and shoot tethered or via the flip screen.

**Sony A7C tip:** Use the flip-out screen for low tabletop angles, and pair a 50mm f/1.8 or 90mm macro with **Focus Magnifier** and **Peaking** for tack-sharp detail. Shoot at f/5.6–f/8 for edge-to-edge sharpness.

**Common mistake:** Lighting from the front (on-camera flash or straight-on window) — it flattens everything. Move the light to the side or behind, and let shadows create dimension.

### 📚 Learning — Tech
> `2026-09-13 09:17:32`

#### 📚 Today's Concept: Caching Strategies (Cache-aside, Write-through, Write-back)

**What it is:** Caching strategies define how your app reads/writes data between a cache and the source of truth (DB). Cache-aside: app checks cache, on miss loads from DB and populates cache. Write-through: writes go to cache and DB synchronously. Write-back: writes go to cache only, DB updated later (async).

**When to use it:** Cache-aside for read-heavy workloads with tolerable staleness (product listings). Write-through when consistency matters and write volume is moderate (user profiles). Write-back for write-heavy, latency-sensitive workloads where some data loss is acceptable (counters, analytics events).

**Example:**
```python
# Cache-aside
user = cache.get(f"user:{id}")
if not user:
    user = db.query(id)
    cache.set(f"user:{id}", user, ttl=300)
```

**Gotcha:** Cache-aside doesn't invalidate on DB writes — you must explicitly delete/update cache keys on mutation, or you'll serve stale data indefinitely. Also, write-back risks data loss if the cache crashes before flushing to DB.

### 🎬 Learning — YouTube
> `2026-09-13 09:17:38`

#### 🎬 今日主題：剪輯 — 4K 素材剪輯工作流程與代理檔設定
**類別：** 剪輯

**是什麼：** 代理檔是將 4K 原始素材轉成低解析度版本，剪輯時用代理檔流暢操作，輸出時再套回原始 4K 畫質。這是專業剪輯的標準流程。

**為什麼重要：** A7C 的 4K 檔案很大，直接剪會卡頓、當機，嚴重拖慢你的產出速度，代理檔能讓老電腦也順跑。

**怎麼做：**
1. 匯入素材後，在剪輯軟體（DaVinci Resolve 免費版最適合新手）選「產生代理檔」。
2. 代理格式選 H.264、解析度 720p 或 1080p。
3. 剪輯時開啟「代理模式」預覽，操作會非常流暢。
4. 輸出前確認代理已關閉，確保算圖用原始 4K。
5. 若用 AI 剪輯工具（如 Descript），先確認它支援代理或自動降轉。

**新手常犯的錯：** 直接拿 4K 硬剪，以為電腦慢是正常的。先建立代理檔再開始剪，養成習慣。

**延伸 idea：** 拍一支「我用 AI 工具剪 4K 旅遊片」的實測影片，記錄從代理設定到輸出的完整流程，這類教學對新手極具吸引力。
