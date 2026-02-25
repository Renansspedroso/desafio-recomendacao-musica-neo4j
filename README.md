# 🎵 Sistema de Recomendação de Músicas com Neo4j

Este repositório contém a entrega do desafio prático de modelagem de grafos e criação de um motor de recomendação utilizando **Neo4j** e **Cypher**.

## 🎯 Objetivo do Projeto
Desenvolver um sistema de recomendação de músicas capaz de identificar padrões de escuta (playCount) e sugerir novas faixas ou artistas aos usuários aplicando conceitos de **Filtragem Colaborativa**.

## 🗂️ Estrutura do Repositório

* **Imagens do Grafo**: Diagramas visuais construídos no Arrows.app mapeando as entidades (`User`, `Song`, `Artist`, `Genre`) e seus relacionamentos (`LISTENED_TO`, `LIKED`, `FOLLOWS`, `PERFORMED_BY`, `IN_GENRE`).
* **`recomendacao_musica.cypher`**: Script completo de banco de dados contendo:
  1. Criação de Constraints (regras de unicidade).
  2. População de dados simulando usuários, artistas de Rock/Pop e volume de reproduções (`playCount`).
  3. **Query de Recomendação**: Consulta avançada em Cypher que recomenda artistas baseando-se no que usuários com gosto musical similar estão ouvindo.

## 🚀 Tecnologias Utilizadas
* Neo4j (AuraDB)
* Cypher Query Language
* Graph Data Modeling
