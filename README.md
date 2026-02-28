# 📊 Crypto Trading Indicators Cheatsheet (Revised 2026)

## **Primary Indicators (Trend & Volatility)**

| **Indicator** | **📌 Purpose** | **⏱️ Best Timeframes** | **⚙️ Typical Settings** | **🚀 Best For** |
|---|---|---|---|---|
| **📈 Simple Moving Average (SMA)** | Identifying macro trends & dynamic S/R | 1H, 4H, Daily, Weekly | 50, 100, 200 periods | Long-term trend bias (e.g., "above 200 SMA = bullish") |
| **📉 Exponential MA (EMA)** | Faster trend-following in volatile markets | 1m, 5m, 15m, 1H, 4H | 9, 21, 50 periods | Quick trend changes, crossovers, intraday bias |
| **📊 Bollinger Bands (BB)** | Volatility measurement & mean reversion | 1m, 5m, 15m, 1H, Daily | 20-period, 2 std deviations | Breakouts, squeezes, and mean-reversion trades |
| **⬆️ Parabolic SAR** | Trailing stops & trend reversal detection | 5m, 15m, 1H, Daily | Start: 0.02, Increment: 0.02, Max: 0.20 | Trailing stop-loss in strong trending markets |
| **📏 Average True Range (ATR)** | Measuring volatility for position sizing | 15m, 1H, 4H, Daily | 14 periods | Stop-loss placement, position sizing — NOT a directional signal |

---

## **Momentum & Oscillator Indicators**

| **Indicator** | **📌 Purpose** | **⏱️ Best Timeframes** | **⚙️ Typical Settings** | **🚀 Best For** |
|---|---|---|---|---|
| **📉 MACD** | Momentum & trend confirmation | 15m, 1H, 4H, Daily | 12, 26, 9 (fast, slow, signal) | Identifying momentum shifts, divergences, crossovers |
| **📊 RSI** | Overbought/Oversold & divergences | 15m, 1H, 4H, Daily | 14 (adjust to 80/20 for high-vol coins) | Divergence detection, trend reversal confirmation |
| **⚡ Stochastic RSI** | Enhanced momentum sensitivity | 5m, 15m, 1H | 14, 3, 3 | Scalping and short-term momentum shifts |
| **🔀 Stochastic Oscillator** | Short-term overbought/oversold | 5m, 15m, 1H | %K: 14, %D: 3 (80/20 levels) | Range-bound markets, reversal timing |
| **📉 Williams %R** | Extreme price conditions | 15m, 1H, 4H | 14 | Identifying overbought (> −20) / oversold (< −80) zones |
| **🔀 KDJ** | Short-term momentum (popular in Asian markets) | 5m, 15m, 1H | 14, 3, 3 | Quick reversal signals in high volatility |
| **📐 ADX (Average Directional Index)** | Trend strength measurement | 15m, 1H, 4H, Daily | 14 | Filtering: ADX > 25 = trending; < 20 = ranging |

---

## **Volume & Flow Indicators**

| **Indicator** | **📌 Purpose** | **⏱️ Best Timeframes** | **⚙️ Typical Settings** | **🚀 Best For** |
|---|---|---|---|---|
| **📈 Volume MA (MAVOL)** | Spotting volume trends | 15m, 1H, Daily | 20, 50 periods | Confirming breakouts with above-average volume |
| **📊 On-Balance Volume (OBV)** | Cumulative buying/selling pressure | 1H, 4H, Daily | N/A (cumulative) | Detecting hidden divergences, early trend reversals |
| **💰 VWAP** | Volume-weighted fair price | Intraday (1m–1H) | Session-based | Intraday fair value, institutional entry/exit zones |

---

## **On-Chain Indicators (Crypto-Native)**

| **Indicator** | **📌 Purpose** | **⚙️ Key Levels** | **🚀 Best For** |
|---|---|---|---|
| **🔗 MVRV Z-Score** | Market over/undervaluation vs. realized value | > 3.7 = overvalued, < 1 = undervalued | Macro cycle top/bottom identification |
| **📡 NVT Ratio** | Network value relative to transaction volume | High NVT = potential overvaluation | Assessing if price is supported by real usage (less reliable post-ETF era — combine with off-chain data) |
| **🔥 Coin Days Destroyed (CDD)** | Long-dormant coin movement | Spikes = distribution | Detecting smart money movement at cycle extremes |
| **💵 Funding Rate** | Perpetual futures market sentiment | Highly positive = overleveraged longs; negative = overleveraged shorts | Gauging crowded positioning, squeeze risk |
| **📈 Open Interest (OI)** | Total outstanding derivatives contracts | Rapid OI growth (50–90%) often precedes volatility | Anticipating volatility spikes, confirming breakout strength |
| **🏦 Exchange Net Flows** | Coins moving on/off exchanges | Net inflows = sell pressure; outflows = accumulation | Gauging supply-side dynamics |

> **⚠️ Note on On-Chain Metrics (Post-ETF Era):** Since the launch of Bitcoin spot ETFs, traditional on-chain metrics like NVT and active addresses have become less directly correlated with price due to significant off-chain trading volume. Always combine on-chain data with derivatives and ETF flow data for a complete picture.

---

## **How to Use Indicators**

### **1. 🔍 Trend Confirmation**
- **Indicators**: EMA (9/21/50), SMA (200), MACD, ADX
- **Setup**: Price above 200 SMA = bullish bias. ADX > 25 confirms a trending market. Use MACD crossovers and histogram direction for momentum confirmation.

