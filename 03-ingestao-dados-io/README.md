# 03. Ingestao de Dados e IO Basico

**Nivel:** Essencial

## Objetivo

Introduzir operacoes de Entrada/Saida (I/O) basicas e manipulacao de listas. Ler arquivos de texto e transformar dados brutos em objetos Java.

## Contexto

Precisamos carregar os dados para analise, comecando devagar.

## Tarefa

1. Branch `tarefa/03-ingestao-dados`
2. Criar classe `TransactionIngestor` que recebe um arquivo e retorna `List<Transaction>`
3. Ler apenas as primeiras 1.000 linhas do CSV
4. Parsing manual da linha, instanciar Record `Transaction`
5. Classe `Main` que imprime as 10 primeiras transacoes importadas
