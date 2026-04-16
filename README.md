💳 Bank 24h

📌 Descrição

Sistema de autoatendimento bancário desenvolvido com foco em validação rigorosa de dados, evitando erros em operações financeiras. Utiliza JavaScript, HTML e CSS, com validação obrigatória usando do while + REGEX.

🎯 Funcionalidades
Login com seleção de banco (tema dinâmico)
Operações:
Saldo
Saque
Depósito
Transferência
Troca de senha
Extrato
PDF
Sair
Histórico de transações com data/hora

🔁 Validação
Uso de do while para repetir até entrada válida
REGEX:
/^\d+(\.\d+)?$/
Regras:
Saque/Transferência: valor > 0 e ≤ saldo
Depósito: valor > 0

⚙️ Técnicas
Array para histórico (.push())
Tratamento de null no prompt
Formatação:
toLocaleString('pt-BR', { style: 'currency', currency: 'BRL' })

🛠️ Tecnologias
HTML
CSS
JavaScript

🔒 Regra Principal
Nenhuma operação é realizada sem validação com DO WHILE + REGEX.
