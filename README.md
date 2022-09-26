# amazon-titles
A dataset (.csv) of 324,511 book reviews from Amazon's US marketplace containing reviewer comments on book titles.

# General info
amazon-titles is a .csv file of 324,511 book reviews from Amazon's US marketplace containing reviewer comments on book titles. The original file from which the dataset was created can be found [here] (https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) (scroll down to the Books_v1_02 file).

The dataset contains the following variables: "review_body", "review_id", "product_id", "product_title", "review_headline"
The values for "product_id" are isbn numbers.

# Usage
This dataset was used for a research project on how reader-reviewers discourse about book titles in online reviews. The output of this research is forthcoming in the journal _[Language and Literature](https://journals.sagepub.com/home/lal).

# Project status
This project is no longer being worked on. 

# Room for improvement
The only preprocessing that was done on the file was to select the five variables identified in the "General info" section above from the 15 variables available in the original file; and to filter out only those observations in which the "review_body" contained the string "*title*". This pre-processing was done in [TAD](https://www.tadviewer.com/) and SPSS. The file was not cleaned or deduplicated. 
