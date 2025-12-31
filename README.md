
## 📅 Agenda Online - Node.js & EJS
Uma aplicação full-stack completa para gerenciamento de contatos, desenvolvida durante estudos avançados de Node.js. O projeto foca no padrão MVC (Model-View-Controller) e na renderização dinâmica de dados no servidor, permitindo que usuários gerenciem seus círculos sociais de forma segura e organizada.

## 🚀 Funcionalidades
Autenticação de Usuários: Sistema completo de cadastro e login com sessões seguras.

Gestão de Contatos (CRUD): Criação, visualização, edição e exclusão de contatos.

Validação de Dados: Verificação de campos obrigatórios, formatos de e-mail e telefones.

Mensagens Flash: Feedback visual instantâneo para o usuário em caso de erros ou sucesso nas operações.

Segurança (CSRF): Proteção contra ataques de falsificação de solicitação entre sites.

Interface Responsiva: Estilização personalizada via CSS para garantir usabilidade em qualquer dispositivo.

## 🛠️ Tecnologias Utilizadas
Node.js: Ambiente de execução para o servidor.

Express: Framework para gerenciamento de rotas e middlewares.

EJS (Embedded JavaScript): View engine para renderização de templates HTML dinâmicos.

MongoDB & Mongoose: Banco de dados NoSQL e modelagem de dados de usuários e contatos.

Express-Session: Gerenciamento de sessões de usuário e autenticação persistente.

Connect-Flash: Armazenamento temporário de mensagens de notificação.

CSS3: Estilização customizada e layout responsivo.

## 📦 Como rodar o projeto
Clone o repositório:

Bash

git clone https://github.com/mvdevelop/agenda-udemy.git
cd agenda-udemy
Instale as dependências:

Bash

npm install
Configure o Banco de Dados: Crie um arquivo .env na raiz do projeto e adicione sua string de conexão do MongoDB:

Snippet de código

CONNECTIONSTRING=seu_link_do_mongodb_atlas
Inicie a aplicação:

Bash

npm start # ou npm run dev (para rodar com nodemon)
Acesse: http://localhost:3000

## 📂 Estrutura de Pastas
Plaintext

agenda-udemy/
├── frontend/         # Arquivos de script e estilo (Source)
├── public/           # Arquivos estáticos servidos (Bundle)
├── src/
│   ├── controllers/  # Lógica de processamento das páginas
│   ├── middlewares/  # Filtros de segurança e variáveis globais
│   ├── models/       # Esquemas e regras de negócio (MongoDB)
│   └── views/        # Templates EJS (HTML dinâmico)
├── server.js         # Configuração principal do servidor
└── .env              # Variáveis de ambiente sensíveis

## 🎨 Preview da Interface
Nota: Adicione aqui uma captura de tela da sua página de login ou da listagem de contatos (ex: Layout limpo com tabelas organizadas e formulários de cadastro).

## 👨‍💻 Autor
Desenvolvido com ❤️ por mvdevelop.

GitHub: @mvdevelop

## 📄 Licença
Este projeto é para fins educacionais e está sob a licença MIT.
