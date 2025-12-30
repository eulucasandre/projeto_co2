# 🌍 Análise das Emissões de Gases de Efeito Estufa no Brasil (1970–2021)

## 👋 Sobre o Projeto

Este projeto faz parte do meu portfólio pessoal em Data Science e apresenta uma análise exploratória completa das emissões de Gases de Efeito Estufa (GEE) no Brasil ao longo de mais de cinco décadas.

O objetivo não é apenas explorar dados ambientais, mas demonstrar domínio prático de manipulação, integração, análise e visualização de dados reais, utilizando fontes oficiais amplamente reconhecidas.

## 🎯 Objetivo do Projeto

Responder, com base em dados, às seguintes perguntas:

* Quais gases mais contribuem para as emissões brasileiras?

* Como essas emissões evoluíram ao longo do tempo?

* Quais setores econômicos são os principais responsáveis?

* Como as emissões se distribuem quando analisadas per capita?

* Existe relação entre população e volume de emissões?

## 🧠 Abordagem Analítica

A análise foi estruturada seguindo um fluxo típico de projetos reais de Data Science:

* Exploração e entendimento dos dados

* Limpeza e padronização

* Transformações estruturais (wide → long)

* Agrupamentos simples e hierárquicos (multi-index)

* Integração de múltiplas bases

* Geração de métricas derivadas

* Visualização orientada a insights

Todo o processo está documentado de forma narrativa no notebook, permitindo acompanhar o raciocínio analítico passo a passo.

## 🛠️ Tecnologias Utilizadas

* Python

* Pandas (manipulação, groupby, merge, pivot_table)

* Plotly Express (visualizações interativas)

* Jupyter Notebook

* Uso de Expressões Regulares (Regex) para limpeza de dados textuais

## 📊 Fontes de Dados

* SEEG – Observatório do Clima (Fonte: https://seeg.eco.br/dados/) 
* Emissões de GEE por gás, setor, estado e ano (1970–2021) (Fonte: https://www.ibge.gov.br/estatisticas/sociais/saude/22827-censo-demografico-2022.html?=&t=resultados)

IBGE – Censo 2022
Dados populacionais utilizados para cálculo de emissões per capita

Essas fontes refletem dados reais, complexos e imperfeitos, exigindo tratamento cuidadoso — exatamente como em cenários profissionais.

## 📈 Principais Insights Obtidos
### 🔥 Gases de Maior Impacto

* O CO₂ é o principal gás emitido no Brasil, representando mais de 90% das emissões totais no período analisado.

### 🏭 Setores Econômicos

* Para o CO₂, o setor de Mudança de Uso da Terra e Florestas aparece consistentemente como o maior emissor.

* Cada gás apresenta um padrão distinto de setor dominante, evidenciando a necessidade de análises segmentadas.

### 📅 Evolução Temporal

* As emissões não seguem uma trajetória linear.

* A análise temporal evidencia períodos críticos de crescimento, reforçando a importância do recorte histórico.

### 🗺️ Emissões Per Capita

* Estados menos populosos tendem a apresentar emissões per capita mais elevadas.

* A análise sugere uma relação entre emissões elevadas e atividades como desmatamento e agropecuária extensiva.

## 📂 Estrutura do Projeto

projeto_co2br/
├── data/          # Dados brutos (SEEG e IBGE)
├── notebooks/     # Notebook principal com a análise
├── results/       # Gráficos e outputs
└── README.md

