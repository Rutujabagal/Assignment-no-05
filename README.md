Fck = float(input(“Enter the value of characteristic compressive strength (fck): “))

# Input for grade of steel

Fy = float(input(“Enter the grade of steel (fy): “))

# Input for modulus of elasticity of steel

Es = float(input(“Enter the value of Modulus of Elasticity of steel (Es): “))

# Input for width

B = float(input(“Enter the value of width (b): “))

# Input for effective depth

D = float(input(“Enter the value of effective depth (d): “))

# Input for bar diameters and number of bars

D1 = float(input(“Enter the value of bar diameter (d1): “))

D2 = float(input(“Enter the value of bar diameter (d2): “))

N1 = int(input(“Enter the number of bars for d1: “))

N2 = int(input(“Enter the number of bars for d2: “))

# Area of steel for two types of bars

Ast1 = n1 * 0.7854 * d1**2

Ast2 = n2 * 0.7854 * d2**2

# Print the areas of steel

Print(“The value of area of steel (Ast1):”, Ast1)

Print(“The value of area of steel (Ast2):”, Ast2)

# Total area of steel

Ast = Ast1 + Ast2

Print(“The value of total area of steel (Ast):”, Ast)
