# Amazon_Vine_Analysis
## Overview of the analysis: Explain the purpose of this analysis.

	  The purpose of the analysis is to write a report that summarizes the analysis performed in Deliverable 2.
  
## Results: Using bulleted lists and images of DataFrames as support, address the following questions:
* How many Vine reviews and non-Vine reviews were there?

	  There were 1266 Vine reviews and 62,028 non-Vine reviews.
    
    <img width="797" alt="Screen Shot 2021-04-18 at 2 50 22 PM" src="https://user-images.githubusercontent.com/75905911/115157107-6e696f80-a055-11eb-8e4e-867f7a4f82ae.png">

    
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
	
    There are 432 Vine reviews that are 5 stars. There are 29, 982 non-Vine reviews that are 5 stars.
    
    <img width="769" alt="Screen Shot 2021-04-18 at 2 50 52 PM" src="https://user-images.githubusercontent.com/75905911/115157130-89d47a80-a055-11eb-854a-a3a581e91a3a.png">

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
	
  The percentage of Vine reviews with 5 stars is 34.12%.
	The percentage of non-Vine reviews with 5 stars is 48.34%.
  
  <img width="1380" alt="Screen Shot 2021-04-18 at 2 49 34 PM" src="https://user-images.githubusercontent.com/75905911/115157097-5a257280-a055-11eb-9a8e-261eae011803.png">


## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
	
  According to my analysis there is no positivity bias for the Vine review program. The percentage of 5       star reviews is higher (48.34%) for non-Vine reviewers than   Vine reviewers (34.12%). Therefore, the       chance of getting a 5 start rating does not depend on whether a reviewer is being paid to review a         product.
	
  An additional analysis that could be done with the dataset is to find out the statistical summaries using   the .describe() function of the Vine reviews vs. non-Vine reviews.
