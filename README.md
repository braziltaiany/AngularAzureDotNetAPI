# AngularAzureDotNetAPI

**Descrição:**
Este projeto consistirá em uma aplicação web de gerenciamento de tarefas (ToDo List) onde os usuários podem criar, editar, excluir e visualizar tarefas. A aplicação terá uma interface de usuário construída com Angular, uma API web para manipular os dados usando .NET C# e o banco de dados será hospedado no Azure.

**Recursos:**
1. **Frontend com Angular:**
   - Interface de usuário responsiva e amigável.
   - Páginas para exibir lista de tarefas, adicionar/editar tarefas e detalhes da tarefa.
   - Integração com a API para consumir e exibir os dados.

2. **Backend com .NET C#:**
   - API RESTful para CRUD de tarefas.
   - Autenticação e autorização para proteger as operações da API.
   - Conexão com o banco de dados para armazenar e recuperar os dados das tarefas.

3. **Azure:**
   - Implantação da API no Azure App Service.
   - Configuração do banco de dados SQL Server no Azure.
   - Configuração de CI/CD (Continuous Integration/Continuous Deployment) para automatizar o processo de implantação.

**Estrutura do Projeto:**
- **frontend:** Pasta contendo o código fonte do aplicativo Angular.
- **backend:** Pasta contendo o código fonte da API .NET C#.
- **docs:** Documentação do projeto.
- **README.md:** Arquivo contendo informações sobre o projeto, instruções de instalação e uso.

**Tecnologias Utilizadas:**
- Angular
- .NET Core (C#)
- Azure App Service
- Azure SQL Database
- HTML/CSS (para o frontend)
- Git (para controle de versão)

**Instruções de Instalação e Uso:**
1. Clone o repositório para a sua máquina local.
2. Navegue até a pasta `frontend` e execute `npm install` para instalar as dependências do Angular.
3. Navegue até a pasta `backend` e abra o projeto no Visual Studio ou em um editor de código de sua preferência.
4. Configure a conexão com o banco de dados no arquivo `appsettings.json`.
5. Execute a aplicação backend para garantir que está funcionando corretamente.
6. Configure a aplicação frontend para apontar para a URL da API backend.
7. Execute a aplicação frontend e teste as funcionalidades.
