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

#A função calculator é o coração da calculadora. Ele usa o 'while' para continuar a executar até que o usuário escolha sair (opção 5). Dentro do laço, ele imprime as opções de operação para o usuário escolher. O usuário entra sua escolha e, se for 5, o laço é interrompido. Caso contrário, ele solicita ao usuário que digite os dois números que deseja usar para a operação.
Em seguida, utilizaremos um bloco if / elif para verificar qual é a opção escolhida pelo usuário. Dependendo da escolha, realizaremos a operação matemática apropriada (adição, subtração, multiplicação ou divisão) e armazenaremos o resultado em uma variável result. Finalmente, imprimimos o resultado para o usuário. Se a escolha do usuário for inválida (não for nenhuma das opções 1 a 4), imprimimos uma mensagem de erro e o laço começa novamente.
