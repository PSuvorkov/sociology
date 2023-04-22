Python для курса Социология города в HSE

Как запускать в Колабе:

КОУЖ для 4 курса: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/4_kurs/4_kurs_kouzh.ipynb)

Тема 4 (данные КОУЖ, описательные статистики по доходам): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/descriptive_statistics.ipynb)

Тема 4 (данные КОУЖ, описательные статистики к ДЗ): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/topic_4_kouzh.ipynb)

Тема 4 (данные БДМО, базисный и цепной темп роста): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/bdmo.ipynb)

Тема 5 (данные ЕМИСС, коэффициент Джини): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/gini.ipynb)

Тема 6 (данные КОУЖ, частоты и частости): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/frequencies.ipynb)

Тема 6 (Данные КОУЖ, Хи-квадрат): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/chi_square.ipynb)

Тема 7 (данные КОУЖ, описательные статистики): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/topic_7_kouzh.ipynb)

Тема 9 (данные опроса использования суточного фонда времени, описательные статистики): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/topic_9_usage_of_time.ipynb)

Тема 10 (данные КОУЖ, описательные статистики): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/topic_10_kouzh.ipynb)

Тема 10 (данные опроса использования суточного фонда времени, описательные статистики): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/topic_10_usage_of_time.ipynb)

Тема 11 (данные КОУЖ, описательные статистики): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/topic_11_kouzh.ipynb)

Тема 12 (данные КОУЖ, описательные статистики): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/topic_12_kouzh.ipynb)

Тема 14 (данные КОУЖ, описательные статистики): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PSuvorkov/sociology/blob/master/notebooks/topic_14_kouzh.ipynb)

Чтобы запустить всё, нажать Runtime (Среда выполнения) > Run all (Запустить всё)

Как запускать на своём компьютере:

1. Склонировать репозиторий через git clone или через зелёную кнопку Code > Download ZIP

2. Установить Python3, если его нет.

### Windows

Инструкция для Windows https://learn.microsoft.com/en-us/windows/python/beginners . Там расписано, как установить VS Code, это необязательно, для курса хватит Jupyter-Notebook . Git для этого курса устанавливать тоже необязательно, но в нем удобно версионировать свои изменения.

### Linux (Ubuntu)

В Ubuntu Python3 предустановлен (проверить командой python3 --version). 

Рекомендуется создать виртуальную среду (см. ниже), во избежание конфликтов с системными библиотеками.

### Mac 

https://docs.python-guide.org/starting/install3/osx/ (возможно, в новых версиях Mac OS также уже предустановлен, проверить командой python3 --version).

Рекомендуется создать виртуальную среду (см. ниже), во избежание конфликтов с системными библиотеками.

3. Установить pip

### Windows

см. инструкцию выше (проверить успешность установки - https://learn.microsoft.com/en-us/windows/python/beginners#install-python)

### Linux (Ubuntu)

https://pip.pypa.io/en/stable/installation/#get-pip-py

### Mac 

https://docs.python-guide.org/dev/virtualenvs/#virtualenvironments-ref

If you installed Python from source, with an installer from python.org, or via Homebrew you should already have pip. Проверить:
```
pip --version
```
```
pip3 --version
```

Если не установлен: https://pip.pypa.io/en/stable/installation/#get-pip-py

4. Создать виртуальную среду virtualenv. Теоретически, этот шаг можно пропустить, практически, не стоит, особенно на Linux или Mac.

https://docs.python-guide.org/dev/virtualenvs/#lower-level-virtualenv

5. Установить jupyter-notebook

https://jupyter.org/install#jupyter-notebook

(если не работает команда для запуска jupyter notebook, попробовать jupyter-notebook

6. Включить виртуальную среду в ноутбуке. Теоретически, этот шаг можно пропустить, практически, не стоит, особенно на Linux или Mac.

https://anbasile.github.io/posts/2017-06-25-jupyter-venv/

7. Установить в виртуальную среду библиотеки для этого репозитория

```
pip install -r requirements.txt
```

