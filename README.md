# Research Artifact: From Academia to Software Development: Publication Citations in Source Code Comments

https://github.com/supatsara-wat/PaperCitationCodeComments

This is a research artifact for the paper: **From Academia to Software Development: Publication Citations in Source Code Comments**. This artifact is a repository consisting of our dataset, statistically representative sample of identified comments, and qualitative coding results reported in our paper. The purposes of this artifact are to enable researchers to replicate our mixed-methods quantitative results of the paper, and to reuse the dataset for further software engineering research.

## Contents
* `README.md` - this file.
  * [Statistically representative sample of 372 comments](https://docs.google.com/spreadsheets/d/e/2PACX-1vQbTS2W0Im6wArUgS8g0pgBX5iV3uqGPcQ-W5UJwKNYpJyvhmUuUx7FSO8VbcVCJZpLZ2LmM3cYQ_31/pubhtml?gid=0&single=true)
  * [Qualitative coding results](https://docs.google.com/spreadsheets/d/e/2PACX-1vRtfzcI0u5p6aGJeHJrezJXz4r6V3jFGG6cypOHprYsAqzv23iXQ_b0IbEmbONvkVfj6yrWb0jDHcpE/pubhtml?gid=0&single=true)
* `dataset.csv` - 272 comments used to train our model (.csv format).
  * The dataset follows a BIO type tagging, which B stands for beginning, I stands for inside, and O stands for outside (of an entity), and consists of the following entities:
    * AUTHOR = author's name
    * BOOKTITLE_OR_JOURNAL = book title
    * TITLE = publication title
    * YEAR = year
    * MONTH = month
    * PAGES = page number
    * VOLUME = volumn number
    * NUMBER = book number
    * ISBN = international standard book number
    * DOI = digital object identifier
    * ISSN = international serial standard number
    * ADDRESS = address
    * PUBLISHER = publisher's name
    * URL = URL link
  
## Authors
- Akira Inokuchi
- [Yusuf Sulistyo Nugroho](https://yusufsn.github.io/)
- Supatsara Wattanakriengkrai
- Fumiaki Konishi
- [Hideaki Hata](https://hideakihata.github.io/)
- [Christoph Treude](http://ctreude.ca/)
- [Akito Monden](http://digi-ana.sakura.ne.jp/)
- Kenichi Matsumoto
