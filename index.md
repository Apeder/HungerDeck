---
title       : Global Childhood Malnutrition 
subtitle    : A Case for More Data 
author      : Andrew Pederson
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction 
# Why Measure Children's Weight and Height?  

Being underweight is a leading indicator for childhood stunting. Stunting is a **permanent** disability that causes:
* Greater risk for illness and premature death
* Reduced cognitive capacity and delayed mental development associated with poorer school performance and reduced adult workforce productivity 
* Greater risk for complications during child birth due to smaller pelvises and risk of delivering a baby with low birth weight

Source: http://en.wikipedia.org/wiki/Stunted_growth

--- .class #id 

## Data 
# Good Data Key to Reduce Stunting

According to UNICEF, about 162 million children were alredy **permanently** stunted in 2012, 90% of whom live in Africa and Asia.  Stunting can be caused by basic malnutrition as well as gastro-intestinal infections that cause recurring diarrhea. 

Source: http://data.unicef.org/resources/2013/webapps/nutrition

Now, we can visualize data about stunting faster and more cheaply than ever.  If I, a lowly liberal arts student, can create the following Shiny masterpiece, with some more practice and expert training, we should be able to track malnutrtion data more closely than ever before: 

https://apeder.shinyapps.io/HungerApp/

---

## Trends
# Stunting is Going Down: National Institute of Health Data
<br>
<img src="http://ehp.niehs.nih.gov/wp-content/uploads/2014/11/ehp.122-A298.g002.jpg" width="800" height="500" />

---

## Trends 
# But Not Fast Enough? 




```
## geom_smooth: method="auto" and size of largest group is <1000, so using loess. Use 'method = x' to change the smoothing method.
```

<img src="assets/fig/unnamed-chunk-2-1.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />

---

## Call to Action 
# A Large Problem that Needs Big Data 

As the previous regional plot shows, the overall trend appears stable over the last 10 years or so, and could even be rising globally.  this is to say nothing of the more disturbing regional and local disparities that are likely hidden in this data.

Costs to address stunting could be as high as 9.5 billion USD. Given the cost and scale of the issue, more granular regional and local data would be invaluable tools for government health departments and civil health organizations to use to target and track interventions.  Stunting is possibly the largest problem facing humanity, and it deserves to be seriously addressed in this generation with renewed vigor and ample resources.

Source: http://www.unicef.org/ethiopia/2_Evidence-based_interventions_for_improvement_of_maternal.pdf

See the "Gaps in the Data App" here, in the result of my blood, sweat and tears: https://apeder.shinyapps.io/HungerApp/
