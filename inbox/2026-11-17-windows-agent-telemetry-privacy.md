---
date: 2026-11-17
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "savings_travel", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-11-17

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

- **AI 類股全面回檔，半導體最慘** — Arm -12.38%、Broadcom -8.50%、AMD -5.58%、NVDA -4.12%，S&P 500 -2.32%、TAIEX -1.96%。這是高 beta AI 殺盤而非估值輪動（P/E 全 N/A）。若你手上有 AI 部位，留意 TAIEX 40,000 心理關卡。([Watchlist 數據])
- **Gemini 4 Hydrogen 全面進駐 Google Search** — 搜尋體驗大改版，同時推出 Gemini Decisions API（校準式多模態決策 API），對做 agent/產品的你是可直接試用的新工具。[Search 升級](https://blog.google/products-and-platforms/products/search/gemini-4-hydrogen-search-upgrade/) · [Decisions API](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/)
- **Agent 安全與成本是今日主線** — Google 的 Agent Anomaly Detection（OpenTelemetry 監控 goal hijack/tool misuse）＋ GKE node pool 為長時 agent session  sizing；另一篇講「不交出憑證也能跑 coding agent」的 sandbox 模式。三篇都值得排進你的工作站/產品 review。[AAD](https://developers.googleblog.com/securing-your-agents-a-hands-on-guide-to-agent-anomaly-detection/) · [GKE sizing](https://developers.googleblog.com/agents-are-sessions-not-requests-size-gke-node-pools-for-ai-agent-sessions/) · [Agent 憑證](https://blog.antonio.cx/running-agents-with-lend)
- **Windows 11 遙測開始追蹤你的 coding agent 與 dev tools** — 建議今天花 10 分鐘審一下工作機的 telemetry 設定。[Link](https://xusheng.dev/posts/windows-coding-agent-telemetry/)
- **11 月機票窗口：日本/泰國現在就該訂** — 日本賞楓旺季（避開 11/20–30），泰國涼季起步；歐洲是全年最便宜窗口（10–14 週前訂）。埃及 11 月是旺季、需 12–16 週前訂。([Flight Tips])

---

- 💻 **Tech**: Windows 遙測追蹤 coding agent、agent 憑證 sandbox 模式、Lean 驗證的詮釋陷阱，加上 agent 效率/記憶/reward 模型論文。
- 🤖 **AI 公司動態**: 無 OpenAI/Anthropic 消息；重點是 Nvidia 在 Jensen Huang 辭職後首次財報電話會議（AI 硬體供應鏈風向球）。
- 🔵 **Google**: Gemini 4 Hydrogen 上 Search、Decisions API 上線、TPU MLPerf/RL 資源、agent 安全與 GKE sizing 指南。
- 📈 **Markets**: 三大市場齊跌的 risk-off 日，S&P -2.32%、TAIEX -1.96%、Nikkei -1.05%，全球宏觀驅動而非台灣個別事件。
- 🏠 **台灣房市**: 量縮價撐，蛋黃區高總價抗跌但流通慢；自住鎖定成熟機能區，投資看中南部租金報酬型物件。
- 📊 **Watchlist**: AI 半導體全面重挫（Arm -12%、AVGO -8.5%），hyperscaler 相對抗跌（MSFT -1.12%），全數跑輸 VOO。
- 🌍 **World News**: 五國 EU 盧安達遣返中心、葉門 Houthi 進逼、俄烏最大規模無人機攻擊、南非兩起槍擊 17 死、Epstein 法醫爭議。
- 📷 **Camera Deals**: 雙11餘溫＋黑五預熱，PChome 查公司貨定價→光華議價，價差 <10% 選公司貨、>20% 再考慮日本代購。
- 🤿 **Dive Gear Deals**: 11 月淡季實體店議價空間大，二手調節器/電腦錶務必要求保卡＋送驗紀錄；東北角浪大轉室內池。
- ✈️ **Flight Tips**: 日本/泰國現在訂（6–10 週）、歐美 10–14 週、埃及 12–

---

## 💻 Tech

### 💻 Tech & AI
> `2026-11-17 13:09:39`

#### Hacker News
- [Windows 11 Is Collecting Data on Which Coding Agents and Developer Tools You Use](https://xusheng.dev/posts/windows-coding-agent-telemetry/) ⭐387
- [Running coding agents without handing them my credentials](https://blog.antonio.cx/running-agents-with-lend) ⭐72
- [Spamhaus new email sender requirements in November](https://www.spamhaus.org/sender-guidelines/) ⭐83
- [Microsoft blames monster email outage on software defect introduced in July fix](https://www.theregister.com/saas/2026/11/16/microsoft-blames-monster-email-outage-on-software-defect-introduced-in-july-fix/5310026) ⭐260
- [United Airlines experiencing a widespread system outage, airline says](https://www.cnn.com/2026/11/16/us/united-airlines-outage) ⭐219
- [Pentagon fails ninth straight audit despite progress in organizing finances](https://www.reuters.com/business/aerospace-defense/pentagon-fails-ninth-straight-audit-despite-progress-organizing-finances-2026-11-16/) ⭐84
- [Strengthening the fight against online child sexual abuse](https://openai.com/index/strengthening-online-child-safety/) ⭐110
- [Interpreting claims that a theorem is correct because it was checked in Lean](https://xenaproject.wordpress.com/2026/11/12/and-the-proof-is-checked-in-lean/) ⭐293
- [The most expensive bargaining chip in history](https://unrelatedfindings.com/essays/the-most-expensive-bargaining-chip-in-history/) ⭐13
- [Tokendoctor – the same Claude Code for up to 38% less](https://github.com/localixai/tokendoctor) ⭐4

#### HuggingFace
- [Reducing Batch Makespan for LLM Agent Workloads through Inference-Environment Coordination](https://huggingface.co/papers/2611.16661)
- [Iris-Z: Scaling One Generative Model Past Specialist Geometry Models](https://huggingface.co/papers/2611.16010)
- [BrickFlow: Connectivity-Guided Brick Reconstruction](https://huggingface.co/papers/2611.17321)
- [Restoring Diversity in Distilled Image and Video Generators by Probing Activations](https://huggingface.co/papers/2611.18550)
- [Re-Search: Dissecting LLM Ideation Through a Two-Player Questioning Game](https://huggingface.co/papers/2611.14487)
- [Dual Flow: Joint Image-Measurement Interpolation for Inverse Problems](https://huggingface.co/papers/2611.05843)

#### ArXiv
- [STA: A Split Temporal Adversary Method for Evaluating Robustness of Multimodal RL-based Driving Policies](http://arxiv.org/abs/2611.20765v1)
- [Instant Weight-Space Consolidation for Long-Term Memory in LLMs](http://arxiv.org/abs/2611.20759v1)
- [GPRM: Global Perspective Process Reward Model](http://arxiv.org/abs/2611.20755v1)
- [Who Benefits from Telemonitoring? Uplift Modelling of a Nationwide Home Blood Pressure Monitoring Programme](http://arxiv.org/abs/2611.20752v1)
- [GainCtrl: Predicting Remaining Gains for Efficient LLM Agent Execution](http://arxiv.org/abs/2611.20736v1)
- [Can LLMs Give Good Product Advice? A Framework for Diagnosing Failures](http://arxiv.org/abs/2611.20734v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-11-17 13:09:46`

#### Tesla
- [Nvidia set for first earnings call since Jensen Huang's resignation](https://finance.yahoo.com/markets/stocks/articles/nvidia-set-first-earnings-call-050234300.html)
- [Stephen King Tells Elon Musk ‘You Sound Like Trump’ After Billionaire Warns Democrats Will ‘Execute Their Plan to End Democracy in America’](https://finance.yahoo.com/media-advertising/articles/stephen-king-tells-elon-musk-033006336.html)
- [Cathie Wood’s $2.2 Billion Bet on Elon Musk Could Soon Become One Giant Stock](https://finance.yahoo.com/markets/stocks/articles/cathie-wood-2-2-billion-032300304.html)
- [Elon Musk says Larry Page’s ‘Five Nines’ AI prediction is right, despite their decade-long feud](https://finance.yahoo.com/technology/ai/articles/elon-musk-says-larry-page-020300821.html)

### 🔵 Google 動態
> `2026-11-17 13:09:43`

#### Google AI Blog
- [New Ask Maps features to help with holiday travel and prep](https://blog.google/products-and-platforms/products/maps/ask-maps-holiday-travel-features-2026/)
- [Google Search gets a major upgrade with Gemini 4 Hydrogen](https://blog.google/products-and-platforms/products/search/gemini-4-hydrogen-search-upgrade/)
- [Gemini Decisions API: Fast, calibrated multimodal decisions](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/)
- [Try Tabletop: Customizable, collaborative spaces for groups to plan, play and do more together.](https://blog.google/innovation-and-ai/models-and-research/google-labs/tabletop/)
- [Experience the art and legacy of Dr. Esther Mahlangu](https://blog.google/company-news/outreach-and-initiatives/arts-culture/esther-mahlangu/)
#### Google Blog
- [Regional voices are rolling out in the Gemini app.](https://blog.google/innovation-and-ai/products/gemini-app/regional-voices/)
- [The era of autonomous attacks has arrived.](https://blog.google/innovation-and-ai/infrastructure-and-cloud/google-cloud/gtig-ai-threat-tracker-q4-2026/)
- [New Google AdMob AI tools help app creators build, fix, and grow faster](https://blog.google/products/publisher-connections/new-google-admob-tools/)
- [New AI training performance benchmarks for Google TPUs](https://blog.google/innovation-and-ai/infrastructure-and-cloud/google-cloud/training-performance-benchmarks-tpus/)
- [Transform notes, research, and sources into interactive sites with Gemini Notebook.](https://blog.google/innovation-and-ai/products/gemini-notebook/interactive-sites/)
#### Google Developers
- [Unlocking Stable On-Policy RL on TPU with Bitwise-Zero Train–Inference Mismatch](https://developers.googleblog.com/unlocking-stable-on-policy-rl-on-tpu-with-bitwise-zero-traininference-mismatch/)
- [TPU Model Design Considerations and Optimization Guide](https://developers.googleblog.com/tpu-model-design-considerations-and-optimization-guide/)
- [Securing Your Agents: A Hands-On Guide to Agent Anomaly Detection](https://developers.googleblog.com/securing-your-agents-a-hands-on-guide-to-agent-anomaly-detection/)
- [Agents are sessions, not requests: size GKE node pools for AI agent sessions](https://developers.googleblog.com/agents-are-sessions-not-requests-size-gke-node-pools-for-ai-agent-sessions/)
- [How Agent Anomaly Detection scores on benchmarks we didn't write](https://developers.googleblog.com/how-agent-anomaly-detection-scores-on-benchmarks-we-didnt-write/)

## 📈 Finance

### 📈 Markets Overview
> `2026-11-17 13:09:49`

#### Indices
- S&P 500: 7,416.59 ▼2.32%
- 台股加權: 40,237.04 ▼1.96%
- 日經 225: 59,032.68 ▼1.05%

### 🏠 台灣房市
> `2026-11-17 13:10:46`

#### AI 分析
## 台灣房市快評（2026-11-17）

**1. 整體趨勢**
高總價住宅大樓仍有穩定成交，實價登錄顯示台北蛋黃區單價站穩每坪百萬以上（換算約 90–150 萬/坪），但交易量集中於特定高總價物件，市場呈「量縮價撐」格局。利率與信用管制未鬆綁下，自住剛需為主力，投資買盤保守。

**2. 值得注意的地區/物件**
- **台北市蛋黃區高總價住宅**：實價登錄多筆 144–963㎡ 大樓成交，單價換算約 91–151 萬/坪，顯示精華區抗跌但總價門檻高、流通慢。
- **新北樹林/三峽廠辦與住宅**：北大特區住宅與三俊街廠辦掛牌增加，反映產業與外溢自住需求。
- **台南善化、台中大甲、高雄三民**：中南部透天、3房與租賃物件活躍，租補報稅需求帶動租屋市場。

**3. 對自住者建議**
優先鎖定交通與生活機能成熟的蛋黃/次蛋黃區，善用實價登錄比價；高總價物件議價空間較大，可談但需留意貸款成數與持有成本。

**4. 對投資者建議**
短期炒作空間有限，宜聚焦**租金報酬穩定**的中南部租賃型物件（如善化可租補透天）或廠辦需求；台北高總價住宅流動性低，不宜短進短出。

**5. 風險提醒**
信用管制與利率環境未明，高總價、大坪數物件去化期長；掛牌資訊多為廣告文案，實際成交仍須以實價登錄與現場查核為準。

#### 591 最新
- [台北市文山區和興路52巷河畔生活家溫馨電梯兩房🌍找中信鉑曜小徐談便宜](https://sale.591.com.tw/sale-detail-21273016.html)
- [台北市中山區松江路☀️❤️松江南京｜優質商辦｜玻璃帷幕｜現有隔間](https://rent.591.com.tw/rent-detail-22363307.html)
- [新北市樹林區學成路台灣三峽北大【皇勝秀鼎】](https://sale.591.com.tw/sale-detail-21273014.html)
- [台北市大安區信義路三段K22租大安站近捷運有車位氣派大樓採光佳](https://rent.591.com.tw/rent-detail-20915878.html)
- [新北市樹林區三俊街65巷大老闆企業首選⭐️全新廠辦⭐️貨櫃碼頭⭐️整棟多戶可選](https://sale.591.com.tw/sale-detail-21273013.html)
- [台南市善化區胡厝寮🏡林媽媽租屋㊝善化胡厝寮社區型透天/可員工宿舍/可租補報稅](https://rent.591.com.tw/rent-detail-22363298.html)
- [台中市大甲區育英路海創🌊Eda大甲媽祖🔥體育場｜朝南3房花園城｜實在高坪效](https://sale.591.com.tw/sale-detail-21273006.html)
- [高雄市三民區南台路195巷【免仲介服務費】三民南台路傢俱齊全️-五泰夫妻黨](https://rent.591.com.tw/rent-detail-22363303.html)

#### 實價登錄 (115S3) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 住宅大樓(11層含以上有電梯) | 963.3㎡ | 29664萬 | 307937元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 399.6㎡ | 14468萬 | 449312元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 379.7㎡ | 10438萬 | 274908元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 267.7㎡ | 8558萬 | 367305元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 144.7㎡ | 5700萬 | 456525元/㎡ |

### 📊 Watchlist
> `2026-11-17 13:10:18`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 156.14 ▼4.12% |
| Market Cap | $3.76T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.7% / 65.2% / 63.7% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 16.49 |
| Beta | 2.22 |
| 52-Week | 148.80 – 243.37 |
| Div. Yield | — |

**Recent News:**
- [Nvidia set for first earnings call since Jensen Huang's resignation](https://finance.yahoo.com/markets/stocks/articles/nvidia-set-first-earnings-call-050234300.html) — USA TODAY
- [US to close AI chip loophole after Nvidia scandal](https://finance.yahoo.com/technology/ai/articles/nvidia-earnings-test-ai-boom-014359078.html) — AFP
- [US to curb China's access to AI chips as Trump heads to Asia](https://finance.yahoo.com/news/us-curb-chinas-access-ai-220054158.html) — Reuters

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 504.28 ▼5.58% |
| Market Cap | $827.06B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.7% / 17.7% / 16.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 12.06 |
| Beta | 2.49 |
| 52-Week | 188.22 – 658.52 |
| Div. Yield | — |

**Recent News:**
- [AMD, MU, SKHY, AVGO: Chip Stocks Ease Overnight After Selloff On New US Chip Restrictions Targeting China](https://finance.yahoo.com/technology/articles/amd-mu-skhy-avgo-chip-040420540.html) — Stocktwits
- [MiTAC Computing Scales Agentic AI with Full-Stack Infrastructure at SC26](https://finance.yahoo.com/technology/ai/articles/mitac-computing-scales-agentic-ai-032200367.html) — PR Newswire
- [Dow Jones Futures: AMD, Nvidia, Micron Lead AI Trade Lower With Nvidia Earnings On Deck](https://finance.yahoo.com/m/d0a3411e-5f2b-302d-801a-a42b1d7ca5ea/dow-jones-futures%3A-amd%2C.html) — Investor's Business Daily

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 517.99 ▼1.12% |
| Market Cap | $3.85T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.7% / 47.1% / 41.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 8.18 |
| Beta | 1.04 |
| 52-Week | 349.20 – 559.15 |
| Div. Yield | — |

**Recent News:**
- [Elite Undervalued Stocks To Own In November 2026](https://finance.yahoo.com/markets/stocks/articles/elite-undervalued-stocks-own-november-043945272.html) — Simply Wall St.
- [Bill Ackman Adds More To Netflix In Q3; Exits Hertz, Cuts Microsoft](https://finance.yahoo.com/markets/stocks/articles/bill-ackman-adds-more-netflix-000807017.html) — Stocktwits
- [Learn Why The Bull Case For IBM Stock Could Change Following Quantum Computing Expansion](https://finance.yahoo.com/markets/stocks/articles/learn-why-bull-case-ibm-231929118.html) — Simply Wall St.

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 283.72 ▼4.07% |
| Market Cap | $3.45T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.3% / 50.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 5.09 |
| Beta | 1.23 |
| 52-Week | 272.11 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [Elon Musk says Larry Page’s ‘Five Nines’ AI prediction is right, despite their decade-long feud](https://finance.yahoo.com/technology/ai/articles/elon-musk-says-larry-page-020300821.html) — TheStreet
- [Warren Buffett's Successor, Greg Abel, Overhauled Berkshire's Portfolio for a 3rd Straight Quarter, Reducing 6 Stocks and Piling Into a Hot Tech IPO](https://finance.yahoo.com/markets/stocks/articles/warren-buffetts-successor-greg-abel-005301045.html) — Motley Fool
- [Brad Gerstner Says AI Is at Its ‘Google 2005’ Moment. Here’s Who He Thinks Wins](https://finance.yahoo.com/technology/ai/articles/brad-gerstner-says-ai-google-000704866.html) — 24/7 Wall St.

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 257.75 ▼3.34% |
| Market Cap | $2.79T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 51.4% / 13.1% / 16.9% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.54 |
| Beta | 1.50 |
| 52-Week | 196.00 – 287.20 |
| Div. Yield | — |

**Recent News:**
- [Elite Undervalued Stocks To Own In November 2026](https://finance.yahoo.com/markets/stocks/articles/elite-undervalued-stocks-own-november-043945272.html) — Simply Wall St.
- [Boeing (BA) ULA Rocket Failure Halts Deployment Of 40 Broadband Satellites](https://finance.yahoo.com/markets/stocks/articles/boeing-ba-ula-rocket-failure-001959401.html) — Simply Wall St.

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 626.41 ▼2.38% |
| Market Cap | $1.60T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.0% / 32.9% / 31.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 5.87 |
| Beta | 1.28 |
| 52-Week | 520.26 – 779.82 |
| Div. Yield | — |

**Recent News:**
- [Daniel Loeb’s Third Point Returned to Nvidia Stock Just Before Its Fall](https://finance.yahoo.com/m/04da2c81-3de5-3ff0-bb2d-6210189e6e20/daniel-loeb%E2%80%99s-third-point.html) — Barrons.com
- [Stock Market Today, Nov. 16: Snap Falls Amid Tech Sector Sell-Off and Ongoing Youth Social Media Addiction Lawsuit Exposure](https://finance.yahoo.com/markets/stocks/articles/stock-market-today-nov-16-223308256.html) — Motley Fool

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 333.40 ▼8.50% |
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
- [AMD, MU, SKHY, AVGO: Chip Stocks Ease Overnight After Selloff On New US Chip Restrictions Targeting China](https://finance.yahoo.com/technology/articles/amd-mu-skhy-avgo-chip-040420540.html) — Stocktwits
- [Why Broadcom Stock Got Mashed on Monday](https://finance.yahoo.com/markets/stocks/articles/why-broadcom-stock-got-mashed-010403830.html) — Motley Fool
- [Broadcom vs. Nvidia: Which Semiconductor Stock Is the Better AI Buy over the Next 3 Years?](https://finance.yahoo.com/technology/ai/articles/broadcom-vs-nvidia-semiconductor-stock-002202308.html) — Motley Fool

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 175.05 ▼12.38% |
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
- [Arm Holdings (ARM) Stock Dropped, So What Is Driving Attention Now?](https://finance.yahoo.com/markets/stocks/articles/arm-holdings-arm-stock-dropped-221118439.html) — Simply Wall St.
- [Why Arm Holdings Plunged Today](https://finance.yahoo.com/markets/stocks/articles/why-arm-holdings-plunged-today-210632944.html) — Motley Fool
- [Arm Stocks Slide 6.72% as Nvidia CEO Search Keeps Rene Haas in Focus](https://finance.yahoo.com/markets/stocks/articles/arm-stocks-slide-6-72-174928553.html) — GuruFocus.com

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 160.39 ▼4.52% |
| Market Cap | $369.97B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.7% / 45.6% / 50.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 34.37 |
| Beta | 1.62 |
| 52-Week | 106.37 – 212.94 |
| Div. Yield | — |

**Recent News:**
- [3 Founder Led Stocks With Revenue Growth Over 32%](https://finance.yahoo.com/markets/stocks/articles/3-founder-led-stocks-revenue-231953046.html) — Simply Wall St.
- [Top 3 Growth Stocks To Watch In November 2026](https://finance.yahoo.com/markets/stocks/articles/top-3-growth-stocks-watch-211558743.html) — Simply Wall St.
- [Direxion and Anthony Pompliano's Silvia Join Forces to Help Investors Rethink Income](https://finance.yahoo.com/markets/options/articles/direxion-anthony-pomplianos-silvia-join-210300213.html) — PR Newswire

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 25.02 ▼7.28% |
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
- [Wall Street ends sharply lower on AI jitters ahead of Nvidia results, Anthropic IPO](https://finance.yahoo.com/news/p-500-nasdaq-futures-slide-104351968.html) — Reuters
- [Could Nvidia Be the Next Super Micro?](https://finance.yahoo.com/markets/stocks/articles/could-nvidia-next-super-micro-182802080.html) — Motley Fool
- [AI Trade Is Tanking the S&P 500, But Average Stock Sees Monthly Gains](https://finance.yahoo.com/m/76dd9d9e-d900-3d63-8844-16483036789a/ai-trade-is-tanking-the-s%26p.html) — Barrons.com

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 379.74 ▼2.69% |
| Market Cap | $1.50T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.3% / 3.3% / 3.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.78 |
| Beta | 1.74 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Nvidia set for first earnings call since Jensen Huang's resignation](https://finance.yahoo.com/markets/stocks/articles/nvidia-set-first-earnings-call-050234300.html) — USA TODAY
- [Stephen King Tells Elon Musk ‘You Sound Like Trump’ After Billionaire Warns Democrats Will ‘Execute Their Plan to End Democracy in America’](https://finance.yahoo.com/media-advertising/articles/stephen-king-tells-elon-musk-033006336.html) — Benzinga
- [Cathie Wood’s $2.2 Billion Bet on Elon Musk Could Soon Become One Giant Stock](https://finance.yahoo.com/markets/stocks/articles/cathie-wood-2-2-billion-032300304.html) — 24/7 Wall St.

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 680.26 ▼2.26% |
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
- [BTAL Buys the Market’s Calmest Stocks and Shorts Its Wildest. It Is Built to Rise When Stocks Fall](https://finance.yahoo.com/markets/options/articles/btal-buys-market-calmest-stocks-130319481.html) — 24/7 Wall St.
- [Investing $500 Per Month in VOO Starting at Age 25 Could Build a Portfolio Worth Over $3 Million by Retirement](https://finance.yahoo.com/markets/stocks/articles/investing-500-per-month-voo-125000477.html) — Motley Fool
- [If You Had Invested $10,000 in the Vanguard S&P 500 ETF (VOO) in 2016, Here's What You Would Have Today](https://finance.yahoo.com/markets/stocks/articles/had-invested-10-000-vanguard-124300986.html) — Motley Fool

## 🌍 News

### 🌍 World News
> `2026-11-17 13:10:49`

- [Five EU countries announce migrant deportation centre in Rwanda](https://www.bbc.co.uk/news/articles/cw987343352go?at_medium=RSS&at_campaign=rss)
- [Houthi rebel advance in Yemen may further destabilise global economy](https://www.bbc.co.uk/news/articles/cmy97qperq9eo?at_medium=RSS&at_campaign=rss)
- [Nvidia dismisses 'Bring Jensen Back' campaign as Trump backs effort to reinstate ex CEO](https://www.bbc.co.uk/news/articles/cry49plv8v3go?at_medium=RSS&at_campaign=rss)
- [Landmark Crimea bridge hit as Russia reports biggest Ukrainian drone attack of war](https://www.bbc.co.uk/news/articles/ckx27v6dpjz0o?at_medium=RSS&at_campaign=rss)
- [When will we see Robert Pattinson as Bond in cinemas?](https://www.bbc.co.uk/news/videos/cmd91xjd9zk2o?at_medium=RSS&at_campaign=rss)
- [Forensic expert says his analysis of autopsy photos suggests Epstein was killed](https://www.bbc.co.uk/news/articles/c5n4exg1kkmyo?at_medium=RSS&at_campaign=rss)
- [Lindsay Clancy to face retrial next year for deaths of her three children](https://www.bbc.co.uk/news/articles/cw5y1v8de35go?at_medium=RSS&at_campaign=rss)
- [Two mass shootings in South Africa leave 17 dead](https://www.bbc.co.uk/news/articles/c8y5x3n4kywpo?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-11-17 13:11:04`

#### AI Tips
# 📷 2026年11月17日 攝影顧問日報

## 【購買優惠】台灣買相機裝備指南

#### 各通路優劣分析

| 通路 | 適合買什麼 | 注意事項 |
|------|-----------|---------|
| **PChome 24h** | 公司貨機身、鏡頭、記憶卡 | 常有「品牌日」折價券，可疊加信用卡回饋；到貨快但價格偏硬 |
| **momo購物** | 配件、腳架、包包、燈具 | 檔期活動折扣深（雙11餘溫、黑五預熱），比價後常最低 |
| **光華商場** | 機身+鏡頭議價、二手鏡 | 可現場試機、殺價空間大；認明「彩虹/正成」等代理商保固貼紙 |
| **日本代購** | 日系品牌機身（Sony/Canon/Nikon/Fuji） | 日圓匯率佳時價差可達 15–25%，但**無台灣保固**、維修需寄回；留意電壓與語言選單 |
| **二手（旋轉拍賣/DCView/攝影社群）** | 鏡頭、副機、老鏡 | 面交驗快門數、感光元件壞點、鏡頭霉斑；要求當場試拍 |

#### 11月檔期攻略（具體行動）
1. **雙11餘溫（11/11–11/20）**：momo、PChome 常有「延長加碼」，鎖定購物車降價通知。
2. **黑五預熱（11月下旬）**：留意 PChome「黑色購物節」與代理商（正成、彩虹）官網組合價。
3. **年底出清**：11月底–12月，舊機型（如上一代機身）降價最兇，是撿公司貨好時機。
4. **實戰建議**：先在 PChome 查「公司貨定價」當基準 → 光華現場議價 → 若價差 <10% 選公司貨保固；>20% 再考慮代購。

---

## 【今日攝影技巧】逆光下的「

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-11-17 13:11:09`

#### AI Tips
# 台灣潛水裝備購買指南（2026年11月）

## 購買優惠

**實體店（依地區）**
- **台北**：潛水貨倉（品項齊、可試穿）、BlueTrend 藍色趨勢（自由潛水強項）、Decathlon 迪卡儂（入門平價）
- **台中**：海人潛水、潛水人
- **高雄**：大洋潛水、海世界
- **墾丁**：旺季店家多，可現場比價＋試裝，但11月部分店家縮短營業時間，出發前先電話確認

**線上**
- **PChome / momo**：適合買配件（蛙鞋扣、防水袋、防霧劑），比價快
- **蝦皮**：找有實體店的賣家（看評價＋是否提供保固），避免來路不明的水貨調節器
- **Facebook 社團**：「台灣潛水二手交流」「潛水裝備買賣」— 11月淡季釋出多，二手 BC、調節器可撿便宜，但**調節器、電腦錶務必要求原廠保卡＋送驗紀錄**

**11月時機點**
- **雙11（11/11）**：線上配件、潛水衣折扣最多，先加購物車比價
- **黑色星期五（11月底）**：國際品牌（Scubapro、Mares、Garmin）官網／代理商常有促銷
- **淡季議價**：11月東北季風起，墾丁、東北角店家生意轉淡，實體店議價空間比夏天大，可談「整套購買」折扣
- **注意**：11月東北角浪大、能見度下降，北部潛水多轉室內池

#### r/scuba
- [26C degree water temp recommended wetsuit setup](https://www.reddit.com/r/scuba/comments/1xxvn8d/26c_degree_water_temp_recommended_wetsuit_setup/)
- [How to I add a valve/safety strap to my BCD?](https://www.reddit.com/r/scuba/comments/1xxo7x0/how_to_i_add_a_valvesafety_strap_to_my_bcd/)
- [How to size for a wetsuit](https://www.reddit.com/r/scuba/comments/1xxqokf/how_to_size_for_a_wetsuit/)
- [Help with diving gear](https://www.reddit.com/r/scuba/comments/1xx9fdh/help_with_diving_gear/)

### ✈️ Flight Tips
> `2026-11-17 13:10:59`

#### AI Flight Tips — November
# November Flight Deals from Taiwan (TPE/TSA) — Expert Tips

**Japan (Tokyo/Osaka/Sapporo)**
- November is **peak** for autumn foliage (late Nov especially) — book 8–10 weeks out; Sapporo shoulder-season is cheaper than Tokyo/Osaka.
- Cheapest: Peach, Scoot, Tigerair Taiwan to Tokyo/Osaka; for Sapporo compare Jetstar Japan via Tokyo or direct Tigerair Taiwan.
- Watch Taiwan carrier "autumn Japan" promos (EVA/China Airlines flash sales) and LCC Tuesday sales; avoid Nov 20–30 foliage peak pricing.

**Thailand (Bangkok/Chiang Mai)**
- November is **shoulder-to-peak** — cool season starts, Chiang Mai Loy Krathong (late Nov) spikes prices; Bangkok is cheaper.
- Book 6–8 weeks out; Chiang Mai during festival needs 10+ weeks.
- Cheapest: Thai Lion Air, Nok Air, Vietjet via Hanoi; direct budget = Tigerair Taiwan/Thai AirAsia.
- Watch AirAsia/Tigerair "Thailand cool season" promos and Vietjet 0đ-style sales for transits.

**Europe (major cities)**
- November is **off-peak** (pre-Christmas) — cheapest Europe window of the year; book 10–14 weeks out for best fares.
- Cheapest: China Airlines/EVA direct to Vienna/Amsterdam/Frankfurt; or Turkish/Emirates via Istanbul/Dubai for Southern Europe.
- Watch Black Friday (late Nov) airline sales and China Airlines "early bird" Europe promos; avoid Dec 15+ return.

**USA (West/East Coast)**
- November is **shoulder** — pre-Thanksgiving cheap, Thanksgiving week (Nov 20–30) expensive; book 10–12 weeks out.
- Cheapest: EVA/China Airlines direct to LAX/SFO/SEA; East Coast via Delta/United or Korean Air via Seoul.
- Watch Thanksgiving-avoidance fares and Black Friday sales; TPE–LAX often dips below TPE–NYC by 30%.

**Egypt (Cairo)**
- November is **peak** (cool, ideal sightseeing) — book 12–16 weeks out; limited direct capacity keeps fares high.
- Cheapest: Emirates/Qatar/Turkish via Gulf/Istanbul; no direct TPE–CAI — one-stop is standard.
- Watch Gulf carrier promos and Egyptair seasonal sales; bundle with Nile cruise packages for value.

**Australia (Sydney/Melbourne)**
- November is **shoulder-to-peak** (pre-summer) — book 8–12 weeks out; Melbourne slightly cheaper than Sydney.
- Cheapest: China Airlines/EVA direct to SYD/MEL; or Scoot via Singapore for budget.
- Watch China Airlines "Australia summer" promos and Scoot sale fares; avoid Dec 20+ Christmas peak.

**Quick rule:** November = book Japan/Thailand now (6–10 wks), Europe/USA 10–14 wks, Egypt 12–16 wks, Australia 8–12 wks. Set fare alerts and pounce on Tuesday/Black Friday sales.

### 🗺️ Travel Deals
> `2026-11-17 13:10:53`

#### r/solotravel
- [First day solo in Australia and I'm already overwhelmed. Does it get better?](https://www.reddit.com/r/solotravel/comments/1xxhfet/first_day_solo_in_australia_and_im_already/)
- [Planning a 4–5 month stay in Egypt, including a longer stay in Aswan – looking for advice](https://www.reddit.com/r/solotravel/comments/1xxvwxn/planning_a_45_month_stay_in_egypt_including_a/)
- [32 F - Looking for help about my thailand trip](https://www.reddit.com/r/solotravel/comments/1xx35tu/32_f_looking_for_help_about_my_thailand_trip/)
- [Singapore tourist visa alone](https://www.reddit.com/r/solotravel/comments/1xxifbx/singapore_tourist_visa_alone/)
- [Japan and southern Thailand in 4 weeks – am I trying to do too much?](https://www.reddit.com/r/solotravel/comments/1xwto04/japan_and_southern_thailand_in_4_weeks_am_i/)

## 📚 Learning

### 📚 Learning — Finance
> `2026-11-17 13:11:12`

#### 📚 Today's Concept: Sector rotation strategy

What it is: Sector rotation is an investing strategy where you shift money between industry sectors (tech, energy, healthcare, utilities) based on where we are in the economic cycle. The idea is that different sectors outperform at different stages—early recovery favors consumer discretionary and tech, while late-cycle favors energy and staples.

Why it matters: It lets you tilt your portfolio toward sectors likely to benefit from the current macro backdrop, potentially beating a static index allocation. It's a way to express a view on the economy without picking individual stocks.

Example: Suppose you expect a recession to end. You rotate $100,000 from defensive utilities into consumer discretionary. If that sector returns 25% over the next year versus 8% for utilities, you gain $25,000 instead of $8,000—a $17,000 edge from the rotation alone.

Rule of thumb: Confirm the rotation with at least two signals (e.g., falling rates plus rising PMI) before moving—sector calls based on a single data point are usually noise, and whipsawing between sectors racks up costs and taxes.

### 🧩 LeetCode Blind 100
> `2026-11-17 13:11:17`

#### 🧩 Blind 100 — 72. Edit Distance [2D DP]
**連結:** https://leetcode.com/problems/edit-distance/
> 📅 **Today's Daily Challenge:** #2879 Minimum Changes to Make K Semi-palindromes [Hard] — Tags: Two Pointers, String, Dynamic Programming — https://leetcode.com/problems/minimum-changes-to-make-k-semi-palindromes/

## **Problem Type:** 2D DP / String DP (Edit Distance family)

**Key Insight:** At each position `(i, j)`, if `word1[i-1] == word2[j-1]`, no operation needed → inherit `dp[i-1][j-1]`. Otherwise, take `1 + min(insert, delete, replace)` = `1 + min(dp[i][j-1], dp[i-1][j], dp[i-1][j-1])`.

**Approach:**
1. Let `dp[i][j]` = min ops to convert `word1[:i]` → `word2[:j]`.
2. Base cases: `dp[i][0] = i` (delete all), `dp[0][j] = j` (insert all).
3. Fill row by row. Match → diagonal; mismatch → `1 + min(left, up, diag)`.
4. Return `dp[m][n]`.

**Python3 Solution:**
```python
class Solution:
    def minDistance(self, word1: str, word2: str) -> int:
        m, n = len(word1), len(word2)
        # Ensure word2 is the shorter one for space optimization
        if m < n:
            word1, word2 = word2, word1
            m, n = n, m

        prev = list(range(n + 1))
        for i in range(1, m + 1):
            cur = [i] + [0] * n
            c1 = word1[i - 1]
            for j in range(1, n + 1):
                if c1 == word2[j - 1]:
                    cur[j] = prev[j - 1]
                else:
                    cur[j] = 1 + min(prev[j], cur[j - 1], prev[j - 1])
            prev = cur
        return prev[n]
```

**Complexity:** Time O(m·n) | Space O(min(m, n))

**Blind 100 Note:** Classic 2D DP on strings — teaches the "three-operation recurrence" (insert/delete/replace) that generalizes to LCS, Longest Palindromic Subsequence, and Delete Operation for Two Strings. Practice: **1143. LCS**, **583. Delete Operation for Two Strings**, **516. Longest Palindromic Subsequence**, **10. Regular Expression Matching**.

**Contest Tips:**
- **Swap to make `word2` shorter** — cuts space to O(min(m,n)); a common interview flex.
- **Off-by-one:** `dp` is `(m+1) × (n+1)`; loop `i` from 1, index `word1[i-1]`.
- **Don't confuse insert/delete direction** — `dp[i][j-1]` = insert into word1, `dp[i-1][j]` = delete from word1.
- **Edge cases:** empty strings → answer is `len(other)`; identical strings → 0.
- **No need for full 2D table** in contests — rolling array is faster and passes all tests.
- If TLE on huge inputs, remember this is inherently O(mn); no shortcut exists for general edit distance.

### 📷 Learning — Photography
> `2026-11-17 13:11:24`

#### 📷 Today's Concept: Special — Shooting Coffee and Beverages (Splash, Steam)

**What it is:** Splash and steam photography freezes or accentuates the dynamic elements of a drink—the crown of a pour, a falling sugar cube, or backlit vapor—using fast shutter speeds or controlled continuous light. It turns an ordinary cup into a kinetic, tactile subject.

**Why it matters:** Motion and atmosphere make beverages feel alive and premium; a frozen splash conveys freshness and energy, while glowing steam adds warmth and mood that a static cup can't.

**How to apply it:**
1. **Control the background:** Use a dark, matte backdrop (black foam board) so light catches only the liquid and vapor.
2. **Backlight the action:** Place a flash or LED behind and slightly above the drink, angled toward camera—this illuminates splashes and makes steam visible.
3. **Freeze the splash:** For droplets, use flash (not shutter speed) to freeze motion—set flash to 1/8–1/32 power for short duration. Drop a sugar cube or pour from height and shoot in burst.
4. **Reveal the steam:** Kill ambient light, backlight the cup, and shoot a slow shutter (1/30–1/60s) on a tripod so vapor streaks softly.
5. **Shoot tethered or burst:** Fire many frames—timing is luck; volume wins.

**Sony A7C tip:** Use Silent Shooting (off) is fine, but enable **Continuous Hi+ burst** and pair with a fast prime like the **FE 35mm f/1.8** close-focusing for tight, backlit pours; manual focus peaking helps lock on the splash zone.

**Common mistake:** Relying on shutter speed alone to freeze splashes—ambient light blurs droplets. Kill ambient and let a short flash duration do the freezing.

### 📚 Learning — Tech
> `2026-11-17 13:11:19`

#### 📚 Today's Concept: API Versioning Strategies

**What it is:** API versioning is the practice of managing changes to an API over time so existing clients keep working while new features ship. It lets you evolve contracts without breaking consumers who depend on older behavior.

**When to use it:** Use it whenever a change is breaking—removing fields, changing types, or altering semantics. E.g., a payments API needs to change its refund response shape; versioning lets new integrations adopt it while legacy mobile apps on v1 keep functioning.

**Example:**
```
GET /v1/users/42        → { "name": "Ada" }
GET /v2/users/42        → { "firstName": "Ada", "lastName": "Lovelace" }
```
(Alternatives: header-based `Accept: application/vnd.api+json;version=2`, or query param `?version=2`.)

**Gotcha:** Versioning isn't free—every version is a maintenance burden you support indefinitely. Teams often version too eagerly (for additive, non-breaking changes) and end up with v1–v7 sprawl. Prefer additive changes and deprecation windows; version only when you truly must break compatibility.

### 🎬 Learning — YouTube
> `2026-11-17 13:11:27`

#### 🎬 今日主題：旅遊 — 一個人旅遊 Vlog 的自拍技巧與腳架使用
**類別：** 旅遊

**是什麼：** 一個人旅遊 Vlog 的自拍技巧，是指用腳架＋相機自己完成「主持人入鏡＋環境畫面」的拍攝流程。核心是讓畫面有互動感，而不是只有風景空景。

**為什麼重要：** 一個人旅行沒有旅伴幫拍，若不懂腳架與自拍節奏，影片容易變成無聊的風景幻燈片，觀眾留不住。

**怎麼做：**
1. 腳架選輕量碳纖維＋藍牙遙控，A7C 開翻轉螢幕確認構圖。
2. 先拍「定點自拍」：腳架架好、走進畫面講一句話，建立人味。
3. 用「走位法」：相機固定，你往前走或轉身，製造動態感。
4. 每個景點拍 3 種鏡頭：自拍講話、環境空景、細節特寫。
5. 收音用領夾麥，腳架旁放手機當備援。

**新手常犯的錯：** 腳架架太高、構圖只拍大頭。避免方式：鏡頭與胸口同高，留環境背景。

**延伸 idea：** 「一人一腳架玩老街」— 用同一支腳架完成自拍開場、小吃特寫、街景走位，剪成 3 分鐘 Vlog，順便測試 AI 剪輯自動上字幕。
