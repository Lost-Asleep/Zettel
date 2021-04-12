# A simple example of class inheritance in Python 3

## Code

```python
class Animal:
    def __init__(self):
        self.num_eyes = 2

    def breathe(self):
        print("Inhale, exhale.")

class Fish(Animal):
    def __init__(self):
        super().__init__()  # Inherit the __init__ from the parent/super class.

    def breathe(self):
        super().breathe()  # Inherit this function from the superclass.
        print("Doing this underwater.")  # And add more stuff to it.
        
    def swim(self):
        print("Moving in water.")

nemo = Fish()
nemo.breathe()
nemo.swim()
```

## Connections

[Python Programing Language Index](../zettel/000E--python-lang-index.md)