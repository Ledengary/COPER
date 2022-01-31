# COPER
**A query-adaptable Semantics-based Search Engine for Persian COVID-19 Articles**

with the surge of pretrained language models, a new pathway has been opened to incorporate persian text contextual information. meanwhile, as many other countries, including iran, are fighting against covid-19, a plethora of covid-19 related articles has been published in iranian healthcare magazines to better inform the public of the situation. however, finding answers in this sheer volume of information is an extremely difficult task. in this paper, we collected a large dataset of these articles, leveraged different bert variations as well as other keyword models such as bm25 and tf-idf, and created a search engine to sift through these documents and rank them, given a user’ s query. our final search engine consists of a ranker and a re-ranker, which adapts itself to the query. we fine-tune our models using semantic textual similarity and evaluate them with standard task metrics. our final method outperforms the rest by a considerable margin.

**All implementations and the two datasets of COVID-19 Articles (COPER Dataset) and PerSICK are available in this repository.**
  
## Reference 

```
@INPROCEEDINGS{9443151,
  author={Khanmohammadi, Reza and Mirshafiee, Mitra Sadat and Allahyari, Mehdi},
  booktitle={2021 7th International Conference on Web Research (ICWR)}, 
  title={COPER: a Query-Adaptable Semantics-based Search Engine for Persian COVID-19 Articles}, 
  year={2021},
  volume={},
  number={},
  pages={64-70},
  doi={10.1109/ICWR51868.2021.9443151}
}
```
