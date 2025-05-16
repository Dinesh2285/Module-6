# Exp.No:30  
## COUNTER CLASS

---

### AIM  
To write a Python program to create a `Counter` class that can increment the value of a counter.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Counter` class.**
   - Initialize the `current` variable with 0.
3. **Define the `increment()` method** to increment the value of `current` by 1.
4. **Define the `value()` method** to return the current value of `current`.
5. **Define the `reset()` method** to reset the `current` value back to 0.
6. **Create a `counter` object** of the `Counter` class.
7. **Call the `increment()` method** three times to increment the counter.
8. **Call the `value()` method** and print the result to show the current counter value.
9. **End the program.**

---

### PROGRAM

```
#Reg.NO-212223060059
#Name-Dineshkumar K

class Counter:
    def __init__(self):
        self.current = 0

    def increment(self):
        self.current += 1

    def value(self):
        return self.current

    def reset(self):
        self.current = 0

counter = Counter()
counter.increment()
counter.increment()
counter.increment()
print("Current counter value:", counter.value())


```

### OUTPUT
![image](https://github.com/user-attachments/assets/cd15ec44-a49a-4acf-8afd-15d2784968a9)


### RESULT
Thus, the python program to create a Counter class that can increment the value of a counter has been executed and verified successfully.
