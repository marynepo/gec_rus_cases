# Разработка нейросетевого метода расчета статистики ошибок употребления падежей в текстах на русском языке

Описание:
В этой работе была обучена модель для исправления ошибок в употреблении падежей с предлогами и был сделан анализ ошибок носителей русского языка в собранном нами наборе письменных данных с помощью созданной модели.

1) Создание датасета - download_lenta.py
2) Генерация ошибок - noisy_data.ipynb
3) Файнтюнинг T5 и предсказание результатов - simple_t5.ipynb
4) Разметка исправлений - tag_mistakes.py

Источники использованных скриптов:

1) [Создание датасета](https://github.com/yutkin/Lenta.Ru-News-Dataset)


[Файлы с предобученной моделью](https://drive.google.com/drive/folders/1-0-AHZSeooAX9uNX0qPPu5bwup6Ys_-Y?usp=sharing)

[Датасет со сгенерированными ошибками](https://www.kaggle.com/datasets/nmaria/noisy-news)

[Датасет с реальными текстами](https://www.kaggle.com/datasets/nmaria/lentaru-20202021)

[Датасет с предсказаниями модели на реальных текстах](https://www.kaggle.com/datasets/nmaria/real-res)

[Датасет предсказаний на сгенерированных данных](https://www.kaggle.com/datasets/nmaria/t5-res)
