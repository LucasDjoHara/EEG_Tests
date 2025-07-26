O notebook EEG_adaptado utiliza uma base de dados que contém informações estatísticas acerca de leituras de EEG com labels classificadas em 3 tipos de emoção, de modo a avaliar o desempenho de algoritmos de ML para realizar a previsão da emoção a partir da leitura do EEG. 

O notebook EEG_adaptado_dreamer realiza a mesma metodologia, porém em uma base de dados que classifica a intensidade do estímulo em 3 categorias, em uma escala de 1 a 5. Nota-se que o desempenho das previsões é extremamente não satisfatório.

Portanto, o notebook EEG_Dreamer_redeneural utiliza de uma rede neural para realizar previsões acerca da intensidade do estímulo, apresentando desempenho superior.

Já a base de dados SEED_V é semelhante à utilizada em EEG_adaptado, porém em vez de extrair média e variância da leitura do canal EEG, extraiu-se a densidade de entropia. Nesta base de dados, existem 720 leituras e a precisão do modelo de random_forest chegou a cerca de 92%. Para cada leitura, utilizou-se a leitura de 62 DE features, uma vez que o aparelho utilizado possuia 62 eletrodos.


O arquivo "emotions.csv" está disponível no link: 
https://drive.google.com/file/d/1cUY2dRzVSqN4pAGYKiOp-5hsvG-jNUjh/view?usp=sharing

O arquivo "dreamer_preprocessed_features.csv" está disponível no link: 
https://drive.google.com/file/d/1sP3lBhEE83IoS-3XEaB8FfHvAq_Dl9FT/view?usp=sharing

O arquivo "de_features_62.csv" está disponível no link: 
https://drive.google.com/file/d/1TMn-d73p04aRAHiZnrDrVhYPe73pmJwP/view?usp=sharing
