# Amazon_Vine_Analysis
## Overview of the Analysis



## Results
### Address the following questions to provide support for a reponse to the Summary question.

### How many Vine reviews and non-Vine reviews were there?
I believe the best way to answer this question is to create a line of code to count the total number of reviews that were part of the Vine program (paid) and a second line of code that will count the reviews that were not part of the Vine program (unpaid). In the photo below the process was completed:
<img src="Resources/count.png">
As seen in cell 6 above the total number of reviews that were part of the Vine program (paid) are 94. Cell 8 displys the total number of reviews not a part of the Vine program (unpaid): 40,471.

### How many Vine reviews were 5 stars? 
The photo below displays the total number of 5 star paid and unpaid reviews: 15,711. The number of 5 star Vine reviews (paid) is 48.
### How many non-Vine reviews were 5 stars?
The photo also displays there are 15,663 non-Vine (unpaid) 5 star reviews.
<img src="Resources/fivestar_reviews.png">

### What percentage of Vine reviews were 5 stars? 
In the photo below the percentage of 5 star Vine (paid) reviews is 38.2%
### What percentage of non-Vine reviews were 5 stars?
The number of non-Vine (unpaid) 5 star reviews represent 38.9%
<img src="Resources/fivestar_percentages.png">


## Summary 
### Is there any positivity bias for reviews in the Vine program? 
There are two sets of reviews, one set is represented by those who are not a part of the Vine program and the pther set is represented by those who are a part of the Vine program. The analysis does not take into consideration whether those who left a review were able to view previous reviews of others before they made their own review of the video game. Herd mentality is a serious issue when trying to analyize datasets of online reviews. Positive reviews tend to influence others to also leave positive reviews or lessen the severity of a negative review. 

In the case of this analysis, the total percentage of five star reviews is 38.73%. Over one-third of all video game reviews are five star. Due to the small number of Vine reviews, 94, compared to the total number of reviews represented in the dataset, 40,565, and the large percentage of 5 star reviews, 38.2%, by Vine program members, indicates the possibility of positivity bias. Even though both five star percentages are similar, 38.9% of non-Vine reviews are five star and 38.2% for reviews by Vine program members, only suggests to me that both five star review datasets may be influenced by positivity bias.

One additional analysis I would suggest is more focused on language used by the reviewer. Is there a similarity in the laguage used by those who provided five star reviews? Machine learning analysis would help determine the frequency and importance of key words to better understand if indeed reviewers influence each other to the point of an observable possitivity bias.
this concludes my analysis PEM
