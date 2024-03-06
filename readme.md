# Projeto de Análise de Vendas

## Visão Geral
Este projeto envolve a realização de uma análise abrangente dos dados de vendas de uma empresa. O objetivo é entender as tendências de vendas, identificar os meses e produtos com melhor desempenho e derivar insights acionáveis para orientar a estratégia de vendas.

## Detalhes Técnicos

### Dependências
- Python
- Biblioteca Pandas
- Biblioteca Matplotlib
- Biblioteca OS

### Preparação dos Dados
Os dados brutos de vendas de cada mês são mesclados em um único arquivo CSV usando a biblioteca Pandas do Python. Durante esse processo, lidamos com valores ausentes e limpamos os dados para garantir precisão em nossa análise.

### Etapas de Análise de Dados
1. **Mesclar dados de vendas mensais:** Combina dados de cada mês em um conjunto de dados consolidado.
2. **Ler o dataframe atualizado:** Carrega o CSV combinado em um dataframe Pandas para análise.
3. **Limpar os dados:** Remover linhas com valores NaN e corrigir tipos de dados quando necessário.
4. **Aumentar dados com colunas adicionais:** Adicionar colunas derivadas úteis como 'Mês', 'Cidade' e 'Vendas' para auxiliar na análise.

### Perguntas Chave Abordadas
1. Qual foi o melhor mês para vendas e quanto foi ganho durante esse mês?
2. Qual cidade vendeu mais produtos?
3. Em que horário os anúncios devem ser exibidos para maximizar a probabilidade de os clientes comprarem produtos?
4. Qual produto vendeu mais e qual pode ser o motivo de suas altas vendas? 
5. Quais produtos são mais frequentemente vendidos juntos?

### Visualização de Dados
Utilizamos Matplotlib para criar representações visuais de nossos achados, incluindo gráficos de barras para comparar vendas em diferentes meses e cidades, e gráficos de linha para determinar os horários ótimos para anúncios.

### Insights e Recomendações
- Insights detalhados baseados na análise.
- Estratégias para aumentar as vendas nos meses de menor desempenho.
