# 📊 **Análise de Dados de Teamfight Tactics (TFT) - Projeto de BI**

## **Descrição do Projeto**

Este projeto de Business Intelligence (BI) foi desenvolvido para analisar detalhadamente os campeões de *Teamfight Tactics (TFT)*, utilizando dados do catálogo atual de campeões. O objetivo é proporcionar insights valiosos sobre o desempenho dos campeões, seus custos, níveis de estrela, e atributos de combate, ajudando jogadores a tomar decisões estratégicas mais informadas.

## **Datasets Utilizados**

O dataset utilizado foi extraído do [Kaggle](https://www.kaggle.com/datasets/riosjoaop/tft-teamfight-tatics-current-set-catalogue?select=champions.csv) e contém informações detalhadas sobre cada campeão, incluindo:
- **Nome**: Nome do campeão.
- **Custo**: Valor em ouro do campeão.
- **Atributos de Combate**: Saúde (Health), Armadura (Armor), Resistência Mágica (MR), Poder de Habilidade (Ability Power), Dano por Segundo (DPS), Dano (Damage), Velocidade de Ataque (Attack Speed), Taxa de Crítico (Crit Rate) e Alcance (Range).
- **Sinergias**: Classes e origens que o campeão possui.
- **Habilidade**: Nome, custo e descrição da habilidade do campeão.

## **Estrutura do Relatório**

O relatório é dividido em três páginas principais, cada uma focada em um aspecto específico da análise dos campeões:

### **Página 1 - Visão Geral dos Campeões**
- **Gráfico de Coluna Clusterizado**: Visualização do custo dos campeões.
- **Gráficos de Barras Clusterizados**: Um gráfico para os campeões com maior saúde e outro para os campeões com maior DPS.
- **Gráficos de Cascata**: Três gráficos mostrando DPS por Damage, DPS e Health por nível de estrela.
- **Filtros Interativos**: Seletor de Custo (1 a 5), Estrelas (1, 2, 3) e Nome dos campeões.

### **Página 2 - Análise de Desempenho por Nível de Estrela**
- **Gráfico de Colunas Clusterizado**: Média de DPS, Damage e Health por nível de estrela.
- **Gráfico de Linha**: Soma de Health, Damage e DPS por nível de estrela.
- **Gráfico de Dispersão**: Comparação entre a soma de DPS e a soma de Health por nível de estrela.
- **Filtros Interativos**: Seletor de Custo (1 a 5), Estrelas (1, 2, 3) e Nome dos campeões.

### **Página 3 - Análise de Custo dos Campeões**
- **Gráfico de Barras Clusterizado**: Contagem de campeões por custo.
- **Gráfico de Rosca**: Distribuição de campeões por custo.
- **Tabela**: Exibição de Nome, DPS, Damage, Health e Custo dos campeões.
- **Treemap**: Média de Health por custo e nome dos campeões.
- **Gráfico de Colunas Empilhadas**: Número de campeões por custo.
- **Filtros Interativos**: Seletor de Custo (1 a 5), Estrelas (1, 2, 3) e Nome dos campeões.

## **Ferramentas Utilizadas**

- **Power BI**: Para criação das visualizações interativas e dashboards.
- **Python (Pandas, NumPy)**: Para manipulação e preparação de dados.
- **Excel**: Para análise exploratória inicial dos dados.

## **Como Utilizar este Relatório**

1. **Clone o Repositório**: Clone este repositório em sua máquina local.
   ```bash
   git clone https://github.com/seu-usuario/tft-analise-dados
2. Importe o Projeto no Power BI: Abra o Power BI e importe o arquivo .pbix do projeto.
3. Explore as Páginas: Navegue pelas páginas do relatório para explorar as diferentes análises de dados.
4. Filtre e Interaja: Utilize os filtros e gráficos interativos para personalizar sua análise.
## Objetivos do Projeto
 - Aprendizado e Prática: Fortalecer habilidades em BI, visualização de dados e análise de jogos.
 - Insights para Jogadores: Oferecer insights valiosos para melhorar a compreensão e estratégias de jogo em TFT.
 - Portfólio Profissional: Adicionar um projeto prático ao portfólio para demonstração de habilidades na área de dados.
## Resultados e Conclusões
Os principais insights extraídos deste projeto incluem:

 - Melhor Compreensão de Custos e Atributos: Análise detalhada dos atributos de campeões em relação ao custo, ajudando a otimizar escolhas durante o jogo.
 - Impacto do Nível de Estrela: Entendimento de como o nível de estrela afeta diretamente o desempenho dos campeões.
 - Visualização de Distribuições de Desempenho: Uso de gráficos e tabelas para ilustrar como diferentes atributos variam entre campeões e suas sinergias.
## Próximos Passos
 - Incorporar Dados Adicionais: Adicionar informações sobre patches e mudanças de balanceamento ao longo do tempo.
 - Aprimorar Visualizações: Incluir visualizações mais avançadas e interativas.
 - Explorar Machine Learning: Aplicar modelos de aprendizado de máquina para prever o desempenho de campeões em diferentes configurações de equipe.
## Contribuições
Contribuições são bem-vindas! Se você deseja melhorar este projeto, sinta-se à vontade para abrir um pull request ou enviar sugestões.
