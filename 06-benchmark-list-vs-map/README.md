# 06. Benchmark de Busca: List vs Map

**Nivel:** Essencial

## Objetivo

Demonstrar a importancia da escolha da estrutura de dados correta. Comparar O(n) de Listas contra O(1) de Mapas em grandes volumes.

## Contexto

Otimize a busca por transacoes.

## Tarefa

1. Branch `tarefa/06-benchmark`
2. Carregar 100.000 transacoes
3. Criar `TransactionListRepository` com busca por nome do cliente retornando `Optional<Transaction>`
4. Medir tempo de busca com `System.nanoTime()` para o pior caso
5. Abstrair `TransactionRepository` como interface
6. Criar implementacao com `Map<String, Transaction>` e comparar tempos
