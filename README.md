# blockChain-Clojure
# 💰 Gerenciador Financeiro baseado em Blockchain em Clojure

## 📌 Sobre o Projeto

Este projeto combina a tecnologia **blockchain** com a elegância da **programação funcional em Clojure** para criar um gerenciador financeiro **seguro**, **imutável** e **transparente**.

A aplicação permite registrar transações financeiras (receitas e despesas) em uma **blockchain**, garantindo a **integridade** dos dados e prevenindo alterações maliciosas.

---

## 🧰 Tecnologias Utilizadas

O projeto é desenvolvido em **Clojure**, uma linguagem funcional que roda na **Java Virtual Machine (JVM)**.  
Principais tecnologias e bibliotecas utilizadas:

- **Clojure 1.10.0** – Linguagem de programação funcional
- **Ring 0.12.5** – Framework para aplicações web
- **Compojure 1.6.1** – Biblioteca de roteamento para web
- **Cheshire 5.8.1** – Manipulação de JSON
- **Java Security** – Utilizada para SHA-256 (hash criptográfico)

---

## 🧱 Arquitetura

O projeto é modularizado em diferentes namespaces:

- `blockchain.clj`: Lida com a criação e validação de blocos, cálculo de hash, e estrutura da blockchain.
- `transacoes.clj`: Responsável pela lógica de transações financeiras (validação, tipos e valores).
- `db.clj`: Gerencia a persistência dos dados locais (em memória ou arquivos).
- `handler.clj`: Define as rotas e trata requisições HTTP via API REST.

---

## 🚀 Como Executar

### ✅ Pré-requisitos

- [Leiningen](https://leiningen.org/) instalado

### 📥 Clonando o Projeto


git clone https://github.com/IgorLucianoVV/blockChain-Clojure.git
cd blockChain-Clojure

### ▶️ Executando o Servidor
- lein ring serve
