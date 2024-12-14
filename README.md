Credit to Kai_Nylund for sourcing the dataset used in this project! 
Link to Dataset: https://huggingface.co/datasets/KaiNylund/twitter-year-splits

How to replicate results:

Step 1: 
Download the test/train dataset linked in the folder

Step 2: 
Download the datasets labeled as (year)_test from the HuggingFace page. 

Step 3: 
Upload the files on your Jupyter lab: the datasets mentioned and the notebook file. Upload the HuggingFace datasets with this format: "year"testdata.csv   (for example, 2015testdata.csv, 2016testdata.csv, etc.)

Step 4: Run through the entire notebook. Read comments to get details on the process.

How to modify code/use different data: 

Comments detail every step of the process. To change the classification algorithm, find the existing algorithms and replace the RandomForest (or LogisticRegression) with the algorithm of your choosing.
To use different data for result gathering, follow the code format at the end to properly replicate the steps.

Good luck and happy data collecting!
