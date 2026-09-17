class PRODUTO:
    def cadastro(self):
        produtos = []

        while True:
            print("\n--- MENU ---")
            print("1 - Cadastrar produto")
            print("2 - Listar produtos")
            print("3 - Sair")

            opcao = input("Escolha uma opção: ")

            if opcao == "1":
                produto = input("Digite o nome do produto: ")
                produtos.append(produto)
                print("Produto cadastrado com sucesso!")

            elif opcao == "2":
                print("\n--- PRODUTOS CADASTRADOS ---")

                if len(produtos) == 0:
                    print("Nenhum produto cadastrado.")
                else:
                    for produto in produtos:
                        print(produto)

            elif opcao == "3":
                print("Saindo...")
                break

            else:
                print("Opção inválida.")


produto = PRODUTO()
produto.cadastro()