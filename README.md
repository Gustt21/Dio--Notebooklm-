# Dio--Notebooklm-

# 🚀 Miniguia de Estudos: Microserviços & Serverless com NotebookLM

Bem-vindo ao meu repositório de estudos! Este projeto foi desenvolvido como parte do desafio da **DIO**, com o objetivo de demonstrar como a Inteligência Artificial (utilizando o NotebookLM) pode ser uma aliada poderosa na curadoria de conhecimento e na aprendizagem ativa.

## 📌 Contexto e Objetivos

O avanço das aplicações em nuvem exige que desenvolvedores compreendam não apenas o código, mas a infraestrutura que o sustenta. Escolhi o tema **Microserviços e Serverless** por ser o pilar da escalabilidade moderna.

**Objetivos de Estudo:**
1. Compreender as diferenças fundamentais entre arquiteturas monolíticas, microserviços e serverless.
2. Identificar casos de uso ideais para funções serverless (FaaS).
3. Analisar os desafios de monitoramento e comunicação em sistemas distribuídos.

---

## 📚 Curadoria de Fontes

Para alimentar o NotebookLM e garantir respostas precisas, selecionei as seguintes fontes de alta autoridade:

1.  **[Microservices Guide - Martin Fowler](https://martinfowler.com/articles/microservices.html):** O artigo seminal que define o conceito.
2.  **[AWS Whitepaper - Serverless Architectures](https://docs.aws.amazon.com/whitepapers/latest/serverless-architectures-lambda/serverless-architectures-lambda.pdf):** Visão técnica e prática da maior provedora de cloud.
3.  **[The Twelve-Factor App](https://12factor.net/pt_br/):** Metodologia para construir aplicações SaaS resilientes.
4.  **[Google Cloud - Microservices Architecture](https://cloud.google.com/learn/what-is-microservices-architecture):** Guia de implementação e benefícios.

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

Abaixo, documento a evolução da minha interação com a IA. Note que o segredo não é a primeira pergunta, mas o refinamento.

### 🧪 O Processo de Refinamento
| Tentativa | Prompt Utilizado | Resultado/Problema | Ajuste Feito |
| :--- | :--- | :--- | :--- |
| **#1** | "O que são microserviços?" | Resposta genérica, estilo Wikipédia. | Solicitei comparação técnica. |
| **#2** | "Compare microserviços com monolitos citando as fontes fornecidas." | Melhorou, mas faltou profundidade em custos. | Pedi uma tabela de trade-offs. |
| **#3** | "Crie um guia de decisão: Quando usar Serverless vs Microserviços?" | **Sucesso!** Resposta estruturada com critérios de latência e custo. | N/A |

> **💡 Cicatriz de Aprendizado (Troubleshooting):**
> Inicialmente, a IA confundiu "Serverless" com "Hospedagem Grátis". Tive que reforçar, via prompt, que o foco era o modelo de execução **Event-Driven** e a abstração da infraestrutura, não apenas o custo zero em camadas gratuitas.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado
* **Microserviços:** Conjunto de serviços autônomos, cada um focado em uma regra de negócio, comunicando-se via APIs ou Mensageria. Ideal para sistemas complexos e grandes times.
* **Serverless:** Modelo onde o provedor de nuvem gerencia a alocação de recursos. O desenvolvedor foca apenas na função. Vantagem: *Scale-to-zero* (paga-se apenas pelo uso).

### 2. Glossário de Conceitos-Chave
* **API Gateway:** Ponto de entrada único que gerencia requisições e as distribui para os microserviços.
* **Cold Start:** O atraso que ocorre quando uma função serverless é invocada após um período de inatividade.
* **Idempotência:** Propriedade de uma operação que pode ser aplicada várias vezes sem alterar o resultado além da primeira aplicação (crucial em sistemas distribuídos).
* **Observabilidade:** Capacidade de medir o estado interno do sistema através de logs, métricas e tracing.

### 3. Prompts Reutilizáveis para Revisão
* *"Explique o conceito de Saga Pattern para um desenvolvedor júnior usando uma analogia de restaurante."*
* *"Com base nos documentos, quais são os 3 principais riscos de segurança em arquiteturas serverless?"*
* *"Gere 5 perguntas de múltipla escolha sobre orquestração de containers para testar meu conhecimento."*

---
