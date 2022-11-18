A value is normalized as follows:
● y = (x – min) / (max – min)

For example, for a dataset, we could guesstimate the min and max observable values as -10 and 30. We can then normalize any value, like 18.8, as follows:

● y = (x – min) / (max – min)
● y = (18.8 – (-10)) / (30 – (-10))
● y = 28.8 / 40
● y = 0.72


A value is standardized as follows:
● y = (x – mean) / standard_deviation

Where the mean is calculated as:
● mean = sum(x) / count(x)
And the standard_deviation is calculated as:
● standard_deviation = sqrt( sum( (x – mean)^2 ) / count(x))

We can guesstimate a mean of 10.0 and a standard deviation of about 5.0. Using these values, we can standardize the first value of 20.7 as follows:
● y = (x – mean) / standard_deviation
● y = (20.7 – 10) / 5
● y = (10.7) / 5
● y = 2.14
