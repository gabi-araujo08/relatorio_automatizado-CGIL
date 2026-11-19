# Perfil dos imigrantes no Brasil

Relatório automatizado em R que analisa o perfil de imigrantes no Brasil
a partir de dados de autorizações de residência (CGIL/CNIg) de 2024 e 2025.

## Dados

Os dados são de fonte pública: Ministério da Justiça e Segurança Pública 
https://unbbr-my.sharepoint.com/:x:/g/personal/obmigra_unb_br/IQDf_RHseClVTZLwP-753klTAeRZqSXXrypZ5GXO4cfGg9A?e=7SvqCK
https://unbbr-my.sharepoint.com/:x:/g/personal/obmigra_unb_br/IQCKiRIxopRwTKRPnwEPE6gMAZ99j-QMvUHiJdDjZKK4SSs?e=ROdUiM

## Arquivos

- `CE1_trabalho1_final.Rmd`: código-fonte do relatório
- `CE1_trabalho1_final.html`: relatório pronto
- `CGIL_CNIg_2024-2.csv` e `CGIL_CNIg_2025-2.csv`: dados de autorizações
- `RNs_geral_17052025.csv`: tabela de amparos legais (resoluções normativas)

## Como reproduzir

1. Baixe o repositório e abra o `.Rmd` no RStudio.
2. Instale os pacotes: `install.packages(c("tidyverse", "stringi", "lubridate", "readr", "knitr", "kableExtra", "scales"))`
3. Clique em **Knit** para gerar o relatório em HTML.

## Autoria

Gabriela Araújo de Oliveira.
