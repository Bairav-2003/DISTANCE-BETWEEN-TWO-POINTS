# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: start
### Step 2: import numpy as np
### Step 3: get a input for l1,l2 
Substitute the values in the distance formula  ![formula](/formula.jpg)
### Step 4: print the value for  distance in 2 decimal points
### Step 5: stop
### PROGRAM:
~~~ python
import numpy as np
l1=[4,2]
l2=[10,6]
dist=np.sqrt(((l2[0]-l1[0])*2)+((l2[1]-l1[1])*2))
print("{:.2f}".format(dist))
~~~
  


### OUTPUT:
![output](./distance2.png)


### RESULT:
Thus the above program run successfully
