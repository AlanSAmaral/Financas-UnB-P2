# Registo de Alterações e Atualização da Base de Dados

**Aluno:** [SEU NOME COMPLETO]
**Matrícula:** 261026205

Este documento detalha as atualizações, correções e limitações metodológicas encontradas durante a reconstrução e ampliação da base de dados face ao trabalho anterior.

## 1. Atualização Temporal e Cobertura
- **Período de Análise:** A série histórica foi atualizada e padronizada para abranger o período mais recente e consistente de 10 anos completos (2014 a 2023).
- **Unidades:** Confirmou-se a compilação para os municípios de Redenção/PA e Tucuruí/PA (Brasil), bem como os indicadores macrofiscais do Estado de Israel.

## 2. Limitações e Tratamento de Dados Ausentes
- **Omissão da variável "Arrecadação Própria":** Durante a verificação dos dados (Siconfi/Finbra), constatou-se uma inconsistência na classificação das rubricas de receitas tributárias próprias locais para os anos iniciais da série em ambos os municípios (quebras de série). Cumprindo a diretriz de **não substituir dados ausentes por zero**, optou-se por focar a análise na **Receita Total** e na forte dependência das **Transferências Correntes**. Estas variáveis apresentam séries completas e são suficientes para responder à pergunta de investigação sobre a ilusão fiscal e o *efeito flypaper*.
- **Variável de Israel:** Utilizou-se a despesa do governo central como percentagem do PIB (fonte: Banco Mundial) para contornar a distorção cambial (Shekel Israelita vs. Real Brasileiro) e a diferença de escala macroeconómica.

## 3. Correções e Transformações Realizadas
- **Ajuste Inflacionário (Valores Reais):** Constatou-se que os dados anteriores não tratavam adequadamente a inflação. Todos os valores monetários brasileiros foram deflacionados utilizando o IPCA (IBGE), trazendo os montantes para valores reais (ano-base de referência: 2025).
- **Reconstrução da Base:** Devido à indisponibilidade de microdados devidamente tratados no repositório de partida, a base de dados teve de ser reconstruída a partir de fontes oficiais e agregadas, garantindo a rastreabilidade exigida na P2.
