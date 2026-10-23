# Value Cruiser: weekly log

A live, public experiment: can a calm Claude agent keep up with the market with less pain? It tracks a **model portfolio** at exactly the guide's weights, **percentages only**, updated every Friday after the US close.

← [Back to the guide](README.md)

## The test (set before the start; never changed)

| | |
|---|---|
| **Start** | Mon Oct 5, 2026 (baseline: Fri Oct 2 close) |
| **Length** | 26 weeks |
| **Pass** | At week 26: a **smaller worst drop than the S&P 500 (SPY)** *and* a return **within 3 points of SPY's** |
| **Context only** | **QQQ** (Nasdaq-100) and **Bitcoin** (IBIT) |
| **Model rules** | Core: VTI 36 · VXUS 27 · GLDM 9 · SGOV 9 · JAAA 9. Value sleeve 10%: picked by the guide's screen on the first Friday of each month (up to 5 names, equal weight, bought at that Friday's close). Until the first screen, the 10% sits in VTI. Rebalanced quarterly or when a part leaves its band. Dividends reinvested. |
| **Expected range** | From the 2022–2026 backtest: 80% of 26-week stretches ended between +2.6% and +14.8%. A week outside the range gets flagged. |

**Honest prior:** in the backtest, Value Cruiser had a smaller worst drop than SPY in **99%** of 26-week stretches, but beat SPY's return in only **32%**. It passed this exact test (calmer *and* within 3 points) in **56%**. A coin flip with a cushion. That's why the verdict waits for week 26.

## Weekly results

| Week | Week ending | Value Cruiser (week) | SPY (week) | Since start | SPY | QQQ | Bitcoin | Worst drop | SPY worst drop | Trades | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 0 | Oct 2, 2026 | — | — | 0.0% | 0.0% | 0.0% | 0.0% | 0.0% | 0.0% | — | Start |
| 1 | Oct 9, 2026 | +0.4% | +1.2% | +0.4% | +1.2% | +0.2% | -2.5% | 0.0% | 0.0% | 1 | Within range |
| 2 | Oct 16, 2026 | -0.7% | -2.0% | -0.3% | -0.8% | -5.3% | -3.4% | -0.7% | -2.0% | 0 | Within range |
| 3 | Oct 23, 2026 | -0.0% | -0.4% | -0.3% | -1.3% | -6.0% | -3.7% | -0.7% | -2.4% | 0 | Within range |

## Value sleeve picks

| Picked | Ticker | Why it screened as cheap | Since pick |
|---|---|---|---|
| Oct 9, 2026 | ADBE | Forward P/E ~9–11x vs ~25x 5-yr median (GuruFocus / valueinvesting.io, Oct 8–9 2026). AI-disruption fear, yet the Sep 10 Q3 beat came with raised full-year guidance (Benzinga, Sep 11 2026). | +8.9% |
| Oct 9, 2026 | CRM | Forward P/E ~14x vs ~28x 5-yr median (GuruFocus, Oct 9 2026). Worries that AI agents shrink seat-based SaaS, but Aug 26 Q2 beat and raised full-year guidance (company release, Aug 26 2026). | +8.5% |
| Oct 9, 2026 | ACN | Forward P/E ~14x vs ~25x 5-yr median (GuruFocus, Oct 9 2026). Fear that AI shrinks consulting, but Oct 1 results showed record bookings and FY27 EPS guided up 6–9% (MarketChameleon, Oct 1 2026). | +19.4% |

## Weekly notes

*Newest first.*

**Oct 23, 2026 · week 3.** A mixed week: the S&P 500 slipped 0.4% and the Nasdaq-100 0.8%, while Value Cruiser ended flat (−0.04%). Gold was the main drag (−4.1%), with international (−1.1%) and VTI (−0.3%) a little lower; the T-bill and AAA ballast inched up.
 The value sleeve did the lifting again: ACN +8.6%, ADBE +7.6%, CRM +3.3% on the week, and the sleeve has grown to about 11.4% of the model. No trades; every core part stayed inside its band. Now −0.3% since start vs the S&P's −1.3%, with a smaller worst drop (−0.7% vs −2.4%), and within the expected range for week 3 (−2.3% to +3.8%).

**Oct 16, 2026 · week 2.** A risk-off week: the S&P 500 fell 2.0% and the Nasdaq-100 5.5%, while Value Cruiser gave up only 0.7%. VTI (−2.1%) and international (−1.6%) did most of the damage; gold slipped 0.7%, and the T-bill and AAA ballast inched up as intended.
 The new value sleeve earned its keep in its first week: ACN +9.9%, CRM +5.1%, ADBE +1.2%, so the 10% sleeve rose about 5% while tech sold off. No trades; every part stayed inside its band. Now −0.3% since start vs the S&P's −0.8%, with a smaller worst drop (−0.7% vs −2.0%), and within the expected range for week 2 (−1.8% to +3.0%).

**Oct 9, 2026 · week 1.** First week at sea: +0.4% vs the S&P 500's +1.2%. Gold (+1.1%) and VTI (+1.0%) pulled, international (−0.7%) dragged, and the T-bill and AAA ballast did what ballast does. Within the expected range (−1.7% to +2.2%).
 First value screen: ADBE, CRM and ACN made the cut, all priced well below their own 5-year forward P/E on AI-disruption fears while their latest results and guidance held up. The 10% sleeve moved out of VTI into the three, equal weight, at Friday's close. Skipped: INTU (estimates cut >10% after its Aug outlook), PEP (reported Oct 8, too close to earnings), CMCSA (the reason looks permanent). 20 of the 50 names could be sourced this run; the rest get another look next month.

---

<sub>Model portfolio, % only. Automated log, not financial advice. Past performance ≠ future results.</sub>
