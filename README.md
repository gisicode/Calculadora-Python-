def calcular(num1, num2, operacao):
    if operacao == '+':
        return num1 + num2
    elif operacao == '-':
        return num1 - num2
    elif operacao == '*':
        return num1 * num2
    elif operacao == '/':
        return num1 / num2
    else:
        return "Operação inválida"

n1 = float(input("Digite o primeiro número: "))
n2 = float(input("Digite o segundo número: "))
op = input("Escolha a operação (+, -, *, /): ")

resultado = calcular(n1, n2, op)
print("Resultado:", resultado)
 
# Calculadora-Python-
# Calculadora Simples em Python  Calculadora no terminal que realiza as quatro operações básicas: soma, subtração, multiplicação e divisão.  ## Como usar 1. Rode o arquivo `calculadora.py` 2. Digite dois números 3. Escolha a operação  ### Exemplo:
