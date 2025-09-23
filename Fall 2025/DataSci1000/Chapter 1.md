Individuals - Objects described by our data

Variables 
- Attribute of an individual
- Can take on different types of values (e.g. integer, boolean, type)
Categorical Variables
- A variable that takes on one of a fixed number of labels
- A **qualitative** property
	- such as colour
Quantitative Variables
- Takes on numerical value where arithmetic makes sense
- Measures something
	- such as height or weight


Datasets with variables have tables for interpretations of each variable and their own description

Exploratory data analysis is the process of using statistical tools and ideas to examine the functions of the data
- Essentially messing around with the data to find trends/patterns or correlations

The distribution of a variable describes the possible values and the frequencies at which they occur

Chapter 1 focuses on visualizing distributions

Pie Chart:
- Angle/Area of each slice represents the relative frequency (percentage) of individuals in each category
- Categories should be mutually exclusive and exhaustive (meaning all individuals will fit at least one category)
- Kinda Useless
	- Cannot select more than category
	- Cannot be used when data does not sum to 100%

Bar Graphs: 
- Consists of bars whose heights represent the proportion or frequency
- Height represents number typically
- Each bar can represent a different category
- Should have spacing in between each bar
- Measures any quantitative variable (relative frequency or count included)

Histogram:
- Displays quantitative data
- Consist of adjacent bars whose heights represent the count or percent (if relative) of values falling in each interval
- Bars must be adjacent to cover the exhaustive list of quantitative list with the exception of empty space indicating no individuals in those intervals
- Measures relative frequency or count
- More bins needed for greater detail in distribution which allows one to see the density curve

Interpreting Histograms:

Center (Location of distribution) - mean or median

Shape - Symmetrical or skewed
Symmetrical when both left and right sides extend out approximately equally from the center

Skewed when one side extends further out
- Positive/Right skewed when extending out right
	- Typical example is wealth/income distribution with income as x-axis, and percentage of people as y-axis
- Negative/Left skewed when extending out left
![[Screenshot 2025-09-09 at 1.00.55 PM.png]]

Variability/Spread - variance, standard distribution 
range, IQR (interquartile range)![[Screenshot 2025-09-09 at 1.02.42 PM.png]]
Image shows datasets with same mean and averages, but different standard deviation

Standard deviation: Average deviation from the mean/median, shown as a distribution


Outlier - observations that break the pattern
- can be necessary to remove to make visualization more useful
![[Screenshot 2025-09-09 at 1.06.52 PM.png]]

Stemplots:
- graphical display of quantitative date using the actual digit of the observation to display the distribution of the data
- leaf is the last digit of an observation's number
- stem would be the common starting digits
![[Screenshot 2025-09-11 at 11.35.48 AM.png]]
Stem is left side of y-axis
- Stem essentially becomes the bin/interval of what would be a histogram
Leaf is right side
- Leaf is essentially how many occurences there are within each stem/interval
**If a stemplot functions as a rotated histogram, what is the point?
- Would appear to just be a easy table to make to model small sets of data while allow one to see the precise values of the data within each interval
- It has more restricted intervals than a histrogram as each digit can only really be divisible by 2

Time Series Plot:
- A graphical display of (usually) quantitative variable against time (time on x-axis)
- 

