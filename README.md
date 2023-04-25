###Classificação de Áudio com Python

Com o objetivo de aprofundar meus conhecimentos em machine learning, eu decidi me aventurar em um projeto diferente do que costumo fazer. Escolhi o tema de classificação de áudio, o que me interessou por ser formado em engenharia elétrica. Depois de estudar e aprender sobre processamento de áudio, criei um notebook utilizando métodos ensemble ao invés de redes neurais, e escolhi a base de dados do Kaggle que contém áudios de abelhas, que foi sugerida por uma bióloga amante de abelhas.

As bibliotecas principais utilizadas nesse projeto foram librosa e scikit-learn, sendo a primeira ideal para processamento de áudio e a segunda, minha favorita para machine learning. No preprocessamento, utilizei a técnica Coeficientes Cepstral de Frequência Mel (MFCC) para transformar a faixa de frequência do áudio em uma faixa de valor diferente, permitindo que o som fosse percebido de igual distância para os humanos, independente da distância em que foi gravado.

Os modelos de machine learning utilizados foram Regressão Logística, Gaussian Naive Bayes, K Vizinhos mais Próximos, Floresta Randômica e Máquina de Vetores de Suporte (SVM), além de dois métodos ensemble: Voting Classifier e Stacking Classifier. Surpreendentemente, todos os modelos criados, mesmo com parâmetros padrões da biblioteca, apresentaram resultados acima de 98% nas métricas utilizadas para avaliação, tais como acurácia, precisão, recall e F1 score.

Esse resultado superou minhas expectativas e me mostrou o poder dos métodos ensemble quando aplicados a um conjunto de dados de áudio, tornando o modelo mais robusto e preciso.

Embora eu não tenha utilizado redes neurais ou otimizado os modelos criados, os resultados obtidos foram muito satisfatórios, e me mostraram a importância de escolher a técnica de preprocessamento correta para um conjunto de dados de áudio, bem como a importância da escolha adequada de algoritmos de machine learning e dos métodos ensemble.

Além disso, esse projeto me permitiu aprofundar meus conhecimentos em processamento de áudio e machine learning, o que me motivou a buscar novos projetos que possam me desafiar e me permitir continuar crescendo como profissional.
