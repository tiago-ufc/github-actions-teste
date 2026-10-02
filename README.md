# Meu Projeto GitHub Actions

Este é um projeto simples criado para demonstrar e testar a execução de uma pipeline de CI/CD utilizando o **GitHub Actions**.

## Workflow configurado
O workflow realiza:
1. Trigger a cada `push` na branch principal (`main` ou `master`).
2. Checkout do repositório via `actions/checkout@v4`.
3. Configuração do ambiente Node.js via `actions/setup-node@v4`.
4. Execução de comandos no terminal (`ls -la`, `node index.js` e `echo`).
