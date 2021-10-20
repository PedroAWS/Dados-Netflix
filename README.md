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

3 -  Transformar os nomes das colunas em Pt-br usando `tabela.rename` <br><br>

![tabela_pt](https://user-images.githubusercontent.com/92749835/138021915-d5675a35-36f7-4877-9cf7-a9b19c8bf277.png)
<br><br>

4 -  tratando dados VAZIOS da tabela `tabela.dropna(how="any" , axis=0)`<br> deletando linhas vazias

# Principais paises que fazem filme
