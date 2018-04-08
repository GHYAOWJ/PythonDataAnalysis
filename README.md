# PythonDataAnalysis

## jupyter
http://jupyter.org/install
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
https://matplotlib.org/
```
import numpy as np
import matplotlib.pyplot as plt
a = [1, 2, 3]
b = [4, 5, 6]
plt.plot(a, b)
plt.plot(a, b, '*')
```
![result](pic/plot.PNG)
```
import numpy as np
import matplotlib.pyplot as plt
x=np.arange(0,6,0.1)
y=np.sin(x)
plt.plot(x,y)
z=np.cos(x)
plt.plot(x,z)
```
![result](pic/plot2.PNG)

### pandas
```
from pandas import Series
a = [1, 2, 3, 4]
s = Series(a)
s.index
s.values
s1 = Series(a, index=['A','B','C','D'])
import numpy as np
s2 = Series(np.arange(5))
d = {'A':1,'B':2,'C':3,'D':4}
s3 = Series(d)
s3.to_dict()
s3.pop('A')
b = s3.pop('B')
s4 = Series(s3, index=['B','C','D'])
s4.isnull()
s4.notnull()
```
