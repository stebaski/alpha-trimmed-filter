# alpha-trimmed-filter
Alpha trimmed filter
Alpha trimmed filter is a mixture of median and mean filter for image processing. 
The mask is applied to the image and before the mean value is calculated outliers are excluded.
Note that when the number of outliers approaches the mask size, the filter becomes a median filter and in other case,
when the num_outliers = 0, the filter is equivalent to a mean filter.
