# Controle de Finanças Pessoais

Este script Python foi desenvolvido para ajudar no controle das finanças pessoais, permitindo que o usuário insira suas despesas mensais e estabeleça metas de poupança. O script calcula se o usuário está gastando dentro do seu orçamento e, caso contrário, sugere reduções nas despesas variáveis para atingir as metas de poupança.

## Requisitos

- Python 3.x
- Bibliotecas Python: `numpy`, `pandas`, `openpyxl`

## Funcionalidades

- Permite ao usuário inserir seu salário mensal e as despesas em diferentes categorias (fixas ou variáveis).
- Calcula automaticamente o total gasto no mês e verifica se o usuário está dentro do orçamento.
- Solicita ao usuário um valor de poupança desejado.
- Se o usuário estiver gastando mais do que ganha, o script sugere reduções nas despesas variáveis para atingir a meta de poupança.
- Salva os resultados em um arquivo Excel com os valores originais das despesas e os valores reduzidos.
- Gera gráficos de pizza para visualizar a distribuição das despesas antes e depois da redução.

## Utilização

1. Execute o script Python `controle_financas.py`.
2. Siga as instruções para inserir seu salário, despesas e meta de poupança.
3. O script calculará automaticamente e informará se você está dentro do seu orçamento.
4. Se necessário, ele sugerirá reduções nas despesas variáveis para atingir a meta de poupança.
5. Os resultados serão salvos em um arquivo Excel chamado `despesas.xlsx`.
6. Você pode visualizar o histórico de finanças, adicionando dados para diferentes períodos e visualizando-os posteriormente.

## Personalização

- Você pode personalizar as categorias de despesas e suas ponderações ajustando o dicionário `ponderacoes_default`.
- O script também inclui funções básicas para adicionar dados de finanças para diferentes períodos e visualizar o histórico de finanças.

---

Sinta-se à vontade para ajustar e expandir o código conforme suas necessidades específicas!
