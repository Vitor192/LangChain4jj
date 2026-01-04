# 🚗 Projeto de Locadora de Carros com IA (LangChain4j)

Este projeto é uma aplicação desenvolvida em **Java 17** utilizando **Spring Boot**, com foco em **Arquitetura de Software integrada com Inteligência Artificial**.  
A aplicação simula os **cálculos e regras de negócio de uma locadora de veículos**, utilizando um **LLM (Gemini)** através do **LangChain4j** para apoiar decisões e interações inteligentes.

---

## 🧠 Tecnologias Utilizadas

- **Java 17**
- **Spring Boot**
- **LangChain4j**
- **LLM Gemini (Google)**
- **Arquitetura em Camadas**
- **API REST**
- **Maven**
- **Git / GitHub**

---

## 🏗️ Arquitetura do Projeto

O projeto segue os princípios de **Arquitetura Spring Boot**, separando bem as responsabilidades:

- **Controller** – Exposição das APIs REST
- **Service** – Regras de negócio da locadora
- **Config** – Configurações do LangChain4j e LLM
- **Integration IA** – Comunicação com o Gemini via LangChain4j

A Inteligência Artificial é utilizada para:
- Auxiliar nos **cálculos de locação**
- Interpretar regras de negócio
- Simular respostas inteligentes baseadas em contexto

---

## 🚘 Funcionalidades

- Simulação de **locação de veículos**
- Cálculo de valores com base em:
  - Tipo de veículo
  - Quantidade de dias
  - Regras de negócio
- Integração com **LLM Gemini** para respostas inteligentes
- API REST para consumo externo
- Estrutura preparada para expansão de novas regras e integrações com IA

---

## 🤖 Inteligência Artificial com LangChain4j

O **LangChain4j** é utilizado como camada de integração entre a aplicação Java e o **Gemini**, permitindo:

- Criação de prompts inteligentes
- Interpretação de regras de negócio
- Respostas dinâmicas baseadas em contexto
- Integração limpa e desacoplada com o Spring Boot

---

## ▶️ Como Executar o Projeto

### Pré-requisitos
- Java 17+
- Maven
- Chave de API do **Gemini**

### Passos
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

# Acesse o diretório do projeto
cd seu-repositorio

# Execute a aplicação
mvn spring-boot:run
