# python-experiments_om_

1. WAP to find roots of quadratic eqations
   
    import cmath
a = float(input("Enter coefficient a: "))
b = float(input("Enter coefficient b: "))
c = float(input("Enter coefficient c: "))

d = b**2 - 4*a*c

root1 = (-b + cmath.sqrt(d)) / (2 * a)
root2 = (-b - cmath.sqrt(d)) / (2 * a)

print(f"roots are {root1} and {root2}")
