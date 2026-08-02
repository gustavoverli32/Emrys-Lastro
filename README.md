# Emrys Lastro

App de finanças pessoais da [Emrys](https://emrys.ai). PWA de arquivo único — HTML, CSS e JS puro, sem build e sem dependências.

## O que faz

- **Visão geral** — saldo do mês, receitas, despesas, cartão e pendências, com barra de orçamento utilizado
- **Receitas e despesas** — 9 categorias, status pago/pendente, e recorrentes lançadas automaticamente todo mês
- **Cartão de crédito** — múltiplos cartões, compras parceladas distribuídas mês a mês, gasto por categoria, maiores gastos e faturas já comprometidas
- **Financiamento** — anel de quitação, saldo devedor e comprovante por parcela
- **Histórico** — comparativo mensal com detalhamento por categoria

## Como rodar

Abra o `index.html` em qualquer navegador, ou sirva a pasta e instale como app pelo navegador do celular.

## Dados

Tudo fica no `localStorage` do dispositivo — nada sai do aparelho.

| Chave | Conteúdo |
| --- | --- |
| `orc-pro-v2` | receitas e despesas por mês |
| `orc-pro-rec-v2` | despesas recorrentes |
| `orc-pro-recr-v1` | receitas recorrentes |
| `orc-pro-fin-v2` | financiamento do veículo |
| `orc-pro-cards-v1` | cartões de crédito |
| `orc-pro-cardtx-v1` | compras no cartão |

## Marca

Fundo `#000000`, superfícies `#0A0A0A`, acento `#FFA260`, azul `#398FFF`.
Satoshi para interface, Instrument Serif itálico no wordmark, JetBrains Mono nos valores.
A marca é o E da Emrys em três barras, com a de baixo transbordando como base.
