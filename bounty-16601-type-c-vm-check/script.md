# Short Script — “Why a VM Gets Zero Weight”

**Target runtime:** 52–58 seconds
**Format:** 9:16 vertical

## Narration + overlays

**0–4s — Hook**
VO: “RustChain doesn’t just ask what CPU you claim to have.”
Overlay: **Claimed hardware ≠ verified hardware**

**4–12s — The gate**
VO: “Its public protocol describes a hardware fingerprint gate before antiquity weight is counted.”
Overlay: **Fingerprint first. Weight second.**

**12–22s — What is checked**
VO: “The whitepaper documents six required fingerprint checks, with extra checks for retro platforms.”
Overlay: **6 required checks • 7 on retro platforms**
Visual note: show six simple diagnostic tiles; do not invent pass results.

**22–34s — The consequence**
VO: “In the published reward algorithm, if the fingerprint fails, that miner’s weight is set to zero.”
Overlay: **fingerprint_passed = false → weight = 0**
Visual note: show the relevant public whitepaper code excerpt, highlighted.

**34–44s — Why it exists**
VO: “That’s the anti-emulation idea: reward weight should follow verified physical hardware, not a label supplied by a VM.”
Overlay: **Anti-emulation = protect physical-hardware weighting**

**44–53s — Important caveat**
VO: “It’s a security design, not a promise that spoofing is impossible. The checks still have to survive real adversaries.”
Overlay: **Security control, not magic**

**53–58s — CTA**
VO: “Read the fingerprint rules yourself in the RustChain whitepaper.”
Overlay: **Inspect the source → github.com/Scottcjn/Rustchain**

## Editing notes

Keep cuts fast but readable. Do not show fabricated command output. If a terminal shot is used, capture an actual public-repo command or source excerpt. No token-price or earnings graphics.