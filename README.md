# Diffusion model

## Table of Contents
- [Sampling](#Sampling)
- [Neural Network](#Neural-Network)
- [Training](#Training)
- [Controling](#Controling)
- [Speeding up](#Speeding-up)
- [reference](#reference)


## Sampeling
`What is Sampeling?`

We put the noise sample through our trained neural network that has understood what a sprite kind of looks like and what it does is it predicts noise. It predicts noise as opposed to the sprite and then we subtract that predicted noise from the noise sample to get something a little bit more sprite-like. 
  
![](docs/images/Sampling_first_part.png)  
  
Now realistically that is just a prediction of noise and it doesn't fully remove all the noise so you need multiple steps to get high quality samples. That's after 500 iterations we're able to get something that looks very sprite-like. So now let's step through this algorithmically.

![](docs/images/Sampling_second_part.png)  
## Neural Network

## Training

## Controling

## Speeding up

## Refrense
