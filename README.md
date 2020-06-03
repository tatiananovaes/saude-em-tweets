Data: maio de 2020

# Saúde em Tweets - Uma Tarefa de Clusterização

Trabalho de Conclusão de Curso apresentado ao Curso de Especialização em Ciência de Dados e Big Data como requisito parcial à obtenção do título de especialista pela PUC Minas.

O trabalho visa à análise de textos de tweets relacionados à saúde, no intuito de buscar insights que possam auxiliar os profissionais da área no exercício de suas atividades. O objetivo do projeto é, portanto, analisar uma coleção de tweets de agências de notícias, postados no período de 2011 a 2015, no intuito de descobrir novos padrões nos dados e identificar temas ou tópicos de interesse ligados à saúde, que possam ser utilizados por especialistas da área. Para tanto, os dados foram pré-processados por meio de aplicação dos modelos Bag of Words e TF-IDF e, em seguida, agrupados em clusters pelo modelo K-Means de aprendizado de máquina não supervisionado.

# Dados
Os dados foram obtidos no sítio da UCI Machine Learning Repository em 29 de janeiro de 2020. O conjunto de dados – Health News in Twitter Data Set – consiste em 16 arquivos texto, cada um relacionado a uma conta Twitter de uma agência de notícias, relativas ao período de 2011 a 2015. Os dados, por seu turno, foram coletados em 2015 por meio de Twitter API por Amir Karami, da Universidade da Carolina do Sul [1].

# Dependências
O projeto foi executado por meio da linguagem de programação interpretada Python no Jupyter Notebook. As principais bibliotecas utilizadas foram OS, Numpy, Pandas, Matplotlib, Seaborn, NLTK, RE, Sklearn e Wordcloud.

# Créditos
[1] KARAMI, A., Gangopadhyay, A., ZHOU, B., & KHARRAZI, H. Fuzzy approach topic discovery in health and medical corpora. International Journal of Fuzzy Systems, 1-12., 2017. Disponível em: <https://archive.ics.uci.edu/ml/datasets/Health+News+in+Twitter>. Acesso em: 29/01/2020.
[2] STACK OVERFLOW. Disponível em: <https://stackoverflow.com/questions/46000191/utf-8-codec-cant-decode-byte-0x92-in-position-18-invalid-start-byte>. Acesso em: 11/02/2020.
[3] STACK OVERFLOW. Disponível em: <https://stackoverflow.com/questions/45037907/python-astypestr-gives-settingwithcopywarning-and-requests-i-use-loc>. 
[4] NASSIF, Luís Filipe da Cruz. Técnicas de Agrupamento de Textos Aplicadas à Computação Forense. Dissertação de Mestrado – Universidade de Brasília - UnB. 2011, p. 15.
[5] BIRD, Steven, Edward Loper e Ewan Klein, Natural Language Processing with Python. O’Reilly Media Inc., 2009.
[6] GOMES, M. Lucas. Clusterização de texto de reclamação não supervisionada usando K-means com python. Disponível em: < https://lamfo-unb.github.io/2019/09/02/cluster_texto/>. Acesso em: 17/02/2020.
[7] SCIKIT LEARN. Sklearn.decomposition.TruncatedSVD. Disponível em: < https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.TruncatedSVD.html > . Acesso em 10/03/2020.
[8] SAWANT, Mrunal. Truncated Singular Value Decomposition (SVD) using Amazon Food Review. Disponível em: <https://medium.com/swlh/truncated-singular-value-decomposition-svd-using-amazon-food-reviews-891d97af5d8d>. Acesso em: 05/03/2020.
[9] SANTANA, Felipe. Algoritmo K-means: Aprenda essa Técnica Essencial através de Exemplos Passo a Passo com Python. Disponível em: <https://minerandodados.com.br/algoritmo-k-means-python-passo-passo/>. Acesso em 04/03/2020.






