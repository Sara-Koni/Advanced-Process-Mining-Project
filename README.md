# Advanced-Process-Mining-Project

This repository contains the necessary files for the replication study of the article "[Prescriptive Process Monitoring for Cost-Aware Cycle Time Reduction](https://arxiv.org/abs/2105.07111)" 
by [Zahra Dasht Bozorgi](https://scholar.google.com/citations?user=XFsTnkgAAAAJ&hl=en/), [Irene Teinemaa](https://irhete.github.io/), [Marlon Dumas](http://kodu.ut.ee/~dumas/), [Marcello La Rosa](http://www.marcellolarosa.com/), 
and [Artem Polyvyanyy](https://scholar.google.com.au/citations?user=CTF5-1EAAAAJ&hl=en).


## Reference

@article{bozorgi2021prescriptive,
  title={Prescriptive Process Monitoring for Cost-Aware Cycle Time Reduction},
  author={Bozorgi, Zahra Dasht and Teinemaa, Irene and Dumas, Marlon and La Rosa, Marcello},
  journal={arXiv preprint arXiv:2105.07111},
  year={2021}
}


## Dependencies

* python 3.9.12
* [NumPy](http://www.numpy.org/)
* [pandas](http://pandas.pydata.org/)
* [scikit-learn](http://scikit-learn.org/stable/index.html)
* [EconML](https://github.com/microsoft/EconML) (for causal models construction)


## Preprocessing

data_bpic17_readyToUse.csv and data_bpic19_readyToUse.csv are the preprocessed files of BPIC 2017 and BPIC 2019 respectively, necessary for the replication study of 
the abovementioned paper. For additional investigations, the event log of BPIC 2018 is also used (https://data.4tu.nl/articles/BPI_Challenge_2018/12688355). 
The preprocessed and sampled version of the BPIC 2018 event log (data_bpic18_readyToUse.csv) is produced by running the file --> BPI 2018 Preprocessing.ipynb. 


## Models

The results from the models can be reproduced by running all the cells of bpi2017_experiments.ipynb, bpi2019_experiments.ipynb, and bpi2018_experiments.ipynb. 


