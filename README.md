# McCulloch-Pitts-artificial-neuron
Implementing McCulloch-Pitts artificial neuron and implementing various Boolean functions

(A) Implement McCulloch-Pitts artificial neuron.

McCulloch Pitt’s model of neurons is a fairly simple model that consists of some (n) binary inputs with some weight associated with each one of them. An input is known as ‘inhibitory input’ if the weight associated with the input is of negative magnitude and is known as ‘excitatory input’ if the weight associated with the input is of positive magnitude. As the inputs are binary, they can take either 2 values, 0 or 1. 
Then we have a summation junction aggregating all the weighted inputs and then passing the result to the activation function. The activation function is a threshold function that gives out 1 as the output if the sum of the weighted inputs is equal to or above the threshold value and 0 otherwise. 
So let’s say we have n inputs = { X1, X2, X3, …. , Xn }
And we have n weights for each= {W1, W2, W3, …., W4}
So the summation of weighted inputs X.W = X1.W1 + X2.W2 + X3.W3 +....+ Xn.Wn
If X ≥ ø(threshold value)
     Output = 1
Else
       Output = 0

(B) Implement various Boolean functions
  (i)Implementation of AND gate using M-P Neuron.
      Implementation of AND gate using M-P Neuron for weights, w1=1, w2=1.
      ysum(g(x))= x1.w1 + x2.w2
      θ=2
      g(x) ≥ θ → 1
      g(x)＜θ → 0
      The threshold value should be a minimum 2 for this case
      Hence, the neuron will be shot only if x1=x2=1 for AND gate using M-P Neoron for weights w1=w2=1

  (ii) Implementation of OR gate using M-P Neuron
        Implementation of OR gate using M-P Neuron for weights, w1=1, w2=1.
        ysum(g(x))= x1.w1 + x2.w2
        θ=1
        g(x) ≥ θ → 1
        g(x)＜θ → 0
        The threshold value should be a minimum 1 for this case
        Hence, the neuron will be shot only if x1=x2=1 for AND gate using M-P Neoron for weights w1=w2=1

  (iii) Implementation of NOR gate using M-P Neuron
        ysum(g(x))= x1.w1 + x2.w2
        θ=-1
        g(x) ≥ θ → 1
        g(x)＜θ → 0
        The threshold value should be a minimum -1 for this case

