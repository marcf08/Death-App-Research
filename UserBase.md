# User Base Size and Scope Study

## Background / Ballpark Estimations
* Reddit and Quora searches indicate that very few individuals are aware of Afternote or Final Wish.
  * Hence, a memorial app may have some novelty value among 18 - 25 year olds.
  * Moreover, Afternote and Final Wish have a small web presence.
    * **Afternote**: Alexa rank ~11.9m.
    * **Final Wish**: Not enough data for an Alexa rank.
   
By any standard, these are not popular services. This is the classic dilemma: the hypothesized product is either extremely novel (unlikely) or there isn't a market for it (more likely).

## Assumptions
* Sudden death, such as by car accident, is not a viable use case. Although we would like for users to use the
app ahead of such tragedies, the reality is that few individuals think about their death
until it is possible or imminent (such as after having received a serious / terminal diagnosis). As a case in point, an [AARP Study](https://www.aarp.org/money/estate-planning/info-09-2010/ten_things_you_should_know_about_writing_a_will.html) found that
2 out of 5 Americans over the age of 45 do not have a will prepared. 
* Based on the AARP Study, we can therefore conclude that 3 out of 5 Americans over the age of 45 both THINK about their death AND consciously choose to do something about it. For this study's purposes, we can refer to them as "the doers."
  * Moreover, a will is a widely recognized legal document. Hence, a less known memorial app would have a smaller userbase than the aforementioned doers. 
* It is important to point out that an individual need not receive a terminal diagnosis in order to be a potential user. A surgery, accident, or serious illness may be sufficient to cause a mortal scare and create a potential user. This potential user base, however, is difficult to quantify. Therefore we should keep the potential userbase to a list of "serious" diagnoses.

## Statistical Data for Potential User Base
To get an estimate of potential users, I took a list of yearly US Cancer diagnoses. I also selected a user base
aged from 18 - 44, largely because they would be most familiar with web apps.

| Cohort                                             | Size      |
|----------------------------------------------------|-----------|
| US Population                                      | 300000000 |
| US Population Aged 18 - 44                         | 112000000 |
| US Population with a Cancer Diagnosis              | 1688780   |
| US Population with a Cancer Diagnosis Aged 18 - 44 | 135000    |

Sources: [1](https://www.cancer.gov/about-cancer/causes-prevention/risk/age), [2](https://seer.cancer.gov/statfacts/html/all.html)

We arrive at a potential US user base of 135,000. This is quite small.

## Known Indicators of Success (or Failure)

### As a Free Service
According to [Andrew Chen](http://andrewchen.co/quora-what-is-considered-a-significant-number-of-users-for-a-free-consumer-internet-product/), a free model requires some tens of millions of users. Even if we accounted for the global population of individuals with a cancer diagnosis, the number of potential users would be far less than what would make such a product viable.

### SaaS Model
A SaaS model is also necessarily difficult due to the price point. Individuals with serious medical conditions cannot be charged at a permium for both moral and practical reasons (most have significant bills). 

The SaaS model is also difficult due its lack of virality.

The SaaS model provides a ready way of predicting revenue. We can perform some "back of the napkin" calculations based on the percentage of the potential user base that we think could be captured.

### YRR Calculations

| Percentage of Potential User Base | ARR at $1 per User / Month  | ARR at $3 per User / Month | ARR at $5 per User / Month |
|-----------------------------------|-----------------------------|----------------------------|----------------------------|
| 1%                                | $16,200                     | $48,600                    | $81,000                    |
| 5%                                | $81,000                     | $243,000                   | $405,000                   |
| 10%                               | $162,000                    | $486,000                   | $810,000                   |
| 25%                               | $405,000                    | $1,215,000                 | $2,025,000                 |
| 50%                               | $810,000                    | $2,430,000                 | $4,050,000                 |


## Conclusion
For such an application to be profitable, we would need to capture a significant portion of the market share (> 25%). However, if these numbers were similar for Europe and Asia, establishing operational and even profitable revenue is not unthinkable. Further analysis is required to understand how technical requirements can impact such a service's profitability. If users upload large volumes of imagery or video, the technical infrastructure will be correspondingly expensive.  
