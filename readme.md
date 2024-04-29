# Diagrama Model-View-Controller
## Análise e Definição do Escopo
<b> Principal Objetivo:</b> O objetivo principal desta aplicação web, criada com o framework Sails.js, é criar uma plataforma robusta e eficiente, na qual o usuário pode interagir através de uma interface desenvolvida com HTML, CSS e Javascript. A interface amigável e responsiva proporcionará uma experiência fluida ao usuário, permitindo uma navegação intuitiva e agradável.

&nbsp;&nbsp;&nbsp;&nbsp;  A interface interage de forma dinâmica com uma API backend desenvolvida em Node.js, com arquitetura MVC e framework Sails.js. A API, que tem uma arquitetura moderna e escalável, permite uma comunicação eficiente entre o front-end e o banco de dados PostgreSQL. O Sails.js é capaz de gerenciar de forma eficiente e segura as operações de acesso e manipulação dos dados armazenados no banco.


&nbsp;&nbsp;&nbsp;&nbsp;  Dessa forma, a aplicação web oferece não apenas uma interface agradável e receptiva para os usuários finais, como também uma base sólida e confiável para o desenvolvimento e manutenção contínua da plataforma. Além disso, a modularidade e a extensão do Sails.js permitem a integração de novos recursos e funcionalidades, garantindo que a plataforma possa crescer e se adaptar às necessidades em constante evolução dos usuários e do mercado.


<b> Principais Módulos, Funcionalidades e Recursos:</b> 
&nbsp;&nbsp;&nbsp;&nbsp; - Autenticação de Usuários: Registro de novos usuários, login e logout de usuários, controle de acesso às funcionalidades da plataforma.

&nbsp;&nbsp;&nbsp;&nbsp; - Feed:
Publicação de ideias, classificação e filtragem de ideias por categorias ou tags, pesquisa avançada por ideias.

&nbsp;&nbsp;&nbsp;&nbsp; - Comunidade: um catálogo de ONGs cadastradas, com a visualização de dados detalhados sobre cada uma (missão, projetos e formas de contato), recursos para que os usuários se envolvam com as ONGs, como doações e voluntariado, lista de projetos para replicação, com objetivos, metodologia e recursos necessários.

## Diagrama
&nbsp;&nbsp;&nbsp;&nbsp; Para o diagrama da aplicação, foi pensado em quebrá-lo em duas partes: uma para a Landing Page e seus conteúdos e outra para a plataforma em si.
### Diagrama da Landing Page
<div align="center" width="100%">
 <sub>Figura 1: Diagrama da Landing Page</sub><br><br>
<img src = "../assets/MVC .drawio.png " alt="image" width="80%" height="auto"></div>


&nbsp;&nbsp;&nbsp;&nbsp; O usuário terá acesso à interação de input somente após efetuar login e cadastro. Em todas as outras páginas, a nossa API responderá somente às solicitações GET e às chamadas de endpoint para o frontend.

### Diagrama da Plataforma
&nbsp;&nbsp;&nbsp;&nbsp; Abaixo, o diagrama da nossa plataforma:
<div align="center" width="100%">
 <sub>Figura 1: Diagrama da Plataforma</sub><br><br>
<img src = "../assets/MVC Plataforma.drawio.png " alt="image" width="80%" height="auto"></div>

&nbsp;&nbsp;&nbsp;&nbsp; Ao acessar a plataforma, o usuário terá a oportunidade de interagir com o banco de dados, desde postagens até visualizações do feed e busca por ONGs, projetos similares e pessoas com interesses semelhantes.













