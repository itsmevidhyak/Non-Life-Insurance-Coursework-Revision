Q1 2 policy basis commonly used for non-proportional reinsurance

- LOD basis aka Claims occurring during basis
  * LOD basis provides direct writer with the cover for claim incidents under the treaty for claims occuring during the defined period
  * Corresponds to the AY basis

- Claims made basis
  * Claims made basis provides direct writer with the cover for claims incidents under the treaty for claims reported during the defined period
  * Corresponds to the Reporting year basis

Q2 What's the risk with switching from claims made basis to claims occurring basis?

- The risk is that there may be periods relating to the policies already written in which the insurer is exposed to risk , but for which there is no insurance cover.
  - eg Suppose as an employer, we switch on 1/1/19 from a claims made policy to a claims occuring policy
  - say on 2/1/19, we discover that the foreman has suffered an injury last year, which appeared to have healed. He has a major relapse now and instituted proceedings for compensation.
  - We can't claim this under our current policy => event occurred last year not now
  - We can't claim in under our previous policy either => claim was not reported last year
 
Q3 Which basis is risky to the reinsurer while writing new business?

- Claims made basis is risky
- Reinsurer may have inherited risks eg latent claims, which has been already incurred, but only came to light once the cover is in place.
- This is exacerbated by the non disclosure by the direct writer.

Q4 What are the key sensitivities around Chain ladder method?

- There are two parts to the chain ladder method: 1. Observed claims in the most recent development period 2. Development pattern
- $C_{i,J} = C_{i,j} . F_j$ and $IBNR =  C_{i,j} . F_j -  C_{i,j}$
- Variability - Claims in the recent development period is highly variable. So, the estimates of ultimate claims are also highly variable.
- Undesirable - because the estimates are highly likely to change as the new information is received.
- Statistical credibility - For long tailed classes of business, observed claims may be extremely small and development may be extremely large.
- We need to stabilise observed claims to ensure the projections of the ultimate claims are less variable and more reliable.

Q5 How exposure based methods solve the above problem?

- Commonly used approach is Bornhuetter-Ferguson method.
- Ultimates =
  * Observed claims in the recent development period +
  * Initial Expected Loss Ratio (IELR) *
  * Remaining Exposure
  * $C_{i,J} = C_{i,j}  + (1- 1/F_j) . EP_i . IELR_i$ and $IBNR =   (1- 1/F_j) . EP_i . IELR_i$
  * We are no longer projecting using earned claims.
  * But rather projecting our expectation of the remaining development multiplied by an estimate of the expected losses.
  * IELRs are obtained using an ad hoc method usually from the data or use pricing info if available.
  * For lines of business such as, Commercial lines, Net of reinsurance or reinsurance inwards, loss ratios will be available from pricing.
  * Other ways - could use target loss ratios
  * Ad hoc derivation - eg use an average of chain ladder in previous 4 quarters
  * issue is - hard to justify to regulators, auditors and other reviewers






