# google-hash-code-more-pizza
My solution for HashCode 2019 practice pizza problem.

The model is described below.

## Let:

<img src="https://render.githubusercontent.com/render/math?math=X_i%20%5Cin%20(0%2C1)"> be the pizza decision array (whether we buy that pizza or not).

<img src="https://render.githubusercontent.com/render/math?math=S_i%20%5Cin%20\N"> be the pizza slices array (our input, with how many slices each pizza have).

<img src="https://render.githubusercontent.com/render/math?math=N"> be the number of different pizzas (length of arrays <img src="https://render.githubusercontent.com/render/math?math=X_i"> and <img src="https://render.githubusercontent.com/render/math?math=S_i"> ).

<img src="https://render.githubusercontent.com/render/math?math=SL"> be the maximum number of slices we are allowed to buy.

## Objective Function:

Max Z = <img src="https://render.githubusercontent.com/render/math?math=%5Csum_%7Bi%3D1%7D%5E%7BN%7DX_i%20S_i">, which is the total sum of slices.

## Restrictions:

We cannot buy more than the maximum number of pizza slices:

![\sum_{i=1}^{N}X_i S_i < SL](https://render.githubusercontent.com/render/math?math=%5Csum_%7Bi%3D1%7D%5E%7BN%7DX_i%20S_i%20%3C%20SL)
