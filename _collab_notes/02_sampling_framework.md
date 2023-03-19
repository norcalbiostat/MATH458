---
tags: math458 # HackMD specific. Don't copy into your file
robots: noindex, nofollow # also HackMD specific.  
title: "Sampling Framework" # you need to copy from here down
author: "Put your name here"
date: today # auto dating will only work in Quarto (.qmd) files
---

# Introduction

The objective of sample surveys is to make inference about a population from information contained in a sample selected from that population. We are usually interested in estimating some population parameter such as the population mean.

# Populations and Representative Samples (1.2)

A sample is representative if it can be used to "reconstruct" what the population looks like and if we can provide an accurate assessment of how good that reconstruction is.

Some definitions are needed to make the notions of a "population" and a "representative sample" more precise.

### Key Terms

-   **Observational Unit**: 
-   **Target Population**: 
-   **Sample**: 
-   **Sampled population**: 
-   **Sampling unit**: 
-   **Sampling frame**: 

In an *ideal* survey, the sampled population will be identical to the target population. 

:::    warning
### You try it
An online bookseller summarizes readers' reviews of the books it sells. Persons who want to rate a book can submit a review online; the bookseller reports the average rating from all reviews on its website.

Describe the target population, sampling frame, sampling unit, and observation unit. Discuss any possible sources of selection bias or inaccuracy of responses.
:::

selection bias or inaccuracy of responses.

* [Matthew]People who left a review, but didn't read the book
* [Zoe] People who feel very strongly about the book will be more likely to respond since the survey is voluntary
* [Rachel] People who have a specific preference of genre or writing style
* [Zoe] Not having the ability to leave a review
* For whatever reason, review bombing could be a factor




----

# Selection Bias (1.3)

**Selection bias** occurs when the target population does not coincide with the sampled population because some population units are sampled at a different rate than intended by the investigator. 

> If a survey designed to study household income has fewer poor households than would be obtained in a representative sample, would the survey estimates of the average or median household income be too high? or to low? 

## Some types of selection bias

::: info
Summarize briefly and provide a unique example (that is, not the one in the text) for the type of selection bias that you are assigned to review. Be prepared to share this out with the class. 
:::

> After class add all examples provided here to your notes. Clean them up (e.g. remove the names and headers)


[Othman] **Convenience Sample**: 
-  Is a method where researchers pick resoponders who are convenient to the researchers.
-  Example: A poll to decrease gas prices.
-  Convenience sampling is being used because the people who responded to the pool have a low income.
- easy to reach/ doesn't take much effort. 


**Purposive or Judgement Sample**: 
 - 
- When researchers use their judgment to select the specific units to be included in the sample; use judgment to select people.
- [Yazmin] Example: Survey to find the most popular drink at Dutch Bros. Selecting people in line at Dutch Bros to take the survey.
- [Zoe] selecting a certain sample on purpose to confirm a prior opinion



[Rachel] and [Jasmine] **Self-Selected Sample**: 
- It occurs when a sample is made up completely by people who chose to be in the sample 
- Example: A survey being done by randomly going to houses and asking to be part of a survey and having them answer questions.
- for some volunteer samples, the surveys may be filled out by the same person multiple times, which will skew the results

[Miguel] **Undercoverage Bias**: 

- Occurs when the sampling frame fails to include some members of the target population. Popution units that are not in the sampling frame have no chance of being in the sample.
- Example: We want to know the amount of red trucks in at Chico. A researcher stands at on Nord Ave and counts the red trucks that passes by. 
- There is undercovery bias within this sampling because the researcher will miss red trucks on other roads. Also, there will be red trucks that will not be driven at all.


[Matthew] **Overcoverage**: 
- Overcoverage selection bias occurs when a sample includes individuals who are overrepresented in the population being studied.

- Example: If the sample is drawn from a list of individuals who have visited the local hospital for a check-up, individuals who are taller and therefore more likely to have visited the hospital multiple times will be overrepresented in the sample. 

- There is overcoverage bias in this example because the people are being counted multiple times and the average height will be overestimated. 


