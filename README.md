# Projeto Final
### Projeto Semantix

#### Maria Fernanda Ferreira Correia
____

# **1. Definição da Problemática**

## **Problema escolhido**
Previsão de risco de diabetes utilizando análise de dados e Machine Learning.

## **Descrição do problema**

O diabetes é uma doença crônica que afeta milhões de pessoas em todo o mundo e pode causar complicações graves, como doenças cardiovasculares, insuficiência renal, problemas de visão e amputações.

O diagnóstico precoce é fundamental para que o paciente possa iniciar o tratamento e adotar hábitos de vida mais saudáveis, reduzindo os riscos associados à doença.

Nesse contexto, a análise de dados e as técnicas de Machine Learning podem auxiliar na identificação de indivíduos com maior probabilidade de desenvolver diabetes, utilizando características como idade, índice de massa corporal (IMC), nível de glicose, histórico médico e outros fatores de risco.

Ao identificar precocemente pacientes com maior risco, profissionais da saúde podem direcionar exames, monitoramento e ações preventivas de forma mais eficiente.

## **Justificativa da utilização de dados**

A utilização de dados permite identificar padrões que nem sempre são perceptíveis por meio da análise tradicional.

Por meio da análise dos dados é possível:

- Identificar os principais fatores associados ao diabetes;
- Avaliar a influência de características físicas e clínicas na ocorrência da doença;
- Construir modelos preditivos para apoiar diagnósticos;
- Auxiliar profissionais da saúde na tomada de decisão;
- Contribuir para estratégias de prevenção e acompanhamento de pacientes.

Além disso, modelos de Machine Learning podem fornecer previsões rápidas e consistentes, servindo como ferramenta de apoio à análise médica.

# 2. Fontes de Dados Públicas e Não Confidenciais

## Base Principal de Dados

### Diabetes Prediction Dataset

O conjunto de dados Diabetes Prediction Dataset será utilizado como base principal para o desenvolvimento deste projeto. A base contém informações clínicas e demográficas de indivíduos, permitindo a análise de fatores associados ao diagnóstico de diabetes e a construção de modelos preditivos.

Entre as principais variáveis disponíveis estão:

* Idade;
* Sexo;
* Hipertensão;
* Doença cardíaca;
* Histórico de tabagismo;
* Índice de Massa Corporal (IMC);
* Nível de glicose no sangue;
* Hemoglobina glicada (HbA1c).

A variável alvo do conjunto de dados é o diagnóstico de diabetes, representado por:

* 0 = Não possui diabetes;
* 1 = Possui diabetes.

**Fonte:**

https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset

## Fonte Complementar

### Pima Indians Diabetes Database

O conjunto de dados Pima Indians Diabetes Database será utilizado como fonte complementar e referência acadêmica, uma vez que é amplamente empregado em pesquisas relacionadas à previsão de diabetes e avaliação de modelos de Machine Learning.

A base contém informações clínicas relevantes, tais como:

* Número de gestações;
* Pressão arterial;
* Nível de glicose;
* Nível de insulina;
* Índice de Massa Corporal (IMC);
* Idade.

A utilização desta base permitirá comparar resultados e compreender quais variáveis apresentam maior influência na identificação da doença.

**Fonte:**

https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

## Fonte de Contextualização

### Organização Mundial da Saúde (OMS)

A Organização Mundial da Saúde disponibiliza informações e estatísticas atualizadas sobre a prevalência do diabetes em nível mundial. Esses dados serão utilizados para contextualizar a relevância do problema estudado e demonstrar os impactos da doença na saúde pública.

**Fonte:**

https://www.who.int/news-room/fact-sheets/detail/diabetes

## **Objetivo do projeto**

Desenvolver um modelo de Machine Learning capaz de prever a ocorrência de diabetes em indivíduos com base em características clínicas e demográficas, identificando os fatores de risco mais relevantes e contribuindo para a detecção precoce da doença.

## **Pergunta de negócio**

*Quais características dos pacientes estão mais associadas ao diagnóstico de diabetes e é possível prever a doença com precisão utilizando técnicas de Machine Learning?*

Esse tema tem uma vantagem adicional: a análise exploratória costuma gerar insights muito claros (glicose, IMC, idade, hipertensão etc.), o que facilita a construção da narrativa do projeto e da apresentação final.


