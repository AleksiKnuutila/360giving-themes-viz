# 360giving-themes-viz

An entry to the 360 Giving Data Visualisation challenge. View it [https://aleksiknuutila.github.io/360giving-themes-viz/](here).

This visualisation answers the question "Who has funded what themes throughout the years?"

Visualisations often rely on pre-defined categories. Instead, this visualisation analyses the language funders use to describe their grants with machine learning.

This visualisation displays distinctive phrases for every year. Distinctive phrases are the ones that are frequent in a particular year but not frequent across the entire dataset.

Distinctive phrases are displayed in stronger colours. The larger a word is the more money was available for associated grants.

Scroll downwards the find different years, and click on words for more information. Use a browser on your desktop or laptop.

Distinctiveness is calculated using the [tf-idf](https://en.wikipedia.org/wiki/Tf–idf) algorithm. See the [notebook](https://github.com/AleksiKnuutila/360giving-themes-viz/blob/master/grants-nlp.ipynb) for details on how this is done.
