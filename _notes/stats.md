---
title: Statistics
category: math
layout: note
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
