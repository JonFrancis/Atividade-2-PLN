# Pré-processamento de Tweets

Realizado o pré-processamento do conjunto de tweets disponível no seguinte link:
https://raw.githubusercontent.com/viniciusrpb/cic0269_natural_language_processing/main/corpus_tweets/twitter-2013train-A.txt

Com base no código-fonte desenvolvido durante a aula, foi complementado as seguintes funcionalidades:

- Remoção de RT's, stopwords, lemmatização (utilizando o dicionário WordNet ou NLTK) ou stemmização (por exemplo, Porter)

- Padronização do texto. Por exemplo, o emoji ":)" ser transformado na palavra "happy"

# Classificação de Imagens de Documentos

Foi feito:

1) Dowload do dataset de documentos escaneados e fazer a divisão em treinamento, validação e testes;

2) Treinamento três redes neurais convolucionais profundas nos dados de teste: AlexNet (sem pré-treinamento), ResNet50 (sem pré-treinamento) e ResNet50 (com pré-treinamento a partir de transfer learning na AlexNet).

2) Comparação dos classificadores baseados nas redes neurais treinadas nas imagens de teste e utilizando a F1-Score macro;

3) Extrair os caracteres de cada documento (em todos: treinamento, validação e testes) e montar um DataFrame contendo o texto formado a partir dos caracteres extraídos. Sugestões: Pytesseract e PyMuPDF.

A parte 3 infelizmente não foi possível, o código do OCR até está implementado, porém demorou muito para rodar e o colab me desconectou da sessão antes de extrair todos os documentos em texto
