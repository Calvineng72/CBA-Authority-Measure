# Unsupervised Extraction of Workplace Rights and Duties from Collective Bargaining Agreements

This is the (partial) code base for our paper [Unsupervised Extraction of Workplace Rights and Duties from Collective Bargaining Agreements](https://www.research-collection.ethz.ch/handle/20.500.11850/473199.1)

The code base covers:

* Parsing articles
* Computing Authority Scores per Article level

The code base does **_not_** cover:

* Splitting Contracts into articles (we developed a customized solution for converting PDFs to text and splitting labor union contracts which is domain specific and does not translate well to other contracts)
* Aggregating authority scores (we aggregated on contract level, but this depends obviously on the specific use case)
* Our analysis which is also heavily customized for Canadian Union Contracts and does not necessarily translate well to other domain


## Installation

Assuming [Anaconda](https://docs.anaconda.com/anaconda/install/) and linux, the environment can be installed with the following command:
```shell
pip install -r requirements.txt
python -m spacy download en
```


