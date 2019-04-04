# neural-network
neural network
import numpy as np
import matplotlib.pyplot as plt #TO CREATE GRAPH
def sigmoid(x): #вычисляет сигм
    return  1/(1+np.exp(-x))# использует экс из модуля num.py
def der_sigmoid(x): #вычисляет сигм#2
    return  sigmoid(x)*(1-sigmoid(x))
    class neuron:#find out neuron class
    def __init__(self,n):                       
        self.w=2*np.random.sample(n)-1
    def calculate(self,inputs):                      
        self.out=sigmoid(np.sum(self.w*inputs))
        neuron1=neuron(2)
neuron1.w=np.array([1,2])
neuron1.calculate(np.array([1,2]))
print(neuron1.out)
print (sigmoid(5))
x=neuron1.w=np.array([1,2])
neuron2.calculate(x,)
print(neuron2.out)
