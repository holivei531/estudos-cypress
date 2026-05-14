# 📘 Cypress - Criando primeiro projeto

## 📌 Sobre este módulo

Este é o primeiro conteúdo do meu repositório de estudos em automação de testes.
Aqui abordo os conceitos iniciais do **Cypress**, incluindo o que é, para que serve e como iniciar um projeto do zero.

---

## 🚀 O que é o Cypress?

O **Cypress** é uma ferramenta moderna de automação de testes voltada principalmente para aplicações web.

Ele permite escrever, executar e debugar testes diretamente no navegador, oferecendo uma experiência simples e eficiente para desenvolvedores e QAs.

---

## 🎯 Para que serve o Cypress?

O Cypress é utilizado para:

* Automatizar testes end-to-end (E2E)
* Validar fluxos completos do usuário
* Testar APIs (requisições HTTP)
* Garantir qualidade em aplicações web
* Identificar bugs antes da produção

---

## ⚙️ Principais vantagens

* Execução rápida dos testes
* Interface gráfica intuitiva
* Debug facilitado (tempo real)
* Não necessita de WebDriver
* Ótima documentação oficial
* Suporte a testes modernos (SPA, APIs, etc.)

---

## 🛠️ Pré-requisitos

Antes de iniciar, você precisa ter instalado:

* Node.js (versão recomendada LTS)
* NPM ou Yarn
* Um editor de código (ex: VS Code)

---

## 📦 Passo a passo: Iniciando um projeto com Cypress

### 1. Criar a pasta do projeto

```bash
mkdir estudos-cypress
cd estudos-cypress
```

➡️ O comando mkdir (make directory) cria uma pasta que terá o nome estudos-cypress.

➡️ O comando cd (change directory) mudar de diretório/pasta, com ele entramos na pasta criada.

---

### 2. Inicializar o projeto Node

```bash
npm init -y
```

➡️ Este comando serve para inicializar um projeto `Node.js` automaticamente criando o arquivo `package.json`, responsável por gerenciar dependências e scripts do projeto.

---

### 3. Instalar o Cypress

```bash
npm install cypress 
```

➡️ Este comando serve para instalar o Cypress no seu projeto.

---

### 4. Abrir o Cypress pela primeira vez

```bash
npx cypress open
```

➡️ Esse comando irá:

* Criar a estrutura inicial do projeto
* Abrir a interface do Cypress

---

### 5. Estrutura criada automaticamente

Após abrir o Cypress, será gerada uma estrutura semelhante a:

```
cypress/
  ├── e2e/
  ├── fixtures/
  ├── support/
cypress.config.js
```

➡️ e2e: End-to-End (testes de ponta a ponta)
* É a pasta onde ficam os arquivos dos testes automatizados.

➡️ fixtures: dados fixos/mockados usados nos testes
* É a pasta onde ficam informações não verdadeiras usadas para testar.

➡️ support: erramentas auxiliares da automação
* É a pasta onde ficam configurações, comandos e reutilizações do Cypress

---

### 6. Executar testes

Modo interativo (interface):

```bash
npx cypress open
```

Modo headless (terminal):

```bash
npx cypress run
```
---

