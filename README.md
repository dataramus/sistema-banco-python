# Sistema Bancário em Python

## Sobre o Projeto

Este projeto é um sistema bancário simples implementado em Python, que permite realizar operações básicas de depósito, saque e consulta de extrato. Este é o 1° desafio do NTT DATA - Engenharia de Dados com Python da DIO.

## Funcionalidades

- **Depósito:** Permite que o usuário deposite um valor positivo na conta.
- **Saque:** Realiza saques, respeitando o limite diário e o saldo disponível na conta.
- **Extrato:** Exibe um resumo das transações realizadas (depósitos e saques) e o saldo atual da conta.
- **Limites de Segurança:** Inclui limitações de saque diárias para prevenir abuso ou erros.

## Motivação

Desenvolvi este projeto para demonstrar minha capacidade de meu entendimento das estruturas de controle em Python, manuseio de dados e implementação de regras de negócio.

## Como Usar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seuusuario/sistema-bancario-python.git
   ```
2. **Navegue até o diretório do projeto:**
   ```bash
   cd sistema-bancario-python
   ```
3. **Execute o script:**
   ```bash
   python sisbanco.py
   ```

### Interface do Usuário

- **Depósito (`d`):** Digite `d` para iniciar um depósito, seguido do valor que deseja adicionar à sua conta.
- **Saque (`s`):** Digite `s` para iniciar um saque, respeitando o limite de saques diários e o saldo disponível.
- **Extrato (`e`):** Digite `e` para visualizar o extrato da conta, que inclui todos os depósitos e saques realizados.
- **Sair (`q`):** Digite `q` para encerrar o programa.

### Exemplo de Uso

```bash
Digite:
[d] para Depositar
[s] para Sacar
[e] para Extrato
[q] para sair

> d
Valor a ser depositado: 100
Depósito realizado com sucesso!

> s
Digite o valor a ser sacado: 50
Saque realizado com sucesso!

> e
Saldo: R$ 50.00
Extrato:
Depósito: R$ 100.00
Saque: R$ 50.00

> q
Saindo do sistema. Obrigado!
```

Muito Obrigado!
