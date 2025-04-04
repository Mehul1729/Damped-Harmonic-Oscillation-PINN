# Test Description:


In this repository I applied a simple PINN (Physics Informed Neural Network) for the problem of Damped Harmoic Oscillator with a Damping ratio varying in the range (0.1, 0.4).
I've used Pytorch for the implementation. 

## Notebook-1: Main Notebook - Training a PINN with ODE Residual and Initial Condition
In this notebook a PINN is trained on loss function: Total Loss = IC_loss + PDE (ODE) Residual. 

![image alt](https://github.com/Mehul1729/Damped-Harmonic-Oscillation-PINN/blob/81c67774b50e0e83515613d487511f5b711155e5/icpde.png)

## Notebook-2: Training a PINN with some initial data points : Data + Physics
Inthis notebook a PINN is trained on loss function: Total Loss = Data_loss + ODE Residual.

![image alt](https://github.com/Mehul1729/Damped-Harmonic-Oscillation-PINN/blob/a39bf70cfa692aa491ae5f7fe793f4cf3280ddef/newla.png)
