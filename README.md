# Best Location for new Oil Well

Based of data on oil samples from three regions, I picked the top 200 wells with the largest predicted volume of reserves. I trained a linear model to pick the region with the highest profit margin and risk lower then 2.5%. Analyzing the data using Bootstrapping technique.

### Conclusions

Region 0 has the most oil in its reserves but the risk of losses is on the maximum threshold.

Region 1 has the least oil in its reserves but the lowest risk and thus highest profit, the model is very accurate for its data so this should be the development region.

Region 2 has substancial oil in its reserve but the risk of losses is the highest and the model is the least accurate for its data.


It could be beneficial to analyze the distribution of oil reserves per region and the features dispersionand corrolation, in order to improve the models quality for regions 2 and 0. This could lead to lower risk of losses in these regions and make development more secure and profitable.
