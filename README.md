# Petrovec
Public repository for the paper **Portuguese Word Embeddings for the Oil and Gas Industry: development and evaluation** 

Large files such as corpora and pre-trained models are available at the project page: http://petroles.ica.ele.puc-rio.br/


Diogo Gomes, Fabio Cordeiro, Bernardo Consoli, Nikolas Santos, Viviane Moreira, Renata Vieira, Silvia Moraes, Alexandre Evsukoff. "Portuguese Word Embeddings for the Oil and Gas Industry: Development and Evaluation". Computers in Industry, vol. 124, 2021, p. 103347. doi:10.1016/j.compind.2020.103347.
http://www.sciencedirect.com/science/article/pii/S0166361520305819

## About
Word embedding models are one of the most fundamental units of natural language processing, enabling machine learning algorithms to achieve great generalization capabilities by providing meaningful representations of words, being able to capture syntactic and semantic features based on their context. However, the oil and gas domain-specific vocabulary represents a challenge to those algorithms, in which words may assume a completely different meaning from a common understanding. The Brazilian pre-salt is an important exploratory frontier for the oil and gas industry, with increasing attractiveness for international investments in exploration and production projects, and most of its documentation is in Portuguese. Moreover, Portuguese is one of the largest languages in terms of number of native speakers. Nonetheless, despite the importance of the petroleum sector of Portuguese speaking countries, specialized public corpora in this domain are scarce. This work proposes PetroVec, a representative set of word embedding models for the specific domain of oil and gas in Portuguese. We gathered an extensive collection of domain-related documents from leading institutions to build a large specialized oil and gas corpus in Portuguese, comprising more than 85 million tokens. To provide an intrinsic evaluation, assessing how well the models can encode domain semantics from the text, we created a semantic relatedness test set, comprising 1,500 word pairs labeled by selected experts in geoscience and petroleum engineering from both academia and industry. In addition, we performed an extrinsic quantitative evaluation on a downstream task of named entity recognition in geoscience, plus a set of qualitative analyses, and conducted a comparative evaluation against a public general-domain embedding model. The obtained results suggest that our domain-specific models outperformed the general model on their ability to represent specialized terminology. 

## How to cite this work?
```
@article{GOMES2021103347,
  title = "Portuguese word embeddings for the oil and gas industry: Development and evaluation",
  journal = "Computers in Industry",
  volume = "124",
  pages = "103347",
  year = "2021",
  issn = "0166-3615",
  doi = "https://doi.org/10.1016/j.compind.2020.103347",
  url = "http://www.sciencedirect.com/science/article/pii/S0166361520305819",
  author = "Diogo da Silva Magalhães Gomes and Fábio Corrêa Cordeiro and Bernardo Scapini Consoli and Nikolas Lacerda Santos and Viviane Pereira Moreira and Renata Vieira and Silvia Moraes and Alexandre Gonçalves Evsukoff",
  keywords = "NLP, Machine learning, Oil and gas, Word embeddings"
}
```
