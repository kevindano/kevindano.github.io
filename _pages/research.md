---
title: ""
layout: single
permalink: /research/
classes: wide
---


# <center> Working Papers  </center>
- - -

**Binary choice logit models with general fixed effects for panel and network data** (with Bo Honoré and Martin Weidner), Econometric Society World Congress Monographs (Conditionally Accepted) <br />
<small>[ <a href="#/" onclick="visib('logitgenFE')">Abstract</a> | [Draft][Draft_logitgenFE] | [Arxiv version][Arxiv_logitgenFE]] 

<div id="logitgenFE" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper systematically analyzes and reviews identification strategies for binary choice logit models with fixed effects in panel and network data settings. We examine both static and dynamic models with general fixed-effect structures, including individual effects, time trends, and two-way or dyadic effects. A key challenge is the incidental parameter problem, which arises from the increasing number of fixed effects as the sample size grows. We explore two main strategies for eliminating nuisance parameters: conditional likelihood methods, which remove fixed effects by conditioning on sufficient statistics, and moment-based methods, which derive fixed-effect-free moment conditions. We demonstrate how these approaches apply to a variety of models, summarizing key findings from the literature while also presenting new examples and new results.
</small><br><br/></div>

[Draft_logitgenFE]:{{ site.baseurl }}{% link assets/files/DHW_logitgenFE.pdf %}

[Arxiv_logitgenFE]: https://arxiv.org/abs/2508.11556


**Moment Restrictions for Nonlinear Panel Data Models with Feedback** (with Stéphane Bonhomme and Bryan S. Graham)  <br />
<small>[ <a href="#/" onclick="visib('feedback')">Abstract</a> | [Draft][Draft_local] | [Arxiv version][Arxiv_paper]] 

<div id="feedback" style="display: none; text-align: justify; line-height: 1.2" ><small>
Many panel data methods place strong a priori restrictions on feedback: how past outcomes, covariates, and heterogeneity map into future covariate levels. In semi-parametric models we characterize the set of all moment functions that are robust to unrestricted feedback and heterogeneity. We provide results for finite-dimenisonal parameters and average effects, and show how to use our characterization for efficiency analysis. We illustrate the approach in the multi-spell mixed proportional hazard duration model and through additional novel examples. 
</small><br><br/></div>

[Draft_local]:{{ site.baseurl }}{% link assets/files/BDG_feedback.pdf %}

[Arxiv_paper]: https://arxiv.org/abs/2506.12569


**Transition Probabilities and Moment Restrictions in Dynamic Fixed Effects Logit Models** *(winner of the Best PhD Student Paper Award, 2023 IAAE Conference)* <br />
<small>[ <a href="#/" onclick="visib('DFEL')">Abstract</a> | [Draft][Draft_JMP] | [Supplement][Supplement_JMP] | [Arxiv version][Arxiv_DFEL_paper]] 

<div id="DFEL" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper introduces a new method to derive moment restrictions in dynamic discrete choice models with strictly exogenous regressors, fixed effects and logistic errors. We show how the structure of logit probabilities and basic properties of rational fractions can be used to construct moment functions free of the fixed effects in a way that scales naturally with the lag order and the number of observed periods. We demonstrate the approach in binary response models of arbitrary lag order, first-order panel vector autoregressions and dynamic multinomial logit models. The semiparametric efficiency bound is characterized for the leading binary case with one lag. 
Finally, we illustrate our results in an application investigating the dynamics of drug consumption among young people.
</small><br><br/></div>

[Draft_JMP]:{{ site.baseurl }}{% link assets/files/JMP_KevinDano.pdf %}

[Supplement_JMP]:{{ site.baseurl }}{% link assets/files/JMP_KevinDano_SupplementalAppendix.pdf %}

[Arxiv_DFEL_paper]: http://arxiv.org/abs/2303.00083

**Functional Differencing in Networks** (with Stéphane Bonhomme)  <br />
<small>[ <a href="#/" onclick="visib('funcdiff_networks')">Abstract</a> | [Draft][Draft_funcdiff_networks_paper] | [Arxiv version][Arxiv_funcdiff_networks_paper] ] 

