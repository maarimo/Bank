💸 Tratamento de Exceções com Conta Bancária
Este é um projeto simples em Java que simula operações básicas de uma conta bancária com foco no tratamento de exceções personalizadas.
---
📋 Descrição
O sistema permite:

Criar uma conta informando número, titular, saldo inicial e limite de saque;

Realizar uma operação de saque;

Lidar com erros utilizando exceções personalizadas (BusinessException) para validar regras de negócio, como:

Valor de saque exceder o saldo;

Valor de saque exceder o limite definido.
---
⚠️ Regras de Negócio
O saque não pode exceder o saldo disponível.

O saque não pode ultrapassar o limite de saque definido.

Caso uma dessas regras seja violada, será exibida uma mensagem de erro clara para o usuário.
