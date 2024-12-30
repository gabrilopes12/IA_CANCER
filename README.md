# Predição de Sobrevida de Pacientes com Câncer Colorretal

Este projeto foi desenvolvido em conjunto com nosso professor/mentor durante um curso, e tem como foco aplicar técnicas de Machine Learning para predizer a sobrevida de 3 anos de pacientes diagnosticados com câncer colorretal.

# 1. O Problema
	•	O câncer colorretal é uma das principais análises relacionadas à saúde, especialmente quando o tempo é um fator crucial.
	•	Nosso objetivo é analisar problemas onde o risco de ocorrência de eventos (como sobrevida) não é homogêneo ao longo do tempo.

# 2. Conjunto de Dados
	•	Fonte: Registro Hospitalar de Câncer de São Paulo (RHC-SP), gerido pela FOSP (Fundação Oncocentro de São Paulo).
	•	Acesso: Banco de dados público.
	•	Características:
	•	1.211.630 pacientes registrados.
	•	105 colunas com informações relevantes.
	•	Registros desde o ano 2000.

 # 3. Objetivo

O principal objetivo do projeto é predizer a sobrevida de 3 anos para pacientes diagnosticados com câncer colorretal, utilizando métodos de Machine Learning.


# 4. Etapas do Projeto

## 4.1 Leitura e Exploração dos Dados
	•	Leitura dos dados: Importação e inspeção inicial.
	•	Integração de bases: Combinação de diferentes bancos de dados.
	•	Tratamento inicial: Identificação e tratamento de valores faltantes e duplicados.
	•	Análise exploratória:
	•	Identificação dos tipos de variáveis.
	•	Estatísticas descritivas das colunas.
	•	Análise de correlação entre variáveis.
	•	Visualizações como histogramas e boxplots.

## 4.2 Preparação dos Dados
	•	Divisão do dataset: Separação em conjuntos de treino e teste.
	•	Normalização: Escalonamento de variáveis numéricas.
	•	Codificação: Transformação de variáveis categóricas para uso em modelos.

## 4.3 Treinamento e Validação
	•	Treinamento: Desenvolvimento de modelos preditivos utilizando os dados tratados.
	•	Validação: Avaliação do desempenho do modelo treinado em dados não vistos.

## 4.4 Utilização do Modelo
	•	Implementação do modelo treinado para predizer a sobrevida de novos pacientes.
