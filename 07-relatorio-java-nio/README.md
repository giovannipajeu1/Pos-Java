# 07. Relatorio Eficiente com Java NIO

**Nivel:** Intermediario

## Objetivo

Exercitar tecnicas de I/O eficiente para grandes arquivos, evitando estouro de memoria (`OutOfMemoryError`). Lazy Loading vs carregar tudo na RAM.

## Contexto

Ler o arquivo inteiro (~493MB) para uma `List<Transaction>` pode estourar a memoria.

## Tarefa

1. Branch `tarefa/07-nio`
2. Testar `OutOfMemoryError` com `-Xmx128m`
3. Criar `TransactionReport` usando `java.nio.file.Files.lines(Path)` (Stream preguicoso)
4. Processar arquivo inteiro calculando: total de linhas, total de fraudes, valor total transacionado
5. Classe `ReportMain` com limite de memoria `-Xmx128m`
