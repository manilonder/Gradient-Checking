# Gradient-Checking
Backpropagation computes the gradients  ∂𝐽/∂𝜃 , where  𝜃  denotes the parameters of the model.  𝐽  is computed using forward propagation and your loss function.
Because forward propagation is relatively easy to implement, you're confident you got that right, and so you're almost 100% sure that you're computing the cost  𝐽  correctly. Thus, you can use your code for computing  𝐽  to verify the code for computing  ∂𝐽/∂𝜃 .
