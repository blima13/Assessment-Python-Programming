# First question:

class Person:
    def __str__(self, name):
        self.name = name

m = Person('Michael')

print(m.name)
