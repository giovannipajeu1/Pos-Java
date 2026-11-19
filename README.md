# Pos-Java - Projeto Pratico: Zenon Bank Fraud Detector

Repositorio mono-repo com os exercicios praticos da pos-graduacao em **Fundamentos Java**.

O projeto simula o cenario de uma fintech ficticia, o **Zenon Bank**, que precisa processar milhoes de transacoes financeiras para detectar fraudes. Os exercicios cobrem desde configuracao do ambiente ate processamento de alta performance com grande volume de dados.

## Estrutura

Cada exercicio e um subprojeto Maven isolado dentro do mono-repo:

| # | Exercicio | Nivel | Tema principal |
|---|-----------|-------|----------------|
| 01 | [Configuracao do Ambiente e Dados](01-configuracao-ambiente/) | Essencial | IDE, Maven/Gradle, Dataset PaySim |
| 02 | [Modelagem com Records](02-modelagem-records/) | Essencial | Java Records, tipos, enums |
| 03 | [Ingestao de Dados e IO Basico](03-ingestao-dados-io/) | Essencial | java.io, parsing CSV, List |
| 04 | [Tratamento de Erros e Optional](04-tratamento-erros/) | Essencial | Exceptions, Optional, validacao |
| 05 | [Analise de Fraudes com Streams](05-analise-fraudes-streams/) | Essencial | Stream API, filter, map, collect |
| 06 | [Benchmark: List vs Map](06-benchmark-list-vs-map/) | Essencial | Collections, O(n) vs O(1), interface |
| 07 | [Relatorio com Java NIO](07-relatorio-java-nio/) | Intermediario | NIO, lazy loading, memoria |
| 08 | [Internacionalizacao](08-internacionalizacao/) | Intermediario | i18n, ResourceBundle, Locale |
| 09 | [Persistencia com JDBC](09-persistencia-jdbc/) | Intermediario | MySQL, Docker, JDBC, SQL |
| 10 | [Ingestao Eficiente](10-ingestao-eficiente/) | Desafio | Concorrencia, batch, threads |

## Dataset

Os exercicios utilizam o dataset **PaySim** do Kaggle (~493MB):
https://www.kaggle.com/datasets/ealaxi/paysim1

O CSV deve ser colocado em um diretorio `data/` na raiz (ja incluido no `.gitignore`).

## Requisitos

- Java 25 (LTS)
- Maven ou Gradle
- IntelliJ IDEA ou Eclipse
- Docker (para o exercicio 09)

## Como executar

Cada exercicio e independente. Entre na pasta do exercicio desejado e execute:

```bash
mvn compile exec:java
```

## Niveis de dificuldade

- **Essencial** - Aplicacao direta do conteudo das aulas
- **Intermediario** - Requer conhecimento mais aprofundado
- **Desafio** - Vai alem, exigindo pesquisa e solucoes mais complexas
