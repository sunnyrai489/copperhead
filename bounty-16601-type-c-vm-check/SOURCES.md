# Sources and Claim Map

Checked against public RustChain source on 2026-09-09.

## 1. Hardware fingerprint gate / number of checks

Source: `Scottcjn/Rustchain/docs/WHITEPAPER.md`, section “Hardware Fingerprinting System”.

Documented statement: RustChain implements a comprehensive 6-check hardware fingerprinting system, with 7 checks for retro platforms; the document says all checks must pass for a miner to receive the antiquity multiplier bonus.

Used for:
- “hardware fingerprint gate before antiquity weight is counted”
- “six required fingerprint checks, with extra checks for retro platforms”

## 2. Failed fingerprint → zero weight

Source: `Scottcjn/Rustchain/docs/WHITEPAPER.md`, section “Reward Distribution Algorithm”.

Published example:

```python
for miner_id, device_arch, fingerprint_passed in miners:
    if not fingerprint_passed:
        weight = 0.0  # VMs/emulators get ZERO
    else:
        weight = get_time_aged_multiplier(device_arch, chain_age_years)
```

Used for:
- “if the fingerprint fails, that miner’s weight is set to zero”
- overlay `fingerprint_passed = false → weight = 0`

## 3. Anti-emulation purpose

Source: `Scottcjn/Rustchain/docs/ARCHITECTURE_OVERVIEW.md`, protocol overview / RIP-200 core principles.

The architecture guide says the network uses 6+ hardware fingerprint checks to prevent VMs/emulators from earning rewards and lists anti-emulation as a core principle.

Used for:
- “reward weight should follow verified physical hardware, not a label supplied by a VM”

## Editorial safeguards

- This package reports what the public documentation says; it does not certify that the implementation defeats every spoofing technique.
- No claim is made about guaranteed earnings, RTC market price, profitability, or investment return.
- No benchmark is used.
- If the source changes before publication, the human publisher should update the affected line rather than preserve stale wording.
