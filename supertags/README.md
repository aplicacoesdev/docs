## 🌟 Supertags 🌟

![Intermediário](https://img.shields.io/badge/intermediário-3f50e7?style=for-the-badge)
![Projeto em Desenvolvimento](https://img.shields.io/badge/projeto%20em%20desenvolvimento-ff6460?style=for-the-badge)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)


![Gif mostrando o funcionamento da aplicação](.docs/images/main.gif)

O projeto SuperTags é um projeto de páginas de anotação (chamadas tags). Nessa aplicação um usuário deve se autenticar para ter acesso à criação de páginas onde pode fazer suas anotações em um editor de texto rico e adicionar propriedades às tags que o ajudem em sua organização.

### 📝 Requisitos Funcionais 📝


1. **Registro de usuário**:

    - Um usuário deve conseguir criar uma conta na aplicação provendo nome, email e senha.
    - Um usuário só poderá se registrar na aplicação se possuir uma senha forte

2. **Login**:

    - Um usuário deve fazer login na aplicação utilizando e-mail e senha
    - Ao fazer login, o usuário precisa ser redirecionado para a parte interna da aplicação que não estará disponível para usuários não logados

3. **Logout**:

    - Um usuário deve conseguir se deslogar da aplicação uma vez que esteja na parte interna da aplicação
    - Ao se deslogar, o usuário deve retornar para a lágina de login

4. **Sessão**
    - Ao fazer o login, a sessão do usuário deve se manter ativa por um período de tempo (exemplo, uma semana), ou seja, se o usuário fechar o navegador nesse intervalo de tempo, ao abrí-lo novamente dentro do período de tempo estipulado, ele deve continuar logado

5. **Criar uma nova SuperTag**:

    -   O usuário deve conseguir criar uma super tag a partir da interface da aplicação

6. **Criar uma nova tag filha**:

    -   O usuário deve conseguir criar uma tag filha associada a uma SuperTag.
    -   Além de criar uma tag associada a uma super tag, é possível que tags também tenham tags filhas.

7. **Colapsar lista de Tags**:

    -   O usuário deve conseguir exibir todas as tags filhas de uma determinada tag, ou fechar essa visualização

8. **Exclusão de tags**:

    -   Uma tag, ou uma super tag, devem poder ser excluidas pela interface.
    -   Ao excluir uma super tag, suas tags filhas também serão excluidas.

9. **Definir o título de uma página**:

    - O usuário deve poder alterar o título de uma página que será inicializada com um valor padrão
    - Além de um valor textual, o título da página deve conter um emoji para sua identificação
    - Ao clicar no emoji, deve ser possível selecionar um emoji de uma lista para substituir o emoji padrão
    - Ao clicar no título da página, deve ser possível alterá-lo

10. **Propriedades**:

    - Uma página deve conter uma lista de propriedades cujos tipos pode ser selecionado entre texto, número inteiro, número real, checkbox ou data
    - Uma propriedade deve ter um valor que possa ser editado de acordo com o tipo da propriedade
    - A lista de propriedades de um documento pode ser colapsada
    - Uma propriedade pode ser excluida pelo usuário

11. **Editor de texto**:

    - O usuário deve ter a sua disposição um editor de texto
    - Se o editor tiver funcionalidades de estilização, o usuário deve conseguir utilizá-las.
    - Se o editor tiver o menu de comandos especiais, o usuário deve ser capaz de utilizá-lo.
     - Deve permitir que o usuário possa digitar texto na interface
    - Pode conter apenas um texto simples, ou um texto estilizado.
    - No caso de utilizar um texto estilizado:
        - **[opcional]** Utilizar um menu de estilização que aparecerá ao selecionar uma palavra onde é possível selecionar uma opção de estilização do texto como itálico, negrito, sublinhado, código ou link
        - **[opcional]** Implementar um menu de comandos especiais onde é possível escolher uma das estilizações abaixo:
            - Título 1 (equivalente ao `<h1>`)
            - Título 2 (equivalente ao `<h2>`)
            - Título 3 (equivalente ao `<h3>`)
            - Lista ordenada (equivalente ao `<ol>`)
            - Lista não ordenada (equivalente ao `<ul>`)
            - Imagem (equivalente ao `<img>`)
            - Link (equivalente ao `<a>`)

12. **Salvamento automático**:
    - O salvamento da página (contendo título, propriedades e conteúdo do editor de texto) deve ser salvo automaticamente no banco de dados relacional
    - Ao abrir a página, esta deve ser preenchida com as últimas alterações feitas pelo usuário.


### 📝 Funcionalidades Extras 📝

-   Integrar algum modelo de inteligência artificial para geração de texto no editor de texto da aplicação.
-   Adicionar, no editor de texto um comando especial para listar as tags da aplicação e linká-las ao textos que está sendo escrito
-   Implementar o fluxo para que o usuário faça o upload de uma imagem de perfil
- Implementar a lógica de alteração de senha de um usuário

### 💡 Recursos úteis para o desenvolvimento desse projeto 💡

#### 📚 Cursos da formação sugeridos 📚:

Obs: Não é necessário ter feito todos os cursos para participar do projeto, mas se houverem dúvidas, esses cursos são um bom ponto de consulta.

-   Especialista.DEV > Trilha React&Next > Fundamentos de React
-   Especialista.DEV > Trilha React&Next > React com Tailwind CSS
-   Especialista.DEV > Trilha React&Next > Next.JS
-   Especialista.DEV > Trilha Banco de Dados > Banco Relacional
-   Especialista.DEV > Trilha Banco de Dados > SQL
-   Especialista.DEV > Trilha Backend > API com Express JS
-   Especialista.DEV > Trilha Backend > Persistência com Knex.js

#### 📰 Artigos do Blog da Formação 📰:

-   [Aprendendo a lidar com erros](https://blog.formacao.dev/aprendendo-a-lidar-com-erros/)
-   [Instalando o PostgreSQL no Windows](https://blog.formacao.dev/instalando-o-postgresql-no-windows/)
-   [Como armazenar senhas de usuários](https://blog.formacao.dev/como-armazenar-senhas-de-usuarios/)
-   [Github Desktop](https://blog.formacao.dev/github-desktop/)
-   [O que é o arquivo .gitignore](https://blog.formacao.dev/o-que-e-o-arquivo-gitignore/)
-   [Validações com o pacote validator](https://blog.formacao.dev/validacoes-com-o-pacote-validator/)

#### 📽️ Vídeos do Canal do Youtube da Cod3r 📽️:

-   [Conceitos Essenciais: O Básico de HTTP](https://www.youtube.com/watch?v=CXzbUwK6lc8)
-   [Criando uma Aplicação do Zero a Nuvem Usando o TurboRepo](https://www.youtube.com/watch?v=SQy5we_2L7Y)
-   [Backend limpo](https://www.youtube.com/watch?v=5p5sE62bBVs)