### **2. 📈 Volatility & Breakouts**
- **Indicators**: Bollinger Bands, ATR, MAVOL, OBV
- **Setup**: Bollinger Band squeeze (narrowing bands) signals incoming volatility. Confirm breakouts with above-average volume (MAVOL) and OBV divergence. Use ATR for stop-loss distance — not as a buy/sell signal.

### **3. ⚖️ Overbought/Oversold Levels**
- **Indicators**: RSI, Williams %R, Stochastic RSI
- **Setup**:
  - RSI > 70 (or 80 for high-vol coins) = overbought; RSI < 30 (or 20) = oversold.
  - **Don't blindly buy at RSI < 30 in a downtrend** — use RSI divergences as counter-trend filters, not standalone signals.
  - Combine with Williams %R (< −80 oversold, > −20 overbought) for confirmation.

### **4. 🔄 Reversals and Entries/Exits**
- **Indicators**: KDJ, Parabolic SAR, Stochastic, RSI divergences
- **Setup**: Look for KDJ/Stochastic crossovers in overbought/oversold zones. Parabolic SAR dot flips confirm trend direction changes. **Always confirm with a trend indicator** — SAR generates false signals in ranging markets.

### **5. 🔗 On-Chain & Derivatives Context (Crypto-Specific)**
- **Indicators**: MVRV Z-Score, Funding Rate, Open Interest, Exchange Flows
- **Setup**: Use MVRV Z-Score for macro cycle positioning. Monitor funding rates and OI for leverage buildup and squeeze risk. Track exchange net flows for supply-side pressure. This layer adds context that traditional indicators miss.

---

## **Indicator Combinations by Strategy**

### **1. ⏱️ Scalping (1m, 5m)**
- **Indicators**: EMA (9, 21), Stochastic RSI, Parabolic SAR, VWAP
- **Goal**: Quick entries/exits on micro-trends with VWAP as fair-value anchor.

### **2. 📅 Day Trading (15m, 1H)**
- **Indicators**: Bollinger Bands, RSI (14), MACD, VWAP, MAVOL
- **Goal**: Capture intraday momentum with volume-confirmed breakouts.

### **3. 📊 Swing Trading (4H, Daily)**
- **Indicators**: SMA (50, 200), MACD, RSI divergences, OBV, ADX
- **Goal**: Ride multi-day trends confirmed by momentum and volume flow.

### **4. 📈 Breakout Trading (Any timeframe)**
- **Indicators**: Bollinger Bands (squeeze), MAVOL, RSI, ATR (for stop placement)
- **Goal**: Enter on volatility expansion with volume confirmation and ATR-based stops.

### **5. 🔗 Macro/Position Trading (Weekly, Monthly)**
- **Indicators**: SMA (200), MVRV Z-Score, OI trends, Funding Rate, Exchange Flows
- **Goal**: Cycle-level positioning using on-chain and derivatives context.

---

## **🛠️ Tips for Success**

- **🔗 Don't Double Count**: Mix categories — one trend + one momentum + one volatility + one flow indicator. Five RSI variants on one chart is redundant.
- **📐 Use ADX as a Filter**: ADX > 25 → use trend-following strategies. ADX < 20 → use mean-reversion strategies. This alone prevents many false signals.
- **📏 ATR is for Sizing, Not Direction**: Set stops at 1.5–2× ATR. Never use ATR as a buy/sell trigger.
- **🔗 Layer On-Chain + Technical**: On-chain data (MVRV, exchange flows) provides the "why" behind price moves that chart patterns alone can't show.
- **📡 Watch Derivatives Data**: Extreme funding rates and rapidly growing OI have historically preceded major squeezes and volatility events in crypto.
- **📚 Backtest Before Deploying**: Validate indicator settings on historical data for your specific coin and timeframe. A 14-period RSI behaves very differently on BTC/USDT 5m vs. an altcoin daily chart.
- **⚠️ Risk Management First**: No indicator combination replaces disciplined stop-losses and position sizing. Define your risk per trade before entering.
- **🌐 Adapt to Market Regime**: Trending markets favor MA crossovers and MACD. Ranging markets favor RSI, Stochastic, and Bollinger Band mean-reversion. Check ADX first.
- **🏦 Account for the ETF Era**: Post-2024, Bitcoin's on-chain metrics are less reliable in isolation due to massive off-chain ETF trading volume. Supplement with ETF flow data and derivatives signals.
- **🤖 Consider Automation**: If using trading bots, combine RSI + MACD for trend confirmation and Bollinger Bands + Volume for breakout detection as proven bot-friendly setups.

---

## **⚠️ Common Mistakes to Avoid**

- **Stacking similar indicators** (e.g., RSI + Stochastic RSI + Williams %R all at once) — this is "double counting" and creates false confidence.
- **Using Parabolic SAR in choppy/ranging markets** — it generates rapid false signals when there's no clear trend.
- **Treating RSI < 30 as an automatic buy** — in a strong downtrend, RSI can stay oversold for extended periods.
- **Ignoring volume** — a breakout without volume is a fakeout until proven otherwise.
- **Over-optimizing settings** — curve-fitting indicator parameters to past data often fails in live markets.

---

*Prepared by Heiswayi Nrird · Revised February 2026*
