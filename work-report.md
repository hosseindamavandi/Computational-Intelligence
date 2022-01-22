## Hosein Damavandi

### Assignment 1 :

---

#### Questions:

![image](https://user-images.githubusercontent.com/83751182/133993994-2c2ec93c-678d-482e-8883-b6aff540ce2b.png)


| **number**   | **Neuron Weights**    |**soma**|
|:-------------|:----------------------|:-------|
| run 1        |[ 2 , -3 , 1 , 0 ]     | 1.5    |
| run 2        |[ -2 , -2 , -2 , -2 ]  | -2.5   |
| run 3        |[ 2 , -1 , 1.5 , -5 ]  | 1      |
| run 4        |[ 1 , 1 , 1 , 1 ]      | -1.5   |
| run 5        |[ 0.5 , -0.5 , 0 , -1 ]| 0      |
 
 

#### Answers:

python:
```py
# get Neuron
a1 = int(input())
a2 = int(input())
a3 = int(input())
a4 = int(input())

# get weight for each Neuron 
w1 = float(input())
w2 = float(input())
w3 = float(input())
w4 = float(input())

# get soma
soma = float(input())

# Calculate the sum of neuron input and its weight
sum = (a1 * w1) + (a2 * w2) + (a3 * w3) + (a4 * w4)

# Output condition
if sum > soma :
    print(1)

else:
    print(0)

```

|      -               |1|2|3|4|5|6|7|8|9|10|11|12|13|14|15|16|
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|       -              |0|0|0|0|0|0|0|0|1|1 |1 |1 |1 |1 |1 |1 |
|        -             |0|0|0|0|1|1|1|1|0|0 |0 |0 |1 |1 |1 |1 |
|         -            |0|0|1|1|0|0|1|1|0|0 |1 |1 |0 |0 |1 |1 |
|          -           |0|1|0|1|0|1|0|1|0|1 |0 |1 |0 |1 |0 |1 |
| run 1                |0|0|0|0|0|0|0|0|1|1 |1 |1 |0 |0 |0 |0 |
| run 2                |1|1|1|0|1|0|0|0|1|0 |0 |0 |0 |0 |0 |0 |
| run 3                |0|0|1|0|0|0|0|0|1|0 |1 |0 |0 |0 |1 |0 |
| run 4                |1|1|1|1|1|1|1|1|1|1 |1 |1 |1 |1 |1 |1 |
| run 5                |0|0|0|0|0|0|0|0|1|0 |1 |0 |0 |0 |0 |0 |

![image](https://user-images.githubusercontent.com/83751182/134060360-e49c5e20-c27e-4ea0-a41f-89cac861a1a3.png)
