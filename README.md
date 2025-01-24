## Projeto Semantix

Apresentamos o nosso projeto de **Arrecadação Federal** dos Estados Brasileiros. Este projeto é baseado em um desenho amostral de 25 anos, utilizando 8 anos de performance.

O objetivo principal deste projeto é **analisar e classificar os Estados Brasileiros de acordo com os impostos arrecadados**, com base nos impostos de importação e exportação arrecadado durante um período. Esta classificação é crucial para identificar quais Estados precisam de mais investimentos.

Através do uso de técnicas avançadas de modelagem e análise, estamos confiantes de que podemos fornecer uma ferramenta robusta e eficaz para ajudar na tomada de decisões.

Os dados utilizados são das Unidades de Federação do Brasil conforme link abaixo:

https://basedosdados.org/dataset/ab4af450-6b41-412e-b7cb-ec7030646c3d?table=17405008-7635-4b38-a14b-bdfcf78351b2


## Descrição do projeto

Notebook que avalia os impostos de importação e exportação dos estados brasileiros durante um período. 

## Bibliotecas utlizadas:

import pandas as pd<br>
import seaborn as sns<br>
import matplotlib.pyplot as plt<br>
import plotly.express as px<br>
import numpy as np<br>
import statsmodels.formula.api as smf<br>
import statsmodels.api as sm<br>
import plotly.express as px<br>
import ipywidgets as widgets<br>
import plotly.graph_objects as go<br>

from pycaret.classification import *<br>
from scipy.stats import t<br>
from ydata_profiling import ProfileReport<br>
from sklearn import metrics<br>
from scipy.stats import ks_2samp<br>
from statsmodels.stats.outliers_influence import variance_inflation_factor as vif<br>
from sklearn.metrics import accuracy_score, roc_curve, auc<br>
from sklearn.cluster import KMeans<br>
from sklearn.compose import ColumnTransformer, make_column_transformer, make_column_selector<br>
from sklearn.ensemble import RandomForestClassifier<br>
from sklearn.impute import SimpleImputer<br>
from sklearn.linear_model import LogisticRegression<br>
from sklearn.model_selection import train_test_split<br>
from sklearn.pipeline import Pipeline, FeatureUnion<br>
from sklearn.preprocessing import FunctionTransformer<br>
from sklearn.preprocessing import OneHotEncoder<br>
from sklearn.ensemble import IsolationForest<br>
from sklearn.pipeline import make_pipeline<br>
from imblearn.over_sampling import SMOTE<br>

* Sistema Operacional: Windows 10
* Jupyter Notebook
* Anaconda Navigator

### Instalação

* Instalar as bibliotecas utilizadas


<!-- ## Ajuda

Qualquer ponto importante de problemas ou erros comuns
```
comando para rodar se o programa tiver uma informação de ajuda
```
--> 

## Autores

Lays Félix 
https://www.linkedin.com/in/laysfelixbusiness

## Histórico de versões

Primeira versão

## Licença de uso

Esse projeto possui licença de uso [NAME HERE] - acesse o arquivo LICENSE.md para mais detalhes.

## Fontes de inspiração

Inspiração, trechos de códigos utilizados, etc.
