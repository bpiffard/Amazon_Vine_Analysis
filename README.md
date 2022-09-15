# Amazon_Vine_Analysis
## Overview of the analysis

The purpose of this analysis was to simulate pulling data into data tables with pre-existing schema that differs from the raw data. The actual analysis was to look into the vine program generated more positive reviews. The vine program was a paid review program. You can read a description of the program [here](https://www.amazon.com/vine/about). The items being revied in this dataset are video games.

## Results

Note that this analysis is very limited as the sample of reviews from the vine program is very small. Here are the results for the vine program:
![y_vine](https://github.com/bpiffard/Amazon_Vine_Analysis/blob/03462126642d09431a0cc15916ce471a5def33dc/images/y_vine_results.png)
Here are the results for reviews from non-vine customers:
![n_vine](https://github.com/bpiffard/Amazon_Vine_Analysis/blob/03462126642d09431a0cc15916ce471a5def33dc/images/n_vine_results.png)
## Summary
As you can see, there are a lot more reviews from normnal customers than those from the vine program. However, the vine reviews seem more likely to be 5-star reviews. Although it can be concluded that the vine program generates more positive reviews, due to the small amount of reviews, it seems unlikely that they alter the resulting overall rating much. One more test that could help us determine the impact of the program is to see if vine ratings are more likely to have a high number of "helpful" votes.
