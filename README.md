# PythonDataAnalysis

## jupyter
```
start 
jupyter notebook

cmd cd Anaconda3\Scripts>
conda -V
conda list
ipython
```
![result](pic/conda-v.png)
![result](pic/conda%20list.png)

### array
```
array.shape
array.size
array.dtype
numpy.arange(初始值,最大值,選項-間隔值)
numpy.zeros([列,行])
numpy.eye(單位矩陣)
```
![result](pic/python_array.PNG)
![result](pic/python_array2.PNG)
![result](pic/python_array3.PNG)

### matrix
```
## mat矩陣
a=numpy.mat(np.random.randint(亂數最大值,size=陣列長度).reshape(列,行))
b=numpy.mat(np.random.randint(亂數最大值,size=陣列長度).reshape(列,行))
a*b
```
![result](pic/matrix.PNG)

### matplotlib
```
import numpy as np
import matplotlib.pyplot as plt
a = [1, 2, 3]
b = [4, 5, 6]
plt.plot(a, b)
plt.plot(a, b, '*')
```
![result](pic/plot.PNG)
