# be-a-better-data-scientist

## Fundamentals

### Reference

* https://en.wikipedia.org/wiki/Confounding
* https://en.wikipedia.org/wiki/Kelly_criterion
* https://en.wikipedia.org/wiki/St._Petersburg_paradox
* https://en.wikipedia.org/wiki/Sammon_mapping
* https://en.wikipedia.org/wiki/Scoring_rule
* https://towardsdatascience.com/horseshoe-priors-f97672b4f7cb
* [Explaining Odds Ratios](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2938757/)
* [Log-transform and its implications for data analysis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4120293/)
* [The little handbook of statistical practice](http://www.jerrydallal.com/lhsp/lhsp.htm)
* https://en.wikipedia.org/wiki/Generalized_estimating_equation
* https://en.wikipedia.org/wiki/Heteroscedasticity-consistent_standard_errors

### Papers

> If you want to read the derivations of the properties of the various tests, they're usually available. I've read Pearson's paper on the multinomial chi-square goodness of fit test, Student's paper on the t-test, later papers by Fisher on both tests (as well as papers by other authors on them); I've read Wilcoxon's paper where he does both the rank sum and signed rank tests; Mann and Whitney's paper that develops U-statistics and extends Wilcoxon's rank sum test; Kruskal and Wallis' paper on their test; Freidman's paper on his, and so on through hundreds more papers.

* [The theory of unbiased estimation](https://projecteuclid.org/download/pdf_1/euclid.aoms/1177731020)
* Some sampling simplified

### Packages for learning

* [matlib](https://cran.r-project.org/web/packages/matlib/)
* [mosiac](https://cran.r-project.org/web/packages/mosaic/index.html)
  * [R for Calclulus](https://dtkaplan.github.io/RforCalculus/preface.html)
  * [Statistical Modeling](https://dtkaplan.github.io/SM2-bookdown/preface-to-this-electronic-version.html)
* [Swirl courses](http://swirlstats.com/scn/title.html)
  * Advanced R programming (functional stuff)
  * Getting and cleaning data
  * Exploritory data analysis
  * Regression models
  * Statistical inference
* [Google ML course](https://developers.google.com/machine-learning/crash-course)

### Articles for learning

* https://www.alexpghayes.com/blog/overfitting-a-guided-tour/

### R Texts for learning

* [Discrete Data Analysis](http://ddar.datavis.ca/)

## Example Analysis

* [Salary Gender](https://juliasilge.com/blog/salary-gender/)
  * linear models
  * linear mixed effects models
  * bayesian multi-level models
* [Building Energy Use](https://towardsdatascience.com/a-complete-machine-learning-walk-through-in-python-part-one-c62152f39420)
* [Matrix Algebra Topics in Statistics and
Economics Using R](http://www.math.uni.wroc.pl/~dyba/materials/AlgLin/chapVinod.pdf)
  * Use base R matrix tools to conduct simple statistical analysis of easy datasets
* [Predicting Defaults](http://dukedatasciencefico.cs.duke.edu/)
  * Interperable models and visualization
* [Generalized Estimating Equations](https://rlbarter.github.io/Practical-Statistics/2017/05/10/generalized-estimating-equations-gee/)
  * `geepack`
* [Physics of personal income](https://arxiv.org/pdf/cond-mat/0202388.pdf)
  * Pareto index parameter change over time in incomes
* [Churn Rates](https://medium.com/swlh/youre-all-calculating-churn-rates-wrong-cbab072cd992)
  * Weibull/Lomax maximum likelihood
* [Anomaly Detection in Google Trends Data](https://github.com/cattystats/Anomaly_Detection)
* [Tidygraph](http://www.questionflow.org/2018/03/06/tao-of-tidygraph/)
  * graph, book

## Exercises

* [USING SINGULAR VALUE DECOMPOSITION TO COMPRESS AN IMAGE OF AN ALLOSAURUS](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxuYXNsdW5kZXJpY3xneDpkMTI4OTI1NTc4YjRlOGE)

## Project Ideas

### Distribution over W-L records and playoff seeding in divisions like NBA/NFL

For example in NBA right now 8th seeds have losing records, how expected would this outcome be?

* [The dreadful race for 8th in the NBA's Western Conference is incredibly unfamiliar](https://www.espn.com/nba/story/_/id/28450353/the-dreadful-race-8th-nba-western-conference-incredibly-unfamiliar)

The idea of expected seed penetration could be explored as well. How often should a division winner expect to make national, etc
  
#### Standings

* [Predicting Playoff Position Probability](https://fansided.com/2019/02/07/nylon-calculus-predicting-playoff-position-probability/)
  * Bayesian Inference
  * Binomial Likelihood
* [Understanding Baseball Team Standings and Streaks
](https://arxiv.org/pdf/0804.1110.pdf)
  
#### Parity

Top heavy vs parity, different resulting distributions based on these initial conditions. As a function of something like Gini coefficient or Pareto index produce W-L distributions.

* [THE IMPACT OF SUPERTEAMS AND PARITY ON THE NBA](https://scholarsbank.uoregon.edu/xmlui/bitstream/handle/1794/24005/Final%20Thesis-Finci.pdf?sequence=1&isAllowed=y)
* [Parity and predictability of competitions](https://arxiv.org/pdf/physics/0608007.pdf)
* [Measuring parity in sports leagues with draws: Further comments](https://ourarchive.otago.ac.nz/bitstream/handle/10523/995/DP_1005.pdf?sequence=3)
* [Parity and Predictability of Competitions](https://arxiv.org/pdf/physics/0608007.pdf)
* [Pigskin Party: A Statistical Analysis on Fantasy Football and “The Machine”](https://web.wpi.edu/Pubs/E-project/Available/E-project-042612-032533/unrestricted/Pigskin_Party_-_A_Statistical_Analysis_on_Fantasy_Football_and_The_Machine.pdf)

#### Scores

* [Scoring dynamics across professional team sports: tempo, balance and predictability](https://epjdatascience.springeropen.com/articles/10.1140/epjds29)
* [Predicting sports scoring dynamics with restoration and anti-persistence](https://arxiv.org/pdf/1504.05872.pdf)
* [NFL Scores Data](https://www.kaggle.com/tobycrabtree/nfl-scores-and-betting-data)
  * Could use NFL/NBA scores to sample from to simulate win/loss distributions based on observed score distributions

#### Projections

* [The Math of Fantasy Football](https://web.wpi.edu/Pubs/E-project/Available/E-project-042513-140309/unrestricted/ASL_MQP_jpa.pdf)
* https://www.inpredictable.com/p/methodology.html

### Random Equations

Generate random equations, how likely are they to have solutions?

It is a well studied problem but could be fun to approach it naively and see if brute force results point towards equations from papers.

#### Papers

* The solution space geometry of random linear equations
* On the solution-space geometry of random constraint satisfaction problems

### Statistical Dynamics in Online Dating

#### Papers

* Dating Relationships in Older Adulthood: A National Portrait
* [Online Dating: A Critical Analysis From the
Perspective of Psychological Science](https://www3.nd.edu/~ghaeffel/OnineDating_Aron.pdf)
* What Happens After You Both Swipe Right: A Statistical Description of Mobile Dating Communications
* Dynamics of Internet Dating
* [Aspirational pursuit of mates in online dating markets](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6082652/)
* The matching hypothesis reexamined
* Leveling the playing field: Longer acquaintance predicts reduced assortative mating on attractiveness
* Relational mate value: Consensus and uniqueness in romantic evaluations
* Non-independent mate choice in humans: Deciphering and utilizing information in a social environment
* Hunter-gatherer social networks and reproductive success
* It takes two to tango: Reproductive skew and social correlates of male mating success in a lek-breeding bird
* The mating sociometer: A regulatory mechanism for mating aspirations
* Who’s right and who writes: People, profiles, contacts, and replies in online dating
* How self-assessments can guide human mating decisions
* Relational mate value: Consensus and uniqueness in romantic evaluations
* Searching for a mate: The rise of the Internet as a social intermediary
* Targeted search in matching markets
* Online exogamy reconsidered: Estimating the Internet's effects on racial, educational, religious, political and age assortative mating
* Polar Similars: using massive mobile dating data to predict dating preferences
* Searching Forever After
* Beauty and Counter-signaling in Online Matching Markets: Evidence from a Randomized Field Experiment
* Gender-specific preference in online dating
* Pragmatic Men, Romantic Women? Performance Feedback Design on Two-sided Matching Platforms
* Waiting to Be Asked: Gender, Power, and Relationship
* Unequal distribution of power in young adult relationships more harmful to women
* Gender differences in mate selection
* The Truth about Lying in Online Dating Profiles
* Courting Trouble: A Qualitative Examination of Sexual Inequality in Partnering Practice
* Why I Don’t Have a Girlfriend
* [Inattentive and Contented: Relationship Commitment and Attention to Alternatives](http://ruby.fgcu.edu/courses/twimberley/10199/psy/inattentive.pdf)
* Counting members in my league: Mate value moderates economic effects of local operational sex ratio
* Singles of both sexes expedite reproduction: Shifts in sexual-timing strategies before and after the typical age of female menopause
* Prevalence and types of sexual inactivity in Britain: analyses of national cross-sectional probability survey data

#### Articles

* [Optimal Stopping and Dating Preferences](https://towardsdatascience.com/probability-theory-and-the-optimal-dating-strategy-for-2018-2b75b26fb0b)
* [Online Dating Report](https://www.kaspersky.com/blog/online-dating-report/)
* [Is Dating Unfair](https://www.waytoosocial.com/is-dating-unfair/)
* [These statistics show why it’s so hard to be an average man on dating apps](https://qz.com/1051462/these-statistics-show-why-its-so-hard-to-be-an-average-man-on-dating-apps/)
* [Tinder Experiments II: Guys, unless you are really hot you are probably better off not wasting your time on Tinder — a quantitative socio-economic study](https://medium.com/@worstonlinedater/tinder-experiments-ii-guys-unless-you-are-really-hot-you-are-probably-better-off-not-wasting-your-2ddf370a6e9a)
* [Least Desirable](https://medium.com/least-desirable/about-least-desirable-a5917edf6016)
* In Defense of Tinder
* [How Tinder Changed Dating](https://www.theatlantic.com/family/archive/2018/12/tinder-changed-dating/578698/)
* [I made a statistical game out of dating](https://www.theguardian.com/global/2017/may/13/love-maths-statistical-game-formula-happiness-dina-nayeri)

#### Comments

* https://news.ycombinator.com/item?id=19385829
* https://www.reddit.com/r/AskFeminists/comments/8lu1vv/do_you_think_womens_advantage_in_dating_is_an/
* https://talkpoverty.org/2016/03/28/the-inequality-of-online-dating/
* https://quillette.com/2019/03/12/attraction-inequality-and-the-dating-economy/

#### Books

Color commentary

* Labor of Love: The Invention of Dating
* Future Sex
* The All-or-Nothing Marriage
* Dataclysm: Love, Sex, Race, and Identity--What Our Online Lives Tell Us about Our Offline Selves
