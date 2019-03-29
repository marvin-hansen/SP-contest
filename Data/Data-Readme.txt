
The 50Y dataset contains accurate open, high, low, and close price as well as volume and daily price percentage change.
The 50 year data is recommended because of its: 
- Correctness
- Completeness (no missing values)
- Easy handling (almost no type conversion required)
- Easy feature engineering 


The 90 year data set needs a lot of special treatment because it:
- Misses 50 data records (NaN)
- Misses an unknown number or data records (many gaps in time series)
- Date conversion can be painful 
- Uses non-standard column names
- Does not contain day percentage change 
- Because open, high, low prices are missing, only a subset of available technical indicator can be calculated.

But hey, it's 90 years of data (~24k rows) that includes the great 1930 recession so if you can make it work, it may work for your model. 
