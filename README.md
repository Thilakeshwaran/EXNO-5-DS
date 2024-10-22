# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 ```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line 1')
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line 2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two line on same graph')
plt.legend()

```
![image](https://github.com/user-attachments/assets/9bc27375-e17a-43d9-b1f5-511090081963)

```
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('some cool customization')

```

![image](https://github.com/user-attachments/assets/f42b5695-b391-4eb5-886b-166f61001e74)

```
years = range(2000, 2012)
apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.9375, 0.9372, 0.939]
oranges = [0.962, 0.941, 0.930, 0.923, 0.918, 0.908, 0.903, 0.907, 0.904, 0.901, 0.896, 0.896]

plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')

plt.title("Crop Yields in Kanto")
plt.legend(['Apples', 'Oranges'])
```
![image](https://github.com/user-attachments/assets/9039d921-31a7-4914-b6fd-4f78a65e69ce)

```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
![image](https://github.com/user-attachments/assets/f2bbd516-503d-4275-9c77-d3546b30c6b6)

```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6,7,8,9,10]
y=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x,y,label="stars",color="green",marker="*",s=30)
plt.xlabel("x-axis")
plt.ylabel("y-axis")
plt.title("Scatter Plot")
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/6db19702-e540-4296-8e40-c6c0e9339c61)

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x

```

![image](https://github.com/user-attachments/assets/2e536482-90f8-4a03-909a-0c07a3483c74)

```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel("x-axis")
plt.ylabel("y-axis")
plt.title("2d Diagram")
plt.show()
```
![image](https://github.com/user-attachments/assets/9af2e7d0-12c8-47b6-bf08-896d76bd8fd1)

```
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')

```
![image](https://github.com/user-attachments/assets/7d1d7658-341e-410a-942b-330e4b85f9a4)

```
import numpy as np
import matplotlib.pyplot as plt
x = np.arange(0, 4 * np.pi, 0.1)
y = np.sin(x)
plt.title("Sine Wave Form")
plt.plot(x, y)
plt.show()
```
![image](https://github.com/user-attachments/assets/ea617c4f-827c-4002-8ad5-9d2cdd4fc1c6)

```
import matplotlib.pyplot as plt
import numpy as np
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1', 'y2'])
plt.show()
```
![image](https://github.com/user-attachments/assets/eb7aeee0-036b-4da1-884b-f1bc89f38d7f)

```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/fbde3235-68db-46fe-80c5-24cf7409ad24)

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('Bar graph')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/4da6c20a-90ca-4963-af42-997ff439422a)

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='g',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No.of people')
plt.title('Histogram')
plt.show()
```
![image](https://github.com/user-attachments/assets/27b23dcc-1b7d-4b46-a050-f14fc9cdb9a5)

```
import matplotlib.pyplot as plt
x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,5,7,3,5,9,2,1]
plt.hist(x,bins=10,color='b',alpha=0.5)
plt.show()
```
![image](https://github.com/user-attachments/assets/91b110ea-5632-4c81-8da7-38f7ee71a314)

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/user-attachments/assets/aceef39e-d906-4452-b41e-fd52191a19f3)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Boxplot')
plt.show()
```
![image](https://github.com/user-attachments/assets/a6d08eaa-ae38-4ad4-ae88-cb7fa6247c68)

```
import matplotlib.pyplot as plt
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','b','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),autopct='%1.1f%%')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/0a3f26b1-21a9-42c4-8ba8-3c01cb4b5a99)

```
labels='python','c++','c','java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/user-attachments/assets/bdd4490b-2a75-4622-8d0c-9b5193a6448d)

# Result:
 Thus the program to Perform Data Visualization using matplot python library for the given datas is been implemented.
