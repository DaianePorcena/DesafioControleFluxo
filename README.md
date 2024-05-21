# Desafio - Controle de  Fluxo

O objetivo deste desafio consiste em exercitar todo o conteúdo apresentado nos módulos: Controle de Fluxo e Tratamento de Exceções do bootcamp [Santander 2024 - Backend com Java](https://web.dio.me/track/santander-2024-backend-com-java).

## 📜 Instruções

O sistema deverá receber dois parâmetros via terminal que representarão dois números inteiros, com estes dois números você deverá obter a quantidade de interações (for) e realizar a impressão no console (System.out.print) dos números incrementados, exemplo:

- Se você passar os números 12 e 30, logo teremos uma interação (for) com 18 ocorrências para imprimir os números, exemplo: "Imprimindo o número 1", "Imprimindo o número 2" e assim por diante.
- Se o primeiro parâmetro for MAIOR que o segundo parâmetro, você deverá lançar a exceção customizada chamada de ParametrosInvalidosException com a segunda mensagem: "O segundo parâmetro deve ser maior que o primeiro"

1. Crie o projeto ``DesafioControleFluxo``
2. Dentro do projeto, crie a classe ``Contador.java`` para realizar toda a codificação do nosso programa.
3. Dentro do projeto, crie a classe ``ParametrosInvalidosException`` que representará a exceção de negócio no sistema.

## 🛠️ Instruções para Rodar o Projeto

- Clone o repositório

````
git clone git@github.com:DaianePorcena/DesafioControleFluxo.git
````
- Navegue até o diretório ``\DesafioControleFluxo\src\``
- Use o comando javac para compilar  o arquivo ``Contador.java``

````
javac Contador.java
````

- Execute o arquivo compilado:

````
java Contador
````