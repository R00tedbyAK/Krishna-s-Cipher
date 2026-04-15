# VishuLeela

**Type:** Forensics / Steganography  
**Difficulty:** Medium  
**Flag Format:** `VISHU{[a-f0-9]{32}}`

## Description

A single PNG image of a ritual arrangement contains a hidden flag. Analyze LSB, metadata, and PNG chunks to extract `FLAG{...}`.

## Provided Files

- `ak_final.png` – The only artifact

## Tools Recommended

- `zsteg`, `steghide`, `binwalk`, `exiftool`, `strings`, `xxd`
- Python with `PIL`, `numpy`

## Constraints

- No brute-force required
- No external files needed
- Fully recoverable from the image alone

## Submission

Submit the flag in the format `FLAG{32_char_hex}`.

## Hint (if stuck)

> *The Lord hides in plain sight — look at the least significant places.*

---

**Good luck, investigator.**