<div id="funcdiff_networks" style="display: none; text-align: justify; line-height: 1.2" ><small>
Economic interactions often occur in networks where heterogeneous agents (such as workers or firms) sort and produce. However, most existing estimation approaches either require the network to be dense, which is at odds with many empirical networks, or they require restricting the form of heterogeneity and the network formation process. We show how the functional differencing approach introduced by Bonhomme (2012) in the context of panel data, can be applied in network settings to derive moment restrictions on model parameters and average effects. Those restrictions are valid irrespective of the form of heterogeneity, and they hold in both dense and sparse networks. We illustrate the analysis with linear and nonlinear models of matched employer-employee data, in the spirit of the model introduced by Abowd, Kramarz, and Margolis (1999).
</small><br><br/></div>

[Draft_funcdiff_networks_paper]:{{ site.baseurl }}{% link assets/files/Note_FD_resubmit_noFrenchabstract.pdf %}

[Arxiv_funcdiff_networks_paper]: https://arxiv.org/abs/2307.11484


# <center> Publications  </center>
- - -

**Identification in a Binary Choice Panel Data Model with a Predetermined Covariate** (with Stéphane Bonhomme and Bryan S. Graham), *SERIEs - Journal of the Spanish Economic Association. Special issue in honor of Manuel Arellano* <br />
<small>[ <a href="#/" onclick="visib('series')">Abstract</a> | [Published version][Published_paper] | [Arxiv version][Arxiv_series_paper] | [Nber version][Nber_series_paper] | [Replication code][replication_julia]] 

<div id="series" style="display: none; text-align: justify; line-height: 1.2" ><small>
We study identification in a binary choice panel data model with a single predetermined binary covariate (i.e., a covariate sequentially exogenous conditional on lagged outcomes and covariates). The choice model is indexed by a scalar parameter, whereas the distribution of unit-specific heterogeneity, as well as the feedback process that maps lagged outcomes into future covariate realizations, are left unrestricted. We provide a simple condition under which the model parameter is never point-identified, no matter the number of time periods available. At the same time, we show in simulations that its identified set can remain informative suggesting that meaningful learning is possible even in short panels with feedback.
</small><br><br/></div>

[Published_paper]: https://link.springer.com/article/10.1007/s13209-023-00290-2

[Arxiv_series_paper]:  https://arxiv.org/abs/2301.05733

[Nber_series_paper]: https://www.nber.org/papers/w31027

[replication_julia]: https://github.com/kevindano/Bonhomme-Dano-Graham-SERIES


**Coordination and Incumbency Advantage in Multi-Party Systems: Evidence from French Elections** (with Francesco Ferlenga, Vincenzo Galasso, Caroline Le Pennec and Vincent Pons), *The Journal of the European Economic Association* <br />
<small>[ <a href="#/" onclick="visib('incumbency')">Abstract</a>  | [Draft][Draft_incumbency_adv] | [Nber version][Nber_incumbency_adv]] | [Replication code][replication_stata]] </small>


<div id="incumbency" style="display: none; text-align: justify; line-height: 1.2" ><small>
In theory, free and fair elections can improve the selection of politicians and incentivize them to exert effort. In practice, incumbency advantage and coordination issues may lead to the (re)election of bad politicians. We ask whether these two forces compound each other. Using an RDD in French two-round local and parliamentary elections, we find that winning an election increases candidates' chances to win the next election by 25.1 percentage points. Close winners are more likely to run again and more likely to win, conditional on running, than close losers. Incumbents run a more personalized campaign communication and face fewer ideologically close competitors, indicating that parties on the winning side coordinate more effectively than the losing side. A complementary RDD reveals that candidates who marginally qualify for the runoff also rally voters, but without affecting the number of competitors on their side. We conclude that party coordination and voters rallying candidates who won or gained visibility in an election both contribute to their success in future races, absent any actual difference in quality with candidates on the losing side.
</small><br><br/></div>

[Draft_incumbency_adv]:{{ site.baseurl }}{% link assets/files/Incumbency_and_runoff_advantage_in_France.pdf %}

[Nber_incumbency_adv]: https://www.nber.org/papers/w30541

[replication_stata]: https://zenodo.org/records/14071530


# <center> Work In Progress  </center>
- - -

**Homophily and transitivity in dynamic network formation** (with Bryan S. Graham and Yassine Sbai Sassi)

**Dynamic Panel Multinomial Logit Models** (with Bo Honoré and Martin Weidner)

**Identification and Estimation of Random Effects Linear Social Interaction Models with Endogenous Peer Selection**  



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
 