class CAIXA:
    def caixaeletronico(self):
        saldo = 1000

        while True:
            print("\n--- CAIXA ELETRÔNICO ---")
            print("1 - Consultar saldo")
            print("2 - Depositar")
            print("3 - Sacar")
            print("4 - Sair")

            opcao = input("Escolha uma opção: ")

            if opcao == "1":
                print(f"Seu saldo é: R$ {saldo:.2f}")

            elif opcao == "2":
                deposito = float(input("Digite o valor do depósito: "))

                if deposito > 0:
                    saldo += deposito
                    print("Depósito realizado!")
                else:
                    print("Valor inválido.")

            elif opcao == "3":
                saque = float(input("Digite o valor do saque: "))

                if saque > saldo:
                    print("Saldo insuficiente.")
                elif saque <= 0:
                    print("Valor inválido.")
                else:
                    saldo -= saque
                    print("Saque realizado!")

            elif opcao == "4":
                print("Obrigado por utilizar o caixa!")
                break

            else:
                print("Opção inválida.")


caixa = CAIXA()
caixa.caixaeletronico()