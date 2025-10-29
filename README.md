# 💾 Sistema de Integração ERP/WMS: "Nexus"

## 🌟 Sobre o Projeto

O **Nexus** é um projeto de desenvolvimento de software em grupo, focado em aprimorar conhecimentos em Python, Devops, Engenharia e Arquitetura de Dados, e Cibersegurança.

Nosso principal objetivo é solucionar o problema de **lançamentos manuais e erros de digitação** em sistemas de gestão. Desenvolveremos uma solução de API que simula a integração automática entre módulos de Pedidos, Notas Fiscais e Expedição (características de um ERP/WMS), garantindo a consistência e a rastreabilidade dos dados.

### 🎯 Problema & Solução
| Problema | Solução |
| :--- | :--- |
| Planilhas manuais, divergência de números e retrabalho operacional. | Desenvolvimento de uma **API (Python)** para integração automática entre os dados de Pedidos, Notas e Expedição, com validação de dados robusta. |

## 🛠️ Tecnologias Principais

| Categoria | Tecnologia | Justificativa |
| :--- | :--- | :--- |
| **Linguagem Principal** | Python 3.x | Foco no aprendizado de *frameworks* robustos de Backend e análise de dados. |
| **Backend/API** | FastAPI / Flask (a ser definido) | Alto desempenho e facilidade para criação de endpoints. |
| **Banco de Dados** | PostgreSQL (Pode ser simulado com SQLite/Docker para dev) | Robusto, amplamente utilizado em ambientes corporativos e com bom suporte a Python. |
| **Metodologia Ágil**| Scrum/Kanban (Gerenciado no Trello) | Para garantir a transparência, inspeção e adaptação do desenvolvimento. |

## 📋 Estrutura de Desenvolvimento e Metodologia Ágil

Este projeto segue uma abordagem ágil, utilizando o Trello para gerenciar o fluxo de trabalho.

### Fases do Projeto (Listas no Trello)

1.  **Backlog do Produto:** Ideias e funcionalidades priorizadas.
2.  **Iniciação e Planejamento:** Setup do ambiente e arquitetura.
3.  **Em Desenvolvimento (Sprint/Doing):** Tarefas ativas (foco no Python/Backend).
4.  **Testes e Qualidade (QA):** Validação de funcionalidades.
5.  **Pronto para Produção:** Funcionalidades aprovadas.
6.  **Concluído (Done):** Entregas finalizadas.
7.  **Robustez e Melhorias Avançadas:** Foco em escalabilidade e práticas profissionais (DevOps, Microsserviços, Observabilidade).

### Áreas de Conhecimento Envolvidas

| Área | Foco de Atuação |
| :--- | :--- |
| **Backend (Python)** | Lógica de Negócio, Criação da API, Testes Unitários. |
| **Engenharia de Dados** | Mapeamento ORM, ETL/Transformação de Dados de Entrada, Logging. |
| **Arquitetura de Dados** | Modelagem do DB, Otimização de *Queries*, Estrutura de Cache. |
| **Front-End** | Dashboard de Visualização, Telas de Consulta (se aplicável ao MVP). |
| **DevOps** | CI/CD, Containerização (Docker), Automação de Infraestrutura. |
| **Cibersegurança** | Autenticação (JWT), Validação de Input, Varredura de Vulnerabilidades. |

## 🚀 Como Executar o Projeto Localmente

### 📌 Pré-requisitos

* Python 3.8+
* Docker e Docker Compose (recomendado para replicar o ambiente de produção)
* Git

### ⚙️ Instalação e Configuração

1.  **Clone o Repositório:**
    ```bash
    git clone [LINK DO REPOSITÓRIO]
    cd nexus
    ```

2.  **Configuração do Ambiente (Recomendado via Docker):**
    ```bash
    # Levanta a aplicação, o banco de dados e dependências
    docker-compose up --build
    ```
    *Se estiver usando virtual environment (venv) localmente:*
    ```bash
    python -m venv venv
    source venv/bin/activate #ou .\venv\Scripts\activate no Windows
    pip install -r requirements.txt
    ```

3.  **Acesso:**
    * **Backend/API:** `http://localhost:[PORTA_BACKEND]`
    * **Documentação da API (Swagger/OpenAPI):** `http://localhost:[PORTA_BACKEND]/docs`
    * **Frontend/Dashboard:** `http://localhost:[PORTA_FRONTEND]` (Se o Front-End for implementado)

## ✅ Executando os Testes

Para garantir que todas as funcionalidades e a lógica de integração estejam corretas:

```bash
# Rodar todos os testes unitários e de integração (Pytest)
pytest
```
---

## 🤝 Colaboradores

Abaixo está a lista de todos os colaboradores do Projeto Nexus.

| Nome | Função Principal | Contato (GitHub/LinkedIn) |
| :--- | :--- | :--- |
| José | Engenheiro de Dados | JoseVF5 |
| Lucas| Backend | lc-dev2558 |
| Paulo| BackEnd | Aeziyr |
| | | |
