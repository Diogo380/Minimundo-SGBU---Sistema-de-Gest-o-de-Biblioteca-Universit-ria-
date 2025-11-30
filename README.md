# 📚 Projeto de Modelagem e Implementação SQL - Sistema de Gestão de Biblioteca Universitária (SGBU)

Este repositório contém os scripts SQL para a criação e manipulação do banco de dados do Minimundo "Sistema de Gestão de Biblioteca Universitária".

---

## 1. Visão Geral do Projeto

* **Minimundo:** Gestão de acervo, usuários, empréstimos e reservas de uma biblioteca universitária.
* **Modelo:** O modelo lógico final está na **Terceira Forma Normal (3FN)**, eliminando redundâncias e garantindo a integridade referencial através do uso de chaves primárias e estrangeiras.

## 2. Tecnologias Utilizadas

* **SGBD:** MySQL (Os scripts foram desenvolvidos com sintaxe MySQL. Ajustes podem ser necessários para PostgreSQL ou SQL Server.)
* **Ferramenta:** MySQL Workbench / pgAdmin
* **Linguagem:** SQL (DDL e DML)

## 3. Estrutura dos Scripts

O diretório `scripts/` contém a ordem de execução dos arquivos:

1.  **`01_ddl_criacao_tabelas.sql`**: Cria o banco de dados `SGBU_Biblioteca` e todas as 8 tabelas do modelo lógico (USUARIO, LIVRO, EMPRESTIMO, etc.) com suas chaves e restrições.
2.  **`02_dml_insercao_dados.sql`**: Insere dados iniciais de exemplo nas tabelas para simular o funcionamento da biblioteca (Comandos INSERT).
3.  **`03_dml_consultas_select.sql`**: Contém as consultas SQL solicitadas para avaliação, utilizando `JOIN`, `WHERE`, `ORDER BY`, `LIMIT` e `GROUP BY`.
4.  **`04_dml_update_delete.sql`**: Contém comandos de atualização e exclusão de dados com condições específicas (`UPDATE` e `DELETE`).

## 4. Instruções de Execução

1.  **Configuração:** Instale e configure o SGBD de sua preferência (Ex: MySQL Server).
2.  **Criação da Estrutura:** Execute o script `01_ddl_criacao_tabelas.sql`.
3.  **Povoamento do Banco:** Execute o script `02_dml_insercao_dados.sql`.
4.  **Testes:** Execute os scripts `03_dml_consultas_select.sql` e `04_dml_update_delete.sql` para testar a manipulação de dados e a integridade do sistema.

---

Com este conteúdo, você tem a base completa para finalizar a etapa de implementação SQL do seu projeto. Gostaria de revisar ou adicionar mais alguma consulta específica para o script de `SELECT`?
