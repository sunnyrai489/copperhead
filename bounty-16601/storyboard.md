# Storyboard — Why a 2003 PowerBook Can Out-Earn a Modern PC on RustChain

**Canvas:** 16:9, 1920×1080
**Target runtime:** 4:45–5:15
**Style:** clean technical explainer; terminal captures + simple diagrams; no invented benchmark footage

| Time | Narration section | Visual / capture instruction | On-screen text |
|---|---|---|---|
| 0:00–0:08 | Hook: old machine vs new machine | Split screen. Left: rights-cleared/generic photo or generated silhouette of a PowerBook-era laptop. Right: modern desktop tower. Slow push-in. | `OLD HARDWARE > NEW HARDWARE?` |
| 0:08–0:25 | Current multiplier comparison | Screen capture the current `rustchain.org` multiplier table. Highlight only the PowerPC G4 row and Modern x86_64 row. Do not animate values not present on page. | `PowerPC G4: 2.50x` / `Modern x86_64: 0.80x` |
| 0:25–0:45 | Different scarce resources | Simple three-column vector diagram: Proof of Work → compute; Proof of Stake → capital; Proof of Antiquity → verified physical hardware identity. | `WHAT IS SCARCE?` |
| 0:45–1:10 | One CPU, one vote | Capture RustChain homepage section containing “1 CPU = 1 Vote.” Then cut to a diagram: one physical CPU icon → one ballot; a stack of VM windows → blocked symbol. | `1 PHYSICAL CPU = 1 VOTE` |
| 1:10–1:45 | Six fingerprint checks | Animate six labeled nodes around a CPU: clock drift, cache timing, SIMD identity, thermal drift, instruction jitter, anti-emulation. Source labels exactly from the current public page. | `6-CHECK HARDWARE FINGERPRINT` |
| 1:45–2:10 | VM economic penalty | Show a virtual-machine stack fading toward zero beside the published VM multiplier. Capture the current RustChain page for source proof before recreating as graphics. | `VM: 0.000000001x (published policy)` |
| 2:10–2:40 | Antiquity table | Scroll/capture the current multiplier table, pausing on 68K/386-486, SPARC, G4, G5, modern x86. Use a vertical age arrow rather than implying speed. | `AGE WEIGHT ≠ COMPUTE SPEED` |
| 2:40–3:10 | Tenure rule | Minimal line graphic showing base multiplier × tenure factor growing 5%/year and capped at +50% after 10 years. Put “per current published rule” below. | `+5% / YEAR • CAP +50%` |
| 3:10–3:35 | What it does not claim | Side-by-side: modern workstation wins a conventional speed meter; vintage machine wins an “antiquity weight” meter. | `NOT A SPEED CLAIM` |
| 3:35–4:00 | Security trade-off | Diagram of fingerprint → classification → multiplier with red arrows labeled firmware / thermal environment / emulation techniques pointing at fingerprint layer. | `HARD PROBLEM: PHYSICAL IDENTITY` |
| 4:00–4:18 | Install | Real terminal capture on a clean environment. Type but do not fake output: `pip install clawrtc`. If recording cannot safely install, show the command as text and capture the official install section instead. | `$ pip install clawrtc` |
| 4:18–4:40 | Inspectable network | Screen-capture public RustChain docs or homepage links for health, epoch, miners and wallet balance. Avoid showing any private wallet data. | `PUBLIC API • PUBLIC REPO` |
| 4:40–5:05 | Closing idea | Return to old-machine silhouette, now connected to a simple network graph. Fade to RustChain homepage tagline. | `KEEP OLD HARDWARE ALIVE` / `1 CPU = 1 VOTE` |

## Capture checklist

1. Capture `https://rustchain.org/` on the day of production so multiplier numbers match the live page.
2. Capture `https://github.com/Scottcjn/Rustchain` for the public-repo shot.
3. If terminal footage is used, record real commands and real output only; never fabricate a successful miner/attestation run.
4. Do not show a real user's wallet identifier, API key, private key, seed phrase or account session.
5. Use only generated, self-created or rights-cleared hardware imagery.
6. Add source URLs in the video description and keep the technical labels aligned with `SOURCES.md`.