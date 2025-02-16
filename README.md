## README do Projeto: Alfala-Server-10-06

Este é um projeto backend desenvolvido com Express.js e Node.js, com o objetivo de fornecer uma API para gerenciamento de livros e favoritos. O projeto utiliza rotas para livros e favoritos, com funcionalidades como listar, inserir e deletar.

### Funcionalidades

*   **Rotas de Livros:**
    *   `GET /livros`: Lista todos os livros.
    *   `POST /livros`: Adiciona um novo livro.
    *   `PUT /livros/:id`: Atualiza um livro existente.
    *   `DELETE /livros/:id`: Deleta um livro.

*   **Rotas de Favoritos:**
    *   `GET /favoritos`: Lista todos os livros favoritos.
    *   `POST /favoritos/:id`: Adiciona um livro aos favoritos.
    *   `DELETE /favoritos/:id`: Remove um livro dos favoritos.

### Tecnologias Utilizadas

*   **Node.js:** Ambiente de execução JavaScript para o backend.
*   **Express.js:** Framework web para Node.js.
*   **Rotas:** Utilizado para definir as rotas da API.
*   **JSON:** Formato de dados utilizado para comunicação entre o frontend e o backend.

### Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/AnaPaula2024/Alfala-Server-10-06.git
    ```

2.  **Instale as dependências:**
    ```bash
    npm install
    ```

3.  **Execute o servidor:**
    ```bash
    npm start
    ```

O servidor estará em execução na porta 8000.

### Estrutura do Projeto

*   `app.js`: Arquivo principal do servidor.
*   `routes/`: Pasta contendo os arquivos de rotas.
*   `controller/`: Pasta contendo os arquivos de controle das rotas.
*   `service/`: Pasta contendo os arquivos de serviços, com a lógica de negócios.
*   `livro.json`: Arquivo contendo os dados dos livros.
*   `favoritos.json`: Arquivo contendo os dados dos livros favoritos.

### Observações

*   Este é um projeto simples com fins didáticos.
*   Os dados dos livros e favoritos estão armazenados em arquivos JSON. Em um ambiente de produção, seria recomendado utilizar um banco de dados.

Sinta-se à vontade para modificar e adaptar este projeto às suas necessidades.
