# R1CS_normalization_banchmark
This is a benchmark for normalization of R1CS

We summarized some rules for generating equivalent R1CS constraint groups based on the logic used by the mainstream Circom compiler to generate R1CS, and designed a more comprehensive benchmark based on these rules. The benchmark includes the following main categories depending on the reflected situation:


- Replacement of variable order in R1CS.
- Transformation of constraint order in R1CS.
- Introduction of multiple new variables in a single linear constraint in R1CS.
- Introduction of multiple new variables in multiple linear constraints in R1CS, with shared new variables.
- Merging and splitting of constraints in R1CS.
