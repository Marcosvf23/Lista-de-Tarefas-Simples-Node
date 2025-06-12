Projeto 1: Lista de Tarefas Simples
Este é um projeto simples de uma aplicação web de lista de tarefas (To-Do List) desenvolvida com Node.js e Express. Ele permite ao usuário adicionar, visualizar e remover tarefas de uma lista.

✨ Funcionalidades
Adicionar tarefas: Insira uma nova tarefa através do formulário na página inicial.

Visualizar tarefas: Todas as tarefas ativas são exibidas na página.

Remover tarefas: Exclua tarefas da lista clicando no "X" ao lado de cada uma.

🚀 Tecnologias Utilizadas
Node.js: Ambiente de execução para o JavaScript no lado do servidor.

Express.js: Framework para a construção da aplicação web e gerenciamento de rotas.

EJS (Embedded JavaScript templating): Motor de templates para gerar o HTML dinamicamente com os dados das tarefas.

body-parser: Middleware para extrair os dados enviados em requisições POST.

⚙️ Como Executar o Projeto
Siga os passos abaixo para rodar o projeto em sua máquina local.

Clone o repositório (exemplo):

git clone https://github.com/seu-usuario/nome-do-repositorio.git

Navegue até a pasta do projeto:

cd nome-do-repositorio

Instale as dependências necessárias:

npm install

Inicie o servidor:

node app.js

O arquivo principal do servidor deve se chamar app.js ou similar.

Abra seu navegador:
Acesse http://localhost:5000 para ver a aplicação funcionando.

📂 Estrutura de Arquivos
/
|-- node_modules/
|-- public/
| |-- style.css # Arquivos de estilo
|-- views/
| |-- index.html # Template da página
|-- app.js # Arquivo principal do servidor
|-- package.json
|-- README.md

app.js: Contém toda a lógica do servidor, configuração do Express e as rotas da aplicação.

views/: Pasta para os arquivos de template (neste caso, index.html com EJS).

public/: Pasta para arquivos estáticos como CSS, imagens e JavaScript do lado do cliente.

package.json: Define as dependências e scripts do projeto.
