# Simulador de Financiamento Imobiliário (Sistema SAC)

##  Sobre o Projeto
Este projeto nasceu de uma necessidade real: entender a fundo a evolução das parcelas e o impacto da amortização no meu próprio financiamento imobiliário (**Urban Vila Maria II**). 

Diferente de simuladores prontos, este script em Python foi desenvolvido para calcular mês a mês o **Sistema de Amortização Constante (SAC)**, onde a parcela diminui ao longo do tempo. O objetivo é consolidar conceitos de lógica matemática e estruturas de repetição, aplicados a uma situação financeira de alto impacto.

##  Funcionalidades
- **Cálculo de Amortização Fixa:** Divide o saldo devedor pelo prazo total.
- **Cálculo de Juros Decrescentes:** Aplica a taxa mensal sobre o saldo devedor atualizado.
- **Projeção de Parcelas:** Exibe uma tabela detalhada com o valor da parcela, juros e saldo restante.
- **Formatação Monetária:** Resultados exibidos com precisão de duas casas decimais.

##  Tecnologias Utilizadas
- **Python 3.x**: Linguagem principal.
- **Lógica de Programação**: Uso de estruturas de repetição (`for` loops) e manipulação de tipos de dados (`float`, `int`).

##  Como funciona a lógica SAC?
No sistema SAC, a amortização é sempre a mesma. O que muda é o juro, que é calculado sobre o que você ainda deve. Por isso, a primeira parcela é sempre a mais cara e a última a mais barata.
