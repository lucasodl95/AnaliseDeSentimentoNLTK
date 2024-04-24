# Análise de Sentimento com Naive Bayes e NLTK

Este projeto consiste em uma aplicação de classificação de sentimento utilizando o algoritmo Naive Bayes para análise de textos em português. O objetivo é classificar frases como positivas ou negativas com base em um conjunto de dados rotulado.

## Pré-requisitos

Antes de executar este projeto, certifique-se de ter instalado as seguintes bibliotecas Python:

*nltk*

*matplotlib*

*pandas*

*scikit-learn*

Você pode instalar essas bibliotecas via pip. Por exemplo:

```bash
pip install nltk pandas scikit-learn matplotlib
```
Além disso, é necessário fazer o download dos recursos do NLTK executando o seguinte código Python:

```bash
import nltk
nltk.download('rslp')
nltk.download('stopwords')
nltk.download('punkt')
```

## Conjunto de Dados

O conjunto de dados usado neste projeto consiste em frases rotuladas como positivas ou negativas em português. O conjunto de dados deve ser fornecido em formato CSV, contendo pelo menos duas colunas: uma com o texto das frases e outra com os rótulos de sentimento (0 para negativo e 1 para positivo).

## Resultados

Os resultados da análise de sentimento são apresentados em um gráfico de pizza, onde é possível visualizar a proporção de frases classificadas como positivas e negativas. Além disso, a acurácia do modelo Naive Bayes é exibida no console.

## Contribuição

Contribuições são bem-vindas! Se você encontrar algum problema, bug ou tiver sugestões de melhorias, por favor, abra uma issue neste repositório.
