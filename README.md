## MLOps проект

#### Задача:
обучение модели fasttext по книге Льва Толстого «Война и мир», выстраивания эмбеддингов на уровне слов для дальнейшего использования модели в различных целях (например, дообучение под более узкие цели)

#### Данные: 
https://www.gutenberg.org/files/2600/2600-0.txt

Для поставленной задачи потребуется предварительная обработка текста, т. е. избавление от знаков препинания и избыточных символов, написание каждого слова строчными буквами

#### Нейросети и библиотеки:
    - `gensim.models: FastText`
    - `gensim.models.word2vec: PathLineSentences`
    - `nltk`
    - `faiss`
    - `numpy`