[Zoe] and [Saul]  **Nonresponse**: 
- occurs when responses are not recieved from members of the chosen sample. 
- Differences between the group of non-respondents and respondents can exist. These differences lead to nonresponse bias.
- Example: A researcher wants to estimate public opinion on the best restaurant in town, and so he sends out ballots to vote to every single household in town, which need to be mailed back to the researcher. 
- there is non-reponse bias in this example because not all of the houses which the ballot was dropped of at are going to fill it out and mail it back to the researcher. 





## Bias everywhere!

Can Bias ever be good? Yes! 


::: success
### Example: Early indicators of lung injury associated with vaping (2019)

By Oct '19, over 1,600 cases of lung injuries and 34 deaths were found to be associated with vaping, but the actual cause of injuries were not known. In 2019 a group of researchers (see text for citation) conducted a study that ultimately led to the recommendation that the public stop using these products until more research on the causal association could be conducted. 

This impact survey had the following types of selection bias: 

* Researchers attempted to interview 83 patients who were reported to have lung injuries but only 53 responded (non-response bias). 
* The sampling frame of 83 only came from physician-reported cases, which means there may be bias if the physicians only reported the more serious cases (undercoverage)
* THC is illegal in that state, so patients may have under-reported their use (undercoverage)
* Individuals who vape, incurred a lung injury but didn't seek care were excluded from the study (undercoverage)
:::

Just because your sample may likely contain bias, being up front about it in your reporting (this is what the limitations section is all about) is a very important aspect of open science. 

----

# Measurement Error (1.4)

* [John-Paul] **Measurement error**: When there is a  difference between the recorded value and the true value of what you are recording.
    * Types
        * Gross: Error due to inexperience/carelessness. E.g. rounding.
        * Systematic: An error due to the procedure.  Typically this kind of error is universally seen in the project
    
* [Chase] **Measurement bias**: 
- EX: A survey wants to ask a lot of questions, so the questoins are divided amoung different modules. Two different modules can give different responses to the same questions.
- When systematic error tends to only occur in one direction

::: success
### Example: Ecology surveys

Often in ecological surveys, areas are divided into plots or grids of smaller size. A sample of plots/grids are selected and the number of plants in those selected grids are counted. 

Field researchers have to make a decision about whether or not to count plants directly on the border. If one researcher always counts plants on the boarder as being inside the grid, and another one does not, their estimate will always be higher than the other person. 
:::


## Surveying people 

Obtaining accurate responses is challenging in all types of surveys. Especially when dealing with humans. 

:::info
### Why humans gotta be so hard?
Write down _all_ reasons you can think of for measurement error in self-report surveys on people. Write down everything that comes to mind, no judgement on if you think its a "good" response or not.  
:::

* People may choose not to respond or lie if theyre embarrassed about the response (like income level)
* [JP]A difference in opinion on a measure of center.(What does it mean to be neutral to something?)
* [JP]The sensitivity of the topic
* 
* They lie

- different ways of thinking on the researchers. 
- does not want to be judged on their response.


* Afraid of being judged by their response 

* [Saul] The mood of the respondent
* Rushing responses (in a time crunch)

* [Jasmine] They fill in the survey with random answers



- [Zoe] shame/embarassment 
- questions regarding illegal substances or topics that the respondant feel that they could get in trouble for their answers
- laziness and honesty of respondant


- [Matthew]Embarassed to report real answer, privacy concern, and lack of understanding

Clear sampling protocols and thoughtful & validated survey design can minimize measurement error. 

----

# Sampling and Nonsampling errors (1.6)

* Most surveys report a "margin of error", often something like "3 percentage points"
* The **margin of error**: describes the sampling error -- the error that occurs from taking one random sample instead of measuring the entire population. Similar to the MOE in a confidence interval. 
* **Nonsampling errors** : cannot be atributed to the sampling variability,but due to selection bias & measurement error. 

-   **Zoe Kunhart**:

    -   Title: "For Black History Month, a look at what Black Americans say is needed to overcome racial inequality"  Url: :https://www.pewresearch.org/fact-tank/2023/01/20/for-black-history-month-a-look-at-what-black-americans-say-is-needed-to-overcome-racial-inequality/ 
    -   The population of interest is Black Americans
    -   There was a few different statistics being estimated in this particular poll, however the statistic I am choosing to focus on is Black Americans opinions on the effectiveness of different used strategies to help Black people move forward towards equality

        -The Margin of Error is plus or minus 2.2 percentage points
