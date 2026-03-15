print("Hello, World!")

num1 = int(input("Digite o primeiro número: "))
num2 = int(input("Digite o segundo número: "))
operacao = imput("digite a operação: ")

match operacao:
    case "+":
        res = num1 + num2 
    case "-":
        res = num1 - num2
    case "*":
        res = num1 * num2
    case "/":
        res = num1 / num2
        
print(f"Resultado é igual a {res}")
