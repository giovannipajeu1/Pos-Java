# 04. Tratamento de Erros e Optional

**Nivel:** Essencial

## Objetivo

Garantir a robustez da aplicacao atraves do tratamento correto de excecoes e do uso de `Optional` para evitar `NullPointerException`. Lidar com dados sujos do mundo real.

## Contexto

O arquivo CSV pode conter linhas corrompidas ou valores nulos.

## Tarefa

1. Branch `tarefa/04-tratamento-erros`
2. Baixar CSV com dados corrompidos para testes
3. Implementar validacoes no record `Transaction` (nenhum nulo, step >= 1, numeros nao negativos)
4. Capturar excecoes de linhas mal formatadas, logar erro e continuar leitura
5. Exibir quantidade de transacoes validas e lista de erros
