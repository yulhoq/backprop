## Lesson 1: Basics of neural network

In this full lession, we will learn how a simple neural network work in simple way.


## How do We Learn?

Just imagine how our brain work: It recognizes the pattern that we see through our eyes. It matches this pattern with our brain's pre-recognise things. That's how brain signal us that "yeah, it is the cat" because our barin know what a cat is look like. We simply compare what we see with the patterns our brain has previously recognized.

## What is Neural Network?

Neural network is a mathmatical model that inspired by human brain. In this case, it learn form data by adjusting "weights" over and over. This allows a neural network learn rules on its own. 

So, we see a biological brain Learn = by changing synapse strength.
on the other hand, an artificial neuron learn = by adjjusting weights + gradient desecnt.

## The Most Simple Neuron


The simplest neuron is a weighted sum of inputs.

Output formula:

y = w₁x₁ + w₂x₂ + ... + wₙxₙ

here, w's are wight and x are input values.

### With 3 steps Neural Network work:

1. It make prediction through **forward pass**. 
   (we will learn it leter)
2. Calculate error by **loss fuction**. The prediction is compared with the true value.
   (we will learn it leter)
3. **Backpropagation**(will learn in this lesson)
4. Then adjust the weights
This process continue over and over until the **convergence**.

**The main learning process is eventually leads to backpropagation**

Input → Forward Pass → Prediction → Loss → Backpropagation → Update Weights

## 3. Example

Imagine a neuron predicting exam success.

Inputs:

Study hours = 4  
Sleep hours = 7  

Weights:

Study weight = 0.8  
Sleep weight = 0.2  

Output:

y = (4 × 0.8) + (7 × 0.2)
## Practice Question

If:

x₁ = 3  
x₂ = 5  

w₁ = 0.6  
w₂ = 0.4  

Compute the neuron output:

y = w₁x₁ + w₂x₂
