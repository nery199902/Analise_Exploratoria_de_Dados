📊 Análise Exploratória de Dados - Avaliação de Hospitais

📌 Objetivo
Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (EDA) em um dataset de hospitais, focando em:
- Identificação de variáveis numéricas e categóricas  
- Tratamento de valores ausentes  
- Padronização de dados  
- Agregação de informações por estado  
- Criação de uma variável de classificação de qualidade  

---

# 📊 Análise Exploratória de Dados - Avaliação de Hospitais

Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (EDA) em um dataset de hospitais, aplicando boas práticas de ciência de dados para transformar dados brutos em insights relevantes.

A análise começou com o carregamento dos dados e a identificação dos tipos de variáveis, separando colunas numéricas e categóricas para melhor entendimento da estrutura do dataset.

Em seguida, foi realizado o tratamento de valores ausentes. Colunas com grande quantidade de dados faltantes e baixa relevância analítica (como footnotes) foram removidas. Já colunas importantes tiveram seus valores ausentes tratados por meio de preenchimento com categorias apropriadas, preservando a integridade dos dados.

Também foi feita a padronização das variáveis categóricas, especialmente nas colunas de estado e tipo de hospital, garantindo consistência na nomenclatura e evitando duplicidade de categorias causadas por diferenças de formatação.

A variável de avaliação hospitalar foi convertida para formato numérico, permitindo a realização de cálculos estatísticos, como média. Valores não disponíveis foram tratados adequadamente para não comprometer a análise.

Na etapa seguinte, os dados foram agregados por estado, possibilitando a análise do número de hospitais por região, bem como a média das avaliações de qualidade. Além disso, foi analisada a distribuição dos tipos de hospital em cada estado, oferecendo uma visão mais completa do sistema de saúde.

Por fim, foi criada uma nova variável categórica que classifica os hospitais em três níveis de qualidade (baixa, média e alta), com base nas avaliações. Essa etapa é fundamental para facilitar análises comparativas e aplicações futuras em modelos de machine learning.

Como resultado, a análise permitiu identificar padrões relevantes, entender a distribuição dos hospitais e criar indicadores estratégicos que podem apoiar a tomada de decisão.

Este projeto demonstra a importância da Análise Exploratória de Dados como etapa essencial em qualquer processo de ciência de dados, garantindo qualidade, consistência e geração de valor a partir dos dados.

## 🛠️ Tecnologias utilizadas
- Python  
- Pandas  
- Google Colab  
