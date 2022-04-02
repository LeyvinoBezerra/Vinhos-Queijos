# Vinhos-Queijos

![image](https://user-images.githubusercontent.com/56727891/161404587-2c8dbd91-d6ec-4467-adbf-a6b3cedee414.png)


- Contextualização de domínio:
    - Essa aplicação tem como objetivo auxiliar e gerenciar um depósito/loja de vinhos e queijos para melhor distribuição e genciamento dos usuários e donos dos estabelecimentos. Decidimos atuar com esse tema, pois futuramente torna-se uma base e esqueleto para aplicações futuras e similares no ramo.

- Objetivo:
    - Temos como objetivo, gerenciar um deposito de mercadorias e auxiliar atores nessa aplicação.

- Funcionalidade e os Recursos:
    - Cadastro/Login de usuários: clientes e funcionários:
        - Os atores, clientes e funcionários poderão criar uma conta e ter acesso diferente para cada uma.
    - Comprar produto:
        - Os usuários clientes, vão escolher quais produtos serão adicionados ao carrinho de compra e finaliza-lá.
    - Favoritar produto:
        - Os usuários clientes, vão escolher qual produto está sempre comprando e favoritar para facilitar a escolha.
    - Pesquisar produto:
        - Os usuários clientes, vão pesquisar qual produto deseja.
    - Receber e-mail:
        - Os usuários clientes, vão receber e-mail's com promoções de produtos favoritados e ultimas compras.
    - Adicionar estoque:
        - Funcionários e donos, vão poder adicionar produtos ao estoque.
    - Remover estoque:
        - Funcionários e donos, vão poder remover produtos do estoque.
    - Alterar estoque:
        - Funcionários e donos, vão poder mudar informações do estoque.
    - Gerar Relatório semanal/diário:
        - Ao final de um dia e um semana, será gerado um relatório de vendas e financeiro.

- Classes-entidade:
    - Cliente:
        - id: primary key
        - nome: String
        - senha: String
        - email: String
        - numero_cel: int
        - cpf: String
        
    - Funcionario:
        - id: primary key
        - nome: String
        - senha: String
        - email: String
        - numero_cel: int
        - cpf: String
        
    - Proprietario:
        - id: primary key
       
    - Produto_Vinho:
        - Nome: String
        - Descriacao: String
        - Validade: Data
        - qnt_estoque: int
        
    - Produto_Queijo:
        - Nome: String
        - tipo: String
        - Peso_total: double
        - Descriacao: String
        - Validade: Data
        - qnt_estoque: int
     
- WireFrame:
    - Tela Inicial
        
     ![image](https://user-images.githubusercontent.com/56727891/161404280-e24a6b15-dfd4-4d0d-b021-231afa5b3dae.png)
        
     - Perfil
       
     ![image](https://user-images.githubusercontent.com/56727891/161404293-f30a0856-6ce3-4ed3-bdb8-50a4aef3a4b9.png)
        
     - Vinhos

     ![image](https://user-images.githubusercontent.com/56727891/161404305-b4f4cab6-508b-486d-9e73-ed27411c6b94.png)

- Arquitetura:
        - iremos usar no projeto o MVC (Model / View / Controller).
    
