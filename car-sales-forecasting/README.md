## 📄 Descrição

Este projeto tem como objetivo prever a quantidade de vendas de carros para os próximos 20 dias, com base em um dataset público baixado do kaggle.com com base em análise de séries temporais. Utilizando o histórico de vendas, foram aplicadas técnicas de limpeza nos dados, seguidas por técnicas de modelagem estatística para realizar as previsões.

## 🗂 Estrutura do Projeto

* `car-sales-forecasting.ipynb` → Se trata do notebook Python com todo o processo de análise e modelagem.
* `datasets/` → Pasta contendo o dataset sobre o qual foram feitas as análises e outros datasets que temos como saída no projeto.
* `requirements.txt` → Dependências para conseguir executar o projeto no notebook Python.
* `README.md` → Arquivo com as informações gerais sobre o projeto.

## 🌐 Tecnologias Utilizadas

* Python
* Numpy
* Pandas
* Matplotlib
* Statsmodels
* Pmdarima

## 📈 Modelos e Testes Estatísticos Utilizados

* Teste de Dickey-Fuller Aumentado
* Teste de KPSS (Kwiatkowski-Phillips-Schmidt-Shin)
* Modelo SARIMA
* Teste de Ljung-Box

## ▶ Como Executar o Projeto

1. **Clone este repositório** digitando no prompt de comando:

    ```git clone https://github.com/rodrigobarbosa333/my-projects.git```

2. **Navegue até o diretório onde está o notebook** digitando o seguinte comando:
	- **No Windows (Prompt de Comando ou PowerShell):** 
	```cd "C:\caminho\para\a\pasta\do\projeto" ```

	- **No macOS/Linux:** 
	```cd /caminho/para/a/pasta/do/projeto ```

3. **Abra o Jupyter Notebook** executando o seguinte código, após o passo anterior:

    ```jupyter notebook```

## 📊 Fonte dos Dados

Os dados utilizados neste projeto foram obtidos no Kaggle:

- [car-sales-report 🔗](https://www.kaggle.com/datasets/missionjee/car-sales-report) - Disponível no Kaggle.

