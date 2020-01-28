# snowy
sedar36update
The purpose of this repository is to track changes to ADMB code in developing a base run for the 2020 snowy grouper update assessment.  The work initializes with the red grouper model, which contains the latest model configuration and options, and is adapted to the SEDAR 36 snowy grouper base model.  The work to date includes:
- removed headboat fleet entirely
- add index to general recretional fleet (GR), RG headboat used as placeholder
- remove commercial handline discards
- remove GR discards
- added MARMAP vertical longline index and age comps with logistic selectivity
- changed commercial other (cO) to commercial longline (cL)


TO DO LIST:
- Remove size limits
- Remove selectivity blocks for cH and cO
- Modify selectivities to match SEDAR 36
  - CVT logistic exponential
  - vll logistic (done)
  - cH logistic
  - cL logistic
  - GR 3 blocks with logistic-exponential
  
  
