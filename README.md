# Pass.in - Event Participant Manager 🧑🏼‍💻

![Captura de ecrã de 2024-04-03 12-11-36](https://github.com/JeffS1lva/pass.in/assets/118827532/dbb462d0-cf09-409f-9276-710c6c435587)



## Descrição 📎

Este projeto é um sistema de gerenciamento de participantes de eventos, construído com uma arquitetura moderna e tecnologias avançadas. Ele permite que os organizadores visualizem, pesquisem e gerenciem os detalhes dos participantes que se inscreveram para um evento específico. A aplicação é composta por um frontend desenvolvido com React, TypeScript, Vite e Tailwind CSS, e um backend construído com Node.js, Prisma e rotas HTTP para expor os endpoints da API. Além disso, utiliza migrations para gerenciar o esquema do banco de dados.
 
## Funcionalidades 🔍
- **Cadastro de Participantes:** A API fornece endpoints para cadastrar novos participantes, incluindo nome, e-mail e outras informações relevantes.
- **Pesquisa de Participantes:** Os organizadores podem pesquisar participantes por nome ou e-mail, utilizando a barra de pesquisa na página da web.
- **Visualização e Edição de Participantes:** Os detalhes dos participantes, como nome, e-mail, data de inscrição e check-in, são exibidos na página da web. Os organizadores podem editar esses detalhes conforme necessário.
- **Paginação de Participantes:** Os resultados da pesquisa são exibidos em uma tabela paginada, permitindo que os organizadores naveguem pelos resultados de forma eficiente.

## Estrutura do Projeto 🏗️
- O projeto é organizado em frontend e backend:

**Frontend:**
- Utiliza React como biblioteca principal para a construção de interfaces de usuário.
- TypeScript é usado para adicionar tipos ao JavaScript, garantindo maior segurança e escalabilidade.
- Vite é usado como ferramenta de build e desenvolvimento para compilar e servir o código.
- Tailwind CSS é utilizado para estilização e design responsivo da interface do usuário.
  
**Backend:**
- Utiliza Node.js como ambiente de execução JavaScript no lado do servidor.
- Prisma é utilizado como ORM para facilitar a comunicação com o banco de dados e realizar operações de CRUD.
- TypeScript é usado para adicionar tipagem estática ao código, melhorando a manutenção e a legibilidade.
- Rotas HTTP são implementadas para expor os endpoints da API e fornecer acesso aos dados dos participantes.

## Interpretação do Código 📝
- O código fonte ele inclui a lógica para lidar com pesquisa, paginação e renderização dos dados dos participantes. Aqui está uma breve interpretação das principais partes do código:
  
**Front-end**
- O componente AttendeeList é responsável por renderizar a interface de gerenciamento de participantes. Ele inclui recursos como pesquisa, paginação e exibição de dados dos participantes em uma tabela. O frontend realiza requisições HTTP para o backend para buscar e enviar dados, garantindo uma experiência de usuário dinâmica e responsiva.

**Back-end**
- Já no backend, o código implementa rotas HTTP para expor endpoints da API que realizam operações CRUD nos dados dos participantes. Utiliza Prisma para interagir com o banco de dados, garantindo uma manipulação eficiente e segura dos dados. Além disso, são utilizadas migrations para gerenciar o esquema do banco de dados, facilitando atualizações e alterações futuras.

## Rodando Localmente ⚙️

Antes de começar, é necessário preparar o ambiente de desenvolvimento.

**Para Windows:**
- Instale o [Node.js.](https://nodejs.org/en)
- Baixe e [instale o Visual Studio Code (VSCode).](https://code.visualstudio.com/)
- Abra o terminal (Prompt de Comando ou PowerShell) para executar comandos.

**Para Linux e Mac:**
- Instale o Node.js:
- No Linux, use o gerenciador de pacotes de sua distribuição. Por exemplo, no Ubuntu: ```sudo apt-get install nodejs.```
- Não Mac, use [Homebrew ](https://brew.sh/): ```brew install node.```
- Instale o [Visual Studio Code](https://code.visualstudio.com/)

**Para obter o código do Projeto:**
- Se você já tem uma conta no github: ```git clone https://github.com/seu-usuario/nome-do-repositorio.git```
- Se não tiver uma conta no GitHub, [Crie uma conta.](https://github.com/)

**Instalação**

Após clonar o projeto, instale as dependências:
- Abra o terminal na pasta do projeto.
- Execute ```npm install```(ou ```yarn install``` se você estiver usando Yarn).

**Executando Projeto**

- Execute ```npm run dev``` para iniciar o servidor de desenvolvimento.

## Tecnologias 🛠️

- Typescript
- Reactjs
- Nodejs
- Prisma
- Vite
- Lucide-React
- DayJs
- Tailwindcss

## Links 🔗 
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jefferson-silva-2258ab230/)

## Licença 📝 

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [MIT](https://choosealicense.com/licenses/mit/) para obter mais detalhes.
