# 💰 Gestão Financeira Pessoal

Sistema web de controle financeiro pessoal em HTML, CSS e JavaScript puro — sem dependências.

## Funcionalidades
- Cadastro de receitas e despesas (categoria, fixa/variável, vencimento, status pago/em aberto)
- Lançamentos recorrentes (repetir por N meses)
- Painel com receitas, despesas, saldo e % da renda comprometida
- Despesas por categoria e próximos vencimentos (com destaque para atrasados)
- Comparativo: gráfico Receitas × Despesas dos últimos 6 meses, fixas × variáveis e resumo mensal
- Investimentos: carteira com cotações em tempo real (ações/FIIs/ETFs via brapi, cripto e moedas via AwesomeAPI) e renda fixa calculada pelo CDI do Banco Central
- Relatório: histórico de 3 a 24 meses e projeção de 24 meses com cenários e vários gráficos
- Backup/restauração em JSON e exportação CSV para Excel
- Login de usuário com dados criptografados (AES-GCM, chave derivada da senha com PBKDF2)
- Logo personalizado ao lado do título
- Tema escuro ou claro (botão ☀️/🌙 no topo)

## Como usar
Abra o `index.html` no navegador. Os dados ficam salvos no `localStorage` do próprio navegador.
