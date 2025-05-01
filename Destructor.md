# Exp.No:5B 
## Destructor

---

### AIM  
To create a Python class vehicle with a destructor.
---

### ALGORITHM

1.Begin the program.

2.Define the vehicle class..

3.Inside the vehicle class, define the __init__ method (constructor) and the __del__ method (destructor).

4.Create an object s2 of the vehicle class. When the object s2 is created, the __init__ method is called, and its print statements are executed.

5.Use the del statement to delete the object s2. This triggers the __del__ method (destructor), and the respective print statements are executed.

6.Terminate the program.
---

### PROGRAM

```
class Vehicles:
def init(self):
print('Vehicle created.')
def del(self):
print("Destructor called, vehicle deleted.")
obj = Fruits()
del obj
```

### OUTPUT
![image](https://github.com/user-attachments/assets/7957394d-0841-4862-af70-d53c63e74074)


### RESULT
Thus, the given python progran is implemented and executed sucessfully.
