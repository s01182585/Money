# Money
class Person:
  def __init__(self, name, date):
    self.name = name
    self.date = date

p1 = Person("Ben Lax","Thursday, March 21, 2024" )

print(p1.name)
print(p1.date)

class Flower:
    def __init__(self, name):
        self.name = name

    def grow(self):
        print("My " +self.name + " is growing.")

    def bloom(self):
        print("My " + self.name + " is blooming.")

def main():
    flower1 = Flower("Salary")
    flower1.grow()
    flower1.bloom()
    flower2 = Flower("Bank Account")
    flower2.grow()
    flower2.bloom()

if __name__ == "__main__":
  main()
