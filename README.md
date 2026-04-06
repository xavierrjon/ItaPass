# 🎟️ ItaPass - Sistema de Venda de Ingressos de Futebol Local

## 📌 Sobre o projeto
Sistema para compra e venda de ingressos de jogos locais com QR Code e validação em entrada.

## 🚀 Funcionalidades

### 🔐 Autenticação

* Cadastro e login
* JWT com roles:

  * USER
  * ORGANIZER

### ⚽ Gestão de Jogos

* Criar jogo:

  * Time mandante
  * Time visitante
  * Data e horário
  * Estádio
* Editar jogo
* Listar jogos disponíveis

### 🏟️ Ingressos

* Tipos de ingresso:

  * Arquibancada
  * Cadeira
  * VIP
* Definir:

  * Preço
  * Quantidade
  * Setor

### 🛒 Compra de Ingressos

* Selecionar jogo
* Escolher setor
* Definir quantidade
* Adicionar ao carrinho
* Finalizar compra

### 🎫 Ingresso Digital

Cada ingresso terá:

* ID único
* QR Code
* Dados:

  * Jogo
  * Setor
  * Nome do comprador
* Status:

  * ATIVO
  * USADO
  * CANCELADO

### 📲 Validação (Entrada no Estádio)

* Tela de scanner (celular do organizador)
* Leitura do QR Code
---

## 🧠 Processo de Design (UI/UX)
👉 Veja o case completo: /docs/case-study.md

## 🛠️ Tecnologias
- React + Vite
- NestJS
- PostgreSQL

## 📸 Preview

## ▶️ Como rodar
