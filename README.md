<div align="center">
  <h1> AI ДЛЯ АНАЛИЗА РЕЗЮМЕ </h1>
</div><br/><br/>

## О ПРОЕКТЕ
<div align="center">
    <p align="justify"> 
      Инструмент, который анализирует информацию из резюме с помощью обработки на естественном языке и находит ключевые слова, группирует их по секторам на основе их ключевых слов. И, наконец, показывает рекомендации, прогнозы,        аналитику соискателю / рекрутеру на основе соответствия ключевых слов.
    </p>
</div>

## ПРИМЕНЕНИЕ
i. Его можно использовать для представления всех данных резюме в структурированном табличном формате, а также в формате csv, чтобы организация могла использовать эти данные в аналитических целях

ii. Предоставляя рекомендации, прогнозы и общую оценку, пользователь может улучшить свое резюме и продолжить его тестирование с помощью нашего инструмента

iii. И это может увеличить посещаемость нашего инструмента благодаря разделу "Пользователи"

iv. Он может быть использован рекрутерами для получения информации о соискателей и их резюме перед трудоустройством

v. Также для получения аналитических данных о ролях, которые больше всего ищут соискатель

<!-- TechStack -->
## ЧТО БЫЛО ПРИМЕНЕНО
<details>
  <summary>Frontend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/HTML">HTML</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS">CSS</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/JavaScript">JavaScript</a></li>
  </ul>
</details>

<details>
  <summary>Backend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li><a href="https://www.python.org/">Python</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.mysql.com/">MySQL</a></li>
  </ul>
</details>

<details>
<summary>Modules</summary>
  <ul>
    <li><a href="https://pandas.pydata.org/">pandas</a></li>
    <li><a href="https://github.com/OmkarPathak/pyresparser">pyresparser</a></li>
    <li><a href="https://pypi.org/project/pdfminer3/">pdfminer3</a></li>
    <li><a href="https://plotly.com/">Plotly</a></li>
    <li><a href="https://www.nltk.org/">NLTK</a></li>
  </ul>
</details>

## ТРЕБОВАНИЕ К ПРОЕКТУ
### Установите все это, чтобы сделать ваш процесс более плавным.
1) Python (3.9.12) https://www.python.org/downloads/release/python-3912/
2) MySQL https://www.mysql.com/downloads/

## Установка и настройка

Чтобы запустить этот проект, выполните следующие задачи

Загрузите файл кода вручную или с помощью git
```bash
git clone https://github.com/THRuder06/Analyze-Resume-Ai.git
```

Создайте виртуальную среду и активируйте ее **(рекомендуется)**

Загрузка библиотек с ``requirements.txt``
```bash
cd../..

pip install -r requirements.txt

python -m spacy download en_core_web_sm

```

После завершения установки создайте базу данных ``sra``

``Поздравляем ваша настройка и установка завершена``.

Запустите файл ``App.py`` с помощью
```bash
streamlit run App.py

```

## ИСПОЛЬЗОВАНИЕ
- После настройки он будет выполнять все действия автоматически
- Вам просто нужно загрузить резюме
- Попробуйте сначала загрузить резюме в папку `Uploaded_Resumes`.
- Идентификатор админа HR - это `hr`, а пароль - `123`.
