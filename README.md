Live site: https://course-frontend-mu.vercel.app/login

Frontend: https://github.com/paulolopest/course_frontend

Backend: https://github.com/paulolopest/course_backend

# Sistema de Gerenciamento de Cursos - README

Este projeto consiste em um sistema de gerenciamento de cursos, com funcionalidades CRUD para cursos e professores associados, incluindo autenticação básica. O desenvolvimento foi realizado utilizando as seguintes tecnologias:

## Frontend
- **React**: Escolhido pela sua popularidade, flexibilidade e eficiência no desenvolvimento de interfaces de usuário dinâmicas.
- **Bibliotecas de gerenciamento de estilos**:. Para estilos, adotei o scss.

## Backend
- **NodeJS com Typescript**: A combinação oferece tipagem estática, facilitando a manutenção do código, e o NodeJS proporciona um ambiente eficiente para desenvolvimento de servidores.
- **Express**: Escolhi o Express como framework web devido à sua simplicidade e flexibilidade, permitindo um desenvolvimento rápido e eficaz.
- **PostgreSQL e Prisma CLI**: Utilizei o PostgreSQL como banco de dados, por ser robusto e confiável. O Prisma CLI facilitou a interação com o banco de dados, oferecendo um ORM para consultas mais intuitivas e seguras.

## Banco de Dados
- **PostgreSQL**: Optei por utilizar o PostgreSQL devido à sua confiabilidade, suporte a transações e capacidade de gerenciamento de dados complexos.

## Funcionalidades Desenvolvidas

### CRUD de Cursos
- **Criação**: Permite a criação de novos cursos com informações como título, descrição e categoria.
- **Edição**: Permite a edição dos cursos existentes, atualizando as informações conforme necessário.
- **Exclusão**: Possibilita a exclusão de cursos que não são mais necessários.
- **Listagem**: Apresenta uma lista de todos os cursos cadastrados, exibindo informações relevantes.

### CRUD de Professores
- **Criação**: Permite a adição de novos professores associados aos cursos.
- **Edição**: Permite a atualização das informações dos professores existentes.
- **Exclusão**: Facilita a remoção de professores quando necessário.
- **Listagem**: Exibe uma lista de todos os professores associados aos cursos.

### Autenticação Básica
- **Criar Conta**: Permite que os usuários se cadastrem no sistema.
- **Login**: Possibilita que os usuários façam login para acessar as funcionalidades protegidas.

## Estrutura do Projeto
- A estrutura de pastas está organizada de forma lógica e modular, facilitando a manutenção e escalabilidade do projeto.

## Observações
- Não foram desenvolvidas funcionalidades para upload de aulas.
- O sistema utiliza links de CDN para imagens.

## Como Executar o Projeto
1. Clone um dos repositórios: 
2. Instale as dependências: `npm install`
3. Execute o código: `npm run dev`


## Considerações Finais
Este projeto foi desenvolvido dentro do prazo estipulado, seguindo as boas práticas de codificação, estruturação e documentação.
