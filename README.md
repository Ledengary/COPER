# COPER
A query-adaptable Semantics-based Search Engine for Persian COVID-19 Articles

with the surge of pretrained language models, a new pathway has been opened to incorporate persian text contextual information. meanwhile, as many other countries, including iran, are fighting against covid-19, a plethora of covid-19 related articles has been published in iranian healthcare magazines to better inform the public of the situation. however, finding answers in this sheer volume of information is an extremely difficult task. in this paper, we collected a large dataset of these articles, leveraged different bert variations as well as other keyword models such as bm25 and tf-idf, and created a search engine to sift through these documents and rank them, given a user’ s query. our final search engine consists of a ranker and a re-ranker, which adapts itself to the query. we fine-tune our models using semantic textual similarity and evaluate them with standard task metrics. our final method outperforms the rest by a considerable margin.

**All implementations and the two datasets of COVID-19 Articles (COPER Dataset) and PerSICK are available in this repository.**
