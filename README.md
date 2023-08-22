# nlp_task
#### загрузка необходимых библиотек в виртуальном окружении

    ```bash
    conda create -n nlp_task python=3.10.12
    conda activate nlp_task
    pip install -r requirements.txt
    ```

__Структура репозитория:__
1. intro.ipynb - токенизация и лемматизация заголовков (titles)
2. train.ipynb - обучение knn и catboost с использованием TF-IDF и эмбедингов языковой модели navec
3. data/lemm_titles.pkl  - лемматизированные заголовки документов
4. data/proc_data.pickle - датасет с токенизированными заголовками
