# 🌟 CI/CD Portfolio - Pipeline com GitHub Actions 🌟

Este projeto demonstra a criação de um pipeline de CI/CD utilizando **GitHub Actions**. O pipeline executa um script Python simples e valida o fluxo de integração contínua.


## 📝 Visão Geral

O objetivo deste projeto é demonstrar como configurar um pipeline de CI/CD utilizando GitHub Actions. O fluxo inclui:
- **Checkout do código:** Recupera a versão mais recente do repositório.
- **Configuração do ambiente:** Instala e configura o Python.
- **Execução da aplicação:** Roda um script que imprime "Hello, DevOps!".

Este projeto é ideal para iniciantes que desejam aprender os conceitos básicos de automação de pipelines e para aqueles que buscam demonstrar habilidades em **DevOps**.


## 🔧 Tecnologias Utilizadas

- **GitHub Actions:** Plataforma de automação e CI/CD integrada ao GitHub.
- **Python 3.9:** Linguagem utilizada para a aplicação simples.
- **Git:** Sistema de controle de versão.
- **VS Code:** Editor de código (opcional, mas recomendado).


## 📂 Estrutura do Projeto

ci-cd-portfolio/
├── app.py              # Script principal que imprime a mensagem
├── .github/
│   └── workflows/
│       └── ci.yml      # Workflow do GitHub Actions
└── README.md           # Documentação do projeto


## 🚀 Como Utilizar

1. **Clone o repositório**
    - git clone https://github.com/Almeidaladson/ci-cd-portfolio.git
    - cd ci-cd-portfolio

2. **Acompanhe a execução do pipeline** 
    - Navegue até a aba Actions no repositório do GitHub e observe a execução do pipeline em tempo real.


## 📚 Aprendizados e Melhorias Futuras

- **Aprendizados**
    - Configuração de pipelines básicos com GitHub Actions.
    - Estruturação de workflows para automatização de tarefas.

- **Melhorias Futuras**
    - Adicionar testes unitários utilizando o framework unittest
    - Incluir etapas de deploy (por exemplo, deploy para um ambiente de testes ou container).
    - Documentar de forma mais detalhada cada etapa do pipeline com exemplos visuais (prints da aba Actions).