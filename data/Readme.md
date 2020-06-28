## Dataset
We provide three processed datasets in : Movielens(movie), Last-FM(music), and Amazon-book(book).
* You can find the full version of recommendation datasets via [Movielens](https://grouplens.org/datasets/movielens/), [Last-FM](http://www.cp.jku.at/datasets/LFM-1b/), [Amazon-book](http://jmcauley.ucsd.edu/data/amazon).
* The linkage used in this dataset is from [KB4Rec](https://github.com/RUCDM/KB4Rec).

Each dataset is organized with following structure:
- `data-name/`
  - `rs/`
    - `u_map.dat`: user id mapping file;
    - `i_map.dat`: item id mapping file;
    - `i2kg_map.tsv`: mapping from original item id to freebase entity;
    - `ratings.txt`: raw rating file of dataset.
  - `kg/`
    - `e_map.dat`: entity id mapping file;
    - `r_map.dat`: relation id mapping file;
    - `train.dat`: mapped triples of train set;
    - `valid.dat`: mapped triples of validation set;
    - `test.dat`: mapped triples of test set.

## Download
Download preprocessed datasets from [google drive](https://drive.google.com/file/d/1zTss-wi7FGi3FmiqBZ8IFllgImoaC53_/view?usp=sharing)
    
## Acknowledgement
Any scientific publications that use our codes and datasets should cite the following paper as the reference:
```
@inproceedings{UPGAN-WWW-2020,
  author    = {Gaole He,
               Junyi Li,
               Wayne Xin Zhao,
               Peiju Liu and
               Ji{-}Rong Wen},
  title     = {Mining Implicit Entity Preference from User-Item Interaction Data for Knowledge Graph Completion via Adversarial Learning},
  booktitle = {{WWW}},
  year      = {2020}
}

@article{Zhao-DI-2019,
   author = {Wayne Xin Zhao and
               Gaole He and
               Kunlin Yang and
               Hong{-}Jian Dou and
               Jin Huang and 
               Siqi Ouyang and
               Ji{-}Rong Wen},
   title = {KB4Rec: A Data Set for Linking Knowledge Bases with Recommender Systems},
   journal = {Data Intelligence},
   volume = {1},
   number = {2},
   pages = {121-136},
   year = {2019},
   doi = {10.1162/dint\_a\_00008},

   URL = {https://doi.org/10.1162/dint_a_00008},
}
```
Nobody guarantees the correctness of the data, its suitability for any particular purpose, or the validity of results based on the use of the data set. The data set may be used for any research purposes under the following conditions:
* The user must acknowledge the use of the data set in publications resulting from the use of the data set.
* The user may not redistribute the data without separate permission.
* The user may not try to deanonymise the data.
* The user may not use this information for any commercial or revenue-bearing purposes without first obtaining permission from us.
