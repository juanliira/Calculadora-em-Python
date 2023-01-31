# Calculadora-em-Python

def calculator():
  while True:
    print("Selecione a operação desejada:")
    print("1. Adição")
    print("2. Subtração")
    print("3. Multiplicação")
    print("4. Divisão")
    print("5. Sair da calculadora")
    
    choice = int(input("Digite sua escolha (1/2/3/4/5): "))
    
    if choice == 5:
      break
    
    num1 = float(input("Digite o primeiro número: "))
    num2 = float(input("Digite o segundo número: "))
    
    if choice == 1:
      result = num1 + num2
      print("Resultado:", result)
    elif choice == 2:
      result = num1 - num2
      print("Resultado:", result)
    elif choice == 3:
      result = num1 * num2
      print("Resultado:", result)
    elif choice == 4:
      result = num1 / num2
      print("Resultado:", result)
    else:
      print("Opção inválida. Tente novamente.")
      
calculator()
