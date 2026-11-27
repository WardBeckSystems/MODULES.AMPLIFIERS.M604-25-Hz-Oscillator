# M604 · Amplifiers

Ward-Beck Systems M604, 1967|0. Wiki page: [M604 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M604.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 45 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 1 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 4 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 113 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 6 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 11 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 27 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [2 topics](FORUM.md): what owners and technicians said about it.

## Circuit description

From [1967 - M604 - Dual Frequency Oscillator (2).pdf](MANUALS/1967%20-%20M604%20-%20Dual%20Frequency%20Oscillator%20(2).pdf) pages 3-8 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

with ref ere n c e t o drawing 8 1-129-02-00 1: integrated cin;:uit z l forwlll the b a. i c o. ci l later circuit, integrated circuita, Z2 a r:4 ZJ provide thea cti v el y balanced output and Ql, Q2, and QJ b the regulator.

Th. aeetion o f Zl aaaociated with ca, C9, R7. a e, RlO. Rll. and R1 3 for. a n active Bridged TEE band paaa filter which _y be hlned to 400 en 1000 Hz. by conditional connect o r auapping. The aine wave output appear. a t era BTld b fed to R34 the eo4ul. front ~Tlel tr1lll e OTlU ol. OUtput of Zl pin I J ia a b o led via R9 to the input o f.eetion 1 of Z l which ac ta a. a COlllparator and ganeratea aqua r e wave. at i t. output the amp litl.1de o f which i. determi na d by CRl and CR.2 (J.JV zen eX' diode.). 'J'he llIIlOUnt o f. qua X'e _v. a igna l fed into the Bridge TEE filter i. dat. X'lIlined by R6. Thb c o nuol will determine the di ator ti o nan d. amplitude atability oft he oa c i l h tor. 'I'he ph a a e X'e lati o n a hip of tha a ig na l volta g ea around. the can parat or aquar. wa v a ga na r ato rand Br id.g. TEE filter o f Z l, ia au e h aa t o X'. generative and therefore prod.uce a con tinuou a oaci l lat ion.

The output amplifier a C'OIlIposed ot then oninverti n g a e c tion Z2 and th. inverting a e c t ion aa provide ana c t ive l y balanced. output at the output coupling capac i t oX' e 19 and C20. TWO 600 ohal outpuu -ar~: P.r ovi de d appearing at the PC connector p ina J, 5 &amp; 4, 6. Thea ein turn are connect.d to the mo4 u le connector and. appear on pina J. 11 and. 4.12 re a pec ti v. l y.

The 2 4 t o 3 6 vck: a'Upp ly voltage ia regulated down 'to l6v. Ql a cta a a the ae r iaa pas a tranaiator, Q2 pe rfoX'llla th. function ot reterence Ulpl i fie rand voltage divider R29. R30 and. cOlllpeX'ed with the relatively cOM u n t emitte r t o baae vo luge (0.6v) of Q2. There aulting difference b U1plifbd by Q2 which intu.rn variaa the baa. current to the aeriea paa. treMiator 01. n:T Q3 a cta a • • high impenaAnce conaten t current CQUX'ca for the co lleetor of Q2 and baae ot Ql.

VOLTAGE C$.RT pca 1 -129

lie connector Pi ru:

10 11 12 13 14

ai 8 1.5..5 13 13 8 8 -13 13 1.5•.5 8 16

·z2 14 B.6 8 16 14

**Z3 14 8.6 B 16 14**

01 2 3 •.5 16

02 16..5 0.6

03 16.5 23.5 23

(1) Supply current nominally 1 8 rna.

(2) Me••ure llle nt. taken with a 20.00 0. ohm / volt Illete r.

(3) Tole renetl o f voltage llItIa. u re:ne n t -= 10%. (4) Supply voltage. e t for 24 vee •

SETW AND TEST PJt9C'£IlUU

1. Apply 2&amp;V dc. lowly to te.t t e r-ina h. and. note that the output eu r rent shauld be between 1 2 -19 _.

2. O1eck that requlator output a t the emitter 01 is +16.SV eSe.

l. Strap oscillator connector for. 00 Hz cwt put frequency. Adjust R6 t o give 0.35&quot; t o 0 ••&quot; distort ion.

Also note that the output level control range.hould b a betwean -13 d8nl to +14 05_ at. 00 H%..

S. Strap e-cillator connector at 1.000 Hz trequanea output. Tha output bval control ra&quot;9a. hou l d be -15 aa. to +10 dBm. Tha total ha rlDOn.ic distortion ah ould be les. than 0.5% (typica Uy Ie.. than 0.1 %) a t +8 deou t put.

6. Tha output eurrant sbould ba approximately 1 8 _ at both f r equa ncy aa tti ng a t + &amp; d!D output laval.

7. lAval chaJJ9a betwean fr~ancia. i. 3 l!B.

Ca..I N EC TOR OUTLINE.

24 V c.ot...1MON

**OUTPUT *1**

OUTPUT #Z.

) 400 H z. STRAP J 1KHz STRAP

0 60. DUAL PREOUENCI OSC ILlA'1&quot;OR. Page 1.

**DESCRIPTION**

.047 Illfd 22 at&quot;d 2Sv 6800 p td

Philip-'

Er10

**C344AB /A 47K**

T36 2-C226-o2SAS

**81 21 -100 -WSRO-682J**

C. 12 pEd Er10 81 01 -100-COGO-12 1K CS 1 2 pEd Erie

CO SOT Ph~l1Pl!l e7 SOT ce. 0 1 mEd 100V C344A8!A10K C,. 0 1 ID.!d ere 12 p t d Erie 8 l 0 1-1 0 0 - COGO-12 1K

ell

6800 ptd 10 atd 2SV 10 lilt!! 2SV

Erl. 8 12 1-100 wSRO-6 82J T3 62-8106-o2SAS

Cl. 10 Jl! d 2SV C15 1000 p t d Er1.8 12 1-100 -WSROI02 K

cIS 2 2 p Ed Er10 8111-1QO-COGO-22 lX en 1000 p Ed 8121-109-w5RO-10 2K c 18 22 pta 8111-100-C9GO-22lK C19 100 IIltd lSV Si eflleJUI E81 00 /1S C20 10 0 lIlt4 lSv

e21 100 Illt:d 35 V Siemens £8 100/35

CRl z e ne r Diode I. R. 1N746 -A CR2 Zene r Diode I. R. lN746 - A CR3 Silicone Di04e I. R. lN400 3

Jl 15 pin COnnector Elco 00 -600 7-0 15 -9 40 -00 2 J2 16 pin connector A:Ilphe nol 26 -15 9 -16

Printed c 1rcui t Brd. WBS 1-129

01 Treneie tor Silicone

**'NPU' 292102**

02 Transistor silicone (I'ilt'N) Pair child 2N51 3 7

03 Transistor PET (P rET) 2N5033

.1 22K ohms phllips/Ohmite All r e.is tors law 5&quot;

R2 22K unless e pe c i t ieCl

R3 100 otherwi.e

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVnRMQnN5YTRhajQ/view?resourcekey=0-X3KH_zqY5iSJhN_xmpuq8A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVnRMQnN5YTRhajQ&resourcekey=0-X3KH_zqY5iSJhN_xmpuq8A" width="240" alt="1967 - M604 - Power Supply.jpg"></a><br><sub>1967|0 · Power Supply</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVEtZRXlIT2NzalU/view?resourcekey=0-bpa-obTi-FEJVCWNf17YBQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVEtZRXlIT2NzalU&resourcekey=0-bpa-obTi-FEJVCWNf17YBQ" width="240" alt="1967 - M604 - Power supply in Rack.jpg"></a><br><sub>1967|0 · Power supply in Rack</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1967|0 · Power supply in Rack_small](https://drive.google.com/file/d/0B0yR0b5T78SKYUo5bU5TRjFCZUk/view?resourcekey=0-SDpnW5Ly_CQXaR7yR9aU9w) · [1967|0 · wbsps - module - m604 power supply in rack_small](https://drive.google.com/file/d/0B0yR0b5T78SKeldaN3hFUUstNVU/view?resourcekey=0-k9XCn5nW3ftzwKLGS2smnw) · [1967|0 · wbsps - module - m604 power supply_small](https://drive.google.com/file/d/0B0yR0b5T78SKLUR0ZE55VTZ6RGM/view?resourcekey=0-s-seApFZW2zhsY-zlYTLsw)

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbGNQc3Y1TXNLbzQ/view?resourcekey=0-Emrw84proyRfJz1FkJy_wA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbGNQc3Y1TXNLbzQ&resourcekey=0-Emrw84proyRfJz1FkJy_wA" width="240" alt="1967 - M604 - 1-129-02-001 - ESS OTHERWISE SPECIFIED IALL ISTORS ARE.jpg"></a><br><sub>1967|0 · 1-129-02-001 - ESS OTHERWISE SPECIFIED IALL ISTORS ARE · <a href="SCHEMATICS/1967%20-%20M604%20-%201-129-02-001%20-%20ESS%20OTHERWISE%20SPECIFIED%20IALL%20ISTORS%20ARE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTGR4UXh5VUVrLU0/view?resourcekey=0-Am9qOTF6SGzNBERXCt2C0w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTGR4UXh5VUVrLU0&resourcekey=0-Am9qOTF6SGzNBERXCt2C0w" width="240" alt="1967 - M604 - 1-129-02-001 - JOK DIST.jpg"></a><br><sub>1967|0 · 1-129-02-001 - JOK DIST · <a href="SCHEMATICS/1967%20-%20M604%20-%201-129-02-001%20-%20JOK%20DIST%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVEhKckhJVllZX0U/view?resourcekey=0-NX6hw1O_FxrIUrIGTEk5kg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVEhKckhJVllZX0U&resourcekey=0-NX6hw1O_FxrIUrIGTEk5kg" width="240" alt="1967 - M604 - 1-129-02-001 - TRIM LONTROL OUTPUT OUT IOMTBDBM.jpg"></a><br><sub>1967|0 · 1-129-02-001 - TRIM LONTROL OUTPUT OUT IOMTBDBM · <a href="SCHEMATICS/1967%20-%20M604%20-%201-129-02-001%20-%20TRIM%20LONTROL%20OUTPUT%20OUT%20IOMTBDBM%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUVpldHVjY1lZTjA/view?resourcekey=0-3eY7StKkj9anEvHfep0OjQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUVpldHVjY1lZTjA&resourcekey=0-3eY7StKkj9anEvHfep0OjQ" width="240" alt="1967 - M604 - 1-129-02-001 - TRIM SEE.jpg"></a><br><sub>1967|0 · 1-129-02-001 - TRIM SEE · <a href="SCHEMATICS/1967%20-%20M604%20-%201-129-02-001%20-%20TRIM%20SEE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTm9TSnhnbUFCNFk/view?resourcekey=0-LAPNKXpF2G3c0RY9mz9JAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTm9TSnhnbUFCNFk&resourcekey=0-LAPNKXpF2G3c0RY9mz9JAw" width="240" alt="1967 - M604 - 1-129-02-001 - UNLESS OTHERW RESISTORS ARE.jpg"></a><br><sub>1967|0 · 1-129-02-001 - UNLESS OTHERW RESISTORS ARE · <a href="SCHEMATICS/1967%20-%20M604%20-%201-129-02-001%20-%20UNLESS%20OTHERW%20RESISTORS%20ARE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbUZyN0tZQnZJc1E/view?resourcekey=0-e7tyKWJkHpnYy0XyDtHFoQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbUZyN0tZQnZJc1E&resourcekey=0-e7tyKWJkHpnYy0XyDtHFoQ" width="240" alt="1967 - M604 - 1-129-06-001 - FINSH EGERM RZA.jpg"></a><br><sub>1967|0 · 1-129-06-001 - FINSH EGERM RZA · <a href="SCHEMATICS/1967%20-%20M604%20-%201-129-06-001%20-%20FINSH%20EGERM%20RZA%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKamJORmdDVXB5aVE/view?resourcekey=0-c-it2srS_xdoK66H8599bA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKamJORmdDVXB5aVE&resourcekey=0-c-it2srS_xdoK66H8599bA" width="240" alt="1967 - M604 - 604-02-001 - MOPICKD OLS.jpg"></a><br><sub>1967|0 · 604-02-001 - MOPICKD OLS · <a href="SCHEMATICS/1967%20-%20M604%20-%20604-02-001%20-%20MOPICKD%20OLS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYlJzZlVIODBtbWc/view?resourcekey=0-DtRimVvvQrju6pJY_CPm2A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYlJzZlVIODBtbWc&resourcekey=0-DtRimVvvQrju6pJY_CPm2A" width="240" alt="1967 - M604 - 604-02-001 - STRAP FOR.jpg"></a><br><sub>1967|0 · 604-02-001 - STRAP FOR · <a href="SCHEMATICS/1967%20-%20M604%20-%20604-02-001%20-%20STRAP%20FOR%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYmNxd3NsMVZobDA/view?resourcekey=0-oDYKufLIEgF9TAOl0X-NfA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYmNxd3NsMVZobDA&resourcekey=0-oDYKufLIEgF9TAOl0X-NfA" width="240" alt="1971 - M604 - 1-129-06-001 - HNZES BARD.jpg"></a><br><sub>1971|4 · 1-129-06-001 - HNZES BARD · <a href="SCHEMATICS/1971%20-%20M604%20-%201-129-06-001%20-%20HNZES%20BARD%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1975 - 604-02-002 - M604A 25 Hz OSCILLATOR SCHEMATIC - DRN MRW - ISS 1.png`, `19xx - 1-129-02-001.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSGRZVEI4SXhMOHM/view?resourcekey=0-7Q0K1MFaAUTX9XNY3MLiTw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSGRZVEI4SXhMOHM&resourcekey=0-7Q0K1MFaAUTX9XNY3MLiTw" width="240" alt="1967 - M604 - P006 - Connector Outline.jpg"></a><br><sub>1967|0 · P006 - Connector Outline</sub></td></tr>
</table>

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | +24 V UNREG | power |  | medium |
| 3 | OUTPUT 1 | out | OUTPUT 1 | medium |
| 4 | OUTPUT 2 | out | OUTPUT 2 | medium |
| 6 | 400 HZ STRAP | strap |  | medium |
| 7 | STRAP COMMON (400 HZ / 1 KHZ) | strap |  | medium |
| 8 | 1 KHZ STRAP | strap |  | medium |
| 9 | GROUND | ground |  | medium |
| 10 | 24V COMMON | ground |  | medium |
| 11 | OUTPUT 1 | out | OUTPUT 1 | medium |
| 12 | OUTPUT 2 | out | OUTPUT 2 | medium |

**Straps:** 400Hz STRAP: P1-6 P1-7 · 1KHz STRAP: P1-7 P1-8

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb202TFZpdWRnWnc/view?resourcekey=0-VC1MREklzj6TQ53A3Zk-Cg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb202TFZpdWRnWnc&resourcekey=0-VC1MREklzj6TQ53A3Zk-Cg" width="240" alt="1967 - M604 - Dual Frequency Oscillator (2).pdf"></a><br><sub>1967|0 · Dual Frequency Oscillator (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKallYVXNSWEhVOGc/view?resourcekey=0-R8TpwkI2vdzmMa98_BGQiQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKallYVXNSWEhVOGc&resourcekey=0-R8TpwkI2vdzmMa98_BGQiQ" width="240" alt="1967 - M604 - Dual Frequency Oscillator.pdf"></a><br><sub>1967|0 · Dual Frequency Oscillator</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNTdtcllTOFVqdDg/view?resourcekey=0-5q-ZXg4z-vCYAkAEiSmuGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNTdtcllTOFVqdDg&resourcekey=0-5q-ZXg4z-vCYAkAEiSmuGw" width="240" alt="1967 - M604 - P001 - Title Page.jpg"></a><br><sub>1967|0 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbUlmakQ1cU9qODA/view?resourcekey=0-cOLjamYoOoCcENU8_8zjyg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbUlmakQ1cU9qODA&resourcekey=0-cOLjamYoOoCcENU8_8zjyg" width="240" alt="1967 - M604 - P002 - Technical Data.jpg"></a><br><sub>1967|0 · P002 - Technical Data</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaVhxTWpLYmhJbkU/view?resourcekey=0-qNm2_se_iLkSAMbgzMCn9A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaVhxTWpLYmhJbkU&resourcekey=0-qNm2_se_iLkSAMbgzMCn9A" width="240" alt="1967 - M604 - P003 - Circuit Description.jpg"></a><br><sub>1967|0 · P003 - Circuit Description</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeUYxY1ZXenYxdjA/view?resourcekey=0-AYKPgNOT_-_YzneL5OCUhg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeUYxY1ZXenYxdjA&resourcekey=0-AYKPgNOT_-_YzneL5OCUhg" width="240" alt="1967 - M604 - P004 - Voltage Chart.jpg"></a><br><sub>1967|0 · P004 - Voltage Chart</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTTRuYmI3UzBQTU0/view?resourcekey=0-cY-MTktqZtgtpYQUfHoWew" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTTRuYmI3UzBQTU0&resourcekey=0-cY-MTktqZtgtpYQUfHoWew" width="240" alt="1967 - M604 - P005 - Setup and Test Procedure.jpg"></a><br><sub>1967|0 · P005 - Setup and Test Procedure</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKekhWMHBLQ3lCUWM/view?resourcekey=0-jG0GMFvZrqPsh2TEPMFnkA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKekhWMHBLQ3lCUWM&resourcekey=0-jG0GMFvZrqPsh2TEPMFnkA" width="240" alt="1967 - M604 - P007 - Parts List 01.jpg"></a><br><sub>1967|0 · P007 - Parts List 01</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZkpVS3JEaUdBaHc/view?resourcekey=0-9ueD4XwxQyhkaSAySe_yXA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZkpVS3JEaUdBaHc&resourcekey=0-9ueD4XwxQyhkaSAySe_yXA" width="240" alt="1967 - M604 - P008 - Parts List 02.jpg"></a><br><sub>1967|0 · P008 - Parts List 02</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ/view?resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ&resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" width="240" alt="1975 - M604 - PRICE LIST - PRICE LIST.jpg"></a><br><sub>1975|8 · PRICE LIST - PRICE LIST</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1967 - M604 - 1-129-02-001 - JOK DIST.kicad_sch](KICAD/1967%20-%20M604%20-%201-129-02-001%20-%20JOK%20DIST.kicad_sch)
- [1967 - M604 - 1-129-02-001 - TRIM LONTROL OUTPUT OUT IOMTBDBM.kicad_sch](KICAD/1967%20-%20M604%20-%201-129-02-001%20-%20TRIM%20LONTROL%20OUTPUT%20OUT%20IOMTBDBM.kicad_sch)
- [1967 - M604 - 1-129-02-001 - TRIM SEE.kicad_sch](KICAD/1967%20-%20M604%20-%201-129-02-001%20-%20TRIM%20SEE.kicad_sch)
- [1967 - M604 - 1-129-02-001 - UNLESS OTHERW RESISTORS ARE.kicad_sch](KICAD/1967%20-%20M604%20-%201-129-02-001%20-%20UNLESS%20OTHERW%20RESISTORS%20ARE.kicad_sch)
- [1967 - M604 - 604-02-001 - MOPICKD OLS.kicad_sch](KICAD/1967%20-%20M604%20-%20604-02-001%20-%20MOPICKD%20OLS.kicad_sch)
- [1967 - M604 - 604-02-001 - STRAP FOR.kicad_sch](KICAD/1967%20-%20M604%20-%20604-02-001%20-%20STRAP%20FOR.kicad_sch)
- [1967 - M604 - Dual Frequency Oscillator p10.kicad_sch](KICAD/1967%20-%20M604%20-%20Dual%20Frequency%20Oscillator%20p10.kicad_sch)
- [1975 - 604-02-002 - M604A 25 Hz OSCILLATOR SCHEMATIC - DRN MRW - ISS 1.kicad_sch](KICAD/1975%20-%20604-02-002%20-%20M604A%2025%20Hz%20OSCILLATOR%20SCHEMATIC%20-%20DRN%20MRW%20-%20ISS%201.kicad_sch)
- [19xx - 1-129-02-001.kicad_sch](KICAD/19xx%20-%201-129-02-001.kicad_sch)
- [M604.kicad_sym](KICAD/M604.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
