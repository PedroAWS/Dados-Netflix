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

4 -  Tratando dados VAZIOS da tabela `tabela.dropna(how="any" , axis=0)` deletando linhas vazias

# Top 10 referência em filme
<br><br>
![principais](https://user-images.githubusercontent.com/92749835/138022258-92d31e3f-3c8c-4223-be3c-bdb0b98bfc38.png)
<br><br>
![newplot (1)](https://user-images.githubusercontent.com/92749835/138022799-c692cc15-57c8-422b-89e6-9b3753c5f8cd.png)
<br><br>
# Existe mais filme ou programa de tv ?

![newplot (2)](https://user-images.githubusercontent.com/92749835/138022801-ed75af5e-bd63-4a44-81c7-de9c42dd2d88.png)
# Genero
![newplot (3)](https://user-images.githubusercontent.com/92749835/138022810-139f7d14-e5dd-48fe-9d5b-2abd11a26226.png)
