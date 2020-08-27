## Expected Learned Clauses For Parity Dataset

| __a__ | __b__ | __x__ | __x = a XOR b__ |
|:---:|:---:|:---:|:---:|
| 0 | 0 | 0 | 1 | 
| 0 | 0 | 1 | 0 |
| 0 | 1 | 0 | 0 | 
| 0 | 1 | 1 | 1 | 
| 1 | 0 | 0 | 0 | 
| 1 | 0 | 1 | 1 | 
| 1 | 1 | 0 | 1 | 
| 1 | 1 | 1 | 0 | 


## CNF
(a ∨ b ∨ ¬x) ∧ (a ∨ ¬b ∨ x) ∧ (¬a ∨ b ∨ x) ∧ (¬a ∨ ¬b ∨ ¬x)