# 🚒 Sistema de Comunicação & Gestão Emergencial – ONG Brigada Caxinguelê

> **Status do Produto:** 🟡 Em Desenvolvimento Iterativo & Incremental  
> **Papel no Projeto:** Analista de Requisitos, Processos & Product Owner (PO)  
> **Contexto:** Projeto prático de Engenharia de Software e Gestão de TI desenvolvido em parceria com a ONG Brigada Voluntária Caxinguelê (Mairiporã-SP).

---

## 📌 Visão Geral do Produto
O projeto consiste na concepção, engenharia de requisitos, mapeamento de processos e especificação de um sistema multiplataforma focado em solucionar as lacunas de comunicação emergencial e centralizar o registro de ocorrências da Brigada Caxinguelê. 

A solução integra um aplicativo móvel operacional para brigadistas e moradores com um painel web administrativo para acompanhamento estratégico e geração de relatórios.

---

## 🛠️ Competências de Gestão & Análise Aplicadas
* **Gestão de Requisitos & Stakeholders:** Condução de entrevistas semiestruturadas com a liderança da ONG para levantamento de Requisitos Funcionais (RF), Não-Funcionais (RNF) e Regras de Negócio.
* **Mapeamento de Processos (BPMN):** Identificação de gargalos operacionais no cenário atual (*As-Is*) e proposição do fluxo de trabalho otimizado (*To-Be*).
* **Modelagem de Sistemas & Dados:** Especificação funcional através de Diagramas UML (Casos de Uso e Classes) e Modelagem Conceitual/Lógica de Banco de Dados Relacional (DER/MER).
* **Gestão Ágil & Backlog:** Organização do fluxo de trabalho e priorização de Sprints utilizando quadro Kanban no Trello.
* **Governança & LGPD:** Definição de políticas de privacidade, controle de acesso baseado em perfis (RBAC) e diretrizes para proteção de dados sensíveis.

---

## 📐 Entregáveis Técnicos & Artefatos de Análise

### 1. Mapeamento e Otimização de Processos (BPMN)
Análise detalhada do fluxo de comunicação operado entre moradores, administração e brigadistas:
* **Cenário Atual (*As-Is*):** Identificação de falhas no acionamento manual e perda de dados.  
  ![Mapeamento Inicial](./mapa-processo-inicial.png)
* **Cenário Proposto (*To-Be*):** Fluxo automatizado via plataforma digital.  
  ![Mapeamento Proposto](./mapa-processo-proposto.png)

---

### 2. Engenharia de Requisitos
Elicitação e documentação das necessidades do sistema e critérios de qualidade:
* **Requisitos Funcionais (RF):** Cadastro, login, mapa de alertas, gerenciamento de disponibilidade e atendimento.  
  ![Requisitos Funcionais](./requisitos-funcionais.png)
* **Requisitos Não-Funcionais (RNF):** Multiplataforma, rastreamento em segundo plano, otimização de consumo de dados e sessão.  
  ![Requisitos Não-Funcionais](./requisitos-nao-funcionais.png)
* **Requisitos de Segurança & LGPD:** Consentimento de localização GPS, criptografia e controle de acesso RBAC.  
  ![Requisitos de Segurança](./requisitos-seguranca.png)

---

### 3. Modelagem de Banco de Dados Relacional
Estruturação conceitual e lógica do banco de dados para garantir integridade e rastreabilidade dos registros:
* **Modelo Conceitual (DER):** Entidades, atributos e relacionamentos.  
  ![Modelo Conceitual DER](./modelo-conceitual-der.png)
* **Modelo Lógico:** Mapeamento de tabelas, chaves primárias (PK) e estrangeiras (FK) normalizadas.  
  ![Modelo Lógico](./modelo-logico.png)

---

### 4. Arquitetura Funcional & Diagramação UML
Detalhamento dos comportamentos e interações entre os atores e o sistema:
* **Diagrama de Casos de Uso:** Ações e permissões de Moradores, Brigadistas e Administradores.  
  ![Diagrama de Casos de Uso](./diagrama-caso-de-uso.png)
* **Diagrama de Classes:** Estrutura estática de entidades, atributos e métodos do sistema.  
  ![Diagrama de Classes](./diagrama-classes.png)

---

### 5. Gestão Ágil do Produto (Kanban / Trello)
Acompanhamento do ciclo de vida das entregas e detalhamento do backlog com critérios de aceite:
* **Visão Geral do Backlog:**  
  ![Quadro Kanban](./trello-kanban.png)
* **Especificação de Histórias & Critérios de Aceite:**  
  ![Card Detalhado](./trello-card-requisitos.png)

---

## 📖 Artigos Científicos & Publicações Acadêmicas

O projeto foi documentado e apresentado em artigos acadêmicos aprovados no Simpósio da Bacia do Juquery (SIMBAJU - FATEC):

1. 📄 [**Fase 1: Mapeamento do Processo Comunicacional da Brigada (III SIMBAJU - Junho/2025)**](./fase1-mapeamento-processos-bpmn.pdf)  
   * **Foco:** Diagnóstico situacional, Business Model Canvas, Personas, Mapas de Empatia e Mapeamento BPMN *As-Is*.
2. 📄 [**Fase 2: Modelagem de Engenharia de Software e Banco de Dados (IV SIMBAJU - Novembro/2025)**](./fase2-arquitetura-banco-dados.pdf)  
   * **Foco:** Elicitação de Requisitos, Diagramas UML (Casos de Uso e Classes), DER/MER e Prototipagem de Alta Fidelidade.
3. 📄 [**Fase 3: Especificação do MVP & Solução Multiplataforma (V SIMBAJU - Junho/2026)**](./fase3-especificacao-mvp-sistema.pdf)  
   * **Foco:** Validação de Requisitos de Segurança/LGPD, Arquitetura Multiplataforma, Geolocalização em Tempo Real e Dashboards de BI.

---

## 🚀 Roadmap de Evolução do Produto
* [x] **Ciclo 1:** Levantamento de requisitos, personas e mapeamento de processos *As-Is/To-Be*.
* [x] **Ciclo 2:** Diagramação UML, modelagem do banco de dados relacional e prototipagem no Figma.
* [x] **Ciclo 3:** Especificação do MVP funcional multiplataforma e painel administrativo.
* [ ] **Ciclo 4 (Em andamento):** Homologação de usabilidade com a equipe da Brigada Caxinguelê e moradores.
* [ ] **Ciclo 5:** Estudo de viabilidade de infraestrutura de nuvem, publicação e diretrizes finais de segurança.
