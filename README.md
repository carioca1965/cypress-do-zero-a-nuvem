🧪 Cypress - Projeto de Testes Automatizados
Este é um projeto de testes automatizados end-to-end desenvolvido com o Cypress, como parte do curso “Cypress do Zero à Nuvem” da escola Talking About Testing.
Ele automatiza os testes da aplicação Central de Atendimento ao Cliente TAT (CAC TAT).

✅ Pré-requisitos
Antes de iniciar, você precisa ter os seguintes softwares instalados em sua máquina:

Node.js (versão 16 ou superior recomendada)

npm (gerenciador de pacotes que já vem com o Node.js)

Git (para clonar o projeto)

Visual Studio Code (opcional, mas recomendado)

⚙️ Instalação do Projeto
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Instale as dependências:


📁 Estrutura do curso
cypress-do-zero-a-nuvem/
├── cypress/
│   ├── e2e/
│   │   ├── CAC-TAT.cy.js         # Testes do formulário principal
│   │   └── privacyPolicy.cy.js   # Testes da página de política de privacidade
│   ├── fixtures/                 # (opcional) dados mockados
│   ├── support/                  # comandos personalizados
├── src/
│   ├── index.html
│   ├── privacy.html
├── package.json
├── cypress.config.js
└── README.md
📌 Informações Adicionais
Os testes utilizam comandos personalizados e boas práticas ensinadas durante o curso.

Os testes de mobile utilizam viewportWidth=410 e viewportHeight=860.

O projeto pode ser estendido com testes para diferentes navegadores ou CI/CD.

👨‍💻 Autor
Carlos Eduardo Pereira Pedroza
📧 carloseduardo391@hotmail.com