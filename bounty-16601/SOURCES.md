# Sources and Claim Map

QA date: 2026-09-09

This file maps factual claims in the script to public/primary sources. Re-check live protocol parameters immediately before publication.

## RustChain primary sources

### RustChain homepage / Proof of Antiquity explainer
https://rustchain.org/

Supports:
- “1 CPU = 1 Vote” positioning.
- Proof of Antiquity rewards vintage hardware more heavily.
- Current six main fingerprint checks: clock-skew/oscillator drift, cache timing, SIMD identity, thermal drift entropy, instruction-path jitter, anti-emulation behavioral checks.
- Additional ROM fingerprint clustering language.
- Current published VM multiplier of `0.000000001x`.
- Current published base multiplier examples used in the script, including PowerPC G4 `2.50x` and Modern x86_64 `0.80x`.
- Current published tenure formula: +5% per year, capped at +50% after 10 years.
- Current install entry point `pip install clawrtc`.

### RustChain repository
https://github.com/Scottcjn/Rustchain

Supports:
- Project is publicly inspectable/open source.
- Source and documentation location used for production verification.

### RustChain API documentation
https://github.com/Scottcjn/Rustchain/blob/main/docs/API.md

Supports:
- Public health/epoch/miner/wallet inspection surfaces referenced in the script.
- Canonical wallet balance endpoint uses `miner_id`.

## Comparative concepts

The finished script does not make quantitative claims about competing chains, but the framing of Proof of Work and Proof of Stake as different resource-allocation models is standard background. No competitor performance, market-price or revenue claim is used.

## Editorial safeguards

1. The phrase “out-earn” refers only to RustChain's published *base weighting/multiplier*, not benchmark performance or guaranteed income.
2. Do not claim a specific RTC/day income. Earnings depend on network participation and protocol state.
3. Do not say hardware fingerprinting is impossible to spoof. The script explicitly describes anti-spoofing as RustChain's continuing security challenge.
4. Do not present generated terminal output as real. Production instructions require real capture or official-source screenshots.
5. Re-check multiplier values, VM weighting and tenure rules against `https://rustchain.org/` before final edit/publish because these are mutable protocol parameters.
6. Do not expose private wallet information, API keys or credentials in screen recordings.

## Current values captured for QA on 2026-09-09

From the live RustChain public explainer indexed this week:
- PowerPC G4 base multiplier: 2.50x
- PowerPC G5 base multiplier: 2.00x
- Modern x86_64 base multiplier: 0.80x
- Apple Silicon: 1.20x
- Generic ARM: 0.0005x
- VM policy multiplier: 0.000000001x
- Tenure growth: 5% per year, capped at +50% after 10 years

These values are included only to document what was QA'd when the package was authored.