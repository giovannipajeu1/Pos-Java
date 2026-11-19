# 10. Ingestao de Dados Completa (e Eficiente)

**Nivel:** Desafio

## Objetivo

Limitar o uso de memoria usando Streams e maximizar o uso do hardware com programacao concorrente e paralela.

## Contexto

Processar o arquivo PaySim completo (6 milhoes de linhas) de forma sequencial e carregando tudo na memoria e inaceitavel.

## Tarefa

1. Branch `tarefa/10-concorrencia`
2. Otimizar insercoes com JDBC Batch
3. Criar `EfficientTransactionIngestor` com metodo `readAsStream` usando `Consumer<Transaction>`
4. Implementar `readBatch` com `Consumer<List<Transaction>>` acumulando lotes de 10 mil
5. Thread pool com `ExecutorService`, explorar virtual threads
6. Processar CSV completo do PaySim, medir tempos e verificar corretude
