# 05. Analise de Fraudes com Stream API

**Nivel:** Essencial

## Objetivo

Exercitar programacao funcional e declarativa para processamento de colecoes. Filtragem, ordenacao, agregacao e agrupamento.

## Contexto

O time de seguranca precisa identificar padroes de fraude rapidamente.

## Tarefa

1. Branch `tarefa/05-streams`
2. Carregar 50.000 linhas com `TransactionIngestor`
3. Criar classe `FraudAnalyzer` usando Stream API para:
   - Filtrar transacoes fraudulentas e contar
   - Top 3 fraudes de maior valor
   - Nomes unicos dos 5 maiores clientes suspeitos
   - Prejuizo total das fraudes (soma dos amounts)
   - Contagem de fraudes por tipo de transacao
4. Classe `Main` invocando cada metodo e imprimindo resultados
