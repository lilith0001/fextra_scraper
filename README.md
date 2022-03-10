# fextra_scraper
Scrape from fextralife into a dictionary.  
This dictionary contains a dictionary for each armor set.  
Each armor set dictionary contains a dictionary corresponding to each of the armor pieces in the set.  
Each armor piece dictionary contains its stats (skill levels, decoration slots)

# usage
Run the following command in the same directory as this notebook to download the site for processing.  
*warning* it will take ~25 minutes to download.  
You can choose to simply load my example_output.json.  
There is an example for this in the notebook.
`wget -r https://monsterhunterrise.wiki.fextralife.com/Armor+Sets`  
Then, you can just go through the notebook cells.  
