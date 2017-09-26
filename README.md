# Proyectomodulo1-
Este es el proyecto para trabajar la ecuación diferencial de temperatura
import numpy as np
import matplotlib.pyplot as plt
from scipy.integrate import odeint
%matplotlib inline
def newton(T,t):    #T1es la temperatura del objeto, T2es la del ambiente
    T2=25
    k=.02
    return -k*(T-T2)