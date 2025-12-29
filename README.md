# Quantum Swing Matrix Pro Ultimate v5.0 – Five-Dimensional Swing Analysis System

![MT5 Indicator](https://img.shields.io/badge/Platform-MetaTrader%205-blue)  
![Version](https://img.shields.io/badge/Version-5.00-brightgreen)  
![Advanced](https://img.shields.io/badge/Type-Advanced%20AI%20%7C%20Fractal%20%7C%20Quantum-orange)  
![License](https://img.shields.io/badge/License-Free%20for%20Personal%20Use-red)

**Quantum Swing Matrix Pro Ultimate** adalah indikator MetaTrader 5 generasi terbaru yang mengintegrasikan **lima dimensi analisis** dalam satu sistem powerful:

1. **Fractal Engine** (Multi-Timeframe + Hurst Exponent + Harmonic)
2. **Volume Profile** & Delta Analysis
3. **Quantum Wave Oscillator** (FFT + Hilbert + Fisher + Jurik + Kalman)
4. **Neural Network Scoring** (7-layer adaptive dengan real-time learning)
5. **Risk Matrix** (VaR + Monte Carlo + Dynamic Position Sizing + Sharpe/Sortino)

Dirancang untuk trader profesional yang mencari **edge institusional** dengan confluence tinggi.

## Fitur Utama

- **Fractal Swing Detection** dengan Hurst Exponent & Adaptive Period
- **Multi-Timeframe Confluence Matrix** (M5 → D1)
- **Quantum Wave Oscillator** berbasis FFT + Hilbert Transform untuk deteksi cycle & phase shift
- **Neural Network 7-14-7-4-3** dengan 7 input (Trend, Momentum, Volume, Volatility, Time, Correlation, Regime) + real-time adaptation
- **Probability Clouds** & VaR Risk Bands
- **Dynamic Position Sizing** + Optimal SL/TP (1:2, 1:3, 1:4) + Monte Carlo VaR
- **Comprehensive Dashboard** dengan 4 kuadran (MTF, Quantum, Neural, Risk)
- **Alert System** (Terminal, Sound, Push, Email) pada signal high-confidence
- **Keyboard Shortcuts**: D (toggle dashboard), R (reset stats), Q/N/M (debug info)

## Cara Install

1. Download file `QuantumSwingMatrixPro.ex5` dari repository ini.
2. Buka MT5 → File → Open Data Folder → MQL5 → Indicators
3. Paste file `.ex5` ke folder Indicators
4. Restart MT5 atau refresh Navigator
5. Drag indikator **Quantum Swing Matrix Pro Ultimate v5.0** ke chart

Rekomendasi: Gunakan pada pair volatil seperti **XAUUSD, GBPJPY, EURUSD** di timeframe M15-H1.

## Input Parameters Utama

| Group               | Parameter                  | Default | Keterangan |
|---------------------|----------------------------|---------|------------|
| Fractal Engine      | InpFractalPeriod           | 5       | Base fractal period |
|                     | InpHurstThreshold          | 0.55    | Minimum Hurst untuk valid swing |
| Quantum Oscillator  | InpFFTLength               | 64      | FFT window (power of 2) |
|                     | InpFisherPeriod            | 10      | Fisher Transform period |
| Neural Network      | InpSignalThreshold         | 0.65    | Threshold sinyal (65%) |
|                     | InpEnableAdaptation        | true    | Learning real-time aktif |
| Risk Matrix         | InpRiskPercent             | 1.0     | Risk per trade |
|                     | InpMonteCarloSims          | 1000    | Simulasi Monte Carlo |
| Visualization       | InpShowDashboard           | true    | Tampilkan dashboard utama |

## Keyboard Shortcuts

- **D** → Toggle dashboard on/off
- **R** → Reset statistics
- **Q** → Print quantum state
- **N** → Print neural network probabilities
- **M** → Print risk metrics

## Catatan Penting

- Indikator ini **gratis untuk penggunaan pribadi**.
- Tidak diperbolehkan untuk dijual ulang atau distribusi komersial tanpa izin.
- Sistem ini sangat kompleks – gunakan dengan **money management yang ketat**.
- Bukan holy grail – tetap lakukan analisis manual sebagai confluence.

## Credit & Support

Dibuat oleh **M4DI~UciH4**  
GitHub: https://github.com/RizkyEvory  

Jika kamu terkesan dengan indikator ini, beri ⭐ di repository!  
Feedback, saran, atau bug report sangat dihargai.

Semoga tradingmu semakin presisi & profit konsisten di tahun 2025! 🌌🚀💎
