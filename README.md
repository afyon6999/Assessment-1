import random
import math

def tanh(x):
    return math.tanh(x)

interval [-0.5, 0.5]
w1 = random.uniform(-0.5, 0.5)
w2 = random.uniform(-0.5, 0.5)
w3 = random.uniform(-0.5, 0.5)
w4 = random.uniform(-0.5, 0.5)

b1 = 0.5
b2 = 0.7

x1 = 1 
x2 = 1 

z1 = w1 * x1 + w2 * x2 + b1
a1 = tanh(z1)

z2 = w3 * x1 + w4 * x2 + b2
a2 = tanh(z2)

print("Output from the first neuron (a1):", a1)
print("Output from the second neuron (a2):", a2)
