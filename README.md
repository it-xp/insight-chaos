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

alg | 1  | 1  | 0 | 1  | 0 | 0 | 1  | 0 | 0 | 1  | 0 | 1  | 0 | 1  | 1  | 0 | 1  | 0 | 1  | 0 | 0 | 1  | 1  | 0 | 0 | 1 
dt1 | 01 | 11 | 0 | 10 | 1 | 1 | 10 | 0 | 0 | 10 | 1 | 00 | 1 | 00 | 10 | 1 | 01 | 0 | 10 | 0 | 1 | 10 | 10 | 0 | 0 | 01
dt2 | 01 | 00 | 0 | 00 | 1 | 0 | 01 | 0 | 1 | 00 | 1 | 01 | 0 | 11 | 10 | 0 | 01 | 0 | 10 | 0 | 1 | 01 | 00 | 1 | 0 | 01
res | 10 | 11 | 0 | 10 | 0 | 1 | 11 | 0 | 1 | 10 | 0 | 01 | 1 | 11 | 00 | 1 | 10 | 0 | 00 | 0 | 0 | 11 | 10 | 1 | 0 | 10
