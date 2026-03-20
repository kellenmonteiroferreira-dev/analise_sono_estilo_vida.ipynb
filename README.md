# analise_sono_estilo_vida.ipynb
 Este projeto analisa a relação entre estilo de vida, estresse e qualidade do sono.
Análise de Qualidade do Sono e Estilo de Vida

 Descrição do Projeto

Este projeto tem como objetivo analisar a relação entre fatores de estilo de vida, saúde e qualidade do sono. A partir de um conjunto de dados contendo informações como nível de estresse, duração do sono, profissão e indicadores fisiológicos, foram aplicadas técnicas de análise exploratória de dados para identificar padrões, relações e possíveis fatores de influência.

A análise busca compreender quais variáveis estão mais associadas à qualidade do sono e como aspectos comportamentais e profissionais podem impactar o bem-estar dos indivíduos.

 Objetivos da Análise

Identificar os principais fatores associados à qualidade do sono

Analisar a relação entre nível de estresse e sono

Avaliar o impacto da duração do sono na sua qualidade

Investigar diferenças entre profissões e gêneros

Explorar possíveis associações entre saúde (IMC, pressão arterial) e sono  
Base de Dados

O conjunto de dados contém informações sobre diferentes aspectos da vida e saúde dos indivíduos, incluindo:

Gênero

Idade

Profissão

Duração do Sono (horas)

Qualidade do Sono

Nível de Estresse

Nível de Atividade Física

Categoria do IMC

Pressão Arterial

Frequência Cardíaca

Passos Diários

Distúrbios do Sono

Durante a análise, algumas colunas foram tratadas e ajustadas para melhor interpretação, incluindo a remoção de variáveis irrelevantes como identificadores únicos.

 Tecnologias:

Python

Pandas → manipulação e análise de dados

Matplotlib → visualização de dados

Seaborn → análise gráfica e correlação

Plotly → gráficos interativos

 Etapas da Análise
1. Preparação dos Dados

Importação da base de dados

Renomeação das colunas para melhor legibilidade

Remoção de colunas não relevantes (ex: ID, passos diários)

2. Análise Exploratória

Distribuição dos dados por gênero e idade

Agrupamentos por profissão e variáveis de saúde

Identificação de padrões gerais

3. Análise de Correlação

Avaliação da relação entre variáveis numéricas

Identificação de correlações fortes, moderadas e fracas

Destaque para:

Estresse vs Qualidade do Sono

Duração do Sono vs Qualidade

Frequência Cardíaca vs Sono

4. Análises Comparativas

Comparação entre gêneros

Avaliação por profissão

Impacto de distúrbios do sono

Relação entre estresse e indicadores de saúde

5. Visualização de Dados

Gráficos de dispersão

Gráficos de barras

Histogramas

Heatmap de correlação

Gráficos interativos

 #Principais Insights

O nível de estresse apresentou forte relação negativa com a qualidade do sono

A duração do sono está positivamente associada à sua qualidade

Indivíduos com maior estresse tendem a apresentar mais distúrbios do sono

Algumas profissões apresentam níveis mais elevados de estresse

Variáveis de saúde como IMC e pressão arterial demonstraram associação com outros fatores analisados

A atividade física, isoladamente, apresentou menor impacto na qualidade do sono

 #Conclusão

Os resultados indicam que a qualidade do sono é influenciada por múltiplos fatores, sendo o estresse o principal elemento associado. A análise também sugere a existência de relações entre variáveis de saúde e estilo de vida, reforçando a importância de uma abordagem integrada para o bem-estar.

É importante destacar que as relações identificadas representam associações estatísticas, não sendo possível estabelecer causalidade com base neste conjunto de dados.

 Possíveis Melhorias Futuras

Aplicação de modelos preditivos

Análise com maior volume de dados

Inclusão de variáveis adicionais

Criação de dashboards interativos

 Autora

Projeto desenvolvido como parte do processo de aprendizado em análise de dados, com foco em desenvolvimento de portfólio profissional.
