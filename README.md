# Trabalho Data Harvesting

## Descrição do Projeto

Esse crawler foi feito para pegar as manchetes das noticias de cada ação especificada para analise e fazer uma analise de sentimento para saber se a média de noticias são mais possitivas ou negativas em relação a cada empresa. 

## Fonte dos dados

[https://news.google.com](https://news.google.com)

## Ferramentas utilizadas

* selenium
* webdriver_manager
* beautifulsoup4
* textblob
* pandas
* seaborn
* matplotlib

## Configurando Ambiente
```shell
# criando ambiente 
python -m venv .venv
source .venv/bin/activate

# instalando dependências
pip install -r requirements.txt
```

## Execução do projeto.

Basta abrir o arquivo [app.ipynb](app.ipynb) no vscode e executar no botão *Run All* no topo do arquivo.


## Resultados obtidos

clicando aqui [app.ipynb](app.ipynb) você vai diretamente para os resultados já executados. Lá é possível ver os gráficos
que exibe a situação de cada empresa analisada.