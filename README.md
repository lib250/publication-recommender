# DS 598 DL4DS Project - Academic Publication Recommender

Before running any of the notebooks, be sure to download the paper ID to title/abstracts mappings [here](https://snap.stanford.edu/ogb/data/misc/ogbn_arxiv/titleabs.tsv.gz), unzip it, and place the `titleabs.tsv` file in the `./data` directory. With that, the notebooks should be able to be run cell-by-cell.

The project aims to explore the application of link prediction to building a recommender system for academic publications using graph neural networks.
More information can be found in the documents in the `documents` folder (more specifically the final report [document](https://github.com/lib250/publication-recommender/blob/main/documents/Final_Report.pdf)). 

The [mid-project check-in notebook](https://github.com/lib250/publication-recommender/blob/main/midproject_checkin.ipynb) contains code progress up to the Mid-project Check-in milestone. This includes some preliminary tests such as dataset exploration, visualization, reconciling different distributions of the dataset, and running a basic model on the Cora_ML dataset.

The [evaluations notebook](https://github.com/lib250/publication-recommender/blob/main/Evaluations.ipynb) contains further analyses and qualitative evaluations of the recommended papers along with some notes. It also includes the training on the ogbn-arxiv dataset along with training using the modified loss function described in the final report.

