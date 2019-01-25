#  Stroop Effect Analysis

## Table of Contents
- [Introduction](#intro)
- [Analysis](#analysis)
- [Conclusion](#conclusion)
- [References](#eeferences)


<a id='intro'></a>
## Introduction
A classic phenomenon from experimental psychology called the Stroop Effect is investigated. A hypothesis regarding the outcome of the task is presented. Some data collected from others who have performed the same task is investigated, and some statistics describing the results are computed. Finally, results in terms of the hypotheses are interpretd.

**Stroop Effect**

In a Stroop task, participants are presented with a list of words, with each word displayed in a color of ink. The participant’s task is to say out loud the color of the ink in which the word is printed. The task has two conditions: a congruent words condition, and an incongruent words condition. In the congruent words condition, the words being displayed are color words whose names match the colors in which they are printed: for example RED, BLUE. In the incongruent words condition, the words displayed are color words whose names do not match the colors in which they are printed: for example PURPLE, ORANGE. In each case, we measure the time it takes to name the ink colors in equally-sized lists. Each participant will go through and record a time from each condition.

![image.png](http://res.cloudinary.com/hrscywv4p/image/upload/c_limit,f_auto,h_2000,q_90,w_1200/v1/107158/Stroop_Test_2_t071jx.jpg)


<a id='analysis'></a>
## Analysis

* The **independent variable** is the type of test whether congruent or incogruent, and the **dependent variable** is the time it takes to recognize/name the colors of the mismatch word/color congruency in seconds.


* An appropriate set of hypotheses for this task:

  **μC:** Congruent sample's response time mean

  **μI:** Incongruent sample's response time mean

  **Set of hypotheses:**
    * The null hypothesis: The congruent and incongruent populations are not different in the time needed to read the text.

      **H0: μC − μI = 0**
    * The alternative hypothesis: The congruent and incongruent populations are different in the time needed to read the text.

      **HA: μC − μI ≠ 0**


* The sample size is 24 participants who performed the tests under two different conditionspoints; the congruent word condition and the incongruent word condition. Therefore, we will conduct a dependent T-Test on the paired samples, which is usually done when collecting data twice for the same person [1].


* Descriptive statistics including a measure of central tendency and a measure of variability are performed.


* The sample size is 24
  **Congruent Sample**:
    * mean of 14.05 seconds
    * standard deviation of 3.56 seconds

  **Incongruent Sample**:
    * mean of 22.02 seconds
    * standard deviation of 4.80 seconds
    
    
* Statistical test is performed, including:
  * Confidence level / Type I error associated with the test
  * Conclusion regarding the hypotheses setup, and whether the results matchup with the expectations
  
  
<a id='conclusion'></a>
## Conclusion

The t-Statistic is smaller than the t-critical value. Thus, the test concludes that there is a significant difference between the two populations. Therefore, we reject the null hypothesis that there is no statistically significant difference between the two populations, and accept the alternative hypotheses concluding that there is a significant difference in the values for congruent and incongruent tests. This does not come as a surprise since from the beginning there was a strong evidence that the two groups were not the same when considering the difference of the values for each participant.


<a id='references'></a>
## References
1. www.statisticshowto.datasciencecentral.com/probability-and-statistics
