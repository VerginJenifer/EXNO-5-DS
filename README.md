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
#Name: D Vergin Jenifer
#Register No.: 212223240174
import pandas as pd
import matplotlib.pyplot as plt
x=[0,1,2,3,4,5]
y=[0,1,4,9,16,25]
plt.plot(x,y)
import matplotlib.pyplot as plt
x=[1,2,3,4,5]
y=[5,6,7,8,9]
plt.plot(x,y)
plt.xlabel('x aixs')
plt.ylabel('y axis')
plt.title('simple line')
plt.show()
x1=[1,2,3,4]
y1=[4,3,2,1]
plt.plot(x1,y1,label="line 1")

x2=[5,6,7,8]
y2=[8,7,6,5]
plt.plot(x2,y2,label="line 2")

plt.xlabel('x axis')
plt.ylabel('y axis')
plt.title("simple 2 line graph")
plt.legend()
plt.show()
x=[1,2,3,4,5,6]
y=[6,7,3,4,5,2]
plt.plot(x,y,color="green",linestyle="dashed",linewidth = 3,marker='o',markerfacecolor="blue",markersize=12)
plt.ylim(1,10)
plt.xlim(1,10)
plt.xlabel("x axis")
plt.ylabel("y axis")
plt.title("customization")
plt.show()
import matplotlib.pyplot as plt
x_v=[0,1,2,3,4]
y_v=[2,3,4,5,6]
plt.scatter(x_v,y_v,s=30,color="green")
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title("scatter plot")
plt.show()
plt.savefig('Test.png')
plt.plot(x_v,y_v,"g*",linestyle="dashed",linewidth=3,markersize=10)
plt.title("2d diagram")
import numpy as np
np.pi
x=np.arange(0,4 * np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="green")
plt.plot(x,y1,color="red")
plt.plot(x,y2,color="red")
plt.legend(["y1","y2"])
plt.show()
x=[5,6,7,8]
y=["a","b","c","d"]
plt.bar(x,y,color="green")
plt.show()
x=[5,6,7,8]
y=["a","b","c","d"]
plt.barh(x,y,color="green")
plt.show()
x=[1,2,3,4,5]
y=[5,4,3,6,1]
c1=["red","green"]
c2=["blue","green"]
plt.bar(x,y,width=0.6,color=c2)
plt.xlabel("x axis")
plt.ylabel("y axis")
plt.title("bar chart")
plt.show()
x=[1,2,3]
y=[5,6,7]
x2=[4,11,10]
y2=[8,9,12]
plt.bar(x,y,color="r")
plt.bar(x2,y2,color="b")
plt.xlabel("x axis")
plt.ylabel("y axis")
plt.show()
a=[2,5,6,10,15,17,30,40,50,66,70,77,88,89]
range=(0,100)
bins=10
plt.hist(a,bins,range,color="g",histtype="bar",rwidth=0.8)
plt.xlabel('age')
plt.ylabel('no of people')
plt.title("my histogram")
plt.show()
import matplotlib.pyplot as plt
x=[2,1,6,4,2,4,8,9,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins =10,color="blue",alpha=0.5)
plt.show()
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
a,b=plt.subplots()
b.boxplot(data)
b.set_title("box plot")
b.set_xlabel("data")
b.set_ylabel("values")
l=["python","C++","C","java"]
sizes=[215,130,244,222]
colors=["r","orange","yellow","b"]
explode=(0,0,0,0)
plt.pie(sizes,explode=explode,labels=l,colors=colors,
autopct="%1.1f%%",shadow=True)
plt.axis('equal')
plt.show()
```
# Outpt :
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/3817f6ff-4b08-4da3-9cdb-24a4629052ba)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/481fb78d-0d71-4b7c-991a-3fc8ab240b75)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/a9b8e109-fc81-4e8a-ae73-93a02e509fd6)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/cd13b337-be36-4b4b-a2e2-8ef9c792ccf8)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/c72ca971-b43f-4b2d-aa1a-38d0097e9739)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/034266f0-2e9b-4f4e-b7e9-c988dd720b44)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/ba8a243b-4104-491e-8c05-81406209baef)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/3f9427c2-d707-4d31-b2fc-2286e7db5533)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/7800e7cd-e4f6-40a1-87f2-915920a4ea9a)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/77455c5a-47b9-4431-8825-ff59cae91d0c)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/3f2fc759-dbd3-4f2b-ae51-edcf22d7e3c6)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/29ffbc1e-eb22-49df-bf3d-2ea0f1210bc8)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/46cf5ab2-e492-46d7-a418-63800af1f709)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/6aced644-d1d6-43d1-837a-cfaed667821d)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/ad954a0e-bd29-4d93-b5cf-6578dbce723b)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/03c0f487-0a8a-455b-b9df-f0ce02350891)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/d70f3180-082b-4fed-8419-7ea1e70ba75c)
![image](https://github.com/VerginJenifer/EXNO-5-DS/assets/136251012/f5ea5222-aa4a-43ee-9fbb-0268f8d585b6)


# Result:
 The program to perform data visualization using the matplotlib Python library for the given data was successfully executed.
