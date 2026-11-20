---
date: 2026-11-20
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-11-20

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

- **Anthropic 歷史性 IPO + 全AI股拋售潮並存**：Anthropic 成為首家純 AI 上市公司，但同日科技股遭血洗（AMD −7.72%、TAIEX −5.12%）。對台灣供應鏈從業者，這是「基本面敘事 vs. 市場風險偏好」的經典分歧日。([BBC](https://www.bbc.co.uk/news/articles/c3x29ggenz12o) / [Reuters](https://www.reuters.com/business/finance/anthropics-historic-debut-put-ais-promise-peril-wall-st-test-2026-11-19/))
- **台股單日 −5.12% 為全球最重災區**：TAIEX 36,458 點，跌幅遠超 S&P（−2.24%）與日經（−4.22%），家鄉市場曝險需留意；AVGO 是 watchlist 唯一逆勢上漲（+1.48%），資金明顯輪動至網通/客製 ASIC。([Yahoo](https://finance.yahoo.com/markets/stocks/articles/tech-takes-beating-ai-trade-030257717.html))
- **Postgres 19 正式上線（Neon / Databricks Lakebase）**：值得排入升級評估；搭配今日「連線池」學習主題，正好檢視 pool 設定與 PgBouncer 架構。([Databricks](https://www.databricks.com/blog/postgresql-19-available-lakebase))
- **Gemini API Tool Retrieval 上線**：讓 agent 存取數百工具卻更省 token — 對正在做 agent 應用的工程師是立即可用的降本手段。([Google](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/))
- **11 月底機票/購物雙檔期**：Black Friday（11/27 前後）是歐洲/澳洲線與相機、潛水配件年底最後大檔；日本避開 11/23 勞動感謝日連假。([Flight Tips 段落](#))

---

- 💻 **Tech**: Anthropic 主導新聞（IPO + Claude 解黑洞物理難題），Gemini 4 Neon 登頂 MEI；speculative decoding 與 agent 安全 benchmark 有新進展。
- 🤖 **AI 公司動態**: Anthropic 逆勢吸金、Tesla Optimus 家事時間表（12–18 月，roadmap 宣稱）、robotaxi 擴至 Dallas；OpenAI 今日無消息。
- 🔵 **Google**: Tool Retrieval、Tunix+Gemma 4 多輪 agentic RL、Streaming DiLoCo、Gemini 4 Hydrogen（機器人）、AI Studio 全端 Android。
- 📈 **Markets**: 全球全面下殺，台股 −5.12% 最重，避險情緒主導、非單一產業問題。
- 🏠 **台灣房市**: 量縮價盤，蛋黃區高總價抗跌；自住鎖定捷運+學區成屋議價（桃園中壢、台中北屯、高雄三民 1,000–2,000 萬帶）。
- 📊 **Watchlist**: 全線收黑，AMD −7.72% 最慘、AVGO 唯一收紅；估值數據全 N/A，僅能看價格行為。
- 🌍 **World News**: Anthropic IPO、ICJ 裁定緬甸對羅興亞種族滅絕、歐洲對俄談判統一立場、川普-普丁-習三方「和平宣言」、葉門 Taiz 圍城。
- 📷 **Camera Deals**: 通路比價表（PChome/momo/光華/日本代購/二手）+ 11 月檔期攻略；黑色星期五為年底最後大檔。
- 🤿 **Dive Gear Deals**: 北台灣實體店與線上通路指南；11 月季末出清，二手 BC/防寒衣可談 5–6 折，調節器/電腦錶須索保養紀錄。
- ✈️ **Flight Tips**: 11 月各航線省錢窗口 — 歐洲全年最便宜、埃及旺季、澳洲旺季前；避開美國感恩節週（11/20–30）。
- 📚 **Finance**: FCF 概念 — 現金流難操

---

## 💻 Tech

### 💻 Tech & AI
> `2026-11-20 12:08:18`

#### Hacker News
- [Gemini 4 Neon is the new #1 on the Models Engineering Index](https://git-aarvin.github.io/mei/) ⭐241
- [Anthropic’s Nasdaq debut](https://www.reuters.com/business/finance/anthropics-historic-debut-put-ais-promise-peril-wall-st-test-2026-11-19/) ⭐994
- [Claude solves two open problems in the physics of black holes](https://www.anthropic.com/research/claude-black-hole-physics) ⭐429
- [Garage Door Spam](https://blog.harrison.page/garage-door-spam/) ⭐786
- [The 98% Slot Machine: How Paid Advertising Became an Extraction Tax](https://globalcommercegraph.com/writing/the-ninety-eight-percent-slot-machine) ⭐231
- [Weight-Space Programming builds neural networks like a 1990s researcher](https://notesbylex.com/weight-space-programming-1990s) ⭐33
- [Postgres 19 is out, and it's available on Neon and Databricks Lakebase](https://www.databricks.com/blog/postgresql-19-available-lakebase) ⭐25
- [Should governments slow frontier AI? Jacob Coxon and Robin Hanson debate [video]](https://www.youtube.com/watch?v=lwfewYL7X0o) ⭐87
- [Unlocking Stable On-Policy RL on TPU with Bitwise-Zero Train–Inference Mismatch](https://developers.googleblog.com/unlocking-stable-on-policy-rl-on-tpu-with-bitwise-zero-traininference-mismatch/) ⭐5
- [An Oregon library ditched Dewey Decimal and got people excited about books again](https://www.fastcompany.com/91597520/oregon-library-ditched-dewey-decimal-wayfinding-system) ⭐212

#### HuggingFace
- [VSpark: Speculative Decoding for Autoregressive Vision-Language-Action Models](https://huggingface.co/papers/2611.22666)
- [WeVisForensics: Self-Evolving Agent for Omni AI-Generated Video Detection](https://huggingface.co/papers/2611.21373)
- [On-Policy Morphing into Hybrid Attention Models](https://huggingface.co/papers/2611.24809)
- [NarrowSpec: Draft Hidden Width Need Not Match the Target in Speculative Decoding](https://huggingface.co/papers/2611.23835)
- [Unfinished-Bench: Measuring Rule Violations by Persistent Agents in Realistic Work Environments](https://huggingface.co/papers/2611.17460)
- [How Far Can Untrained Neural Networks Go in Anomaly Detection? From Tables to Pixels](https://huggingface.co/papers/2611.08136)

#### ArXiv
- [When Do Rankings Beat Signs? Gradient Direction Recovery under Even Nuisance](http://arxiv.org/abs/2611.26055v1)
- [Reference-Free Humanoid Skateboarding via Termination-Shaped Reinforcement Learning](http://arxiv.org/abs/2611.26054v1)
- [Studying AI Act Mentions: A first look at the impact of the European Union's AI regulation on Hugging Face](http://arxiv.org/abs/2611.26050v1)
- [Fixing the Twin, Not the Detector: Sim-to-Real Roadside LiDAR Detection from Digital-Twin Data](http://arxiv.org/abs/2611.26035v1)
- [SEOYUN: Refusal-Inducing Exam Documents for AI-Glasses Pipelines](http://arxiv.org/abs/2611.26033v1)
- [The Delayed Societal Cost of Unfairness](http://arxiv.org/abs/2611.26030v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-11-20 12:08:26`

#### Tesla
- [Tech takes a beating as AI trade comes unstuck despite Anthropic surge](https://finance.yahoo.com/markets/stocks/articles/tech-takes-beating-ai-trade-030257717.html)
- [Is Tech in a Bear Market? 20 Tech Stocks Fall Up to 76% From Highs](https://finance.yahoo.com/markets/stocks/articles/tech-bear-market-20-tech-224039016.html)
- [Musk Says Optimus Will Do the Dishes “Within 12-18 Months.” Here’s Where Tesla’s Robot Stands](https://finance.yahoo.com/technology/ai/articles/musk-says-optimus-dishes-within-223752612.html)
- [Tesla Robo-Taxi Expands to Dallas. It Isn’t Enough.](https://finance.yahoo.com/m/bb73f711-c5b1-3f23-8b24-3dd6a248b942/tesla-robo-taxi-expands-to.html)

### 🔵 Google 動態
> `2026-11-20 12:08:22`

#### Google AI Blog
- [Introducing Tool Retrieval in the Gemini API](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/)
- [Walter Isaacson on curiosity and creativity in the AI age.](https://blog.google/innovation-and-ai/technology/ai/dialogues-walter-isaacson/)
- [The Gemini app is now available on lower-memory Android devices.](https://blog.google/innovation-and-ai/products/gemini-app/gemini-lower-memory-devices/)
- [Put Gemini to work for you](https://blog.google/innovation-and-ai/products/gemini-app/tasks-in-gemini-free-new-features/)
- [New Ask Maps features to help with holiday travel and prep](https://blog.google/products-and-platforms/products/maps/ask-maps-holiday-travel-features-2026/)
#### Google Blog
- [ICYMI: Transfer your history from other AI apps into Gemini.](https://blog.google/innovation-and-ai/products/gemini-app/switch-ai-assistants-transfer-history/)
- [How we’re putting one of quantum mechanics’ deepest features to the test at scale.](https://blog.google/innovation-and-ai/models-and-research/quantum-computing/putting-one-of-quantum-mechanics-deepest-features-to-test-at-scale/)
- [Introducing Tool Retrieval in the Gemini API](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/)
- [Walter Isaacson on curiosity and creativity in the AI age.](https://blog.google/innovation-and-ai/technology/ai/dialogues-walter-isaacson/)
- [A smarter way to track and buy clean energy](https://blog.google/company-news/outreach-and-initiatives/sustainability/granular-certificates-clean-energy-2026/)
#### Google Developers
- [Multi-Turn Agentic Reinforcement Learning with Tunix and Gemma 4 on Google TPUs](https://developers.googleblog.com/multi-turn-agentic-reinforcement-learning-with-tunix-and-gemma-4-on-google-tpus/)
- [Distributed LLM Training Across Metros: Streaming DiLoCo in MaxText](https://developers.googleblog.com/distributed-llm-training-across-metros-streaming-diloco-in-maxtext/)
- [Gemini 4 Hydrogen: a faster model for general purpose robotics](https://developers.googleblog.com/gemini-hydrogen-for-robotics/)
- [Accelerating development for massive Git repositories](https://developers.googleblog.com/accelerating-development-for-massive-git-repositories/)
- [Build full-stack Android apps with Gemini in Google AI Studio](https://developers.googleblog.com/build-full-stack-android-apps-with-gemini-in-google-ai-studio/)

## 📈 Finance

### 📈 Markets Overview
> `2026-11-20 12:08:28`

#### Indices
- S&P 500: 7,175.83 ▼2.24%
- 台股加權: 36,458.21 ▼5.12%
- 日經 225: 56,937.00 ▼4.22%

### 🏠 台灣房市
> `2026-11-20 12:09:31`

#### AI 分析
## 台灣房市快評（2026-11-20）

**1. 整體趨勢**
央行信用管制與高利率環境持續壓抑成交量，市場呈「量縮價盤」格局；但高總價住宅大樓實價登錄仍見單價 27–46 萬/㎡（約 90–150 萬/坪）成交，顯示蛋黃區資產抗跌、資金集中化明顯。預售與成屋讓利案增加，買方議價空間擴大。

**2. 值得注意的地區/物件**
- **高總價蛋黃區大樓**：實登 115S3 多筆 144–963㎡、總價 5,700 萬–2.97 億成交，單價最高約 45.6 萬/㎡（≈151 萬/坪），台北市中心、松江南京、中山區店面/商辦租案熱絡，商用與都更題材仍吸金。
- **桃園中壢、平鎮**：A21 捷運、交流道、SOGO 海華商圈租案與平興學區透天掛牌活躍，屬「捷運+學區+低總價」剛需熱區。
- **台中北屯、沙鹿**：北屯全新未住大四房雙平車、沙鹿鹿陽國小旁整理別墅，反映台中「總價帶 1,500–2,500 萬」換屋與首購並進。
- **高雄三民**：高樓層 2 房+車位首購產品，屬南部低基期、自住剛需型。

**3. 對自住者建議**
優先鎖定「捷運/學區+成屋」議價，桃園中壢、台中北屯、高雄三民等總價 1,000–2,000 萬帶產品，善用賣方讓利與貸款寬限期，避免追高預售。

**4. 對投資者建議**
短線炒作空間有限，聚焦蛋黃區商辦/店面租金收益與都更危老題材；高總價住宅流動性差，宜以長期持有、租金報酬率 2.5% 以上為門檻，避開供給量大的重劃區。

**5. 風險提醒**
信用管制未鬆綁、餘屋去化壓力與利率走向為三大變數，進場前務必查實登比價、確認貸款成數，保留現金流緩衝。

#### 591 最新
- [台中市沙鹿區保順三街💕專任獨家~沙鹿鹿陽國小旁臨路全新整理朝南美別墅💕](https://sale.591.com.tw/sale-detail-21291053.html)
- [桃園市中壢區南園二路可租補!近A21捷運.中壢交流道.SOGO海華商圈精美三房車](https://rent.591.com.tw/rent-detail-22380632.html)
- [台北市中山區南京東路二段K64租松江南京站漂亮裝潢黃金店面](https://rent.591.com.tw/rent-detail-22336019.html)
- [桃園市平鎮區復旦路二段獨家｜小夫妻帶您買好房｜聯新平興學區超大地坪透天](https://sale.591.com.tw/sale-detail-21291052.html)
- [台北市中山區建國北路一段☀️❤️松江南京｜玻璃帷幕｜挑高大廳｜方正採光佳](https://rent.591.com.tw/rent-detail-22380631.html)
- [新北市淡水區中山北路三段31巷專約|W丰上｜日式禪風景觀三房+平車](https://sale.591.com.tw/sale-detail-21291049.html)
- [高雄市三民區遼北街悅讀綠森活首購高樓漂亮2房+車位](https://sale.591.com.tw/sale-detail-21291047.html)
- [台中市北屯區松竹路二段178巷北屯🍊北屯米蘭雙星全新未住大四房B1柱邊連號雙平車](https://sale.591.com.tw/sale-detail-21291048.html)

#### 實價登錄 (115S3) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 住宅大樓(11層含以上有電梯) | 963.3㎡ | 29664萬 | 307937元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 399.6㎡ | 14468萬 | 449312元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 379.7㎡ | 10438萬 | 274908元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 267.7㎡ | 8558萬 | 367305元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 144.7㎡ | 5700萬 | 456525元/㎡ |

### 📊 Watchlist
> `2026-11-20 12:08:58`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 145.98 ▼3.30% |
| Market Cap | $3.52T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.9% / 66.1% / 62.5% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.20 |
| Beta | 2.22 |
| 52-Week | 145.71 – 243.37 |
| Div. Yield | — |

**Recent News:**
- [Dan Ives Calls Tech Selloff a Panic Moment but Anthropic IPO Shows Proof of Demand](https://finance.yahoo.com/technology/ai/articles/dan-ives-calls-tech-selloff-040000322.html) — BeInCrypto
- [Why Did NVDA, NIO, ONDS Stocks Tumble To 52-Week Lows Today?](https://finance.yahoo.com/markets/stocks/articles/why-did-nvda-nio-onds-035448393.html) — Stocktwits
- [Dow Jones Futures: Techs Slide, Anthropic Retreats After Ugly Market Reversal To New Lows](https://finance.yahoo.com/m/9e02231d-41cd-31ac-b37f-993325b8a4ca/dow-jones-futures%3A-techs.html) — Investor's Business Daily

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 489.19 ▼7.72% |
| Market Cap | $802.31B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.7% / 17.7% / 16.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 11.70 |
| Beta | 2.49 |
| 52-Week | 188.22 – 658.52 |
| Div. Yield | — |

**Recent News:**
- [Dan Ives Calls Tech Selloff a Panic Moment but Anthropic IPO Shows Proof of Demand](https://finance.yahoo.com/technology/ai/articles/dan-ives-calls-tech-selloff-040000322.html) — BeInCrypto
- [Dow Jones Futures: Techs Slide, Anthropic Retreats After Ugly Market Reversal To New Lows](https://finance.yahoo.com/m/9e02231d-41cd-31ac-b37f-993325b8a4ca/dow-jones-futures%3A-techs.html) — Investor's Business Daily
- [Nikkei 225 Falls 4.5% and SoftBank Plunges 15% as Wall Street’s AI Selloff Puts Asian Stocks on Track for Their Worst Week Since 2020](https://finance.yahoo.com/markets/world-indices/articles/nikkei-225-falls-4-5-034108190.html) — 24/7 Wall St.

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 498.30 ▼1.78% |
| Market Cap | $3.70T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.7% / 47.1% / 41.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 7.86 |
| Beta | 1.04 |
| 52-Week | 349.20 – 559.15 |
| Div. Yield | — |

**Recent News:**
- [Microsoft CEO Nadella faces uncomfortable reality after outage](https://finance.yahoo.com/technology/articles/microsoft-ceo-nadella-faces-uncomfortable-034700949.html) — TheStreet
- [Akamai Technologies (AKAM) Expands Mobile Enterprise Browser Security](https://finance.yahoo.com/technology/articles/akamai-technologies-akam-expands-mobile-031634349.html) — Simply Wall St.
- [Tech takes a beating as AI trade comes unstuck despite Anthropic surge](https://finance.yahoo.com/markets/stocks/articles/tech-takes-beating-ai-trade-030257717.html) — AFP

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 272.66 ▼3.46% |
| Market Cap | $3.32T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.3% / 50.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.93 |
| Beta | 1.23 |
| 52-Week | 272.11 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [How High Can ANT Stock Go? Wall Street Debut Sparks Valuation Debate – One Analyst Sees Amazon-Google Scale Opportunity In Anthropic](https://finance.yahoo.com/markets/stocks/articles/high-ant-stock-wall-street-022355679.html) — Stocktwits
- [Nvidia Backed AI Data Center Demand Puts Schneider Electric Stock In Focus](https://finance.yahoo.com/technology/ai/articles/nvidia-backed-ai-data-center-021420909.html) — Simply Wall St.
- [Is Your VOO Fund Secretly An AI Bet?](https://finance.yahoo.com/markets/stocks/articles/voo-fund-secretly-ai-bet-005820625.html) — Trefis

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 257.37 ▼3.87% |
| Market Cap | $2.78T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 51.4% / 13.1% / 16.9% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.53 |
| Beta | 1.50 |
| 52-Week | 196.00 – 287.20 |
| Div. Yield | — |

**Recent News:**
- [Tech takes a beating as AI trade comes unstuck despite Anthropic surge](https://finance.yahoo.com/markets/stocks/articles/tech-takes-beating-ai-trade-030257717.html) — AFP
- [How High Can ANT Stock Go? Wall Street Debut Sparks Valuation Debate – One Analyst Sees Amazon-Google Scale Opportunity In Anthropic](https://finance.yahoo.com/markets/stocks/articles/high-ant-stock-wall-street-022355679.html) — Stocktwits
- [Nvidia Backed AI Data Center Demand Puts Schneider Electric Stock In Focus](https://finance.yahoo.com/technology/ai/articles/nvidia-backed-ai-data-center-021420909.html) — Simply Wall St.

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 596.22 ▼3.27% |
| Market Cap | $1.52T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.0% / 32.9% / 31.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 5.59 |
| Beta | 1.28 |
| 52-Week | 520.26 – 779.82 |
| Div. Yield | — |

**Recent News:**
- [Is Your VOO Fund Secretly An AI Bet?](https://finance.yahoo.com/markets/stocks/articles/voo-fund-secretly-ai-bet-005820625.html) — Trefis
- [Meta Platforms 'Reevaluating' 2030 Net Zero Goal as AI Buildout Strains Clean Energy Supply](https://finance.yahoo.com/energy/articles/meta-platforms-apos-reevaluating-apos-004314275.html) — MT Newswires
- [Apple May Try to Challenge Meta for Personal Agent Supremacy](https://finance.yahoo.com/m/218adf20-fceb-3955-ab5b-5c4bc9cf9107/apple-may-try-to-challenge.html) — Barrons.com

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 346.65 ▲1.48% |
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
- [Is Broadcom (AVGO) Stock Stretched Or Still Reasonable On Cash Flow?](https://finance.yahoo.com/markets/stocks/articles/broadcom-avgo-stock-stretched-still-031317832.html) — Simply Wall St.
- [Is Your VOO Fund Secretly An AI Bet?](https://finance.yahoo.com/markets/stocks/articles/voo-fund-secretly-ai-bet-005820625.html) — Trefis
- [Anthropic Joins World's Most Valuable Public Companies After IPO](https://finance.yahoo.com/markets/stocks/articles/anthropic-joins-world-apos-most-005806406.html) — MT Newswires

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 177.17 ▼3.39% |
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
- [Is Tech in a Bear Market? 20 Tech Stocks Fall Up to 76% From Highs](https://finance.yahoo.com/markets/stocks/articles/tech-bear-market-20-tech-224039016.html) — BeInCrypto
- [The 25 Biggest US IPOs of All Time](https://finance.yahoo.com/markets/stocks/articles/25-biggest-u-ipos-time-172550995.html) — Kiplinger
- [At AI Summit, Industry Titans Wave Off Market Woes—and Defend Jensen Huang](https://finance.yahoo.com/m/b4ceaf2c-2be0-3edd-98d2-13d5b3cc7cca/at-ai-summit%2C-industry-titans.html) — Barrons.com

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 153.68 ▼1.91% |
| Market Cap | $354.49B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.7% / 45.6% / 50.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 32.93 |
| Beta | 1.62 |
| 52-Week | 106.37 – 212.94 |
| Div. Yield | — |

**Recent News:**
- [Palantir Technologies (PLTR) Gets A Fresh AI Signal From A Key Platform Partner](https://finance.yahoo.com/technology/ai/articles/palantir-technologies-pltr-gets-fresh-200954508.html) — Simply Wall St.
- [Salesforce vs. Palantir Technologies: Which Software Stock Is a Better Buy for 2027?](https://finance.yahoo.com/markets/stocks/articles/salesforce-vs-palantir-technologies-software-195204969.html) — Motley Fool
- [How Does Palantir Technologies (PLTR) FedStart Milestone Change Its Federal AI Case?](https://finance.yahoo.com/technology/ai/articles/does-palantir-technologies-pltr-fedstart-191135783.html) — Simply Wall St.

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 23.84 ▼1.24% |
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
- [Is HPE's AI Server Boom Turning Into Cash?](https://finance.yahoo.com/technology/ai/articles/hpes-ai-server-boom-turning-211143765.html) — Trefis
- [Short Seller Raises Questions About Nvidia's Former Top Sales Executive. $2.5 Billion China Chip Case In Focus.](https://finance.yahoo.com/markets/stocks/articles/short-seller-raises-questions-nvidias-194917610.html) — International Business Times
- [Muddy Waters Has Issued a New Short Call on Nvidia. I Still Expect NVDA Stock to Grind Higher.](https://finance.yahoo.com/news/muddy-waters-issued-short-call-185326049.html) — Barchart

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 374.41 ▼2.43% |
| Market Cap | $1.48T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.3% / 3.3% / 3.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 13.59 |
| Beta | 1.74 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [Tech takes a beating as AI trade comes unstuck despite Anthropic surge](https://finance.yahoo.com/markets/stocks/articles/tech-takes-beating-ai-trade-030257717.html) — AFP
- [Is Tech in a Bear Market? 20 Tech Stocks Fall Up to 76% From Highs](https://finance.yahoo.com/markets/stocks/articles/tech-bear-market-20-tech-224039016.html) — BeInCrypto
- [Musk Says Optimus Will Do the Dishes “Within 12-18 Months.” Here’s Where Tesla’s Robot Stands](https://finance.yahoo.com/technology/ai/articles/musk-says-optimus-dishes-within-223752612.html) — TIKR

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 658.01 ▼2.25% |
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
- [Is Your VOO Fund Secretly An AI Bet?](https://finance.yahoo.com/markets/stocks/articles/voo-fund-secretly-ai-bet-005820625.html) — Trefis
- [Anthropic Just Went Public at $1.5 Trillion. VOO Won’t Own a Share Until Late 2027 at the Earliest](https://finance.yahoo.com/markets/stocks/articles/anthropic-just-went-public-1-235241841.html) — 24/7 Wall St.
- [A 66-Year-Old With $600,000 in VOO Owns Nvidia Without Ever Buying a Share. SCHD Owns None.](https://finance.yahoo.com/markets/stocks/articles/66-old-600-000-voo-233251936.html) — 24/7 Wall St.

## 🌍 News

### 🌍 World News
> `2026-11-20 12:09:34`

- [Anthropic becomes one of world's most valuable public companies in stock market debut](https://www.bbc.co.uk/news/articles/c3x29ggenz12o?at_medium=RSS&at_campaign=rss)
- ['I tell my son it's just fireworks': People inside besieged Yemeni city speak to BBC](https://www.bbc.co.uk/news/articles/cx7v2d8q879eo?at_medium=RSS&at_campaign=rss)
- [Myanmar committed genocide against Rohingya minority, top UN court rules](https://www.bbc.co.uk/news/articles/c804wzp20ddvo?at_medium=RSS&at_campaign=rss)
- [Europe ready for talks with Russia on ending war in Ukraine, leaders say](https://www.bbc.co.uk/news/articles/ckzd9nln5e6go?at_medium=RSS&at_campaign=rss)
- [Trump, Putin and Xi release 'peace declaration' after historic meeting](https://www.bbc.co.uk/news/articles/c623j4ln97x7o?at_medium=RSS&at_campaign=rss)
- [California targets Nvidia in China AI chip probe](https://www.bbc.co.uk/news/articles/cqn70vxp5p4no?at_medium=RSS&at_campaign=rss)
- [Fiona the hippo dies after swallowing a hat at Cincinnati Zoo](https://www.bbc.co.uk/news/articles/cwz0k3172xzko?at_medium=RSS&at_campaign=rss)
- [Judge finds Thomas Markle mentally fit to stand trial on child abuse charges](https://www.bbc.co.uk/news/articles/crgj35ldz2zxo?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-11-20 12:09:50`

#### AI Tips
# 📷 台灣攝影採購 & 今日技巧指南（2026-11-20）

## 【購買優惠】台灣買相機裝備最佳管道

#### 各通路優缺點速覽

| 通路 | 適合買什麼 | 優點 | 注意事項 |
|------|-----------|------|----------|
| **PChome 24h** | 公司貨機身、鏡頭、配件 | 到貨快、可刷卡分期、常有「24h購物金」回饋 | 價格通常最硬，比價後再下單 |
| **momo購物** | 機身+鏡頭組合、記憶卡、腳架 | 常發折價券、mo幣回饋、雙11/黑五檔期殺 | 注意是否為「平輸/水貨」，看清楚保固 |
| **光華商場（台北）** | 機身、鏡頭、二手、議價空間大 | 可現場試機、當面議價、店家競爭 | 比價3家以上；索取發票與保固卡 |
| **日本代購/Bic Camera** | 日系鏡頭、機身（匯率好時） | 價差可達10–20%、退稅 | 無台灣保固、維修需寄回；注意電壓與韌體 |
| **二手（旋轉拍賣、DCView、FB社團）** | 鏡頭、機身、老鏡 | 價格最低、可撿好貨 | 面交驗快門數、感光元件入塵、鏡頭霉斑 |

#### 11月季節性省錢時機 ⏰
- **雙11（11/11）剛過**：momo、PChome 常有「延長加碼」到11月中，留意**購物金折抵**與**滿額贈**（記憶卡、相機包）。
- **黑色星期五（11/27 前後）**：電商與部分實體店會跟進，是年底前最後一波大檔。
- **週年慶（百货公司）**：法雅客、燦坤等配合百貨滿千送百，**買高單價機身最划算**（回饋可疊加）。
- **

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-11-20 12:09:56`

#### AI Tips
# 台灣潛水裝備購買指南（2026年11月）

## 購買優惠

**實體店（北台灣）**
- **潛水人（Diving Pro）**：台北市中山區，代理多個國際品牌（Scubapro、Mares），可試穿後購買，會員有折扣。
- **海人潛水**：新北市，適合初學者套裝採購，常有「全套裝備」組合價。
- **藍洞潛水**：墾丁地區，適合南下潛水時順便採購，淡季（11月）議價空間較大。

**線上通路**
- **PChome 24h / momo**：適合買配件（蛙鞋扣、防水袋、潛水燈），比價方便、退換貨快。
- **蝦皮商城**：找有實體店的賣家（如「潛水貨倉」），避免來路不明的二手調節器。
- **Facebook 社團**：「台灣潛水二手裝備交流」、「潛水裝備買賣」— 11月常有潛季結束出清，二手 BC、防寒衣價格可談到原價 5–6 折，但**調節器、電腦錶務必要求原廠保養紀錄**。

**11月季節提示**
- 台灣東北角潛季約在10–11月收尾，店家會推「季末出清」；墾丁、小琉球仍可潛，但東北季風讓北部海況轉差，**採購可趁店家衝年底業績時議價**。
- 雙11（11/11）電商檔期是買配件、潛水燈、防水背包的好時機；大型裝備（BC、調節器）建議實體試穿再買。
- 若計畫明年春天潛旅（菲律

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-11-20 12:09:43`

#### AI Flight Tips — November
# November Flight Deals from Taiwan (TPE/TSA) — Expert Tips

**Japan (Tokyo/Osaka/Sapporo)**
- November = peak for autumn foliage (late Nov especially); Sapporo shoulder/cold but cheaper. Book 6–8 weeks out; LCC fares spike fast for late-Nov weekends.
- Cheapest: Peach, Tigerair Taiwan, Scoot via Singapore for Tokyo/Osaka; fly into Osaka (KIX) and train to Kyoto to save vs. Tokyo.
- Watch: Peach/Tigerair "early bird" sales ~2–3 months out; avoid Japan's Nov 23 Labor Thanksgiving long weekend.

**Thailand (Bangkok/Chiang Mai)**
- November = start of cool/dry peak season (especially Chiang Mai, Loy Krathong in late Nov). Book 4–6 weeks out; still good value.
- Cheapest: Thai Lion Air, Nok Air, or Vietjet/AirAsia via Bangkok; direct EVA/China Airlines if you value time over ~NT$2–3k savings.
- Watch: AirAsia/Vietjet flash sales; Chiang Mai prices jump around Yi Peng/Loy Krathong — book that leg early.

**Europe (any major city)**
- November = deep off-peak (post-summer, pre-Christmas) — cheapest month of the year for Europe. Book 8–12 weeks out.
- Cheapest: China Airlines/EVA direct to Amsterdam/Frankfurt/Vienna, or one-stop via Istanbul (Turkish), Doha (Qatar), or Dubai (Emirates) — often NT$5–10k cheaper.
- Watch: Black Friday (late Nov) fare sales on Turkish/Qatar/Emirates; avoid flying out the week of Nov 23–30 (US Thanksgiving crowds on connections).

**USA (West/East Coast)**
- November = off-peak except Thanksgiving week (Nov 20–30) — avoid that window entirely. Book 10–14 weeks out for best fares.
- Cheapest: EVA/China Airlines direct to LAX/SFO/SEA/ONT; for East Coast, connect via West Coast or use Korean Air/ANA via Seoul/Tokyo.
- Watch: Thanksgiving-week surcharges; post-Thanksgiving (early Dec) is a sweet spot. Set Google Flights alerts now for Jan–Feb travel.

**Egypt (Cairo)**
- November = ideal peak season (cool weather) — book 8–12 weeks out; limited direct options mean fares firm up early.
- Cheapest: China Airlines/EVA to a Gulf hub + EgyptAir/Emirates/Qatar connection; or Turkish via Istanbul (often best value).
- Watch: EgyptAir seasonal promos and Gulf-carrier Black Friday sales; book Cairo leg early — inventory is thin from Taiwan.

**Australia (Sydney/Melbourne)**
- November = shoulder/pre-summer — good value before Dec peak. Book 6–10 weeks out.
- Cheapest: China Airlines/EVA direct to SYD/MEL; or Scoot/Vietjet via Singapore/Ho Chi Minh for ~NT$3–5k less.
- Watch: Black Friday sales (late Nov) on China Airlines/EVA; avoid mid-Dec onward when summer fares surge.

**Quick rules:** Set Google Flights + Skyscanner alerts now; Tuesday/Wed

## 📚 Learning

### 📚 Learning — Finance
> `2026-11-20 12:09:58`

#### 📚 Today's Concept: Free Cash Flow (FCF)

What it is: Free Cash Flow is the cash a company generates from operations after paying for capital expenditures (physical assets like servers, factories, equipment). It's the money left over that can be returned to shareholders, pay down debt, or reinvest.

Why it matters: FCF is harder to manipulate than net income because it tracks actual cash, not accounting adjustments. It tells you whether a company can fund itself without constantly raising capital.

Example: A company reports $500M operating cash flow and spends $150M on capital expenditures (data centers, equipment). FCF = $500M - $150M = $350M. If it has 100M shares outstanding, that's $3.50 FCF per share. If the stock trades at $70, the FCF yield is 5% — you're paying $20 for every $1 of annual free cash.

Rule of thumb: Watch for FCF that consistently trails net income — it often signals aggressive accounting or heavy capital needs. A healthy company should convert roughly 70-100% of net income into FCF over time.

### 🧩 LeetCode Blind 100
> `2026-11-20 12:10:04`

#### 🧩 Blind 100 — 50. Pow(x, n) [Math & Geometry]
**連結:** https://leetcode.com/problems/pow(x,-n)/
> 📅 **Today's Daily Challenge:** #3298 Maximize Consecutive Elements in an Array After Modification [Hard] — Tags: Array, Dynamic Programming, Sorting — https://leetcode.com/problems/maximize-consecutive-elements-in-an-array-after-modification/

## **Problem Type:** Binary Exponentiation (Fast Exponentiation / Divide & Conquer)

**Key Insight:** Compute `x^n` in O(log n) by squaring the base and halving the exponent — `x^n = (x²)^(n/2)` for even n, `x · x^(n-1)` for odd n. Handle negative `n` by inverting the base.

**Approach:**
1. If `n < 0`, replace `x` with `1/x` and `n` with `-n`.
2. Initialize `result = 1`.
3. While `n > 0`:
   - If `n` is odd, multiply `result *= x`.
   - Square the base: `x *= x`.
   - Halve the exponent: `n //= 2`.
4. Return `result`.

**Python3 Solution:**
```python
class Solution:
    def myPow(self, x: float, n: int) -> float:
        if n < 0:
            x = 1 / x
            n = -n
        result = 1.0
        while n:
            if n & 1:
                result *= x
            x *= x
            n >>= 1
        return result
```

**Complexity:** Time O(log n) | Space O(1)

**Blind 100 Note:** Classic binary exponentiation — the canonical "reduce exponent by half each step" pattern. Tests whether you avoid the naive O(n) loop (which TLEs on `n = 2³¹-1`). Related: `Sqrt(x)`, `Super Pow`, `Count Good Numbers`, matrix exponentiation (Fibonacci via fast power).

**Contest Tips:**
- **Edge case `n = -2³¹`**: In C++/Java, `-n` overflows int. In Python this is safe (arbitrary precision), but be aware if porting.
- **`x = 0, n < 0`**: Mathematically undefined (division by zero) — LeetCode guarantees this won't happen, but note it.
- **Use `n & 1` and `n >>= 1`** instead of `%` and `//` — marginally faster and idiomatic.
- **Don't use `math.pow` or `**`** — LeetCode expects you to implement it (and `**` on huge ints can be slow/memory-heavy for large exponents).
- **Recursive version** is cleaner to write but risks stack depth on `n ≈ 2³¹`; iterative is safer.
- **Precision**: floating-point rounding is fine here since LeetCode accepts `1e-5` tolerance.

### 📷 Learning — Photography
> `2026-11-20 12:10:11`

#### 📷 Today's Concept: Special — Macro Photography: Extension Tubes vs Macro Lens

**What it is:** Extension tubes are hollow spacers that fit between your lens and camera to reduce minimum focus distance, while a true macro lens is optically designed for 1:1 magnification. Both let you fill the frame with tiny subjects, but they solve the problem differently.

**Why it matters:** Macro unlocks detail your eye ignores—dew on a leaf, texture in skin, the geometry of a flower. It's a cheap way to add a whole new visual language to your street and portrait work.

**How to apply it:**
1. Start with a cheap set of extension tubes (10mm + 16mm) on your existing lens—stack them for more magnification.
2. Expect to lose infinity focus and light; tubes cost you roughly a stop or two, so shoot wide open or add light.
3. Focus by moving your body, not the ring—at macro distances, tiny movements matter.
4. Stop down to f/8–f/11 for usable depth of field; it's razor-thin up close.
5. For serious work, a dedicated macro lens (e.g., 90mm) gives 1:1, autofocus, and better sharpness.

**Sony A7C tip:** Enable **Focus Magnifier** and **Peaking** (Menu > Focus Assist) for manual macro focusing—the A7C's EVF makes critical focus far easier than guessing.

**Common mistake:** Beginners chase magnification but forget light and stability—handheld macro at f/11 in shade yields blurry, noisy shots. Use a tripod or brace against something, and add continuous light or a flash.

### 📚 Learning — Tech
> `2026-11-20 12:10:06`

#### 📚 Today's Concept: Database Connection Pooling

**What it is:** Connection pooling maintains a cache of reusable database connections that are shared across requests instead of opening and closing a new connection each time. This avoids the expensive overhead of TCP handshakes, authentication, and connection setup on every query.

**When to use it:** Use it in any server application handling concurrent requests—web APIs, background workers, or microservices. For example, a REST API serving 500 req/s would collapse without pooling, since each request opening its own Postgres connection would exhaust the DB's connection limit and add ~50ms of setup latency.

**Example:**
```python
from sqlalchemy import create_engine

engine = create_engine(
    "postgresql://user:pass@localhost/db",
    pool_size=10,        # steady connections
    max_overflow=20,     # burst capacity
    pool_timeout=30,     # wait before erroring
)
# Each engine.connect() borrows from the pool, returns on close
```

**Gotcha:** A common mistake is setting `pool_size` too high "for safety"—each connection consumes DB memory and a backend process. 10 connections per app instance × 20 pods = 200 DB connections, which can overwhelm Postgres. Size pools against your DB's `max_connections`, not your traffic. Also remember to use a pooler like PgBouncer when scaling horizontally.

### 🎬 Learning — YouTube
> `2026-11-20 12:10:15`

#### 🎬 今日主題：剪輯 — 轉場的克制使用：何時不要加特效
**類別：** 剪輯

**是什麼：** 轉場特效是剪輯軟體中切換鏡頭的效果（如滑動、縮放、旋轉），但「克制使用」意味著多數時候用最單純的硬切，只在敘事需要時才加特效。

**為什麼重要：** 過多花俏轉場會讓觀眾出戲、顯得業餘，也掩蓋了內容本身；乾淨的剪輯反而讓你的畫面與故事更被信任。

**怎麼做：**
1. 預設全部用硬切，先剪完一版再說。
2. 只在「時間或空間跳躍」時才考慮轉場（如從白天到夜晚）。
3. 全片特效轉場控制在 1–2 個以內。
4. 用音樂節拍或動作銜接（如揮手、關門）取代特效。
5. 剪完自己靜音看一遍，問：這個轉場有幫助理解嗎？

**新手常犯的錯：** 把 AI 工具提供的花俏轉場全用上，導致節奏破碎。避免方法：先關掉自動轉場建議，手動只留必要的一個。

**延伸 idea：** 拍一支「同一天用硬切 vs 特效轉場剪兩版」的對比影片，分享哪版更耐看，順便展示你的攝影畫面。
