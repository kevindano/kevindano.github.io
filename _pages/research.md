---
title: ""
layout: single
permalink: /research/
classes: wide
---

# <center> Working Papers  </center>
- - -

**Transition Probabilities and Identifying Moments in Dynamic Fixed Effects Logit Models**, *Comments welcome* <br />
<small>[ <a href="#/" onclick="visib('DFEL')">Abstract</a> | [Draft][DFEL_paper] | [Arxiv version][arxiv]] 


<div id="DFEL" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper introduces an algebraic approach to derive identifying moments in dynamic logit models with strictly exogenous regressors and additive fixed effects.  It is based upon two common features in this class of models. First, many (individual-specific) transition probabilities can be expressed as conditional expectations of functions of the data and common parameters given the initial condition, the regressors and the fixed effects. We call such functions transition functions.  Second, after a certain time period, multiple transition functions map to the same transition probabilities. This  motivates a differencing strategy leveraging the multiplicity of transition functions to produce valid moment conditions in panels of adequate length. We detail the construction of identifying moments in scalar models of arbitrary lag order as well as first-order panel vector autoregressions and dynamic multinomial logit models. A simulation study illustrates the small sample performance of GMM estimators based on our methodology.
</small><br><br/></div>

[DFEL_paper]:{{ site.baseurl }}{% link assets/files/Draft_DFEL_KevinDano.pdf %}

[arxiv]: http://arxiv.org/abs/2303.00083

**Identification in a Binary Choice Panel Data Model with a Predetermined Covariate** (with Stéphane Bonhomme and Bryan S. Graham), *Submitted* <br />
<small>[ <a href="#/" onclick="visib('series')">Summary</a> | [Draft][series_paper] ] 


<div id="series" style="display: none; text-align: justify; line-height: 1.2" ><small>
We study identification in a binary choice panel data model with a single predetermined binary covariate (i.e., a covariate sequentially exogenous conditional on lagged outcomes and covariates). The choice model is indexed by a scalar parameter, whereas the distribution of unit-specific heterogeneity, as well as the feedback process that maps lagged outcomes into future covariate realizations, are left unrestricted. We provide a simple condition under which the model parameter is never point-identified, no matter the number of time periods available. At the same time, we show in simulations that its identified set can remain informative suggesting that meaningful learning is possible even in short panels with feedback.
</small><br><br/></div>

[series_paper]: https://arxiv.org/pdf/2301.05733.pdf

**Coordination and Incumbency Advantage in Multi-Party Systems: Evidence from French Elections** (with Francesco Ferlenga, Vincenzo Galasso, Caroline Le Pennec and Vincent Pons), *Submitted* <br />
<small>[ <a href="#/" onclick="visib('incumbency')">Abstract</a>  | [Draft][incumbency_adv] ] </small>


<div id="incumbency" style="display: none; text-align: justify; line-height: 1.2" ><small>
In theory, free and fair elections can improve the selection of politicians and incentivize them to exert effort. In practice, incumbency advantage and coordination issues may lead to the (re)election of bad politicians. We ask whether these two forces compound each other. Using an RDD in French two-round local and parliamentary elections, we find that winning an election increases candidates' chances to win the next election by 25.1 percentage points. Close winners are more likely to run again and more likely to win, conditional on running, than close losers. Incumbents run a more personalized campaign communication and face fewer ideologically close competitors, indicating that parties on the winning side coordinate more effectively than the losing side. A complementary RDD reveals that candidates who marginally qualify for the runoff also rally voters, but without affecting the number of competitors on their side. We conclude that party coordination and voters rallying candidates who won or gained visibility in an election both contribute to their success in future races, absent any actual difference in quality with candidates on the losing side.
</small><br><br/></div>

[incumbency_adv]: https://www.dropbox.com/s/fivg9pv3z6weh22/20221003_Incumbency_and_runoff_advantage_in_France.pdf?dl=0

# <center> Work In Progress  </center>
- - -
<!--- **Transition probabilities and identifying moments in (V)AR and dynamic multinomial panel logit models with fixed effects** [draft coming soon]  --->

**Relaxing Strict Exogeneity in Nonlinear Panel Data Models** (with Stéphane Bonhomme and Bryan S. Graham)



**Identification and estimation of random effects linear social interaction models with endogenous peer selection**  [draft coming soon]



[//]: This java script is the button to show abstract
 <script>
  function visib(id) {
   var x = document.getElementById(id);
   if (x.style.display === "block") {
     x.style.display = "none";
   } else {
     x.style.display = "block";
   }
 }
 </script>

 [//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
 