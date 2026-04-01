# Data Storytelling with Mean, Median, and Mode in Python

Imagine you're running a bakery. Every day, you record how many cookies
you sell. Some days are slow, others are booming. To understand...

::::### Data Storytelling with Mean, Median, and Mode in Python 

**Imagine you're running a bakery.** Every day, you record how many
cookies you sell. Some days are slow, others are booming. To understand
your sales better, you need a summary --- a snapshot of your numbers.
That's where *mean*, *median*, and *mode* come in: the three trusty
sidekicks of data analysis.


<figcaption>Photo by <a
href="https://unsplash.com/@masiemay?utm_source=medium&amp;utm_medium=referral"
class="markup--anchor markup--figure-anchor"
data-href="https://unsplash.com/@masiemay?utm_source=medium&amp;utm_medium=referral"
rel="photo-creator noopener" target="_blank">May Lawrence</a> on <a
href="https://unsplash.com?utm_source=medium&amp;utm_medium=referral"
class="markup--anchor markup--figure-anchor"
data-href="https://unsplash.com?utm_source=medium&amp;utm_medium=referral"
rel="photo-source noopener" target="_blank">Unsplash</a></figcaption>


### What Are They?
1.  [**Mean**: The smooth operator. It calculates the *average* by
    spreading your sales evenly across all days.]
2.  [**Median**: The middle grounder. It identifies the *middle value*
    of your sorted sales, telling you what a "typical" day looks
    like.]
3.  [**Mode**: The crowd favorite. It finds the most *frequently
    occurring* sales number, highlighting your best-selling
    scenario.]
::::### The Formula for Success 

Let's break it down:

**Mean**: Add up all the values and divide by the number of days.

**Median**: Sort your data. If odd, pick the middle value. If even,
average the two middle values.

**Mode**: Spot the number that repeats the most.

#### Ingredients for Analysis
- [A dataset (e.g., cookie sales per day:
  `[2, 19, 44, 44, 44, 51, 56, 78, 86, 99, 99]`)]
- Python libraries: `statistics` or
  `numpy`

#### Instructions in Python:
Import required libraries:

```python
import statistics as stats

### or ###

import numpy as np 
```

Step 1: Define your dataset:

``` 
data = [2, 19, 44, 44, 44, 51, 56, 78, 86, 99, 99]
```

Step 2: Calculate the mean:

``` 
mean = sum(data) / len(data)
print(f"Mean: {mean}")

### Or ###

mean = stats.mean(data)
print(f"Mean: {mean}")
```

Step 3: Calculate the median:

``` 
median = stats.median(data)
print(f"Median: {median}")
```

Step 4: Calculate the mode:

``` 
mode = stats.mode(data)
print(f"Mode: {mode}")
```

Step 5: Run all together:

```python
import statistics as stats
data = [2, 19, 44, 44, 44, 51, 56, 78, 86, 99, 99]
mean = sum(data) / len(data)
median = stats.median(data)
mode = stats.mode(data)
print(f"Mean: {mean}")
print(f"Median: {median}")
print(f"Mode: {mode}")
```

#### Output Example
For the cookie sales dataset
`[2, 19, 44, 44, 44, 51, 56, 78, 86, 99, 99]`:

- **Mean**: 56.54 (Your average sales)
- **Median**: 51 (A typical day's sales)
- **Mode**: 44 (Your most frequent result)

By the end of this tutorial, you've learned how to tell a story with
your data. Whether it's cookies, sales, or surveys, the *mean, median,*
and *mode* have your back in uncovering insights. What's your dataset's
story?
::::::::::::By [Kyle Jones](https://medium.com/@kyle-t-jones) on
[December 29, 2024](https://medium.com/p/43c46764e7f6).

[Canonical
link](https://medium.com/@kyle-t-jones/data-storytelling-with-mean-median-and-mode-in-python-43c46764e7f6)

Exported from [Medium](https://medium.com) on November 10, 2025.
