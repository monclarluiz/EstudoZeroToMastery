#Given the below class:
class Cat:
    species = 'mammal'
    def __init__(self, name, age):
        self.name = name
        self.age = age

# 1 Instantiate the Cat object with 6 cats

cat1 = Cat("Bob", 18)
cat2 = Cat("Tom", 20)
cat3 = Cat("Jerry", 5)
cat4 = Cat("Chris", 30)
cat5 = Cat("Fabio", 23)
cat6 = Cat("Monc", 17)

bichano = [cat1, cat2, cat3]
bichano2 = [cat4, cat5, cat6]

# 2 Create a function that finds the oldest cat

def oldest_cat(gatos):
    maior_idade = 0 
    for i in gatos:
        if i.age > maior_idade:
            maior_idade = i.age
    return maior_idade

# 3 Print out: "The oldest cat is x years old.". x will be the oldest cat age by using the function in #2

print(f"The oldest cat is {oldest_cat(bichano)} years old.")
print(f"The oldest cat is {oldest_cat(bichano2)} years old.")
