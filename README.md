# Projeto de PSET SI1N-UVV

* **Aluno:** Caíque Almeida Amaral
* **Matrícula:** 202305874
* **Professor:** Abrantes Araujo Silva Filho
* **Turma:** SI1N
* **Monitora:** Suellen Miranda

### Estrutura de Diretórios
- **pset1**
  - **[si1n_202305874_postgresql.architect](./uvv_bd1_uvv/pset1/si1n_202305874_postgresql.architect)**
  - **[si1n_202305874_postgresql.pdf](./uvv_bd1_uvv/pset1/si1n_202305874_postgresql.pdf)**
  - **[si1n_202305874_postgresql.sql](./uvv_bd1_si1n/pset1/si1n_202305874_postgres.sql)**

### O PSET
Um Problem Set (PSET) é um conjunto de problemas e tarefas difíceis (alguns
extremamente difíceis) que o forçarão a estudar e realmente compreender a matéria.
Esse trabalho consiste em um PSET com objetivo de implementar um banco de dados no PostgreSQL, a partir de um diagrama relacional, e escrever códigos SQL para gerar diversos relatórios.

* Banco de Dados = 'uvv'
* Esquema Lógico = 'lojas'

### Diagrama Relacional
A partir do **SQL Power Architect** criei todas as tabelas e seus atributos incluindo comentários, criando chaves primárias, cardinalidades, relacionamentos, chaves estrangeiras e chaves compostas. Os arquivos gerados foram:

* **[arquivo.architect](./uvv_bd1_uvv/pset1/si1n_202305874_postgresql.architect)** consiste no código para rodar o diagrama dentro do Software.
* **[arquivo.pdf](./uvv_bd1_uvv/pset1/si1n_202305874_postgresql.pdf)** consiste em um arquivo PDF com uma imagem do diagrama.

### Implementação do banco de dados no PostgreSQL
A implementação do banco de dados foi feita no **PostgreSQL**, o sistema de gerenciamento de bancos de dados open source mais avançado que existe atualmente. Todo o passo a passo está descrito no **script.sql**, o qual está comentado e organizado de forma que qualquer leitor possa compreender cada comando usado.

* Caso queira testa-lo em seu terminal Linux é necessário usar o seguinte comando:

```
psql -U postgres < si1n_202305874_postgresql.sql 
```

### Comandos PostgreSQL

| Sintaxe do Comando  | Ação                       |
|---------------------|----------------------------|
| DROP DATABASE       | Apagar Banco de Dados      |
| DROP USER           | Apagar Usuário             |
| CREATE DATABASE     | Criar Banco de Dados       |
| CREATE USER         | Criar Usuário              |
| SET ROLE            | Define o Usuário Corrente  |
| SET SEARCH_PATH     | Alterar o Esquema Padrão   |
| CREATE TABLE        | Criar Tabela               |
| CREATE SCHEMA       | Criar Esquema Lógico       |
| ALTER TABLE         | Alterar tabela             |
| ADD CONSTRAINT      | Adicionar Restrição        |
| COMMENT ON DATABASE | Comentar Banco de Dados    |
| COMMENT ON TABLE    | Comentar Tabela            |
| COMMENT ON COLUMN   | Comentar Coluna            |
