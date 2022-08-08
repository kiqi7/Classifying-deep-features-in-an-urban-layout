# Classifying deep features in an urban layout

It is offered a type of street network to capture the character of urban layout and category different places around the world. Deep learning algorithm is been study performances of hyper-parameters modify.
\begin{document}

dissertation submit link \url{file:///Users/kiki/Downloads/Classifying-deep-features-in-an-urban-layout.html}
\end{document}

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

## Hyper-parameters Settings
1. Count of Sampling in each cities
2. Scales of map size: 0.25km, 1km, 4km.
3. Street Network types: Drive, Walk, All.


## Results
### [Training Process](https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/tree/master/Results)

| Scales     | Street Network types | Epoch | Output Accuracy |
| ---      | ---       | ---       | ---       |
| 0.25 km | Drive  | 1900 | 87.7% |
| 0.25 km | All  | 1400 | 83% |
| 1 km | Drive  | 2800 | 93.2% |
| 4 km | Drive  | 400 | 87.2% |

*Street Network types = 'Drive', Activation function = 'ReLu', Scale = '4km', Epochs = '400'*

*Final Accuracy = 87.2%*
<img src='https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/blob/master/Results/Sigmoid_acc.png'>


### [Confusion Matrix](https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/tree/master/Confusion%20Matrix)
![Sigmoid Classification results](https://github.com/kiqi7/Classifying-deep-features-in-an-urban-layout/blob/master/Confusion%20Matrix/matrix_ReLu.png)

