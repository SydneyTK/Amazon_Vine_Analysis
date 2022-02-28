# Amazon_Vine_Analysis
Mod 16 Challenge- Big Data 

# Overview 
The below analysis will look at the pet product indistry and specifically compare and contract reveiws of various pet products. Amazon Vine is a program where manufactuers pay a fee to have Amazone provide products to Vine members with the requirement that the member leaves a reveiw. Below you will find the analysis is trying to determine if there is any bias towards Vine members leaving favorable reveiws. 

# Results 
* How many Vine reviews and non-Vine reviews were there?
Overall there was 38,010 reviews. Of that suprisingly only 170 reveiws were from Vine members and 37,840 were not Vine members. 
![Total Votes](/Resources/TotalReviews.png)

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? 
Overall there was 20,677 five-star reviews, roughly 54% of all reviews. Only 65 of these five-star reviews were Vine members, and 20,612 were not. 
![Five-Star Count](/Resources/FiveStar.png)

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? 
Of the Vine reviews 38% were five-star, and of the non-Vine reviews 54% were five-star reviews. 
![Five-Star Count](/Resources/FiveStarVine.png)

# Summary 
Positivity bias is when you are more inclined for some reason (in this case the fact that some reviewers are paid) to say or have possitive opinions. Obviously this could easily skew our data. In this case it is difficult to say with confidance how influential the possibility of a positive bias could be because there was such a small number of vine reviews. Of over 38,000 reviews only 170 were Vine members. More data would definately be helpful. However I would argue that the trend points towards some positivity bias. Of the very small number of paid/vine reveiws 38% were five-star or very possitive, which is not darastically different than 54% of non-paid reveiws that were 5-star. But in the non-paid case ten of thousands of more reviews were taken into consideration. 

## Additional Analysis 
I would be curious to know how the length of the paid 5-star reveiws compares to the length of the un-paid five-star reveiws. Are paid reviewers really hyping up the product with long, detailed and helpful reviews? Or are they just giving it 5-stars? Integrating Natural Language Processing could be of use for this analysis. 
