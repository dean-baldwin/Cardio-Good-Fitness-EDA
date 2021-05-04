# Cardio Good Fitness EDA

<div style="background-color:#e7e7e7; padding: 10px;">
    <b>Objective</b> - Preliminary Data Analysis. Explore a dataset of customer related information for three treadmill units and extract basic observations about the data.

<b>Expectations:</b>
<ul>
    <li>
       Come up with a customer profile (characteristics of a customer) of the different products 
    </li>
    <li>
       Perform uni-variate and multi-variate analyses
    </li>
    <li>
       Generate a set of insights and recommendations that will help the company in targeting new customers
    </li>
</ul>
    
<b>Context</b> The data is for customers of the treadmill product(s) of a retail store called Cardio Good Fitness. It contains the following variables:
<ul>
    <li>
       Product - the model no. of the treadmill
    </li>
    <li>
       Age - in no of years, of the customer
    </li>
    <li>
       Gender - of the customer
    </li>
    <li>
       Education - in no. of years, of the customer
    </li>
    <li>
       Marital Status - of the customer
    </li>
    <li>
       Usage - Avg. # times the customer wants to use the treadmill every week  
    </li>
    <li>
       Fitness - Self rated fitness score of the customer (5 - very fit, 1 - very unfit) 
    </li>
    <li>
       Income - of the customer 
    </li>
    <li>
       Miles- expected to run 
    </li>
</ul>

</div>

# Executive Summary
***NOTE:*** Product Findings are based solely on data contained within the dataset

### The Following Section Identify Shared Characteristics For Customers Across Each Product

#### Common Characteristics Shared Across All 3 Products

<i>The following is a summary of characteristcs common across all three products (TM195, TM498, TM798)</i>

<ul>
<li>
    All three products show higher adoption by customers whose education aligns with key academic milestones (Associate, Bachelor, and Graduate degrees)
</li>
<li>
    Customers for all three products appear to align with an age bracket of ~19 to 47, with the median age of customer being ~26/27 years old. Though users who purchased the TM798 appear to be in a more focused subset of the age range.
</li>
 <li>
    There appears to be a positively skewed (right-skewed) distribution in regards to Age.
</li>
 <li>
    There appears to be a positively skewed (right-skewed) distribution in regards to Expected Miles Run.
</li>
<li>
    All three products show a similar ratio between single and partnered customers, with Couples out numbering Individuals
</li>  
<li>
    A positive coorelation appears to exist between income and education for all three products
</li>
</ul>

#### Characteristics Shared By TM195 and TM498 Customers
   <i>The following is a summary of characteristcs associated with customers who purchased the TM195 and TM498</i>
<ul>
<li>
    Customers who purchase the TM195 and TM498 have the same median age of ~26 with 50% of customers within each product category falling into a similar box range of ~24 to ~34.
</li>
<li>
    Customers who purchase the TM195 and TM498 appear to rate themselves as a fitness level of 3.
</li>
<li>
    Customer who purchase the TM195 and TM498 appear to align with the same key academic milestones (Associate and Bachelor)
</li>
<li>
    Unlike customers who purchase the TM798, there does NOT appear to be a positive correlation between Income and expected miles run for customer who purchased the TM195 and TM498
</li>
<li>
    Unlike customers who purchase the TM798, there does NOT appear to be a correlation between Income and the self rating of fitness level for customer who purchased the TM195 and TM498
</li>
<li>
    Unlike customers who purchase the TM798, there does NOT appear to be a strong correlation between Age and the self rating of fitness level for customer who purchased the TM195 and TM498
</li>
<li>
    The TM195 and TM498 appear to have equal prepresentation based on Gender.
</li>
</ul>

### The Following Section Identify Unique Characteristics For Customers of Each Product
#### Unique Characteristics Associated with TM195 Customers
<i>The following is a summary of characteristcs associated with customers who purchased the TM195</i>
<ul>
<li>
    Median Age of 26 with a range of 18 - 47. 50 percent of customers fall within the Age of 23 - 34.
</li>
<li>
    Median Income of \$49k with a range of \$30k - \$70k. 50 percent of customers fall within the Income of \$40k - \$55k.
</li>
</ul>

#### Unique Characteristics Associated with TM498 Customers
<i>The following is a summary of characteristcs associated with customers who purchased the TM498</i>
<ul>
<li>
    Median age of 26 with a range of 19 - 45. 50 percent of customers fall within the age of 24 - 34.
</li>
<li>
    Median Income of \$50k with a range of \$35k - \$69k. 50 percent of customers fall within the Income of \$47k - \$55k.
</li>
</ul>

#### Unique Characteristics Associated with TM798 Customers
<i>The following is a summary of characteristcs associated with customers who purchased the TM798</i>
<ul>
<li>
    Median Income of \$75k with a range of \$50k - \$105k. 50 percent of customers fall within the Income of \$60k - \$90k.
</li>
<li>
    Males appear to be far more likely to purchase the TM798, with female customers representing only 17.5 percent of owners. ***Note*** As the TM798 is showing a higher engagement with couples this may be due to units being purchased and associated with males, verify data. 
</li>
<li>
   Customers rate themselves at the higher end of the fitness scale 
</li>
<li>
   Customers achieved a higher education level than typically associated with the TM195 and TM498 
</li>
<li>
   Couples appear to set higher goals in regard to expected miles run 
</li>
<li>
    There appears to be a positive correlation between income and expected miles run.
</li>
<li>
    There appears to be a positive correlation between income and self rating of fitness level.
</li>
<li>
    There appears to be a positive correlation between Age and self rating of fitness level.
</li>
<li>
    Customers who purchase the TM798 appear to rate themselves as a fitness level of 3 or higher, with 50 percent of customers ratingin themselves as 4.0 - 5.0.
</li>
</ul>

### The Following Section Provides Buyer Persona's For Each Product
#### Buyer Persona for TM195
<ul>
<li>
    Beginner to intermediate user.
</li>
<li>
    Recent college graduate (Community College or Undergraduate).
</li>
<li>
    Young professional 1 - 3 years of work experience.
</li>
</ul>

#### Buyer Persona for TM498
<ul>
<li>
    Beginner to intermediate user.
</li>
<li>
    Recent college graduate (Community College or Undergraduate).
</li>
<li>
    Young professional 3 - 7 years of work experience.
</li>
<li>
    The TM498 is an upsell opportunity for potential buyers of the TM195
</li>
</ul>

#### Buyer Persona for TM798
<ul>
<li>
    Intermediate to advanced user.
</li>
<li>
    Recent college graduate, specifically graduate level or higher.
</li>
<li>
    Working professional 5+ years of work experience.
</li>
<li>
    Married couple or couple shopping together
</li>
<li>
    Conduct further research into Gender disparity and determine if product features need to be address or improved marketing strategies.
</li>
</ul>
