# Impact of Minimum Wage on Employment in LA

## Motivation
While keeping up with local news, I noticed a recurring debate: "Does raising 
the minimum wage actually hurt employment?" Some argue it reduces hiring, 
others say it boosts local spending. I wanted to move beyond textbook 
arguments and test this with real-world data from my own backyard — Los 
Angeles. This kind of question using data to evaluate the real-world 
impact of a policy is the same analytical process I want to apply to 
environmental and infrastructure decisions in engineering.

## Project Goal
Is there a statistically significant negative correlation between minimum 
wage hikes and employment rates in the Los Angeles area?

## Data
- Location: Los Angeles, California
- Time range: 2010–2026
- Language: Python
- Data source: U.S. Bureau of Labor Statistics (unemployment rate, 
  employment-to-population ratio)

## Process and Reflection
Finding and cleaning the data took much longer than I expected. This was my 
first time working with a government data source directly, and figuring out 
how to navigate BLS's website was harder than I thought — tutorials and 
documentation from other analysts helped a lot. My first attempt to pull 
data with a library kept failing, so I switched to a simpler, more manual 
approach that I could fully understand and troubleshoot myself.

I ended up writing two versions of the same analysis using different 
methods, which helped me understand the underlying logic much better than 
if I had only done it one way. I also went back and renamed variables and 
simplified my comments so that the code reflects how I actually think 
through a problem. I want to be able to open this again in two months and 
immediately understand my own reasoning, not just the output.

## Future Application
This project reinforced that I want to keep working with real datasets to 
answer concrete questions, rather than staying purely theoretical. I'm 
planning to apply the same approach pulling public data, cleaning it, 
and testing a hypothesis to environmental datasets going forward.
