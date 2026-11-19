# 09. Persistencia em Banco com JDBC

**Nivel:** Intermediario

## Objetivo

Conectar a aplicacao Java a um banco de dados real (MySQL) usando JDBC padrao. Insercoes em lote (Batch) para performance.

## Contexto

Transacoes devem ir para o MySQL.

## Tarefa

1. Branch `tarefa/09-jdbc`
2. Definir `docker-compose.yml` e subir MySQL com Docker
3. Criar `script.sql` com tabela `TRANSACTIONS`
4. Adicionar driver MySQL no `pom.xml`/`build.gradle`
5. Criar `TransactionSQLRepository` implementando `TransactionRepository`
6. Classe `DBMain` que le CSV e insere no banco (10 mil transacoes), medindo tempo
