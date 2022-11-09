# Description
## MS LJMU Azure Log Reg.ipynb
- Basic EDA on Azure 2019 Trace dataset and Logistic regression applied on vmcategory to figure out if it is correlated
- Also isolate anomolous vms with negative p95 as our target group

## ClusteringFiltering.ipynb
- Perform clustering on filtered dataset 
- targeting vms where there is a spike between 95 percentile and max where average remains more or less linear

## SingleTSDataset.ipynb
- To create datasets of the desired sample from the entire 200 plus gb dataset

## GRU_TS_*.ipynb
- Multiple VM datasets run to predict max cpu usage
- calculate the savings if they reduce the infrastructure to half in time when not required
