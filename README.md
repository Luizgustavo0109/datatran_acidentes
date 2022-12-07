# datatran_acidentes
                 
# Classificador de Acidentes

> **Descrição do dataset**
> 
> Análise dos acidentes rodoviários reportados pela *Polícia Rodoviária Federal (PRF)* em 2020. Cada registro corresponde a uma ocorrência (*acidente*),
> incluindo dados de localidade, nome da BR, KM, condições meteriológicas e da estrada, horário, causa e tipo do acidente, quantidade de feridos e mortos.

> **Bibliotecas e pacotes utilizados**
> ~~~PYTHON
> import pandas as pd
> import numpy as np
> import seaborn as sns
> import matplotlib.pyplot as plt
> from datetime import datetime
> from joblib import dump
> import warnings

> **Problema**
>
> Cronstruir um modelo de classificação que predirá a probabilidade de haver ilesos em um acidente.

> **Técnica de machine learning**
>
> *SUPORT VECTOR MACHINE (SVM):*
> É um algoritmo de aprendizado de máquina supervisionado que pode ser usado para desafios de classificação ou regressão. No entanto, é usado
> principalmente em problemas de classificação.
