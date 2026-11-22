
# 🏦 Institutional PO3 Pro: Algorithmic AMD & Smart Money Execution Engine
**Strict Non-Repainting Power of 3 Architecture with 15m A+M Filtering, 5m IFVG Auto-Entries & Live HTF Dashboards (Pine Script v6)**

---

### 1. Multi-Timeframe PO3 Architecture: Session-Synced AMD (`15m` A+M → `5m` IFVG)

<img width="1835" height="1079" alt="XAUUSD_2026-11-23_04-28-52" src="https://github.com/user-attachments/assets/be8d4d5c-631e-4561-8cd4-f935d222f4a5" />

The **Power of 3 (PO3 / AMD)** is one of the most sophisticated institutional concepts in modern financial markets. Rather than forcing all three phases onto a single noisy timeframe, this engine separates structural confirmation from precision execution across two synchronized timeframes:

#### A. Strict 3-Session Institutional Alignment (New York Time)
| Phase | Institutional Session | Execution Timeframe | Core Function |
| :--- | :--- | :--- | :--- |
| **A — Accumulation** | 🟡 **Asia Session** (`20:00 – 00:00 NY`) | **`15m`** | Builds the clean institutional range and filters out oversized, low-probability days (`NO PO3 today`). |
| **M — Manipulation** | 🟣 **London Session** (`02:00 – 05:00 NY`) | **`15m`** | Detects liquidity sweeps of the Asian High/Low (or breakout pullbacks & failed-M bias flips). |
| **D — Distribution** | 🔵 **New York Session** (`07:00 – 10:00 NY`) | **`5m`** | Waits for a confirmed **`5m` IFVG** (Inversion Fair Value Gap) to trigger the automated trade entry. |

#### B. Why `15m` Structure + `5m` Execution?
- **Higher-Timeframe Clarity (`15m`):** The `15m` chart filters out lower-timeframe noise, ensuring that the **Accumulation** box and **Manipulation** liquidity sweep represent genuine institutional footprints.
- **Sniper Entry Precision (`5m`):** Once `15m` A + M are locked in, the engine monitors the `5m` chart for a strong candle close through an opposing Fair Value Gap (**`5m` IFVG**) — automatically firing the **Distribution** trade at the exact shift in order flow.

---

### 2. Zero-Switching Single-Chart Workflow: `1H` Premium/Discount & HTF OB/GP Confluence

Constantly switching between `1W`, `1D`, `4H`, `1H`, `15m`, and `5m` charts during live market sessions causes hesitation and missed entries. This engine solves that by projecting **all Higher-Timeframe (HTF) institutional data directly onto your `5m` execution chart**.

#### A. `1H` Premium & Discount Directional Filter
- **Macro Intraday Bias:** Because the `1H` timeframe sits directly above both `15m` and `5m`, the engine locks the `1H` range Equilibrium (`50% EQ`) directly onto the `5m` chart.
- **Directional Confirmation:**
  - 🔴 **Above `50%` (Premium Zone):** Confirms high-probability **SELL** setups.
  - 🟢 **Below `50%` (Discount Zone):** Confirms high-probability **BUY** setups.

#### B. Long-Term HTF Institutional Zones (`4H` / `1D` / `1W` OB & GP)
- **Automated HTF Mapping:** Plots fresh Higher-Timeframe **Order Blocks (OB)** and **Golden Pockets (GP)** from `1H`, `4H`, `1D`, and `1W` with real-time **Fill % tracking** (`FRESH`, `TESTED`, `WEAK`, `NEAR BREAK`).
- **Real-World Confluence Example (`★ STRONG` Setup):**
  1. Price taps into a Higher-Timeframe **`4H` Supply OB** or **Golden Pocket** (confirming macro bearish direction).
  2. Simultaneously, the `15m` engine completes **Accumulation + Manipulation** right inside that `4H` zone.
  3. The `5m` chart prints a confirmed **IFVG** → The engine automatically flags it as a **`★ STRONG`** institutional setup and executes the trade.

---
<img width="2752" height="1536" alt="Gemini_Generated_Image_qcubgjqcubgjqcub" src="https://github.com/user-attachments/assets/bab71c3a-98ae-4917-afd3-84ae7611f7c7" />
### 3. Automated Trade Execution, Noise Filtering & Dual Live Dashboards

- **100% Non-Repainting (Candle-Close Only):** Every `15m` sweep, `5m` IFVG, and HTF zone update executes strictly on confirmed candle closes (`barstate.isconfirmed`).
- **Complete Auto-Trade Mapping:** Every valid signal automatically plots and tracks:
  - 🎯 **Automated Entry Level**
  - 🛡️ **Dynamic Stop Loss (`SL`)** placed beyond the manipulation extreme + ATR buffer (with automatic **Breakeven** after `TP1`)
  - 💰 **Dual Take-Profit Targets (`TP1` & `TP2`)** dynamically targeting opposite liquidity (`PDH`/`PDL`), HTF FVGs, or fixed R-multiples.
- **Smart Fake-Signal Protection:** Automatically blocks overtrading on choppy or overextended days with clear **`NO PO3 today`** chart labels.
- **Dual Institutional Dashboards:** Includes a real-time **PO3 & MTF Status Table** alongside a dedicated **GP Zones Fill % Table** (`1H`/`4H`/`1D`/`1W`) for instant decision-making from a single screen.
