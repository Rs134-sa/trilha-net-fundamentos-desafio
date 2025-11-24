# 🚗 Sistema de Estacionamento em C#

## 📝 Descrição
Este é um projeto de console simples desenvolvido em C# como parte do desafio de fundamentos da trilha .NET. O programa simula um sistema de gerenciamento de estacionamento, permitindo ao usuário cadastrar veículos por sua placa, removê-los (calculando o valor a ser pago com base no tempo de permanência) e listar todos os veículos atualmente estacionados.

---

## ✨ Funcionalidades

O sistema apresenta um menu interativo com as seguintes opções:

1.  **Cadastrar veículo:** Solicita a placa do veículo e o adiciona à lista de veículos estacionados.
2.  **Remover veículo:** Solicita a placa do veículo e a quantidade de horas que ele permaneceu estacionado. Em seguida, calcula o valor total a ser pago com base em um preço inicial e um preço por hora (definidos no início da execução) e remove o veículo da lista.
3.  **Listar veículos:** Exibe a placa de todos os veículos que estão no estacionamento.
4.  **Encerrar:** Finaliza a execução do programa.

---

## 💻 Tecnologias Utilizadas

-   **C#**: Linguagem de programação principal.
-   **.NET**: Plataforma de desenvolvimento utilizada para criar a aplicação de console.

---

## 🚀 Como Executar o Projeto

Para executar este projeto em sua máquina local, você precisará ter o SDK do .NET instalado. Siga os passos abaixo:

1.  **Clone o repositório** (caso o projeto esteja em um) ou simplesmente tenha os arquivos em um diretório local.

2.  **Navegue até o diretório do projeto** através do seu terminal (como PowerShell, CMD ou Terminal):
    ```sh
    cd d:\Projetos\trilha-net-fundamentos-desafio\DesafioFundamentos
    ```

3.  **Execute o projeto** com o seguinte comando do .NET CLI:
    ```sh
    dotnet run
    ```

4.  O programa será iniciado no console, solicitando o preço inicial e o preço por hora. Após fornecê-los, o menu principal será exibido para que você possa interagir com o sistema.

---

## 📂 Estrutura do Projeto

O código-fonte está organizado da seguinte forma:

```
DesafioFundamentos/
├── Models/
│   └── Estacionamento.cs  # Classe principal que contém toda a lógica do estacionamento.
└── Program.cs             # Ponto de entrada da aplicação, responsável pelo menu e interação com o usuário.
```

-   `Program.cs`: Arquivo responsável por iniciar a aplicação, coletar os preços do usuário, instanciar a classe `Estacionamento` e exibir o menu de opções em um loop.
-   `Models/Estacionamento.cs`: Contém a classe `Estacionamento`, que encapsula a lógica de negócio do sistema. Isso inclui os métodos para adicionar, remover e listar veículos, bem como o cálculo do preço.

---

*Este projeto foi desenvolvido como parte do desafio de projeto "Construindo um Sistema Para Estacionamento com C#" da DIO.*

---

## 👨‍💻 Autoria

Feito por [Raiane de Sá](https://github.com/Raiane-S) - Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/raiane-s/)!
