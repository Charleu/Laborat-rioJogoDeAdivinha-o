# 🎮 Jogo de Adivinhação - Projeto Serverless com AWS

Este repositório contém um laboratório prático desenvolvido como parte da formação Developer Associate da [Escola da Nuvem](https://escoladanuvem.org/). O objetivo foi criar uma aplicação **serverless** utilizando serviços da AWS para implementar um jogo de adivinhação, com backend em Python e frontend estático hospedado na nuvem.

---

## 🚀 Tecnologias e Serviços Utilizados

- **AWS Lambda** – Função com a lógica do jogo em Python  
- **Amazon API Gateway** – Exposição de rotas para acesso à Lambda  
- **Amazon S3** – Hospedagem do frontend estático (HTML/CSS/JS)  

---

## 📚 O que foi aprendido

### 🧠 AWS Lambda
- Criação e implantação de funções Lambda com Python
- Upload do código via arquivo `.zip`
- Compreensão de conceitos como **tempo de execução** e **ARN (Amazon Resource Name)**

### 🌐 Amazon API Gateway
- Criação de uma API HTTP para acionar a função Lambda
- Definição de **rotas** e métodos HTTP (como `GET`)
- Gerenciamento de **estágios** (ex: `prod`)
- Configuração de **CORS** para permitir chamadas de diferentes origens

### 🗂️ Amazon S3
- Publicação de um site estático (`index.html`) em um bucket S3
- Criação e configuração de buckets com nomes globais únicos
- Habilitação da **hospedagem estática**
- Ajustes de permissões para acesso público ao conteúdo
- Criação de políticas de bucket para liberar acesso com `s3:GetObject`

---

## 🔗 Integração dos Serviços

A arquitetura da aplicação foi totalmente serverless e integrada da seguinte forma:



Habilitação da hospedagem estática

Ajustes de permissões para acesso público ao conteúdo

Criação de políticas de bucket para liberar acesso com s3:GetObject

🔗 Integração dos Serviços
