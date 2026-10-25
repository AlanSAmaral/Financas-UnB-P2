# Finanças do Setor Público - P2 (2026.2)
**Universidade de Brasília (UnB) - CCA0169 - Turma 01**
**Professor:** Lucas Oliveira Gomes Ferreira
**Aluno:** [SEU NOME COMPLETO]
**Matrícula:** 261026205

## 📌 Sobre o Projeto
Este repositório contém a avaliação P2 da disciplina de Finanças do Setor Público. O trabalho consiste na atualização de uma base de dados macroeconômica e fiscal e na elaboração de um artigo científico.

**Unidades de Análise:**
- Município 1: Redenção/PA (Brasil)
- Município 2: Tucuruí/PA (Brasil)
- País: Israel

## 📂 Estrutura do Repositório
- `Artigo_Matricula_261026205.pdf`: Artigo científico completo contendo o estudo bibliométrico e análise de dados.
- `Base_Original/`: Cópia dos dados do trabalho anterior (link do Google Drive fornecido).
- `Base_Atualizada_e_Tratada.xlsx`: Planilha contendo os dados brutos coletados (Siconfi, IBGE e Banco Mundial) e os dados tratados (deflacionados e padronizados).
- `Dicionario_de_Variaveis.md`: Detalhamento das variáveis, fontes e metodologias de cálculo.
- `Registro_de_Alteracoes.md`: Documento relatando as inconsistências encontradas na base anterior e as correções aplicadas.
- `Scripts/`: Códigos em R (incluindo a rotina do pacote `bibliometrix`).

## ⚙️ Instruções de Reprodução
1. A coleta de dados municipais (2016-2025) foi realizada via Siconfi/Finbra (Tesouro Nacional) e IBGE.
2. Os dados de Israel foram extraídos do World Bank Open Data.
3. Para deflacionar os valores monetários brasileiros para preços reais (ano-base 2025), utilizou-se o IPCA (IBGE).
4. O estudo bibliométrico pode ser reproduzido rodando o script R disponibilizado na pasta correspondente.
