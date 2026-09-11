<div align="center">
📚 Sistema de Empréstimo de Livros

Sistema desenvolvido para organizar e aprimorar o processo de empréstimo, devolução e entrada de livros da biblioteca da Escola São Bernardo (ESB).

</div>
📖 Sobre o projeto

O Sistema de Empréstimo de Livros tem como objetivo organizar e facilitar o gerenciamento dos processos realizados pela biblioteca da Escola São Bernardo (ESB), com foco principalmente nos alunos dos cursos técnicos de Enfermagem e Farmácia.

Atualmente, parte dessas atividades é realizada manualmente, o que pode dificultar o controle dos empréstimos, devoluções, prazos, multas e entrada de novos exemplares.

A proposta do projeto é modelar e informatizar esses processos, tornando o gerenciamento dos livros mais organizado, eficiente e fácil de acompanhar.

🎯 Objetivos

O sistema tem como principais objetivos:

📚 Organizar o processo de empréstimo e devolução de livros;
📝 Registrar os empréstimos realizados;
📅 Controlar os prazos de devolução;
🔄 Permitir o controle das prorrogações;
💰 Identificar e controlar possíveis atrasos e multas;
📦 Facilitar o controle dos livros disponíveis no estoque;
📥 Organizar o processo de entrada de livros recebidos por doação;
🔎 Centralizar as informações relacionadas aos livros e empréstimos;
📊 Tornar os processos da biblioteca mais claros e fáceis de acompanhar.
⚙️ Principais funcionalidades

O sistema deverá contemplar funcionalidades relacionadas a:

👤 Cadastro e consulta de alunos;
📚 Cadastro e consulta de livros;
📖 Registro de empréstimos;
🔄 Registro de devoluções;
📅 Controle do prazo de devolução;
⏳ Controle de prorrogações;
💰 Controle de multas por atraso;
📦 Controle do estoque de livros;
📥 Registro da entrada de livros por doação;
🔎 Consulta da situação dos exemplares.

Observação: as funcionalidades poderão ser ampliadas ou modificadas conforme a evolução do projeto e o levantamento dos requisitos.

🔎 Processo de empréstimo

O processo começa quando um aluno procura um livro na biblioteca e solicita o empréstimo.

📚 Empréstimo
O aluno procura o livro na biblioteca.
A matrícula do aluno é verificada.
Caso esteja matriculado, é disponibilizada uma ficha de retirada.
O aluno preenche a ficha corretamente.
A situação e a disponibilidade do livro são verificadas.
O empréstimo é registrado.
O comprovante é entregue ao aluno.
⏰ Devolução

O prazo inicial para devolução do livro é de 7 dias.

Caso necessite de mais tempo, o aluno poderá solicitar uma prorrogação. O processo permite até 3 prorrogações.

No momento da devolução:

📕 A condição física do livro é verificada;
⚠️ Caso o exemplar esteja danificado, o aluno poderá ser solicitado a realizar a reposição;
📅 A data de devolução é conferida;
💰 Caso exista atraso, a multa correspondente é calculada;
📚 Após a conferência, o livro retorna ao estoque como disponível.
📦 Entrada de novos livros

O projeto também contempla o processo de entrada de livros provenientes de doações.

Quando uma editora manifesta interesse em realizar uma doação, os títulos disponíveis são catalogados e uma lista é preparada para avaliação.

O processo ocorre nas seguintes etapas:

📋 Catalogação dos títulos disponíveis;
📝 Preparação da lista para avaliação;
📩 Solicitação de autorização;
⏳ Aguardar aprovação;
🤝 Contato com os doadores;
📦 Separação e embalagem dos livros;
🧾 Emissão da nota de doação;
🚚 Envio dos livros para a biblioteca;
🔎 Recebimento e conferência dos exemplares;
📚 Classificação e catalogação;
🏷️ Etiquetagem dos livros;
📦 Entrada dos exemplares no estoque.
🔄 Modelagem do processo

O processo completo da biblioteca foi modelado utilizando a notação BPMN (Business Process Model and Notation).

O diagrama representa as principais etapas envolvidas nos processos de empréstimo, devolução e entrada de novos livros.

<div align="center">

</div>
📋 Regras de negócio

Entre as principais regras identificadas durante o levantamento do processo estão:

Regra	Descrição
📅 Prazo de empréstimo	O prazo inicial para devolução é de 7 dias.
🔄 Prorrogação	O empréstimo pode ser prorrogado até 3 vezes.
📕 Conservação	A condição do livro deve ser verificada no momento da devolução.
💰 Atraso	Livros devolvidos após o prazo estão sujeitos à aplicação de multa.
📦 Estoque	Após a devolução e conferência, o exemplar retorna ao estoque.
📥 Doação	Livros recebidos por doação devem passar por conferência, classificação e catalogação antes de entrarem no estoque.
🛠️ Tecnologias

Esta seção pode ser atualizada conforme as tecnologias utilizadas no desenvolvimento.

Linguagem: A definir
Banco de dados: A definir
Framework: A definir
Modelagem: BPMN
Documentação: Microsoft Word
📁 Estrutura da documentação

Os principais documentos utilizados durante o desenvolvimento do projeto estão disponíveis neste repositório:

📄 Documentação do projeto — escopo e informações levantadas durante o desenvolvimento;
🔄 Diagrama BPMN — representação visual dos processos da biblioteca.
👥 Equipe
Integrante
Enzo Alexandrino
Kauã Vinícius
João Pedro
Matheus Duque
Mauro Sena
🚧 Status do projeto
<div align="center">
🚧 Em desenvolvimento

O projeto encontra-se em fase de levantamento, documentação e modelagem dos processos da biblioteca.

</div>
📌 Próximos passos
 Finalizar o levantamento de requisitos;
 Validar as regras de negócio;
 Definir a arquitetura do sistema;
 Definir as tecnologias utilizadas;
 Modelar o banco de dados;
 Desenvolver as funcionalidades principais;
 Realizar testes;
 Documentar a utilização do sistema.
