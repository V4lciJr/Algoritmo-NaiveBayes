# Algoritmo-NaiveBayes
Naive Bayes é um algoritmo que gera uma tabela de probabilidades a partir de uma técnica de classificação de dados, é baseado nos estudos de Thomas Bayes e “naive” significa ingênuo, uma referência a linha de análise do algoritmo paa as características da base de dados em questão.
Na prática, o algoritmo Naive Bayes é frequentemente utilizado para classificar textos, como na detecção de spam ou na categorização de documentos. Ele usa a frequência das palavras para calcular a probabilidade de um documento pertencer a uma determinada classe (por exemplo, spam ou não spam).
Embora o algoritmo Naive Bayes seja simples e rápido, nem sempre é o classificador mais preciso, principalmente quando as características são altamente correlacionadas. No entanto, em muitos casos, o Naive Bayes pode fornecer resultados satisfatórios com um pequeno número de dados de treinamento.

Na Biblioteca Scikit-Learn, possui várias implementações para o algoritmo Naive Bayes, na sua documentação você encontra:
- Gaussian Naive Bayes
- Multinomial Naive Bayes
- Complement Naive Bayes
- Bernoulli Naive Bayes
- Categorical Naive Bayes

No nosso exemolo, utilizamos o *Bernoulli Naive Bayes*, que implementa os algoritmos de treinamento e classificação de Naive Bayes para dados que são distribuídos de acordo com distribuições Bernoulli multivariadas; ou seja, pode haver vários recursos, mas cada um é assumido como uma variável de valor binário (Bernoulli, booleana). Portanto, essa classe requer que as amostras sejam representadas como vetores de recursos de valor binário; se receber qualquer outro tipo de dado, uma BernoulliNB instância pode binarizar sua entrada (dependendo do binarizeparâmetro). Você pode encontrar mais informações na documentação da biblioteca Scikit-Learn (Link nas Referências).
A base que utilizamos que é muito usada como objeto de estudos para aulas da aréa, você pode encontra-la nesse site [https://archive.ics.uci.edu/dataset/73/mushroom] ou usar o comando !pip install ucimlrepo no google colab ou no notebook que estiver utilizando.

## Referências
- [https://rockcontent.com/br/blog/naive-bayes/]
- [https://scikit-learn.org/stable/modules/naive_bayes.html]
- [https://joaoclaudionc.medium.com/o-algoritmo-naive-bayes-descri%C3%A7%C3%A3o-e-implementa%C3%A7%C3%A3o-em-python-35757ade6b36]
