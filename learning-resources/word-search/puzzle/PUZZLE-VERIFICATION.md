# Interactive BMX Word Search — Puzzle Verification

**Grid dimensions:** 20 × 20  
**Coordinate system:** One-based row and column notation (`R#C#`).  
**Search directions tested:** horizontal, vertical, and diagonal; forward and backward.

## Transcribed grid

```text
GMIWQOJGPPFGQTTRKEUA
RKJZARFPSIEIUOKENOOJ
LZRSOZRGVVOLOEMNTSLW
FBGFOZJTQXCXCAVCSSPI
ICVLHQVBTLVORRNIBRTY
QFOCMZQGGLQIJOHNFEYI
FLWLETDRATPXFNBALDQE
IDPYILIXETSGQOTSWLOM
ODLBCOADSXYNORAOVISJ
TEHRRNMROBQCJEATYNCG
TBNRJCOMOZWBPSDHNEBN
IDBYYANSGIJRAHNOOVHZ
XMAACRDXNAQATIAMSDAN
UBHPCEBWOPLCTMRSNJYJ
OHBUJVAZMLAKEAIEIFFT
MQIBTICGSXYERNMNBBIY
QXLLZCKLLOBNSOBLOJBM
NTLCLHHRZNFSOXNSRJXJ
UDLEEYNQHJYYNOIFZFBJ
FMWNGXSMTGUJELLISCXK
```

## Verification results

| # | Term | Status | Verified match or matches |
|---:|---|---|---|
| 1 | NORA | Multiple matches (2) | R7C14-R4C14 (up); R9C12-R9C15 (right) |
| 2 | Encinas | Verified unique | R2C16-R8C16 (down) |
| 3 | Thomsen | Verified unique | R10C16-R16C16 (down) |
| 4 | Patterson | Verified unique | R11C13-R19C13 (down) |
| 5 | Hill | Verified unique | R15C2-R18C5 (down-right) |
| 6 | Miranda | Verified unique | R16C15-R10C15 (up) |
| 7 | Brackens | Verified unique | R11C12-R18C12 (down) |
| 8 | Loncarevich | Verified unique | R8C6-R18C6 (down) |
| 9 | Ellis | Verified unique | R20C13-R20C17 (right) |
| 10 | CUP | Not located | None |
| 11 | GT | Multiple matches (5) | R3C8-R4C8 (down); R6C8-R5C9 (up-right); R6C9-R5C9 (up); R6C9-R7C10 (down-right); R20C10-R20C9 (left) |
| 12 | Redline | Verified unique | R5C18-R11C18 (down) |
| 13 | Diamondback | Verified unique | R7C7-R17C7 (down) |
| 14 | Mongoose | Verified unique | R15C9-R8C9 (up) |
| 15 | Robinson | Verified unique | R18C17-R11C17 (up) |
| 16 | Hutch | Verified unique | R14C3-R18C7 (down-right) |
| 17 | Shimano | Verified unique | R11C14-R17C14 (down) |

## Critical findings

- `CUP` is preserved as official list position 10 but does not occur in the supplied grid.
- `NORA` occurs twice. No intended occurrence is selected without an official answer key.
- `GT` occurs five times. No intended occurrence is selected without an official answer key.
- All other listed terms occur once.
- The published puzzle and answer list are preserved exactly; no silent correction is applied.
