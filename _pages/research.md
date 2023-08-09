---
title: ""
layout: single
permalink: /research/
classes: wide
---

# <center> Working Papers  </center>
- - -

**Transition Probabilities and Identifying Moments in Dynamic Fixed Effects Logit Models**, *(winner of the Best PhD Student Paper Award, 2023 IAAE Conference)* <br />
<small>[ <a href="#/" onclick="visib('DFEL')">Abstract</a> | [Draft][Draft_DFEL_paper] | [Arxiv version][Arxiv_DFEL_paper]] 


<div id="DFEL" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper deals with estimation of dynamic discrete choice models. Specifically, we introduce an algebraic approach to derive identifying moments in dynamic logit models with strictly exogenous regressors and additive fixed effects.  It is based upon two common features in this class of models. First, many (individual-specific) transition probabilities can be expressed as conditional expectations of functions of the data and common parameters given the initial condition, the regressors and the fixed effects. We call such functions transition functions.  Second, after enough time periods, multiple transition functions map to the same transition probabilities. This  motivates a differencing strategy leveraging the multiplicity of transition functions to produce valid moment conditions in panels of adequate length. We detail the construction of identifying moments in scalar models of arbitrary lag order as well as first-order panel vector autoregressions and dynamic multinomial logit models. A simulation study illustrates the small sample performance of GMM estimators based on our methodology.
</small><br><br/></div>

[Draft_DFEL_paper]:{{ site.baseurl }}{% link assets/files/Draft_DFEL_KevinDano.pdf %}

[Arxiv_DFEL_paper]: http://arxiv.org/abs/2303.00083

**Functional Differencing in Networks** (with Stéphane Bonhomme), *Submitted* <br />
<small>[ <a href="#/" onclick="visib('funcdiff_networks')">Abstract</a> | [Draft][Draft_funcdiff_networks_paper] | [Arxiv version][Arxiv_funcdiff_networks_paper] ] 

<div id="funcdiff_networks" style="display: none; text-align: justify; line-height: 1.2" ><small>
Economic interactions often occur in networks where heterogeneous agents (such as workers or firms) sort and produce. However, most existing estimation approaches either require the network to be dense, which is at odds with many empirical networks, or they require restricting the form of heterogeneity and the network formation process. We show how the functional differencing approach introduced by Bonhomme (2012) in the context of panel data, can be applied in network settings to derive moment restrictions on model parameters and average effects. Those restrictions are valid irrespective of the form of heterogeneity, and they hold in both dense and sparse networks. We illustrate the analysis with linear and nonlinear models of matched employer-employee data, in the spirit of the model introduced by Abowd, Kramarz, and Margolis (1999).
</small><br><br/></div>

[Draft_funcdiff_networks_paper]:{{ site.baseurl }}{% link assets/files/Note_FD_resubmit_noFrenchabstract.pdf %}

[Arxiv_funcdiff_networks_paper]: https://arxiv.org/abs/2307.11484

**Identification in a Binary Choice Panel Data Model with a Predetermined Covariate** (with Stéphane Bonhomme and Bryan S. Graham), *Submitted* <br />
<small>[ <a href="#/" onclick="visib('series')">Abstract</a> | [Draft][Draft_series_paper] | [Arxiv version][Arxiv_series_paper] | [Nber version][Nber_series_paper] | [Replication code][replication_julia]] 


<div id="series" style="display: none; text-align: justify; line-height: 1.2" ><small>
We study identification in a binary choice panel data model with a single predetermined binary covariate (i.e., a covariate sequentially exogenous conditional on lagged outcomes and covariates). The choice model is indexed by a scalar parameter, whereas the distribution of unit-specific heterogeneity, as well as the feedback process that maps lagged outcomes into future covariate realizations, are left unrestricted. We provide a simple condition under which the model parameter is never point-identified, no matter the number of time periods available. At the same time, we show in simulations that its identified set can remain informative suggesting that meaningful learning is possible even in short panels with feedback.
</small><br><br/></div>

[Draft_series_paper]:{{ site.baseurl }}{% link assets/files/Draft_SERIES_revision.pdf %}

[Arxiv_series_paper]:  https://arxiv.org/abs/2301.05733

[Nber_series_paper]: https://www.nber.org/papers/w31027

[replication_julia]: https://github.com/kevindano/Bonhomme-Dano-Graham-SERIES


**Coordination and Incumbency Advantage in Multi-Party Systems: Evidence from French Elections** (with Francesco Ferlenga, Vincenzo Galasso, Caroline Le Pennec and Vincent Pons), *Submitted* <br />
<small>[ <a href="#/" onclick="visib('incumbency')">Abstract</a>  | [Draft][Draft_incumbency_adv] | [Nber version][Nber_incumbency_adv]] </small>


<div id="incumbency" style="display: none; text-align: justify; line-height: 1.2" ><small>
In theory, free and fair elections can improve the selection of politicians and incentivize them to exert effort. In practice, incumbency advantage and coordination issues may lead to the (re)election of bad politicians. We ask whether these two forces compound each other. Using an RDD in French two-round local and parliamentary elections, we find that winning an election increases candidates' chances to win the next election by 25.1 percentage points. Close winners are more likely to run again and more likely to win, conditional on running, than close losers. Incumbents run a more personalized campaign communication and face fewer ideologically close competitors, indicating that parties on the winning side coordinate more effectively than the losing side. A complementary RDD reveals that candidates who marginally qualify for the runoff also rally voters, but without affecting the number of competitors on their side. We conclude that party coordination and voters rallying candidates who won or gained visibility in an election both contribute to their success in future races, absent any actual difference in quality with candidates on the losing side.
</small><br><br/></div>

[Draft_incumbency_adv]:{{ site.baseurl }}{% link assets/files/20221003_Incumbency_and_runoff_advantage_in_France.pdf %}

[Nber_incumbency_adv]: https://www.nber.org/papers/w30541

# <center> Work In Progress  </center>
- - -

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
 