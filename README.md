# CSE_676_project
With the increased use of e-commerce websites, it is helpful to have a quick and valuable insight of reviews of products bought online, to discern important customer feedback in a short summary, leaving out irrelevant information. While the overall rating provides a general indication of the product’s validity, the customer review section provides a more detailed picture to people who plan on buying the product. We propose an application type project which aims to summarize the customer feedback using Natural Language Processing techniques to improve the buying and selling experience for our target audience: customers and sellers on e-commerce platforms. In this project, we perform Extractive Text Summarization on product reviews for any given E-commerce platform, for an impactful and improved consumer experience. We are experimenting with 3 models, fine tuning them and comparing their results and analysis.

Following models are trained :

google/T5 model <br/>
google/Pegasus model <br/>
facebook/Bart model <br/>

Dataset was downloaded from [here](https://huggingface.co/datasets/amazon_us_reviews) but only a subset of the dataset was downloaded and used due to computational issues.<br/>

Instructions to run the project:<br/>

- You can download the dataset from the current repository: data.csv
- Simply run each notebook and check the results.<br/>
- Run the following notebooks:
  - T5_summarization_for_amazon_us_reviews_cse676.ipynb 
  - facebook/BART.ipynb 
  - PEGASUS.ipynb 

If running these notebooks on colab or any other platform, you need to set output directories or init directories wherever applicable in the notebook


References: <br/>
https://shivanandroy.com/fine-tune-t5-transformer-with-pytorch/




