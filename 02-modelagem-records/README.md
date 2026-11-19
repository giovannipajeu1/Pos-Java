# 02. Modelagem de Transacoes do PaySim com Records

**Nivel:** Essencial

## Objetivo

Modelar dados imutaveis e modernos com Java Records, garantindo integridade e encapsulamento desde a criacao do objeto.

## Contexto

Vamos modelar o CSV do PaySim em objetos Java.

## Tarefa

1. Branch `tarefa/02-records`
2. Criar Java Record `Transaction` com as colunas do CSV (`step`, `type`, `amount`, `nameOrig`, etc.)
3. Usar convencoes Java (`camelCase`) e tipos corretos
4. `type` como enum: `CASH_IN`, `CASH_OUT`, `DEBIT`, `PAYMENT`, `TRANSFER`
5. Abstrair cliente de origem e destino em tipos separados
6. Classe `Main` que cria e imprime transacoes de exemplo
