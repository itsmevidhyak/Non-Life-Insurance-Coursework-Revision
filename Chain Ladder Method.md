# Chain Ladder Method

- Statistical method of estimating outstanding claims
- Weighted average of past claim development is projected into the future
- Projection is based on the ratios of cumulative past paid/incurred claims, for successive years of development.

## Key assumptions:
  * The earliest year of origin is fully run-off or atleast that the final outcome for that year can be estimated with confidence. In second case, a tail factor will be required.
  * The assumed pattern of development derived from past experience will remain appropriate in the future.
  * Where triangle is unadjusted for inflation present within the data, the method builds an implicit assumption that a weighted average of past inflation will be repeated in the future.
- Widely used for estimating ultimate losses.
- Historical data is used to project future claims.
- variants: paid BCL, incurred BCL, inflation adjusted BCL

## How to apply
- Create claims triangles by development period and origin period.
- Calculate development ratios and apply the latest diagonal to complete the triangle.
- Apply tail factor if needed.
- Subtract the current incurred claims from ultimate to get the reserves.
- Inflation adjusted triangle can be used if an explicit inflation assumption is needed.
- Don't apply mechanically, rather exercise judgment to ensure results are reasonable.

## Advantages
- can be applied to variety of datasets
- simple to use, provides useful insights into the data, a generally accepted standard actuarial method
- provided data can be arranged into a development triangle, it can be used to project historical claims to ultimate
- basic method is modifiable to allow for data distortions
- straightforward, easy to relate results back to pattern of development
- can serve as a starting point for a number of other methods, eg BF method

## Disadvantages
- Results are distorted by unusual claims experience. eg very good/very bad past experience => violates the assumption past is a better representative of future
- Adjustments are needed because we can't project the unusual experience just as normal experience. It would result in under/over estimation of ultimates
- Limited use of recent cohorts, particularly for long-tailed cohors.
    * Liability classes - there may be no fully developed cohorts available
    * In such cases, estimate tail factor and apply it to most developed cohort
    * We may base this tail factor on the result of fitting a curve to the actual claims development, other info such as benchmarks, or use a different method to estimate the ultimate claims.
    * Alternatives - BF method - incorporates an expectation of ultimate loss, ACPC method - claim number development may run-off quicker than claim amount development
- Projection of experience to date that may be light or heavy.
    * Cases where no claims are present or a series of large claims are present
    * Adjustments needed or consider other method
- More care needed to prevent unusual features in the data having a significant impact on the results
    * Cases eg. One-off large loss development distorts the development patterns or calendar-year effect due to changes in claims handling procedures
