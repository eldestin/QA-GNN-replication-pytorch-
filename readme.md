# This repository refer to [@Michihiro Yasunaga](https://github.com/michiyasunaga/qagnn "Github repository"), please read the paper first. Also, a ppt is provided for better understanding the working flow of this model.

## Please read this file before running the provided Code
## This Repository is a replication for QA-GNN, which is a Question-Answering model using Knowledge Graph for stuctured reasoning


### Dataset Download

The [raw text download address](https://github.com/michiyasunaga/qagnn/blob/main/download_raw_data.sh "Check this file in Github")

Preprocessing step:  

1. Run commensenseqa-cpnet-preprocess.ipynb for each cell, notice that you need to specify the path by yourself
2. Run the process-csqa.ipynb for processing raw data in commonsense qa dataset
3. Run the create-match-pattern-cpnet.ipynb for each cell, specify the path by yourself
4. Run the generate-subgraph.ipynb for each cell

The processing step needs quite a lot time, So if you don't want to run the preprocessing code, please follow the step:

1. Here I use the processing dataset provided by [@Michihiro Yasunaga](https://github.com/michiyasunaga/qagnn "Github repository"), please click the [link](https://nlp.stanford.edu/projects/myasu/QAGNN/data_preprocessed_release.zip "Download address") provided here.

### Train Baseline

You can run the following Notebook from my kaggle account, here is the [link](https://www.kaggle.com/code/eldestinofeng/baseline-qa "My kaggle notebook"). I have already made it public.

### Train QAGNN

I provide the code in a zip file, which is called QA-GNN model.ipynb, you can just run the following cell for training.

That's all.
