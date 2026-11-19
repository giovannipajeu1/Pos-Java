# 08. Internacionalizacao do Relatorio

**Nivel:** Intermediario

## Objetivo

Abordar a criacao de aplicacoes globais (i18n), formatar dados sensiveis a cultura (moeda, data) e traduzir textos dinamicamente.

## Contexto

O relatorio de fraudes deve ser exportado em ingles ou portugues.

## Tarefa

1. Branch `tarefa/08-i18n`
2. Internacionalizar a classe `ReportMain` para portugues e ingles
3. Criar bundles `report_pt.properties` e `report_en.properties` com `ResourceBundle`
4. Formatar valores monetarios com `NumberFormat` conforme o `Locale`
5. Argumento para o usuario escolher entre portugues e ingles
