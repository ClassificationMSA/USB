# Method of Selecting Results for Each Model-Based Approach

### Behavioral model results

For each behavioral model, 31 microservice identifications are performed, and the median of the accuracies is used.

### Semantic model results

For each semantic model, 31 microservice identifications are performed, and the median of the accuracies is used.

### Integrated model results

A linear combination of semantic and dynamic models is used.

+ ### The method of how alpha (��) values are extracted in the integrated model.

1) Adjusting the alpha (��) values between 0 and 1, 31 results are generated for each alpha.
2) The accuracy of a specific alpha (��) value is the median of the results obtained from 31 iterations.
3) The alpha value with the highest accuracy among them was selected for use.


