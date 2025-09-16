# Controle-de-Gastos-com-Spring-Boot-e-HTMX
Arquivos do projeto controle de gastos
Claro! Um bom arquivo README para um projeto no GitHub deve ser claro, conciso e fornecer todas as informações necessárias para que outros desenvolvedores entendam e possam rodar o projeto. Aqui está um modelo que você pode adaptar para o seu projeto de Controle de Gastos com Spring Boot e HTMX.

💰 Controle de Gastos
Aplicativo de gerenciamento financeiro pessoal construído com Spring Boot para o backend e HTMX para um frontend dinâmico e eficiente, sem a necessidade de JavaScript complexo.

🚀 Visão Geral
Este projeto oferece uma solução simples e eficaz para o controle de gastos pessoais. Ele permite que os usuários registrem receitas e despesas, categorizem transações e visualizem um resumo financeiro. A principal característica é a utilização do HTMX, que proporciona uma experiência de usuário semelhante à de uma SPA (Single Page Application) ao atualizar partes da página de forma dinâmica, mas com a simplicidade de renderização no lado do servidor (Server-Side Rendering - SSR).

🛠️ Tecnologias
Backend:

Spring Boot: Framework robusto para o desenvolvimento rápido e eficiente de aplicações Java.

Spring Data JPA: Para a persistência de dados.

Thymeleaf: Motor de template para renderizar o HTML dinamicamente no backend.

Frontend:

HTMX: Biblioteca que permite acessar recursos modernos como AJAX diretamente no HTML, mantendo a arquitetura server-side.

HTML & CSS: A base da interface do usuário.

Banco de Dados:

H2 Database (ou o banco de dados de sua preferência): Configurado para ser um banco de dados em memória para desenvolvimento, mas pode ser facilmente substituído.

⚙️ Pré-requisitos
Para rodar este projeto localmente, você precisa ter o seguinte instalado:

Java 17+

Maven ou Gradle (o projeto utiliza Maven, mas é facilmente adaptável para Gradle).

🏃 Como Rodar o Projeto
Clone o repositório:

Bash

git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Compile e rode o aplicativo com Maven:

Bash

./mvnw spring-boot:run
Se você estiver no Windows, use:

Bash

mvnw.cmd spring-boot:run
Acesse a aplicação:

Após a inicialização, a aplicação estará disponível em http://localhost:8080.

🗺️ Funcionalidades
CRUD de Transações: Adicione, edite e remova receitas e despesas.

Categorização: Associe transações a categorias (ex: Alimentação, Transporte, Lazer).

Dashboard: Visão geral dos gastos e receitas por período.

Interface Dinâmica com HTMX: Ações como adicionar uma nova transação ou deletar um item atualizam a página instantaneamente, sem a necessidade de um refresh completo.

📝 Contribuições
Contribuições são sempre bem-vindas! Se você tiver alguma ideia para melhorar o projeto, encontrou um bug ou deseja adicionar uma nova funcionalidade, sinta-se à vontade para abrir uma issue ou enviar um pull request.
Feito por Rafael Bavaresco Messias Moura.

📄 Licença
Este projeto está licenciado sob a Licença MIT.
