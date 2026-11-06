---
title: The Export of Goods (Control) (Amendment No 7) Order 1994
id: uksi/1994/534
type: UnitedKingdomStatutoryInstrument
category: secondary
status: as-enacted
made_date: '1994-03-01'
text_date: null
extent: null
source_url: https://www.legislation.gov.uk/uksi/1994/534
pdf_urls:
- http://www.legislation.gov.uk/uksi/1994/534/made/data.pdf
pending_changes: 1
repealed_on: null
attribution: © Crown and database right. Derived from content available under the Open Government Licence v3.0 from legislation.gov.uk.
summary: ''
---

# The Export of Goods (Control) (Amendment No 7) Order 1994

> This is the text as originally enacted or made. It may have been changed since; check legislation.gov.uk for the current version.

1994 No. 534

CUSTOMS AND EXCISE

The Export of Goods (Control) (Amendment No 7) Order 1994

Made

1st March 1994

Coming into force

2nd March 1994

The Secretary of State, in exercise of powers conferred by section 1 of the Import, Export and Customs Powers (Defence) Act 1939[^f00001] and now vested in him[^f00002], and of all other powers enabling him in that behalf, hereby makes the following Order:

**1.** This Order may be cited as the Export of Goods (Control) (Amendment No 7) Order 1994 and shall come into force on 2nd March 1994.

**2.** The Export of Goods (Control) Order 1992[^f00003] shall be further amended as follows:—

in Group 3 of Part III of Schedule 1—

- (i) for entry 3A001 sub—head a.2, there shall be substituted the following:

  > - Microprocessor microcircuits, microcomputer microcircuits, microcontroller microcircuits, electrical erasable programmable read-only memories (EEPROMs), static random-access memories (SRAMs), storage integrated circuits manufactured from a compound semiconductor, analogue-to-digital converters, digital-to-analogue converters, electro-optical or optical integrated circuits for signal processing, field programmable gate arrays, field programmable logic arrays, neural network integrated circuits, custom integrated circuits for which either the function is unknown or the control status of the equipment in which the integrated circuit will be used is unknown, or Fast Fourier Transform (FFT) processors, as follows:
  >   - (a) Rated for operation at an ambient temperature above 398 K (125°C);
  >   - (b) Rated for operation at an ambient temperature below 218 K (−55°C); or
  >   - (c) Rated for operation over the entire ambient temperature range from 218 K (−55°C) to 398 K (125°C);
  >   - Note: This sub-head does not apply to integrated circuits for civil automobile or railway train applications.

  ;
- (ii) for entry 3A001 sub-head a.11, there shall be substituted the following:

  > - Digital integrated circuits based upon any compound semiconductor and having either of the following:
  >   - (a) An equivalent gate count of more than 300 (2 input gates); or
  >   - (b) A toggle frequency exceeding 1.2 GHz.
  > - Note: This sub-head does not apply to microprocessor microcircuits, microcomputer microcircuits, microcontroller microcircuits, electrical erasable programmable read-only memories (EEPROMs), static random-access memories (SRAMs), storage integrated circuits manufactured from a compound semiconductor, analogue-to-digital converters, digital-to- analogue converters, electro-optical or optical integrated circuits for signal processing, field programmable gate arrays, field programmable logic arrays, neural network integrated circuits, custom integrated circuits for which either the function is unknown or the control status of the equipment in which the integrated circuit will be used is unknown, or Fast Fourier Transform (FFT) processors;

  ;
