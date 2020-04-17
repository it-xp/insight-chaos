# insight-chaos
interpret random byte sequences as structured algorithms 

## R&amp;D: BiScript and Interpretative cryptography 
Mathematically simplest, from bi- to multi- glyph syntax based programming languages family for burn up cryptography performance and possibilities

### 1. Simpliest BiGlyph language:
any algorithm is collection of sequences of instructions, which read, generate, or transform data.
in simpliest way, we are have a two glyphs, for represent algorithms and data, most often this is 0 and 1.
how we are can write code, using that restriction?
any code is a sequence, s simpliest algorithm will be obe bit length and means do somethig one, from two posibilities.
For example, we are can get three bit sequences, algorithm and two data sets, and set a rule, if in first sequence 0, then we are get next bit from two other sequences summ it each other by module 2 (XOR), or if 1, get next two bytes from data sequences and summ it by module 4

alg | 0 | 0 | 0 | 0 | 1  | 1  | 1  | 1  | 1  | **1**  | 1  | **1**  | 1  | 1  | **1**  | 1  | 1  | **1**  | 1  | **1**
----|---|---|---|---|----|----|----|----|----|--------|----|--------|----|----|--------|----|----|--------|----|---
dt1 | 0 | 0 | 1 | 1 | 00 | 01 | 10 | 11 | 00 | **01** | 10 | **11** | 00 | 01 | **10** | 11 | 00 | **01** | 10 | **11**
dt2 | 0 | 1 | 0 | 1 | 00 | 00 | 00 | 00 | 01 | **01** | 01 | **01** | 10 | 10 | **10** | 10 | 11 | **11** | 11 | **11**
res | 0 | 1 | 1 | 0 | 00 | 01 | 10 | 11 | 01 | **10** | 11 | **00** | 10 | 11 | **00** | 01 | 11 | **00** | 01 | **10** 
