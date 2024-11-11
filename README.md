Michael Roman - 2024 # type: ignore

# type: ignore importamos los codigos necesarios 


import math
import numpy as np
from  matplotlib import pyplot as plt


x=np.array(range(400)) * 0.1
y= np.zeros(len(x))
for i in range(len(x)):
  y(i) = math.sin(x(i))
 # type: ignore Creamos un grafico
plt.plot(x,y)
plt.show
