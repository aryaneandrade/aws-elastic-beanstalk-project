# 🚀 Projeto Elastic Beanstalk com Docker 


![GitHub repo size](https://img.shields.io/github/repo-size/aryaneandrade/aws-elastic-beanstalk-project)
![GitHub stars](https://img.shields.io/github/stars/aryaneandrade/aws-elastic-beanstalk-project?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/aryaneandrade/aws-elastic-beanstalk-project)
![AWS](https://img.shields.io/badge/built%20with-AWS-orange?logo=amazonaws&logoColor=white)

Este repositório documenta todas as etapas do projeto prático desenvolvido durante a **Mentoria Desafio Labs 2.0** da Formação AWS, ministrada pelo **Henrylle Maia**. O foco foi trabalhar com aplicações gerenciadas, Docker e CDN na AWS, utilizando o serviço **Elastic Beanstalk** para deploy e gerenciamento da aplicação.

---

## 🧠 Objetivo

Criar uma aplicação Dockerizada, gerenciada via Elastic Beanstalk, com deploy automatizado, monitoramento, troubleshooting, integração com o Amazon ECR, variáveis de ambiente configuradas e comunicação com banco de dados no Amazon RDS, garantindo uma solução funcional, resiliente e escalável.

---

## 📊 Arquitetura da Solução

A arquitetura contempla:

- Aplicação Docker containerizada  
- Deploy e gerenciamento via **AWS Elastic Beanstalk**  
- Registro de imagem Docker no **Amazon ECR**  
- Banco de dados relacional no **Amazon RDS**  
- Monitoramento e logs via **AWS CloudWatch**  
- Automação com **shell scripts** para deploy e manutenção  

---

## 📌 Etapas do Projeto

### Fase 1 – Configuração e Deploy Inicial
- Criação da aplicação Docker e ambiente no Elastic Beanstalk  
- Configuração do pipeline de deploy via integração com Amazon ECR  

### Fase 2 – Monitoramento e Troubleshooting
- Análise detalhada de logs e métricas pelo CloudWatch  
- Resolução de problemas durante o deploy para garantir estabilidade  

### Fase 3 – Atualização e Rollback
- Atualização das versões da aplicação no Elastic Beanstalk  
- Implementação de rollback para versões anteriores quando necessário  

### Fase 4 – Automação e Configuração Avançada
- Desenvolvimento de scripts shell para automatizar processos de deploy e rollback  
- Configuração de variáveis de ambiente para gerenciamento seguro de configurações  
- Integração da aplicação com o banco de dados Amazon RDS para persistência de dados  

---

## 🛠️ Tecnologias e Serviços Utilizados

| Categoria      | Tecnologias                                                                 |
|----------------|------------------------------------------------------------------------------|
| Containers     | Docker, Amazon ECR, Elastic Beanstalk                                       |
| Banco de Dados | Amazon RDS                                                                  |
| Monitoramento  | AWS CloudWatch                                                              |
| Automação      | Shell Script                                                                |
| Segurança      | Configuração de variáveis de ambiente no Elastic Beanstalk                  |

---

## ✅ Resultados Obtidos

- Aplicação Dockerizada com deploy gerenciado pelo Elastic Beanstalk  
- Pipeline de integração com Amazon ECR para atualização contínua da aplicação  
- Monitoramento eficiente e troubleshooting com CloudWatch  
- Automação via shell scripts para agilizar deploys e rollback  
- Comunicação segura e persistência de dados com Amazon RDS  

---

## 📷 Capturas de Tela

### 🗂️ Arquitetura da Solução

![Arquitetura](assets/arquitetura.png)

---

### 🚀 Deploy da Aplicação no Beanstalk

![Ambiente Elastic Beanstalk](assets/ambiente.png)

---

### 💻 Aplicação em Execução

![Aplicação](assets/aplicacao.png)

---

### 🛠️ Execução das Migrations para Estruturação do Banco RDS

![Migrations](assets/migrates.png)

---

### 📊 Monitoramento do Ambiente de Desenvolvimento

![Monitoramento](assets/monitoramento.png)


---

## 📄 Licença

Este projeto foi desenvolvido exclusivamente para fins educacionais e não possui fins comerciais.

---

## 💬 Contato

Se quiser trocar ideias sobre aplicações gerenciadas na AWS, Docker, Elastic Beanstalk ou automatização com scripts, estou à disposição:

- LinkedIn: www.linkedin.com/in/aryane-andrade  
- Email: aryaneands@gmail.com  

---

> 🔥 Desenvolvido por Aryane, aplicando na prática os conhecimentos adquiridos na Formação AWS com Henrylle Maia, com foco em Docker, Elastic Beanstalk e automação.
