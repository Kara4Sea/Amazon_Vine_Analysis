# Amazon Vine Analysis

## Overview of the analysis
The purpose of this analysis is to understand if being a vine member and receiving payment for reviews results in a positivity bias.

## Results

![vine_table](https://user-images.githubusercontent.com/110419577/212188093-48d8c8c8-fbb1-4622-8aef-7cc67a066776.png)

* In total, there were 285 paid Vine reviews and 31,545 unpaid Non-Vine reviews.
![vine_review_totals](https://user-images.githubusercontent.com/110419577/212186023-97db4e73-34e4-4c27-b1ee-caf2431d4880.png)

* There were 163 5-star Vine reviews, and 14,614 5-star Non-Vine reviews.
![5_star_totals](https://user-images.githubusercontent.com/110419577/212186456-1e2a568e-c243-4efb-8e7e-80353880cf29.png)

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
57.2% of Vine reviews were 5-stars. 46.3% of Non-Vine reviews were 5-stars. I calculated this bye taking each 5-star total and diving that by the reviews total and then multiplying by 100.

## Summary

There is a positivity bias for reviews in the Vine program as a larger percentage of Vine reviews were 5-star than Non-Vine reviews. I can suggest an additional analysis to support this statement. In this analysis, we would find a sample of "Unhelpful Reviews", that is reviews that when the 'helpful_votes' are divided by 'total_votes' are less than 0.5. And then compare the percentage of 5-star reviews between Vine and Non-Vine. It's possible that we could see a larger amount of Unhelpful Reviews within the Vine group at 5-stars.
