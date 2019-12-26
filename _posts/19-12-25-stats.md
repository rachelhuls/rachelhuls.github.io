---
title: Statistics
category: math
tags: [stats, notes]
layout: note
---

Topics from an introductory statistics course. The professor described his course as a social science class with some algebra and a calculator. This is not a proof or mathematicsheavy approach. This course focused on how and when to apply different methods of statistics.  

## Main Sections
  - Descriptive Statistics
  - Probability
  - Confidence Intervals
  - Hypothesis Testing
  
  
---

### Descriptive Statistics
  - Definitions
    - Statistics
    - Descriptive Statistics
    - Parameter vs. Statistic
    - Qualitative vs. Quantitative Data
    - Discrete vs. Continuous Variables
  - Levels of Measurement
    - Nominal
    - Ordinal
    - Interval
    - Ratio
  - Sampling Methods
    - Simple Random 
    - Stratified
    - Cluster
    - Convenience
    - Systematic
  - Frequency Types and Depictions
    - Frequency
    - Relative Frequency
    - Cumulative Frequency
    - Table
    - Stem and Leaf Plot 
  - Numerical Measures of Data
    - Mean
    - Median
    - Mode
    - Standard Deviation
    - Resistant Measure
    - Corresponding Variables for Population & Sample Datta
  - Distributions of Data
    - Normal Distribution
    - Skewed Distribution
  - Measures of Positions
    - The Z Score
    - Percentiles
  - Finding Outliers
    - Chebychev's Rule
    - Empirical Rule
    - Boxplot
    - IQR
  - Five Number Summary
    - Minimum
    - Q1
    - Median
    - Q3
    - Maximum
    

--- 
### Probability

  - Definitions
    - Sample Space
    - Event
    - Simple Event
    - Random Variable
  - Finding Probability
    - Classical Approach
    - Empirical Approach
  - Logic
    - Mutually Exclusive Events
    - Union 
    - Not
  - Probability Distribution of Discrete Random Variable
    - Conditions
    - Expected Value 
    - Fair and Unfair Games
    - Binomial Experiments and Distribution
        - Conditions
        - Ti-84: binompdf & binomcdf
  - Probability Distribution of Continuous Random Variable
    - Normal Probability Density Function
        - Conditions and Properties
        - Ti-84: normalpdf & normalcdf
    - Standard Normal Distribution
        - Conditions
        - Ti-84: InvNorm
    - Sampling Distribution of the Mean
        - The Mean and Standard Deviation
        - Conditions for Normal or Approximately Normal Distribution
            -  Central Limit Theorem
        - Normal Probability Plots
        

---         
### Confidence Intervals
  - Definitions
    - Point Estimate
    - Confidence Interval Estimate
    - Confidence Level
    - Margin of Error
  - Margin of Error
    - Equation
    - Dependencies
  - Constructing a Confidene Interval
    - Mean 
        - One-Sample Z Interval 
        - One-Sample T Interval 
        - Determining Sample Size
    - Population Proportion
        - Review of Binomial Distribution
        - One-Proportion Z Interval
        - Determining Sample Size
    - Variance 
        - Program Int1SD (does not come with calculator)    
        - Intro to Chi Squared Distribution


--- 
### Hypothesis Testing
  - Definitions
    - Null and Alternate Hypothesis 
    - Level of Significance: Alpha
    - Beta
  - Relationship of Alpha and Beta
  - Two Approaches
    - The Classical Approach
    - The P-Value Approach
  - Possible Decisions
    - Fail To Reject Null Hypothesis
    - Reject Null Hypothesis
  - Why can't we accept the Null Hypothesis? 
  - Four Outcomes of Hypothesis Testing
    - True Positive
    - True Negative
    - False Positive: Type 1 Error
    - False Negative: Type 2 Error
  - Understanding Type 1 and Type 2 Errors
  - The 5 Parts of Hypothesis Testing
    - State Null and Alternate Hypothesis
    - Decision Rule
    - Finding the P-Value
    - Decision
    - Interpretation
  - One Sample Testing
    - Mean
        - Z Test 
        - T Test
    - Population Proportion
        - One-Proportion Z Test 
    - Variance
        - Program Test1SD (does not come with calculator)  
  - Two Sample Testing
    - Dependent vs. Independent Samples 
    - Mean
        - Dependent Samples:
            - (Paired) T Test
            - Wilcox Signed Rank Test
        - Independent Samples: Two-Sample T Test
            - Unpooled
            - Pooled
    - Median
        - Wilcox Signed Rank Test 
    - Population Proportion
        - Two-Proportion Z Test 
    - Variance
        - Two-Sample F Test
    - Other
        - Goodness of Fit
        - Contingency Analysis
        - LinReg T Test
        - Anova


--- 


--- 
# Two Sample Testing

## Testing Difference in Population Mean
Questions to ask:
* Dependent or Independent Samples? 

Dependent
: individuals from one sample are used to determine the individuals in the other sample
: matched pairs samples

Independent
: individuals from one sample do not control selection of individuals for the other sample

Pro tip: if the size of sample one is different from the size of sample two, the samples must be independent. Why? There isn't
a way to match each item in the sample with a partner. 

### Dependent Samples
 
#### The (Paired) T Test 
 
     Conditions: 
       * Dependent samples
       * Population differences are normally distriuted or the sample size is greater than 30
       
     We can use the T Test on the Ti-84 calculator. In order to do so, we must first put our data into list 1 and list 2. Then we can use list 3 to find the difference between list 1 and 2. List 3 is the list we will use in the T test. 
     
#### The Wilcox Signed Rank Test
 
     Conditions: 
       * Dependent samples
       * Population differences are symmetric
     
     This test also work for finding the median. 
     
### Independent Samples
  
#### The Two Sample Z Test 
  
    Conditions: 
       * Independent samples
       * Normal populations or the sample size is greater than 30
       * Population standard deviations are both known
       
#### The Two Sample T Test (Welch's T Test)
  
    Conditions: 
       * Independent samples
       * Normal populations or the sample size is greater than 30
       * Population standard deviations are both unknown
    
    When using the Two Sample T Test in the Ti-84, we select unpooled if we do not know anything about the population standard deviations and we are not assuming that the standard deviations are equal. 
    
## Testing for Differences in Population Proportions 

#### Two Proportion Z Test 
    Conditions: 
       * Independent samples
       * np(1-p)>=10 for both samples (where p stands for p-hat)
 
## Testing for Differences in Population Variance

#### Two Sample F Test for Two Population Standard Deviation
    Conditions: 
       * Independent samples
       * Populations are normally distributed
       
    Note: The lower the standard deviation, the more consistant the data. 
    
    
# Tests for Qualitative Data 

## The Chi-Square Goodness of Fit Test
   
    Conditions: 
       * All expected frquencies are at least 1
       * At most 20% of expected frequencies are less than 5
       
    This test checks if an observed sample of data fits with the an expected distribution. 
    
    The observed data is composed of whole numbers while the expected distribution is composed of decimals between 0 and 1. 
    All of the expected distribution numbers should add to 1. 
    
## Contingency Table Analysis
   
    Conditions: 
       * All expected frquencies are at least 1
       * At most 20% of expected frequencies are less than 5 
       
    This test helps determine if choosing from a certain group affects the results. 
    It is like the chi square goodness of fit test, but is arranged differently. 
    
    Null hypothesis: samples are independent
    Alternate Hypothesis: samples are dependent
