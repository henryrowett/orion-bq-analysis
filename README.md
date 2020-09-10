# orion-bq-analysis
Analysis on 'data-engineering-prod' data

### Colab
https://colab.research.google.com/github/henryrowett/orion-bq-analysis/blob/master/orion_data_analysis.ipynb#scrollTo=1cIs3cI5PqnW

### What 
- Reads table data from 'data-engineering-prod'
- Collects relevant data
- Uploads json to [google bucket](https://console.cloud.google.com/storage/browser/data-engineering-prod-bq-analysis;tab=objects?forceOnBucketsSortingFiltering=false&project=data-integration-prod&supportedpurview=project&prefix=&forceOnObjectsSortingFiltering=false)
- Writes json to bq table ‘data-integration-prod.data_engineering_prod_bq_analysis.data_engineering_prod_bq_analysis'

