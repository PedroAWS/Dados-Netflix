# Dados-Netflix
 
## Passos Importar as bibliotecas para analise de dados
1 -  
 `import pandas as pd `<br>
 `import plotly.express as px` <br>
 `import matplotlib.pyplot as plt` <br>
 `import seaborn as sns` <br>
 `import plotly.express as px`<br>
 `%matplotlib inline`<br>
 `import seaborn as sns`<br>

2 -  Importar a tabela para dento do Jupyter <br> tabela = `pd.read_csv("netflix_titles.csv")`

3 -  transformar tabela em portugues usando `tabela.rename`

4 -  tratando dados VAZIOS da tabela `tabela.dropna(how="any" , axis=0)`<br> deletando linhas vazias