- (iii) in Note 2.b to entry 4A003, *N.B.* 1 shall be deleted and in *N.B* 2, the number “2.” shall be deleted;
- (iv) in entry 4A003 head g shall be deleted;
- (v) in Category 4, for the Technical Note to Category 4 there shall be substituted the following:

  > Note to Category 4
  >
  > **Composite Theoretical Performance (CTP)**
  >
  > **Abbreviations used in this Note**
  >
  > |  |  |
  > | --- | --- |
  > | CE | computing element (typically an arithmetic logical unit) |
  > | FP | floating point |
  > | XP | fixed point |
  > | t | execution time |
  > | XOR | exclusive OR |
  > | CPU | central processing unit |
  > | TP | theoretical performance (of a single CE) |
  > | CTP | composite theoretical performance (multiple CEs) |
  > | R | effective calculating rate |
  > | WL | word length |
  > | L | word length adjustment |
  > | \* | multiply |
  > |  | Execution time ‘t’ is expressed in microseconds, TP and CTP are expressed in millions of theoretical operations per second (Mtops) and WL is expressed in bits. |
  >
  > **1. Outline of the CTP calculation method**
  >
  > CTP is a measure of computational performance given in Mtops. For the purpose of this category, in calculating the CTP of an aggregation of CEs the following three steps are required:
  >
  > Calculate the effective calculating rate R for each CE;
  >
  > **2.** Apply the word length adjustment (L) to the effective calculating rate (R), resulting in a Theoretical Performance (TP) for each CE;
  >
  > **3.** If there is more than one CE, combine the TPs resulting in a CTP for the aggregation.
  >
  > Details of these steps follow.
  >
  > |  |  |
  > | --- | --- |
  > | Note 1: | For aggregations of multiple CEs which have both shared and unshared memory subsystems, the calculation of CTP is completed hierarchically, in two steps: first aggregate the groups of CEs sharing memory, second calculate the CTP of the groups using the calculation method for multiple CEs not sharing memory. |
  > | Note 2: | CEs that are limited to input/output and peripheral functions (e.g disk drive, communication and video display controllers) are not aggregated into the CTP calculation. |
  >
  > Step 1: **The effective calculating rate R**
  >
  > | *For CEs implementing: Note: Every CE must be evaluated independently* | *Effective calculating rate, R* |
  > | --- | --- |
  > | XP only | [formula: see source](https://www.legislation.gov.uk/uksi/1994/534) |
  > |  | If no add is implemented use: |
  > | (R <sub>xp</sub>) | [formula: see source](https://www.legislation.gov.uk/uksi/1994/534) |
  > |  | If neither add nor multiply is implemented use the fastest availablearithmetic operation as follows: |
  > |  | [formula: see source](https://www.legislation.gov.uk/uksi/1994/534) |
  > |  | See Notes X & Z |
  > | FP only<br>(R <sub>fp</sub>) | Max<br>[formula: see source](https://www.legislation.gov.uk/uksi/1994/534) |
  > |  | See Notes X & Y |
  > | Both FP and XP<br>(R) | Calculate both<br>R <sub>xp</sub>' R <sub>fp</sub> |
  > | For simple logic processors not implementing any of the specified arithmetic operations. | [formula: see source](https://www.legislation.gov.uk/uksi/1994/534)<br>- Where t <sub>log</sub> is the execute time of the XOR, of for logic hardware not implementing the XOR, the fastest simple logic operation. |
  > |  | See Notes X & Z |
  > | For special logic processors not using any of the specified arithmetic or logic operations. | [formula: see source](https://www.legislation.gov.uk/uksi/1994/534)<br>- Where R\| is the number of results per second, WL is the number of bits upon which the logic operation occurs, and 64 is a factor to normalise to a 64 bit operation. |
  >
  > |  |  |
  > | --- | --- |
  > | Note W: | For a pipelined CE capable of executing up to one arithmetic or logic operation every clock cycle after the pipeline is full, a pipelined rate can be established. The effective calculating rate (R) for such a CE is the faster of the pipelined rate or non-pipelined execution rate. |
  > | Note X: | For a CE which performs multiple operations of a specific type in a single cycle (e.g., two additions per cycle or two identical logic operations per cycle), the execution time t is given by:<br>[formula: see source](https://www.legislation.gov.uk/uksi/1994/534) |
  > |  | CEs which perform different types of arithmetic or logic operations in a single machine cycle are to be treated as multiple separate CEs performing simultaneously (e.g., a CE performing an addition and a multiplication in one cycle is to be treated as two CEs, the first performing an addition in one cycle and the second performing a multiplication in one cycle). |
  > |  | If a single CE has both scalar function and vector function, use the shorter execution time value. |
  > | Note Y: | For the CE that does not implement FP add or FP multiply, but that performs FP divide:<br>[formula: see source](https://www.legislation.gov.uk/uksi/1994/534) |
  > | If the CE implements FP reciprocal but not FP add, FP multiply or FP divide, then [formula: see source](https://www.legislation.gov.uk/uksi/1994/534) |  |
  > |  | If none of the specified instructions is implemented, the effective FP rate is 0. |
  > | Note Z: | In simple logic operations, a single instruction performs a single logic manipulation of no more than two operands of given lengths. In complex logic operations, a single instruction performs multiple logic manipulations to produce one or more results from two or more operands. |
  >
  > Rates should be calculated for all supported operand lengths considering both pipelined operations (if supported), and non-pipelined operations using the fastest executing instruction for each operand length based on:
  >
  > **1.** Pipelined or register-to-register operations. Exclude extraordinarily short execution times generated for operations on a predetermined operand or operands (for example, multiplication by 0 or 1). If no register-to register operations are implemented, continue with (2).
  >
  > **2.** The faster of register-to-memory or memory-to-register operations; if these also do not exist, then continue with (3).
  >
  > **3.** Memory-to-memory.
  >
  > In each case above, use the shortest execution time certified by the manufacturer.
  >
  > Step 2: **TP for each supported operand length WL**
  >
  > Adjust the effective rate R (or R') by the word length adjustment L as follows:
  >
  > [formula: see source](https://www.legislation.gov.uk/uksi/1994/534)
  >
  > - where L = (1/3 + WL/96)
  >
  > |  |  |
  > | --- | --- |
  > | Note: | The word length WL used in these calculations is the operand length in bits. (If an operation uses operands of different lengths, select the largest word length.) |
  > |  | The combination of a mantissa ALU and an exponent ALU of a floating point processor or unit is considered to be one CE with a Word Length (WL) equal to the number of bits in the data representation (typically 32 or 64) for purposes of the CTP calculation. |
  >
  > This adjustment is not applied to specialised logic processors which do not use XOR instructions. In this case TP = R.
  >
  > Select the maximum resulting value of TP for:
  >
  > - Each XP—only CE (R<sub>xp</sub>);
  > - Each FP—only CE (R <sub>fp</sub>);
  > - Each combined FP and XP CE (R);
  > - Each simple logic processor not implementing any of the specified arithmetic operations; and
  > - Each special logic processor not using any of the specified arithmetic or logic operations.
  >
  > Step 3: **CTP for aggregations of CEs, including CPUs**
  >
  > For a CPU with a single CE,
  >
  > - CTP = TP
  >
  > (for CEs performing both fixed and floating point operations
  >
  > - TP = max (TP<sub>fp</sub>, TP<sub>xp</sub>))
  >
  > CTP for aggregations of multiple CEs operating simultaneously is calculated as follows:
  >
  > |  |  |
  > | --- | --- |
  > | Note 1: | For aggregations that do not allow all of the CEs to run simultaneously, the possible combination of CEs that provides the largest CTP should be used. The TP of each contributing CE is to be calculated at its maximum value theoretically possible before the CTP of the combination is derived. |
  > |  | N.B. To determine the possible combinations of simultaneously operating CEs, generate an instruction sequence that initiates operations in multiple CEs, beginning with the slowest CE (the one needing the largest number of cycles to complete its operation) and ending with the fastest CE. At each cycle of the sequence, the combination of CEs that are in operation during that cycle is a possible combination. The instruction sequence must take into account all hardware and/or architectural constraints on overlapping operations. |
  > | Note 2: | A single integrated circuit chip or board assembly may contain multiple CEs. |
  > | Note 3: | Simultaneous operations are assumed to exist when the computer manufacturer claims concurrent, parallel or simultaneous operation or execution in a manual or brochure for the computer. |
  > | Note 4: | CTP values are not to be aggregated for CE combinations (inter) connected by local area networks, Wide Area Networks, input/ output shared connections/devices, input/output controllers and any communication interconnection implemented by software. |
  > | Note 5: | CTP values must be aggregated for multiple CEs specially designed to enhance performance by aggregation, operating simultaneously and sharing memory, — or multiple memory/CE — combinations operating simultaneously utilising specially designed hardware. This aggregation does not apply to assemblies described by entry 4A003d |
  > |  | [formula: see source](https://www.legislation.gov.uk/uksi/1994/534)<br>- where the TPs are ordered by value, with TP1 being the highest, TP2 being the second highest,…, and TPn being the lowest. Ci is a coefficient determined by the strength of the interconnection between CEs, as follows: |
  >
  > For multiple CEs operating simultaneously and sharing memory:
  >
  > - C<sub>2</sub> = C<sub>3</sub> = C<sub>4</sub> = … = C<sub>n</sub> = 0.75
  >
  >   |  |  |
  >   | --- | --- |
  >   | Note 1: | When the CTP calculated by the above method does not exceed 194 Mtops, the following formula may be used to calculate C<sub>i</sub>:<br>[formula: see source](https://www.legislation.gov.uk/uksi/1994/534)<br>- where m = number of CEs or groups of CEs sharing access.<br>provided:<br>**1.** The TPi of each CE or group of CEs does not exceed 30 Mtops;<br>**2.** The CEs or groups of CEs share access to main memory (excluding cache memory) over a single channel; and<br>**3.** Only one CE or group of CEs can have use of the channel at any given time.<br>N.B. This does not apply to items controlled under Category 3. |
  >   | Note 2: | CEs share memory if they access a common segment of solid state memory. This memory may include cache memory, main memory, or other internal memory. Peripheral memory devices such as disk drives, tape drives or RAM disks are not included. |
  >
  > For multiple CEs or groups of CEs not sharing memory, interconnected by one or more data channels:
  >
  > - C<sub>i</sub> = 0.75 \* k<sub>i</sub> (i = 2, …,32) (see Note below)
  > - \= 0.60 \* k<sub>i</sub> (i = 33, …,64)
  > - \= 0.45 \* k<sub>i</sub> (i = 65, …,256)
  > - \= 0.30 \* k<sub>i</sub> (i > 256)
  >
  > The value of C<sub>i</sub> is based on the number of CEs, not the number of nodes.
  >
  > where
  >
  > - k<sub>i</sub> = min (S<sub>i</sub>/K<sub>r,</sub> 1), and
  > - K<sub>r</sub> = normalising factor of 20 Mbytes/s.
  > - S<sub>i</sub> = sum of the maximum data rates (in units of Mbytes/s) for all data channels connected to the i<sup>th</sup> CE or group of CEs sharing memory.
  >
  > When calculating a C<sub>i</sub> for a group of CEs, the number of the first CE in a group determines the proper limit for C<sub>i</sub>. For example, in an aggregation of groups consisting of 3 CEs each, the 22nd group will contain CE<sub>64</sub>, CE<sub>65</sub> and CE<sub>66</sub>. The proper limit for C<sub>i</sub> for this group is 0.60.
  >
  > Aggregation (of CEs or groups of CEs) should be from fastest-to-slowest; i.e.:
  >
  > - TP<sub>1</sub> ≥ TP<sub>2</sub> ≥ … ≥ TP<sub>n,</sub> and
  >
  > in the case of TP<sub>i</sub> = TP<sub>i+1</sub>, from the largest to smallest; i.e.:
  >
  > C<sub>i</sub> ≥ C<sub>i+1</sub>
  >
  > |  |  |
  > | --- | --- |
  > | Note: | The k<sub>i</sub> factor is not to be applied to CEs 2 to 12 if the TP<sub>i</sub> of the CE or group of CEs is more than 50 Mtops; i.e., C<sub>i</sub> for CEs 2 to 12 is 0.75.; and |
- (vi) in entry 5A001 sub-head b.10.b shall be deleted.

M. V. Coolican

An assistant Secretary

Department of Trade and Industry

1st March 1994

(This note is not part of the Order)

This Order amends the Export of Goods (Control) Order 1992:

- (i) by removing from control certain computer related equipment; and
- (ii) by clarifying the control on certain electronic components.

It also replaces the Technical Note to Category 4.

## Annotations

[^f00001]: Footnote: [1939 c. 69](https://www.legislation.gov.uk/ukpga/1939/69).

[^f00002]: Footnote: *See* S.I. [1970/1737](https://www.legislation.gov.uk/uksi/1970/1737).

[^f00003]: Footnote: S.I. [1992/3092](https://www.legislation.gov.uk/uksi/1992/3092), as amended by S.I. [1992/3305](https://www.legislation.gov.uk/uksi/1992/3305) and S.I. [1993/1020](https://www.legislation.gov.uk/uksi/1993/1020), [1692](https://www.legislation.gov.uk/uksi/1993/1692), [1825](https://www.legislation.gov.uk/uksi/1993/1825), [2515](https://www.legislation.gov.uk/uksi/1993/2515) and [3264](https://www.legislation.gov.uk/uksi/1993/3264).
