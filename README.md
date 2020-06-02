# Classifying deep features in an urban layout

It is offered a type of street network to capture the character of urban layout and category different places around the world. Deep learning algorithm is been study performances of hyper-parameters modify.

## [Database](https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/tree/master/Drive_4km)
Access OpenStreetMap to generate dataset

### [10 different cities are selected to make the layout classification](https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/tree/master/City%20Boundary)
**London, Beijing, Paris, Moscow, Los Angeles, Bangkok, New York, Sydney, Mumbai and Amsterdam**

*City Edge Example: Log Angeles and related Coordinate points*
<p align="center">
<img src="https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/blob/master/City%20Boundary/Los%20Angeles.png" style=centerme height="400"></p>

*Dataset Example*


*The following map images are Los Angeles, London and Paris*

<img src='https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/blob/master/Drive_4km/Los%20Angeles%2C33.95%20-118.38%2C4.png' height="260">  <img src= 'https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/blob/master/Drive_4km/Greater%20London%2C51.47%20-0.11%2C4.png' height="260">  <img src= 'https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/blob/master/Drive_4km/Paris%2C48.84%202.28%2C4.png' height="260">

## Results
### [Training Process](https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/tree/master/Results)

| Scales     | Street Network types | Epoch |     Output Accuracy     |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |



| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |

*Street Network types = 'Drive', Activation function = 'ReLu', Scale = '4km', Epochs = '400'*

*Final Accuracy = 87.2%*
<img src='https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/blob/master/Results/Sigmoid_acc.png'>


### [Confusion Matrix](https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/tree/master/Confusion%20Matrix)
![Sigmoid Classification results](https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/blob/master/Confusion%20Matrix/matrix_ReLu.png)

