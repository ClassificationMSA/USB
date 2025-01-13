# Hybrid Model

The hybrid model is a normalized linear combination of the Behavioral model and the Semantic model.

These weights are optimized for each web application to maximize the accuracy of microservice identification.

The comparison for maximum accuracy is based on the median 
accuracy obtained by conducting 30 microservice identification experiments for all possible weight combinations.

## Alpha Weights (Values applied to the Behavioral model)

| Web Application | Alpha Weight |
|------------------|--------------|
| JP2             | 0.5          |
| JP6             | 0.4          |
| PetClinic       | 0.35         |
| ShoppingApp     | 0.5          |
| DayTrader       | 0.2          |
