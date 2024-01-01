Думаю, как и когда воспользоваться этим - всем понятно

NLP - практика

ALL in one https://colab.research.google.com/drive/1XwzMA4LTW-6-NfUbS883GWu9AvWF6Wwu?usp=sharing

Praktika 1 - https://colab.research.google.com/drive/1n-OF_2V7yHhT3qGG9KEJ1RXqrSdvqpyT?usp=sharing

Praktika 2 - https://colab.research.google.com/drive/1vpzCnxlOEfhxhKC_F6DpynVhXmHBHFf8?usp=sharing

Praktika 4 - https://colab.research.google.com/drive/1Ngvo2CxIUYzvLs-pfZJ6_KWDTlVpLhFm?usp=sharing

Praktika 3 - https://colab.research.google.com/drive/1Mff4CbhumqJNKX2SpT7nwWXKoJ6VLmWi?usp=sharing

Praktika 5 - https://colab.research.google.com/drive/1yMaL0-AkN0VsE0Yq-sxk-jWmeI4JB4RP?usp=sharing

Praktika 6 - https://colab.research.google.com/drive/12jGgXLJvYa-tBnqKwg4VpKmmii9l6pQ_?usp=sharing

&nbsp;

Задание 1 = Praktika 1 и т.д.

Задание 1. Сравнить качество методов векторизации CountVectorizer и TF-IDF на примере задачи классификации текстов. Сделать выводы.

Датасет:

from sklearn.datasets import fetch_20newsgroups

newsgroups_train = fetch_20newsgroups(subset='train')

Темы: alt.atheism, misc.forsale, soc.religion.christian, talk.politics.mideast

Алгоритм МО: логистическая регрессия

 

Задание 2. На примере задачи классификации текстов определить насколько предобработка текста (стемминг, лемматизация, стоп-слова и т.д.) влияет на качество обучения модели. Сделать выводы.  

Датасет:

from sklearn.datasets import fetch_20newsgroups

newsgroups_train = fetch_20newsgroups(subset='train')

Темы: alt.atheism, misc.forsale, soc.religion.christian, talk.politics.mideast

Алгоритм МО: логистическая регрессия

 

Задание 3. Сравнить качество обучения классических методов машинного обучения и методов глубокого обучения на примере задачи классификации текстов. Сделать выводы.

Датасет:

from sklearn.datasets import fetch_20newsgroups

newsgroups_train = fetch_20newsgroups(subset='train')

Темы: alt.atheism, misc.forsale, soc.religion.christian, talk.politics.mideast

 

Задание 4. Используя модель Word2vec постройте эмбеддинги и визуализируйте их. Сделать выводы.

Задание 5. Сравнить две модели трансформеров на примере машинного перевода. Перевод следующий: русский -> английский -> испанский -> арабский -> русский. Сделать выводы.

Задание 6. Используя трансформеры сделать генерацию русскоязычного текста. Дообучить трансформер тестами Достоевского и повторить генерацию. Сделать выводы.
