# data-512-a2

# Goal:
The goal of this project is to explore the concept of 'bias' through data on Wikipedia articles - specifically, articles on political figures from a variety of countries. Here, we have combined a dataset of Wikipedia articles with a dataset of country populations, and used a machine learning service called ORES to estimate the quality of each article.

# Source of Data
Wikipedia data - figshare - https://figshare.com/articles/Untitled_Item/5513449  
Population data - http://www.prb.org/DataFinder/Topic/Rankings.aspx?ind=14  

# Licence of Source Data
Source data falls under the MIT licence. Link: https://wikimediafoundation.org/wiki/Terms_of_Use/en#Our_Terms_of_Use

# Relevant APIs:
For this project, we used the APIs provided by wikipedia.
ORES API for each articles scores - https://ores.wikimedia.org/v3/#!/scoring/get_v3_scores_context_revid_model

# Final Data 
For each article, the dataset provides the following  

country - country  
article_name - name of the article  
revision_id - last revision id corresponding to wikipedia  
article_quality - quality of the aricles from the ORES service  
population - population in that country  
