# TaskMaster Pro

> Um app de gerenciamento de tarefas colaborativo e intuitivo.

##  Descrição
TaskMaster Pro nasceu como um projeto acadêmico para aprender React e Node.js. Ele permite que equipes organizem tarefas, definam prazos, marquem status e colaborem de forma simples e eficiente.

##  Tecnologias Utilizadas
- **Front-end**: React  
- **Back-end**: Node.js + Express  
- **Banco de dados**: MongoDB  
- **Gerenciamento de versão**: Git e GitHub

##  Instalação
1. Clone o repositório:  
   `git clone https://github.com/seuusuario/taskmaster-pro.git`  
2. Acesse a pasta do servidor:  
   `cd server && npm install && npm start`  
3. Acesse o front-end:  
   `cd ../client && npm install && npm start`  
4. O app estará disponível em `http://localhost:3000`

##  Exemplo de Uso
- Criar uma tarefa:
```bash
curl -X POST http://localhost:3000/tasks \
  -H 'Content-Type: application/json' \
  -d '{"title":"Fazer README","dueDate":"2025-09-01"}'
