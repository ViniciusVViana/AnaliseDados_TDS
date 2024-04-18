# Relatorio de TDS - Pratica 04
## Análise de dados usando python
### Preparação de ambiente:
#### Instalação do python:
1. Acessei o [site oficial do Python](https://www.python.org).
2. Instalei a versão mais recente do Python (versão: 3.12.3).
    1. Adicionei ás variáveis de ambiente do windows.
#### Instação das bibliotecas utilizadas:
    pip install matplotlib
    pip install pandas
    pip install seaborn4
    pip install request
    pip install numpy
Ambiente pronto para começar a programar.
### Código:
1. Importei as bibliotecas no código:
     
        import matplotlib.pyplot as mpl
        import numpy as np
        import pandas as pd
        import seaborn as sb
        import requests
        import csv
2. Criei o caminho para salvar os arquivos:

        caminhoArquivo = "./dadosAcidentes.csv
        caminhoArquivoFiltrado = "./dadosAcidentesfiltrados.csv

[!NOTE]
hello