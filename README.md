###Classificação de Áudio com Python
Com o intuito de aprofundar meus conhecimentos em machine learning, procurei realizar algo
diferente do normalmente eu vejo entre projetos de machine learning, com isso achei o tema de
classificação de áudio, por ser formado em engenharia elétrica, me interessei pelo tema, e aqui
estamos.

Depois de um processo de aprendizagem sobre alguns temas sobre processamento de áudio, consegui
criar este notebook, no início ia abordar modelos baseados em redes neurais também, porém quando
fiz os modelos de machine learning teve ótimos resultados, logo invés de construir redes neurais,
utilizei métodos ensemble.

Quando tive que escolher a base de dados que futuramente iria trabalhar, busquei referen-
cias entre meus conhecidos, então uma certa bióloga que ama abelhas e adora falar delas,
me influenciou muito na minha decisão rsrs, nesse projeto estou utilizando uma base de da-
dos do Kaggle que contém vários áudios de abelhas, divididos entre “abelha” e “não abelha”
https://www.kaggle.com/datasets/andrewlca/bee-audio-object-detection.

As principais bibliotecas usadas nesse projeto foram librosa e scikit learning, sendo librosa
uma poderosa biblioteca para processamento de áudios e scikit learning favorita quando o
assunto é machine learning.

No preprocessamento utilizei a técnica Coeficientes Cepstral de Frequência Mel (MFCC), isto
é, uma escala de transformação não linear onde transforma a faixa de frequência do áudio em uma
faixa de valor diferente, para que quando reproduzir o áudio soar idêntico para uma pessoa, ou
seja, independente da distância que foi gravado o áudio, depois dessa transformação, o áudio vai
ser percebido de igual distância para os humanos.

Os modelos de machine learning foram Regressão Logística, Gaussian Naive Bayes,
K Vizinhos mais Próximos, Floresta Randômica, Máquina de Vetores de Suporte (SVM),
também utilizei dois métodos ensemble, que faz o uso de vários modelos para construir um modelo
mais robusto, que são Voting Classifier e Stacking Classifier.

Os resultados superaram minha expectativa, de forma que nem utilizei redes neurais ou otimizei os
modelos criados, todos estão com parâmetros padrões da biblioteca, e nas métricas que usei para
avaliar os modelos, todos ficarão acima de 98%, seja a acurácia, a precisão, o recall ou o F1 score.
