# 📦 Nexus: Integração Logística Automatizada (ERP/WMS)

## 💡 Visão Geral do Projeto

O **Projeto Nexus (Integração Logística Automatizada)** visa resolver o problema crônico de **lançamentos manuais e erros de digitação** em processos logísticos, que resultam em planilhas eternas, divergência de números e retrabalho.

Esta solução consiste em desenvolver um sistema robusto de integração entre os módulos de Planejamento de Recursos Empresariais (ERP) e Sistema de Gerenciamento de Armazém (WMS), garantindo a sincronização automática e em tempo real de **Notas Fiscais, Pedidos e Status de Expedição**.

Este projeto foi desenhado para ser um caminho de evolução técnica, levando a equipe do conhecimento básico ao avançado nas tecnologias modernas, utilizando **Python** como linguagem principal.

## 🎯 Objetivos Principais

* **Eliminar Retrabalho:** Automatizar a entrada de dados do pedido/nota fiscal no estoque/expedição.
* **Consistência de Dados:** Garantir que ERP e WMS trabalhem com as mesmas informações em tempo real.
* **Rastreabilidade:** Fornecer visibilidade completa do status do pedido, desde a venda até a entrega.
* **Evolução da Equipe:** Utilizar uma arquitetura moderna e ferramentas avançadas (DevOps, Mensageria, Orquestração) para capacitar a equipe técnica.

## 🛠️ Stack Tecnológica

O projeto ILA é construído sobre uma arquitetura robusta e escalável.

| Componente | Tecnologia Principal | Uso Específico |
| :--- | :--- | :--- |
| **Back-end** | Python (Flask/Django) | API RESTful para manipulação de Pedidos e Notas. |
| **Banco de Dados** | PostgreSQL | Armazenamento persistente e transacional dos dados ERP/WMS. |
| **Comunicação** | RabbitMQ / Kafka | Troca de mensagens assíncrona e confiável entre ERP e WMS. |
| **Engenharia de Dados** | Apache Airflow, Python/Pandas | Orquestração do pipeline de integração ETL. |
| **Front-end** | React / Vue.js | Interface para visualização e cadastro de pedidos. |
| **DevOps** | Docker, Docker Compose, GitHub Actions | Containerização, ambientes locais e CI/CD. |

## 🚀 Como Executar o Projeto Localmente

Para iniciar o desenvolvimento, você precisará apenas do **Docker** e **Docker Compose** instalados.

1.  **Clone o Repositório:**
    ```bash
    git clone [LINK DO SEU REPOSITÓRIO]
    cd projeto-ila
    ```

2.  **Configurar Variáveis de Ambiente:**
    * Crie um arquivo `.env` na raiz do projeto e defina as variáveis de ambiente necessárias (credenciais do DB, chaves secretas, etc.).

3.  **Suba os Serviços com Docker Compose:**
    ```bash
    docker-compose up --build
    ```
    *Este comando irá construir as imagens e iniciar todos os serviços (Back-end, Front-end, DB, Mensageria).*

4.  **Acesse as Aplicações:**
    * **Back-end API:** `http://localhost:[PORTA_BACKEND]/api/v1/`
    * **Front-end:** `http://localhost:[PORTA_FRONTEND]`
    * **RabbitMQ Management:** `http://localhost:[PORTA_RABBITMQ]`

## 🛣️ Estrutura do Projeto e Próximos Passos

O projeto está organizado em **Épicos (Etapas 1-6)**, com tarefas específicas de Engenharia de Dados, Back-end, Front-end, DevOps e Cibersegurança.

**Consulte o quadro Trello para o *status* atual e os *checklists* detalhados de cada tarefa.**

Principais diretórios:
* `src/api_erp/`: Back-end da API principal (módulos ERP).
* `src/servico_wms/`: Serviço Python consumidor de mensagens (módulos WMS/Expedição).
* `src/data_integration/`: Scripts Python e DAGs do Airflow para ETL.
* `src/frontend/`: Código da aplicação web (Interface do Usuário).

---

## 🤝 Colaboradores

Abaixo está a lista de todos os colaboradores do Projeto Nexus. Por favor, adicione seu nome e função após ingressar na equipe.

| Nome | Função Principal | Contato (GitHub/LinkedIn) |
| José | Engenheiro de Dados | JoseVF5 |
| | | |
| | | |
| | | |
