# Test Description:


In this repository I applied a simple PINN (Physics Informed Neural Network) for the problem of Damped Harmoic Oscillator with a Damping ratio varying in the range (0.1, 0.4).
I've used Pytorch for the implementation. 

## Notebook-1: Training a PINN with ODE Residual and Initial Condition
In this notebook a PINN is trained on loss function: Total Loss = IC_loss + PDE (ODE) Residual.
