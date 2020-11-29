| Kevin                          | David                                                        | General                                                      |
| ------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| - Dependency Parsing approach. | - Conclusion in Lexical Semantics. Delete `just_words` approach. | - Extract conclusions for each approach taking into account various pairs of sentences and comparing the different implemented approaches between them. |
| - Sum of weights approach.     | - Conclusion in WSD                                          | - Write more about the performed steps.                      |
|                                | - Conclusions in PoS Taggers.                                |                                                              |
|                                | - WS + Lemmas approach.                                      |                                                              |
|                                | - WS + Synsets approach.                                     |                                                              |

Top scores:

1. **LT: 0.587** <-
2. **WT: 0.561** <-
3. **S: 0.548** <-
4. WS: 0.528 <-
5. LESK: 0.480 <-

**Combination:**

**`w1*Sim(word_tok) + w2*Sim(lemma_tok) + w3*Sim(S) + w4*Sim(WS) + w5*sim(Lesk) +  w6*(Dp)` with `sum(wX = 1)`**

