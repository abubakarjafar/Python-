Copy code
print("Simple Calculator")

num1 = float(input("Shigar da lamba ta farko: "))
num2 = float(input("Shigar da lamba ta biyu: "))

print("Zaɓi aiki:")
print("1. Ƙari (+)")
print("2. Ragi (-)")
print("3. Ninkawa (*)")
print("4. Rabawa (/)")

choice = input("Shigar da 1/2/3/4: ")

if choice == "1":
    print("Sakamako:", num1 + num2)

elif choice == "2":
    print("Sakamako:", num1 - num2)

elif choice == "3":
    print("Sakamako:", num1 * num2)

elif choice == "4":
    print("Sakamako:", num1 / num2)

else:
    print("Zaɓi bai dace ba.")
