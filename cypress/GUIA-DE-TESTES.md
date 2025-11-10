# 🧪 Testes automatizados com Cypress

Este projeto contém testes automatizados de ponta a ponta (E2E) utilizando o [Cypress](https://www.cypress.io/), criados como parte do curso **Cypress do Zero à Nuvem**.

---

## 🚀 Pré-requisitos

Antes de começar, verifique se você tem instalado em sua máquina:

- [Node.js](versão v20.19.5)

---

## ▶️ Como executar os testes

Antes de rodar os testes, instale as dependências do projeto:

```bash
npm install

🧭 Abrir o Cypress em modo interativo

Abre a interface do Cypress, permitindo escolher os testes manualmente:

npm run cy:open

📱 Abrir o Cypress em modo mobile

Abre o Cypress simulando um dispositivo móvel com resolução 410x860:

npm run cy:open:mobile

⚙️ Executar os testes no modo headless

Executa todos os testes diretamente no terminal (sem abrir o navegador):

npm run test
