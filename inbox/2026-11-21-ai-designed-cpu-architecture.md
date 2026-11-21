---
date: 2026-11-21
tags: [daily-digest, automated]
sections: ["tech_ai", "tech_ai_companies", "tech_google", "finance_markets", "finance_realestate", "finance_stock", "news_world", "savings_camera", "savings_dive", "savings_flight", "learning_finance", "learning_leetcode", "learning_photography", "learning_tech", "learning_youtube"]
---

# Daily Digest — 2026-11-21

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

- **全球同步大拋售，台股跌最重**：TAIEX 單日 −6.23%（36,033），S&P 500 −5.64%，日經 −5.06%；自選股中 Arm ▼16.7%、Broadcom ▼14.0%、NVIDIA ▼14.0%。這是系統性 risk-off，不是個股問題 — 若手上 AI 硬體部位偏重，先確認資金與停損紀律，別在恐慌日做臨時決策。([BBC 市場報導](https://www.bbc.co.uk/news/articles/c6808ym10vzgo))
- **AI 設計 CPU 架構「Frostbite」通過形式驗證**：AI 自行發現、設計並形式驗證的 CPU 架構，是 AI 輔助硬體設計的里程碑，值得追蹤後續是否可複現。([link](https://architectlabs.com/blog/frostbite))
- **Google 開發者生態大補帖**：Gemini API 的 Tool Retrieval（數百工具、更少 token）、Agent Gateway 語意治理政策（執行前攔檢 tool call）、跨雲 Agent 異常偵測（吃 OpenTelemetry）。做 agent 應用的話，這三項直接影響架構選型。([Tool Retrieval](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/)、[語意治理](https://developers.googleblog.com/check-what-your-ai-agents-do-before-they-do-it-with-semantic-governance-policies/))
- **Anthropic 數學家宣稱用 AI 證明黎曼猜想**（尚待驗證），同時 HN 上另有廣義黎曼猜想的未驗證證明 PDF — 兩件事都別當定論，但值得留意 AI 在數學領域的節奏。([BBC](https://www.bbc.co.uk/news/articles/c6pqr2g7w059o)、[PDF](https://alpo.ge/remark.pdf))
- **可執行的省錢窗口**：歐洲/美國線現在是離峰價（歐洲 11 月最便宜），日本/泰國要 2–4 週內下手；相機等黑色星期五（11/27 前後）第二波折扣，別在雙11後急買。([Flight Tips]、[Camera Deals] 見下方)

---

- 💻 **Tech**：AI 設計 CPU 架構 + LLM 服務效率（TideCache）、agent 安全控制與 LLM 商業誘因偏誤研究並進；另有 Framework 筆電負評熱議。
- 🤖 **AI 公司動態**：全部是 Tesla（Cybercab 擴點 Dallas、Thiel 基金清倉、Ellison 合作訊號）；今日無 OpenAI / Anthropic 產品消息。
- 🔵 **Google**：五則開發者導向更新，主軸是「可規模化的 tool-using agent」＋「執行前治理與跨雲監控」。
- 📈 **Markets**：三大指數同步重挫逾 5%，台股 −6.23% 跌幅最大，避險情緒極端。
- 🏠 **台灣房市**：信用管制下量縮盤整，蛋黃區撐盤、蛋白區讓利；自住鎖定捷運成熟商圈中古大樓議價，投資看租金投報而非價差。
- 📊 **Watchlist**：全線下跌，半導體/AI 硬體最慘（Arm −16.7%、AVGO −14.0%、NVDA −14.0%），微軟/Google 相對抗跌；估值欄位全 N/A，僅能視為價格面波動。
- 🌍 **World News**：科技股拖累美股進入修正；俄飛彈落波蘭（無人傷亡，波蘭稱挑釁）；英國脫歐後尋求更緊密對歐關係；Anthropic 黎曼猜想話題。
- 📷 **Camera Deals**：通路優劣比較＋11 月下旬黑五第二波折扣，建議電商截圖比價再帶去光華殺 5%；日圓偏弱代購價差 15–25% 但無台灣保固。
- 🤿 **Dive Gear Deals**：東北季風季北部潛季尾聲，店家推季末出清與明年潛旅早鳥；二手重裝務必看保養紀錄並送店檢測。
- ✈️ **Flight

---

## 💻 Tech

### 💻 Tech & AI
> `2026-11-21 12:07:27`

#### Hacker News
- [Levent Alpöge claims proof of the Generalized Riemann Hypothesis [pdf]](https://alpo.ge/remark.pdf) ⭐2437
- [NINLIVE: The Nine Inch Nails live archive](https://ninlive.com/) ⭐162
- [Restricting AI agents in mobile operating systems platforms from capturing data](https://signal.org/blog/protecting-your-privacy/) ⭐527
- [Why the Airbus A321XLR often gets stuck climbing for first few hours of flight](https://simpleflying.com/airbus-a321xlr-often-stuck-climbing-1st-few-hours-flight/) ⭐97
- [The Hungry Butler Effect: Concealed Commercial Incentives in LLMs](https://www.researchgate.net/publication/418143113_The_Hungry_Butler_Effect_Concealed_Commercial_Incentives_and_the_Erosion_of_Epistemic_Rigour_in_Large_Language_Models) ⭐21
- [I Don't Trust Visual Recordings Anymore. But One Day I Will Again](https://spectrum.ieee.org/fighting-back-against-deep-fakes) ⭐11
- [If you can't explain something in simple terms, you don't understand it (2017)](https://kottke.org/17/06/if-you-cant-explain-something-in-simple-terms-you-dont-understand-it) ⭐638
- [I'll never buy Framework hardware again](https://poolp.org/posts/2026-11-20/ill-never-buy-framework-hardware-again/) ⭐772
- [Frostbite: A new CPU architecture discovered, designed and verified by AI](https://architectlabs.com/blog/frostbite) ⭐632
- [AI is giving everyone the same advice](https://a90.com/experiments/same-advice/) ⭐64

#### HuggingFace
- [Time Series Structure Learning with Local Causal Parent Discovery](https://huggingface.co/papers/2611.26232)
- [Teaching Vision-Language-Action Models to Stop Safely](https://huggingface.co/papers/2611.26239)
- [PAD: Policy-Aware Data Valuation for Autonomous Driving](https://huggingface.co/papers/2611.25604)
- [Lang-SVG: Hierarchical Image Vectorization with Language Priors](https://huggingface.co/papers/2611.15941)
- [Squoosh Bench: Evaluating UX-1 on 318 Historical Website A/B Tests](https://huggingface.co/papers/2611.25200)
- [RL Post-Training in Diffusion Transformers Is Activation Steering](https://huggingface.co/papers/2611.26627)

#### ArXiv
- [RL Post-Training in Diffusion Transformers Is Activation Steering](http://arxiv.org/abs/2611.26627v1)
- [PlayCraft: Designing Engaging Games from Agent Play Experience](http://arxiv.org/abs/2611.26624v1)
- [TideCache: Efficient Hybrid LLM Serving with Transparent Cache Management and Layer-Wise Streaming](http://arxiv.org/abs/2611.26619v1)
- [One Prior, Two Dynamics: Repurposing Video Diffusion Transformers for Self-Supervised Latent Action Learning](http://arxiv.org/abs/2611.26617v1)
- [AgentRoboCritic: Understanding the Capability of Frontier Agents on Direct Robot Control](http://arxiv.org/abs/2611.26613v1)
- [Bio-PM-Guided Synthetic IMU Generation](http://arxiv.org/abs/2611.26607v1)

### 🤖 AI 公司動態 (OpenAI / Anthropic / Tesla)
> `2026-11-21 12:07:33`

#### Tesla
- [In 2000, Elon Musk Crashed His Uninsured $1 Million McLaren Trying to Show Peter Thiel What It Could Do. In 2025, Thiel’s Fund Quietly Sold Every Tesla Share It Owned](https://finance.yahoo.com/markets/stocks/articles/2000-elon-musk-crashed-uninsured-015202939.html)
- [Has AI's honeymoon ended on Wall Street?](https://finance.yahoo.com/markets/stocks/articles/ais-honeymoon-ended-wall-street-004604807.html)
- [Zero To Sixty: Tesla Expands Cybercab To Dallas As Waymo Pauses Freeway Operations This Week](https://finance.yahoo.com/technology/articles/zero-sixty-tesla-expands-cybercab-004541551.html)
- [David Ellison Calls Elon Musk’s $1 Billion Investment ‘an Honor and a Privilege,’ Open to Future Starlink Collaboration](https://finance.yahoo.com/media-advertising/articles/david-ellison-calls-elon-musk-233006805.html)

### 🔵 Google 動態
> `2026-11-21 12:07:30`

#### Google AI Blog
- [Introducing Tool Retrieval in the Gemini API](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/)
- [Walter Isaacson on curiosity and creativity in the AI age.](https://blog.google/innovation-and-ai/technology/ai/dialogues-walter-isaacson/)
- [The Gemini app is now available on lower-memory Android devices.](https://blog.google/innovation-and-ai/products/gemini-app/gemini-lower-memory-devices/)
- [Put Gemini to work for you](https://blog.google/innovation-and-ai/products/gemini-app/tasks-in-gemini-free-new-features/)
- [New Ask Maps features to help with holiday travel and prep](https://blog.google/products-and-platforms/products/maps/ask-maps-holiday-travel-features-2026/)
#### Google Blog
- [Get your year-end tasks done with new Connected Apps.](https://blog.google/products-and-platforms/products/search/connected-apps-holiday-errands/)
- [How Watch Duty is using Gemini to get wildfire alerts out faster](https://blog.google/company-news/outreach-and-initiatives/google-org/watch-duty-gemini-tool/)
- [ICYMI: Transfer your history from other AI apps into Gemini.](https://blog.google/innovation-and-ai/products/gemini-app/switch-ai-assistants-transfer-history/)
- [How we’re putting one of quantum mechanics’ deepest features to the test at scale.](https://blog.google/innovation-and-ai/models-and-research/quantum-computing/putting-one-of-quantum-mechanics-deepest-features-to-test-at-scale/)
- [Introducing Tool Retrieval in the Gemini API](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/)
#### Google Developers
- [Agent Anomaly Detection: Safeguarding agents across other clouds](https://developers.googleblog.com/agent-anomaly-detection-safeguarding-agents-across-other-clouds/)
- [How to securely connect internal Cloud Run MCP servers to Gemini Enterprise](https://developers.googleblog.com/how-to-securely-connect-internal-cloud-run-mcp-servers-to-gemini-enterprise/)
- [Check what your AI agents do before they do it, with Semantic governance policies](https://developers.googleblog.com/check-what-your-ai-agents-do-before-they-do-it-with-semantic-governance-policies/)
- [How to handle user, connector, and agent auth in Gemini Enterprise with a custom UI](https://developers.googleblog.com/how-to-handle-user-connector-and-agent-auth-in-gemini-enterprise-with-a-custom-ui/)
- [Multi-Turn Agentic Reinforcement Learning with Tunix and Gemma 4 on Google TPUs](https://developers.googleblog.com/multi-turn-agentic-reinforcement-learning-with-tunix-and-gemma-4-on-google-tpus/)

## 📈 Finance

### 📈 Markets Overview
> `2026-11-21 12:07:35`

#### Indices
- S&P 500: 6,910.39 ▼5.64%
- 台股加權: 36,033.29 ▼6.23%
- 日經 225: 56,436.65 ▼5.06%

### 🏠 台灣房市
> `2026-11-21 12:08:23`

#### AI 分析
## 台灣房市觀察（2026-11-21）

**1. 整體趨勢**
央行選擇性信用管制持續，投資買盤退場，市場以自住剛需為主，成交量低檔盤整、價格呈「蛋黃區撐盤、蛋白區讓利」的兩極化格局。高總價產品靠少數換屋與現金買盤支撐，但去化天數明顯拉長，賣方議價空間擴大。

**2. 值得注意的訊號**
- **實價登錄高總價集中在精華區大坪數**：本期揭露多筆 144–963㎡ 大樓，單價 27–46 萬/㎡（約 90–150 萬/坪），顯示蛋黃區高總價仍有成交，但屬個案、非全面性。
- **租賃市場活躍度高於買賣**：591 掛牌以雙北、台中套房與共生公寓為主，反映高房價下「以租代買」需求強勁，尤其捷運沿線、可租補物件。
- **重劃區與外圍新案讓利**：台中單元十二、沙鹿、桃園八德等外圍區物件以「裝潢、車位、租補」為賣點搶客，議價空間較大。

**3. 對自住者建議**
- 善用當前買方市場，優先鎖定**捷運/成熟商圈中古大樓**，議價從實價登錄最低價往下談，蛋黃區保值性優於外圍新案。
- 避開供給量大的重劃區高總價預售，留意建商讓利與餘屋出清機會。

**4. 對投資者建議**
- 短期價差空間有限，**租金投報率**才是關鍵；雙北捷運套房、可租補物件現金流較穩，但須留意空置與管理成本。
- 高總價大坪數流動性差，不建議短線進場；若布局長期，聚焦產業聚落（中科、南科周邊）的剛需租賃產品。

**5. 風險提醒**
信用管制與囤房稅2.0效應持續發酵，多屋族持有成本上升；外圍區若賣壓擴大，價格修正風險高於蛋黃區，進場前務必確認區域餘屋量與去化速度。

#### 591 最新
- [台中市北屯區南興一路我是承辦🕊️單元十二｜鉅虹水岸岩｜精美裝潢三房平車｜美視野](https://sale.591.com.tw/sale-detail-21297587.html)
- [台南市永康區中華路727巷長億城全新裝潢套房](https://rent.591.com.tw/rent-detail-22385535.html)
- [新北市永和區文化路149巷NO.038永和文化路｜頂溪站｜仁愛公園｜樂華夜市｜可租補](https://rent.591.com.tw/rent-detail-21967828.html)
- [桃園市八德區中華路31巷獨家專任-中山路輝煌世紀超值感四房車](https://sale.591.com.tw/sale-detail-21297588.html)
- [台中市沙鹿區台灣大道七段432巷意志力✅可雙租補✅網路第四台✅近靜宜弘光台灣大道電梯套房](https://rent.591.com.tw/rent-detail-22385540.html)
- [台北市中正區南昌路一段74巷NO.052中正南昌路2，中正紀念堂站，共生公寓](https://rent.591.com.tw/rent-detail-22001514.html)
- [台北市信義區信義路六段永春廣慈象山捷運&101信義商圈](https://rent.591.com.tw/rent-detail-22385537.html)
- [台北市中正區泉州街18巷NO072中正泉州街｜小南門站，可租補，共生宅](https://rent.591.com.tw/rent-detail-21967840.html)

#### 實價登錄 (115S3) 近期成交
| 地址 | 類型 | 面積 | 總價 | 單價 |
|---|---|---|---|---|
|  | 住宅大樓(11層含以上有電梯) | 963.3㎡ | 29664萬 | 307937元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 399.6㎡ | 14468萬 | 449312元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 379.7㎡ | 10438萬 | 274908元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 267.7㎡ | 8558萬 | 367305元/㎡ |
|  | 住宅大樓(11層含以上有電梯) | 144.7㎡ | 5700萬 | 456525元/㎡ |

### 📊 Watchlist
> `2026-11-21 12:07:58`

##### NVIDIA (NVDA)
| Metric | Value |
|---|---|
| Price | 125.53 ▼14.01% |
| Market Cap | $3.03T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 74.9% / 66.1% / 62.5% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 11.35 |
| Beta | 2.22 |
| 52-Week | 124.50 – 243.37 |
| Div. Yield | — |

**Recent News:**
- [Is CoreWeave (CRWV) Fairly Valued After Fresh MLPerf Results?](https://finance.yahoo.com/markets/stocks/articles/coreweave-crwv-fairly-valued-fresh-031612848.html) — Simply Wall St.
- [Photronics (PLAB) Stock Could Be 29% Undervalued Despite Fresh AI Supply Chain Uncertainty](https://finance.yahoo.com/markets/stocks/articles/photronics-plab-stock-could-29-031602463.html) — Simply Wall St.
- [NVDA Stock Sees Biggest Fall In 22 Months, But Top Analyst Says Nvidia’s AI Boom Isn’t Over Yet — Here Are 5 Reasons Why](https://finance.yahoo.com/markets/stocks/articles/nvda-stock-sees-biggest-fall-024825298.html) — Stocktwits

##### AMD (AMD)
| Metric | Value |
|---|---|
| Price | 424.39 ▼13.25% |
| Market Cap | $696.04B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 53.7% / 17.7% / 16.8% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 10.15 |
| Beta | 2.49 |
| 52-Week | 188.22 – 658.52 |
| Div. Yield | — |

**Recent News:**
- [Mets Owner Steve Cohen’s Fund Dumped Nearly All of Its AMD and Bet $1 Billion That Microsoft Is the Safer AI Stock. AMD Has Fallen 31% Since](https://finance.yahoo.com/markets/stocks/articles/mets-owner-steve-cohen-fund-234704839.html) — 24/7 Wall St.
- [At AI Summit, Industry Titans Wave Off Market Woes—and Defend Jensen Huang](https://finance.yahoo.com/m/b4ceaf2c-2be0-3edd-98d2-13d5b3cc7cca/at-ai-summit%2C-industry-titans.html) — Barrons.com
- [Anthropic’s Day Two Drop Fuels Broader Tech Rout; Dan Ives Points To ‘Perfect Storm’](https://finance.yahoo.com/technology/ai/articles/anthropic-day-two-drop-fuels-223031373.html) — Stocktwits

##### Microsoft (MSFT)
| Metric | Value |
|---|---|
| Price | 484.52 ▼2.77% |
| Market Cap | $3.60T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 67.7% / 47.1% / 41.2% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 7.65 |
| Beta | 1.04 |
| 52-Week | 349.20 – 559.15 |
| Div. Yield | — |

**Recent News:**
- [Billionaire Bill Ackman’s Top 5 Stocks After Selling Stakes to Open a Brand-New Position](https://finance.yahoo.com/markets/stocks/articles/billionaire-bill-ackman-top-5-013837421.html) — Insider Monkey
- [Has AI's honeymoon ended on Wall Street?](https://finance.yahoo.com/markets/stocks/articles/ais-honeymoon-ended-wall-street-004604807.html) — AFP
- [Allooloo Tops 100M Capital Markets AI Agent Traffic a Month](https://finance.yahoo.com/technology/ai/articles/allooloo-tops-100m-capital-markets-000600422.html) — PR Newswire

##### Google (GOOGL)
| Metric | Value |
|---|---|
| Price | 265.29 ▼2.70% |
| Market Cap | $3.23T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 60.9% / 33.3% / 50.0% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.80 |
| Beta | 1.23 |
| 52-Week | 264.22 – 408.61 |
| Div. Yield | — |

**Recent News:**
- [Top 5 Stocks to Buy According to Billionaire George Soros](https://finance.yahoo.com/markets/stocks/articles/top-5-stocks-buy-according-010421254.html) — Insider Monkey
- [Morgan Stanley sends a strong signal to Google stock investors](https://finance.yahoo.com/markets/stocks/articles/morgan-stanley-sends-strong-signal-010300969.html) — TheStreet
- [Review & Preview: Hype Halted](https://finance.yahoo.com/m/7f9bf2d2-c34f-310e-9971-12201d455bb0/review-%26-preview%3A-hype-halted.html) — Barrons.com

##### Amazon (AMZN)
| Metric | Value |
|---|---|
| Price | 246.82 ▼4.10% |
| Market Cap | $2.67T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 51.4% / 13.1% / 16.9% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 4.34 |
| Beta | 1.50 |
| 52-Week | 196.00 – 287.20 |
| Div. Yield | — |

**Recent News:**
- [Dow Jones Futures: Market Has Worst Week Since Covid Amid Nvidia, Anthropic. Does Fear Gauge Offer Hope?](https://finance.yahoo.com/m/9ef9da98-bccf-3565-9a30-9bc3e57ad4b9/dow-jones-futures%3A-market-has.html) — Investor's Business Daily
- [Amazon's re:Invent Conference Starts Nov. 30. Here's What the Stock Did in the Month After the Last 10.](https://finance.yahoo.com/markets/stocks/articles/amazons-invent-conference-starts-nov-021202008.html) — Motley Fool
- [Billionaire Bill Ackman’s Top 5 Stocks After Selling Stakes to Open a Brand-New Position](https://finance.yahoo.com/markets/stocks/articles/billionaire-bill-ackman-top-5-013837421.html) — Insider Monkey

##### Meta (META)
| Metric | Value |
|---|---|
| Price | 560.84 ▼5.93% |
| Market Cap | $1.43T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 81.0% / 32.9% / 31.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 5.25 |
| Beta | 1.28 |
| 52-Week | 520.26 – 779.82 |
| Div. Yield | — |

**Recent News:**
- [Billionaire Bill Ackman’s Top 5 Stocks After Selling Stakes to Open a Brand-New Position](https://finance.yahoo.com/markets/stocks/articles/billionaire-bill-ackman-top-5-013837421.html) — Insider Monkey
- [Bill Ackman’s Top 10 Stocks After Selling Stakes to Open a Brand-New Position](https://finance.yahoo.com/markets/stocks/articles/bill-ackman-top-10-stocks-013227518.html) — Insider Monkey
- [George Soros Raised His Meta (META) Stake by 596%. Then the Stock Fell](https://finance.yahoo.com/markets/stocks/articles/george-soros-raised-meta-meta-011000430.html) — Insider Monkey

##### Broadcom (AVGO)
| Metric | Value |
|---|---|
| Price | Broadcom: 304.41 ▼14.02% |
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
- [Data Center AI Chips Could Change the Winners: Broadcom and Marvell](https://finance.yahoo.com/technology/ai/articles/data-center-ai-chips-could-232554816.html) — 24/7 Wall St.
- [Stock Market Today, Nov. 20: Stocks Plunge as AI Trade Unwinds](https://finance.yahoo.com/markets/stocks/articles/stock-market-today-nov-20-223513707.html) — Motley Fool

##### Arm Holdings (ARM)
| Metric | Value |
|---|---|
| Price | Arm Holdings: 152.20 ▼16.72% |
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
- [Arm (ARM) Stock Looks Undervalued Despite Rich Sales Expectations](https://finance.yahoo.com/markets/stocks/articles/arm-arm-stock-looks-undervalued-021442325.html) — Simply Wall St.
- [Prediction: Nvidia Stock Will Do This in the 6 Months After a New CEO Takes Over, According to History](https://finance.yahoo.com/markets/stocks/articles/prediction-nvidia-stock-6-months-000251264.html) — Motley Fool
- [At AI Summit, Industry Titans Wave Off Market Woes—and Defend Jensen Huang](https://finance.yahoo.com/m/b4ceaf2c-2be0-3edd-98d2-13d5b3cc7cca/at-ai-summit%2C-industry-titans.html) — Barrons.com

##### Palantir (PLTR)
| Metric | Value |
|---|---|
| Price | 143.49 ▼6.63% |
| Market Cap | $330.99B |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 84.7% / 45.6% / 50.3% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 30.74 |
| Beta | 1.62 |
| 52-Week | 106.37 – 212.94 |
| Div. Yield | — |

**Recent News:**
- [If You Invest $500 in Palantir Each Month Starting Now, This is What You’d Have in 5 Years](https://finance.yahoo.com/markets/stocks/articles/invest-500-palantir-month-starting-160409470.html) — 24/7 Wall St.
- [Cathie Wood's Ark Has Been Selling Palantir Stock. Under $160, I'd Buy It Now.](https://finance.yahoo.com/markets/stocks/articles/cathie-woods-ark-selling-palantir-140402274.html) — Motley Fool
- [One Number That Makes Palantir A Buy](https://finance.yahoo.com/markets/stocks/articles/one-number-makes-palantir-buy-133833221.html) — Trefis

##### Super Micro (SMCI)
| Metric | Value |
|---|---|
| Price | Super Micro: 21.65 ▼11.16% |
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
- [Dell Stock Plunges 10% in the AI Selloff and Heads for Its Worst Month Since Its 2018 Return to the Stock Market. Earnings Are Tuesday](https://finance.yahoo.com/markets/stocks/articles/dell-stock-plunges-10-ai-180702531.html) — 24/7 Wall St.
- [What HPE Holders Should Watch In Monday's Margin](https://finance.yahoo.com/markets/stocks/articles/hpe-holders-watch-mondays-margin-175741992.html) — Trefis
- [Ex-Super Micro executive, married to Jensen Huang’s ex-sales chief, says she took a CEO job at an Nvidia customer days before a $2.5 billion China smuggling scandal broke](https://finance.yahoo.com/technology/articles/ex-super-micro-executive-married-152004969.html) — Fortune

##### Tesla (TSLA)
| Metric | Value |
|---|---|
| Price | 345.82 ▼7.64% |
| Market Cap | $1.37T |
| P/E (TTM / Fwd) | N/A / N/A |
| EPS (TTM / Fwd) | N/A / N/A |
| Revenue (TTM) | N/A |
| Gross / Op / Net Margin | 19.3% / 3.3% / 3.1% |
| Free Cash Flow | N/A |
| ROE | N/A |
| D/E Ratio | N/A |
| P/B | 12.55 |
| Beta | 1.74 |
| 52-Week | 297.38 – 498.83 |
| Div. Yield | — |

**Recent News:**
- [In 2000, Elon Musk Crashed His Uninsured $1 Million McLaren Trying to Show Peter Thiel What It Could Do. In 2025, Thiel’s Fund Quietly Sold Every Tesla Share It Owned](https://finance.yahoo.com/markets/stocks/articles/2000-elon-musk-crashed-uninsured-015202939.html) — 24/7 Wall St.
- [Has AI's honeymoon ended on Wall Street?](https://finance.yahoo.com/markets/stocks/articles/ais-honeymoon-ended-wall-street-004604807.html) — AFP
- [Zero To Sixty: Tesla Expands Cybercab To Dallas As Waymo Pauses Freeway Operations This Week](https://finance.yahoo.com/technology/articles/zero-sixty-tesla-expands-cybercab-004541551.html) — Stocktwits

##### Vanguard S&P 500 ETF (VOO)
| Metric | Value |
|---|---|
| Price | Vanguard S&P 500 ETF: 635.54 ▼5.33% |
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
- [Stocks Erase 2026 Gains as AI Selloff Deepens](https://finance.yahoo.com/markets/stocks/articles/stocks-erase-2026-gains-ai-032122511.html) — etf.com
- [If the AI Bubble Pops, It Won't Look Like You Expect](https://finance.yahoo.com/markets/stocks/articles/ai-bubble-pops-wont-look-233827314.html) — etf.com
- [Does Gold Protect You When Stocks Fall?](https://finance.yahoo.com/markets/commodities/articles/does-gold-protect-stocks-fall-190127712.html) — Trefis

## 🌍 News

### 🌍 World News
> `2026-11-21 12:08:25`

- [Tech stock sell-off drags markets down as Anthropic shares slide](https://www.bbc.co.uk/news/articles/c6808ym10vzgo?at_medium=RSS&at_campaign=rss)
- [UK to explore even closer ties with EU after agreeing deal, says Burnham](https://www.bbc.co.uk/news/articles/c6jreyqgw4e9o?at_medium=RSS&at_campaign=rss)
- [Russian missile hits Poland as Ukraine's allies hold military exercise, says Tusk](https://www.bbc.co.uk/news/articles/cqx2x9dklxnro?at_medium=RSS&at_campaign=rss)
- [French police officers sentenced for beating of music producer Michel Zecler](https://www.bbc.co.uk/news/articles/ck9d7e9wvvweo?at_medium=RSS&at_campaign=rss)
- [In a year of AI solving maths problems, Anthropic may have just solved the biggest](https://www.bbc.co.uk/news/articles/c6pqr2g7w059o?at_medium=RSS&at_campaign=rss)
- [Gérard Depardieu and French author investigated over sexual allegations](https://www.bbc.co.uk/news/articles/c9ly43pj10mvo?at_medium=RSS&at_campaign=rss)
- [Russia targets Kyiv crossings days after Ukraine hits Crimean Bridge](https://www.bbc.co.uk/news/articles/c6x29gn4pdn9o?at_medium=RSS&at_campaign=rss)
- [Mamdani announces plan to close New York's Rikers Island jail by 2032](https://www.bbc.co.uk/news/articles/cmjeqv89egylo?at_medium=RSS&at_campaign=rss)

## ✈️ Savings

### 📷 Camera Deals
> `2026-11-21 12:08:35`

#### AI Tips
# 📷 2026-11-21 攝影顧問日報

## 【購買優惠】台灣買相機裝備攻略

#### 各通路優劣分析

| 通路 | 適合買什麼 | 注意事項 |
|------|-----------|---------|
| **PChome 24h** | 公司貨機身、鏡頭、記憶卡 | 雙11後仍有「感恩回饋」檔期；比價快、退貨方便，但價格通常非最低 |
| **momo** | 組合包（機身+配件）、腳架 | 11月常有「黑五暖身」券，疊加 momo 幣回饋；注意是否為平輸 |
| **光華商場** | 二手鏡頭、副廠配件、議價空間大 | 現金價可殺 3–8%；當場驗貨（測對焦、看入塵、查快門數） |
| **日本代購** | 日系品牌機身/鏡頭（匯率佳時） | 2026年11月日圓仍偏弱，價差可達 15–25%；但**無台灣保固**，維修需寄回 |
| **二手（DCView、旋轉拍賣、臉書社團）** | 高階鏡頭、停產機種 | 面交必測：快門數、感光元件壞點、鏡頭霉斑/霧化 |

#### 11月季節性省錢時機
- **雙11剛過（11/11）**：別急！11月下旬常有「清庫存」與**黑色星期五（11/27 前後）** 第二波折扣，尤其是 PChome、momo 的相機品類。
- **年底換機潮前夕**：12月新機上市前，舊款（如上一代無反）在光華與電商會有一波降價，現在是**議價黃金期**。
- **實戰建議**：先在 PChome/momo 截圖比價，帶去光華實體店議價，常能再壓 5%。日本代購則鎖定「匯率 + 免稅 + 信用卡回饋」三重疊加。

---

## 【今日攝影技巧】用「

#### r/photomarket
_No posts today_

### 🤿 Dive Gear Deals
> `2026-11-21 12:08:40`

#### AI Tips
# 台灣潛水裝備購買指南（2026年11月）

## 購買優惠

**實體店（北台灣）**
- **潛水貨倉（Dive Warehouse）**：台北市區，代理多個國際品牌（Scubapro、Mares、Aqualung），常有組合優惠，適合一次購足輕裝+重裝。
- **海人潛水（Ocean Man）**：新北，維修服務口碑好，買調節器可談保養套裝。
- **藍鯨潛水**：台中，中部潛友常去，二手寄賣區值得挖寶。
- **墾丁在地店（如台灣潛水、CTdiver）**：南下潛旅時順便買，部分店家對課程學員給折扣。

**線上/社團**
- **蝦皮、PChome**：適合買輕裝（面鏡、蛙鞋、防寒衣），比價快，但重裝（調節器、BCD）建議實體店買以確保保固與維修。
- **Facebook 社團**：「台灣潛水裝備買賣交流」「潛水二手裝備交流」— 11月東北季風起，北部潛友開始出清裝備，二手調節器、防寒衣議價空間大。**買二手重裝務必要求看保養紀錄，調節器建議送店檢測再付款。**

**11月季節提示**
- 11月是**東北季風季**，北部（東北角）潛季尾聲、海況轉差，墾丁/小琉球/綠島仍可潛。此時店家常推**季末出清**與**明年潛旅預購**（如菲律賓、馬爾地夫行程早鳥）。
- **雙11（11/11）**電商檔期

#### r/scuba
_No posts today_

### ✈️ Flight Tips
> `2026-11-21 12:08:31`

#### AI Flight Tips — November
# Flight Deals Guide — Departing Taiwan (Nov 2026)

**Japan (Tokyo/Osaka/Sapporo)** — November is **peak** for autumn foliage (late Nov) but **off-peak** early-month; fares spike around 11/20–12/5. Book **6–10 weeks out** (now is ideal for early-Dec). Cheapest: Peach, Tigerair Taiwan, Scoot via TPE→NRT/KIX; Sapporo via Scoot/Peach often ~NT$6–9k one-way. Watch Peach's "Fly Day" Tuesday sales and Tigerair's flash fares.

**Thailand (Bangkok/Chiang Mai)** — November is **peak** (cool season, Loy Krathong ~11/24); Chiang Mai also peak for Yi Peng. Book **8–12 weeks ahead**; last-minute is expensive. Cheapest: Thai Lion Air, Nok Air, VietJet (via SGN/HAN), or China Airlines promo fares TPE→BKK ~NT$5–7k. Watch VietJet's 0đ promos and AirAsia Free Seats (usually Feb/Mar).

**Europe (any major city)** — November is **deep off-peak** (low season, cheapest month) — great value now. Book **8–14 weeks out**; fares bottom ~10 weeks. Cheapest: China Eastern/China Southern via PVG/CAN, or Turkish via IST; TPE→LHR/CDG/FRA often NT$18–26k round-trip. Watch China Airlines/EVA seasonal promos and Turkish Airlines IST stopover deals.

**USA (West/East Coast)** — November is **shoulder/off-peak** except Thanksgiving week (11/26) — avoid that window. Book **10–16 weeks out** for best fares. Cheapest: Starlux/China Airlines direct TPE→LAX/SFO/SEA (~NT$28–38k RT); East Coast via Korean Air/Asiana through ICN often cheaper. Watch Starlux launch promos and EVA's "Early Bird" sales.

**Egypt (Cairo)** — November is **peak** (ideal weather, high season) — book **10–14 weeks ahead**. No direct flights; cheapest via Istanbul (Turkish), Doha (Qatar), or Dubai (Emirates); TPE→CAI ~NT$30–42k RT. Watch Turkish Airlines' IST–CAI add-on deals and Qatar's stopover packages.

**Australia (Sydney/Melbourne)** — November is **shoulder/rising peak** (pre-summer, fares climbing toward Dec). Book **8–12 weeks out**. Cheapest: China Airlines/EVA direct TPE→SYD/MEL (~NT$28–36k RT), or Scoot/VietJet via SIN/SGN for less. Watch China Airlines' Australia promo fares and Scoot's "Make It Count" sales.

**Quick action:** Lock Europe and USA now (off-peak pricing is live); book Japan/Thailand within 2–4 weeks for early-Dec travel; set fare alerts on Google Flights/Skyscanner for Egypt and Australia.

## 📚 Learning

### 📚 Learning — Finance
> `2026-11-21 12:08:43`

#### 📚 Today's Concept: Return on Equity (ROE)

What it is: Return on Equity (ROE) measures how much profit a company generates for every dollar of shareholder equity, calculated as net income divided by average shareholders' equity. It's essentially the "return on investment" from the perspective of the company's owners.

Why it matters: ROE lets you compare how efficiently different companies convert investor capital into profits, which is useful for spotting well-run businesses versus capital-burning ones. A consistently high ROE often signals a durable competitive advantage.

Example: Suppose Company X earns $120 million in net income and holds $600 million in average shareholders' equity. ROE = $120M / $600M = 20%. That means for every $1 of equity invested, the company generates $0.20 in annual profit. If a peer earns only 8%, Company X is deploying shareholder capital far more effectively.

Rule of thumb: Look for ROE consistently above 15%, but check the debt load first—companies can inflate ROE by borrowing heavily rather than operating better, so a high ROE paired with rising debt is a warning sign, not a green light.

### 🧩 LeetCode Blind 100
> `2026-11-21 12:08:46`

#### 🧩 Blind 100 — 208. Implement Trie [Tries]
**連結:** https://leetcode.com/problems/implement-trie/
> 📅 **Today's Daily Challenge:** #3576 Find Subtree Sizes After Changes [Medium] — Tags: Array, Hash Table, String, Tree, Depth-First Search — https://leetcode.com/problems/find-subtree-sizes-after-changes/

**Problem Type:** Trie (Prefix Tree) — tree-based string data structure

**Key Insight:** Each node represents a character; store children in a dict and a boolean `is_end` flag. Insert/search/prefix all walk the tree one character at a time — no need to store full strings.

**Approach:**
1. Define `TrieNode` with `children = {}` and `is_end = False`.
2. `insert`: walk/create a node per char, mark last node `is_end = True`.
3. `search`: walk chars; return `True` only if path exists **and** `is_end` is set.
4. `startsWith`: same walk, but return `True` if path exists (ignore `is_end`).

**Python3 Solution:**
```python
class Trie:
    def __init__(self):
        self.root = {}

    def insert(self, word: str) -> None:
        node = self.root
        for ch in word:
            node = node.setdefault(ch, {})
        node['#'] = True  # sentinel marks end-of-word

    def search(self, word: str) -> bool:
        node = self.root
        for ch in word:
            if ch not in node:
                return False
            node = node[ch]
        return '#' in node

    def startsWith(self, prefix: str) -> bool:
        node = self.root
        for ch in prefix:
            if ch not in node:
                return False
            node = node[ch]
        return True
```
*(Dict-of-dicts is fastest in Python for contests — avoids class overhead. `'#'` sentinel is safe since inputs are lowercase letters.)*

**Complexity:** Time O(L) per operation (L = word/prefix length) | Space O(total chars inserted)

**Blind 100 Note:** Canonical Trie problem — the template for all prefix-tree questions. Represents the "Trie" pattern: fast prefix lookups, autocomplete, word dictionaries. Practice next: **211 Design Add and Search Words**, **212 Word Search II**, **648 Replace Words**, **1268 Search Suggestions System**.

**Contest Tips:**
- `search` vs `startsWith` differ **only** by the `is_end` check — a classic bug source.
- Use `dict.setdefault(ch, {})` to insert-and-descend in one line.
- Sentinel `'#'` beats a separate `is_end` key for speed and clarity.
- Empty string edge case: `search("")` should be `False` unless inserted; `startsWith("")` is always `True`.
- For wildcard variants (211), switch to recursion/DFS over children.

### 📷 Learning — Photography
> `2026-11-21 12:08:51`

#### 📷 Today's Concept: Sony A7C — S-Log2 vs S-Log3: When to Use Each

**What it is:** S-Log2 and S-Log3 are Sony's logarithmic gamma curves that flatten contrast and color to preserve maximum dynamic range for grading. S-Log3 mimics film negative density with cleaner shadows and more natural highlight rolloff, while S-Log2 is an older, flatter curve with more shadow detail baked in.

**Why it matters:** Choosing the right curve means cleaner shadows in low light (S-Log2) or smoother, more gradable highlights in high-contrast scenes (S-Log3) — the difference between muddy skin tones and cinematic flexibility.

**How to apply it:**
1. Use S-Log3 for controlled, high-contrast scenes — golden hour, backlit portraits, bright skies — where you want maximum highlight recovery.
2. Switch to S-Log2 in low light or when shadows dominate, since it holds shadow detail with less noise.
3. Always expose to the right: set zebras at 94% (S-Log3) or 100% (S-Log2) and push highlights just below clipping.
4. Shoot at base ISO 100 (S-Log3) or 200 (S-Log2) to minimize noise.
5. Grade with a Sony-provided LUT as a starting point, then refine contrast and saturation manually.

**Sony A7C tip:** Assign Picture Profile to a custom button (Menu → Custom Key) so you can toggle PP8 (S-Log3) and PP7 (S-Log2) instantly between shots.

**Common mistake:** Underexposing S-Log3 "to protect highlights" — this crushes shadows and amplifies noise on the A7C's 8-bit codec. Expose brighter than feels right; recover highlights in post, not shadows.

### 📚 Learning — Tech
> `2026-11-21 12:08:48`

#### 📚 Today's Concept: OAuth 2.0 and JWT internals

**What it is:** OAuth 2.0 is a delegation framework that lets a user grant a third-party app limited access to their resources without sharing credentials, issuing access tokens via flows like authorization code. JWT is a compact, self-contained token format (header.payload.signature) often used as the access token, carrying claims that servers verify cryptographically without a database lookup.

**When to use it:** Use OAuth 2.0 when your app needs to access another service's resources on a user's behalf—e.g., "Sign in with Google" or letting a calendar app read a user's Google Calendar. Use JWT for stateless auth between microservices or APIs where you want to avoid session lookups.

**Example:**
```json
// JWT payload (base64url-decoded)
{
  "sub": "user_123",
  "scope": "calendar.read",
  "exp": 1735689600,
  "iss": "https://auth.example.com"
}
// Server verifies signature + exp, no DB hit needed
```

**Gotcha:** People conflate the two—JWT is *not* OAuth, just a token format. And never trust a JWT's claims without verifying the signature; decoding base64 is not validation. Also, JWTs can't be revoked easily—keep lifetimes short and pair with refresh tokens.

### 🎬 Learning — YouTube
> `2026-11-21 12:08:54`

#### 🎬 今日主題：開箱 — 評測 vs 開箱 vs 使用心得的定位差異
**類別：** 開箱

**是什麼：** 評測是帶明確結論的比較分析（適合誰、值不值得買）；開箱是第一次拆封的驚喜過程；使用心得是長期使用後的真心話。三者目的不同，觀眾期待也不同。

**為什麼重要：** 定位混淆會讓觀眾不知道為什麼要看你的影片，也影響搜尋曝光與頻道辨識度，對剛起步的你尤其關鍵。

**怎麼做：**
1. 開箱片聚焦「第一次」的視覺驚喜與第一印象，長度控制在 5-8 分鐘。
2. 評測片要有比較對象與明確結論，適合累積搜尋流量。
3. 使用心得片設定「使用 X 週/月後」的時間框架，建立信任感。
4. 同一產品可拆成開箱→心得→評測三支片，形成內容階梯。
5. 用 AI 剪輯工具先剪開箱片（素材單純、節奏好抓），降低門檻。

**新手常犯的錯：** 把開箱拍成評測，還沒用就先下結論。避免方式：開箱片只講第一印象與外觀細節，結論留給心得片。

**延伸 idea：** 「A7C 開箱 + 一週後心得」兩支片：第一支拍拆封與初拍測試畫面，第二支分享實際帶去旅遊拍攝的優缺點，自然銜接你的攝影 Vlog 方向。
