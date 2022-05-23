# CSE_676_project
In this project, we perform Extractive Text Summarization on product reviews for any given E-commerce platform, for an impactful and improved consumer experience. We are experimenting with 3 models, fine tuning them and comparing their results and analysis.

Following models are trained :

google/T5 model <br/>
google/Pegasus model <br/>
facebook/Bart model <br/>

Dataset was downloaded from https://huggingface.co/datasets/amazon_us_reviews but only a subset of the dataset was downloaded and used due to computational issues.<br/>

Instructions to run the project:<br/>

1.You can download the dataset from the current repository: data.csv<br/>
2.Simply run each notebook and check the results.<br/>
3.Run the following notebooks:<br/>
T5_summarization_for_amazon_us_reviews_cse676.ipynb <br/>
facebook/BART.ipynb <br/>
PEGASUS.ipynb <br/>

If running these notebooks on colab or any other platform, you need to set output directories or init directories wherever applicable in the notebook


References: 
https://shivanandroy.com/fine-tune-t5-transformer-with-pytorch/




