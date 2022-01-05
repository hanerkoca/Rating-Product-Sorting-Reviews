### Rating-Product-Sorting-Reviews
#### *Description: The Dataset describes ratings and comments of one electronic device from Amazon.*<br>
*Columns of Dataset:*<br>
reviewerID: ID Number of Customer<br> asin: ID Number of Product<br> reviewer Name: Name of Customer<br> helpful: Vote of comments (positive, negative)<br> reviewText: comment<br> overall: rating<br> summary: summary of comment<br> unixReviewTime: Date of comment, that created from Amazon<br> reviewTime: Date of comment<br> day_diff: Difference between date of Analyse and date of comment<br> helpful_yes: Positive votes of comment (These are from another customers)<br> total_vote: total votes<br>
#### *Firstly we will calculate the average rating and also time-based-weighted average rating. Then, we will see how the current comments effect the average rating.<br> At the end we will sort the comments with wilson lower bound score more accurately.*
