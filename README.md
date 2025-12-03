# 📽️ Desafio da DIO: Modelagem de Dados em Grafos de um Serviço de Streaming

Este projeto foi desenvolvido como parte de um desafio da DIO para criação de um **grafo de conhecimento** utilizando **Neo4j Aura**, **Cypher** e a ferramenta **arrows.app** para modelagem visual.
O objetivo é projetar o banco de dados de um novo serviço de streaming, com foco na estrutura de relacionamentos que permite implementar um **sistema de recomendação** de filmes e séries.

---

## 🧩 Tarefas

Modelar e criar um grafo que represente:

### **🟦 Entidades (Nós)**

* `User`
* `Movie`
* `Serie`
* `Genre`
* `Actor`
* `Director`

### **🟧 Relacionamentos**

* `WATCHED` (com propriedade `rating`)
* `ACTED_IN`
* `DIRECTED`
* `IN_GENRE`

### **🔧 Entregáveis**

1. **Diagrama ou esboço do modelo de grafo** (criado no arrows.app e exportado como imagem)
2. **Script Cypher**, contendo:

   * Constraints únicas para cada Label
   * Criação de pelo menos **10 exemplos** para cada Label
   * Relacionamentos coerentes entre os nós

#### Disponíveis em: https://github.com/clauke/dio-neo4j-streaming/tree/main/assets
---

## 🧱 Modelagem do Grafo

A modelagem foi feita no **arrows.app**, seguindo boas práticas:

* Labels em **singular** (ex.: `Movie` em vez de `Movies`)
* Propriedades significativas para cada entidade
* Relacionamentos direcionados e nomeados
* Uso padronizado de IDs únicos (ex.: `userId`, `movieId`)

Após a finalização do diagrama, ele foi exportado como **PNG** e incluído na entrega.

---

## 🧾 Script Cypher

O script inclui:

✔ Criação de **constraints**
✔ Criação de **exemplos reais** de filmes, séries, gêneros, atores e diretores
✔ Criação de **usuários** com avaliações reais
✔ Conexões entre os dados para simular um sistema de recomendação

O script foi totalmente revisado e executado no **Neo4j Aura**, garantindo compatibilidade.

---

## 🚀 Tecnologias Utilizadas

* **Neo4j Aura**
* **Cypher**
* **arrows.app**
* **readme.so**
---

## 🎯 Conclusão

O projeto atinge todos os requisitos do desafio:

* Grafo modelado visualmente
* Script Cypher funcional e completo
* Dados realistas e coerentes
* Estrutura preparada para análises e recomendações
* Uso correto de constraints, relações e boas práticas de modelagem Neo4j

---

##📌 Como Executar

Acesse sua instância no Neo4j Aura, copie e cole o script Cypher disponibilizado.
