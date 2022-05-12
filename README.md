# 06-Detection_Emotions_Text_Twitter_spaCy

OBS: Caso o Github não renderize o arquivo .ipynb use os links abaixo:
- <a href="https://nbviewer.org/github/Julio-M39/06-Detection_Emotions_Text_Twitter_spaCy/blob/main/Classificacao_Textos_Tweeter_spaCy.ipynb">Clique aqui!</a>

# Classificação de sentimentos em textos do Twitter

**Base de dados:**
- <a href="https://www.kaggle.com/datasets/augustop/portuguese-tweets-for-sentiment-analysis">Kaggle!</a>

Este conjunto de dados tem tweets em português divididos em classes positivas, negativas e neutras para classificação de polaridade de sentimento. Para coletar e rotular os casos positivos e negativos, utilizou-se o método de supervisão distante do uso de emoticons positivos e negativos utilizados por Go et al. (2009). Para os neutros, foram utilizados textos objetivos de contas de boletins informativos populares e hashtags específicas adaptadas de Kouloumpis et al. (2011).

Nesse trabalho são utilizados apenas os tweets de classe positiva e negativa.

**Conjuntos de dados de treinamento:**
- 50k tweets positivos e negativos sem qualquer tema

**Conjuntos de dados de teste:**
- 5k tweets positivos e negativos sem qualquer tema

Todos eles têm um número igual de casos entre as classes. Seus rótulos de sentimento foram transformados da seguinte forma:
- Rótulo negativo: 0
- Rótulo positivo: 1

As etapas do projeto foram definidas em:
- Etapa 1: Importação das bibliotecas
- Etapa 2: Carregamento das bases de dados
- Etapa 3: Função para pré-processamento dos textos
- Etapa 4: Pré-processamento da base de dados
- Etapa 5: Criação do classificador
- Etapa 6: Testes com uma frase
- Etapa 7: Avaliação de treinamento (base de dados de teste)
