# Arquitetura Model-View-Controller(MVC) 
## Descrição
### Descrição
Desenvolvimento e apresentação de uma proposta de uma arquitetura detalhada para o projeto em grupo com a Parceiros Voltuntários. Arquitetura Model-View-Controller(MVC) de uma aplicação web, que utiliza o framework "Sails.js", com diagramas produzidos na ferramenta de diagramação "draw.io"(https://www.draw.io/).  

## Análise e Definição do Escopo
### Objetivo
Construir uma aplicação web que usa o framework "Sails.js", ambiente de execução "Node.js" e o serviço "Render" para estabelecer uma arquitetura Model-View-Controller(MVC), que se conecta com um cliente web, que interage com o usuário por meio de HTML, CSS e Javascript. O MVC troca dados com um servidor próprio para a base de dados que é construída por meio do PostegreSQL.

### Módulos, Funcionalidades, Recursos
Landing Page:
- Página Principal: Exposição de conteúdo que motiva o usuário a participar de projetos voluntários ou utilizar da plataforma.
- Cadastro: Possibilidade de efetuar cadastro na plataforma
- Login: Possibilidade de efetuar login na plataforma

Plataforma:
- Autenticação de usuário: Cadastro de usuários, login, e logout.
- Feed: Visualizar publicações próprias e de outros usuários. Possibilidade de filtrar posts por tags ou categorias. 
- Publicar: Criar e postar posts com ideias em geral ou específicas relacionadas ao trabalho voluntário ou ao voluntariado.
- Comunidade: Visualizar perfis de ONGs cadastradas na plataforma. Cada ONG fornece dados sobre suas missões, projetos e metodologia. ONGs podem criar posts também
- Perfil: 

### Escopo
Funcionalidades Essenciais

## Diagrama
### Sobre Diagramas
Os diagramas do MVC foram criados e divididos em duas imagens diferentes. Uma se refere a "Landing Page" e a outra à "Plataforma". Isso permite uma maior organização durante o planejamento, desenvolvimento e implementação da arquitetura. Também, pois se fosse apenas uma imagem, ficaria com um excesso de conteúdo, diminuindo a legibilidade devido ao zoom ou tamanho da letra.

### Diagrama da Landing Page
Nesse diagrama, os itens na coluna "Views" são as diferentes páginas da "Landing Page" do site. Os diferentes itens da coluna "Controllers" se referem aos métodos HTTP sendo utilizados em cada página. O item da coluna "Models" está relacionado às informações a serem enviadas para a base de dados "PostgreSQL".
<div align="center" width="100%">
<img src = "assets/MVCLandingPage.png " alt="MVCLandingPage">
<sup>Figura 1: Aquitetura MVC da Landing Page, Fonte: Material produzido pelos autores (2024)</sup>
</div>

### Diagrama da Plataforma
<div align="center" width="100%">
<img src = "assets/MVCPlataforma.png " alt="MVCPlataforma">
<sup>Figura 2: Aquitetura MVC da Plataforma, Fonte: Material produzido pelos autores (2024)</sup>
</div>
