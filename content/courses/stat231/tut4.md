---
title: Tutorial 4
linktitle: Tut4
toc: true
type: docs
date: "2019-06-28T00:00:00Z"
lastmod: "2019-06-27T00:00:00Z"
draft: false
menu:
  stat231:
    parent: Tutorial
    weight: 4
weight: 4
---

This week (Friday, June 28), I will be teaching two tutorial sections this week (11:30 -- 12:20 & 14:30 -- 15:20)

In this tutorial, we'll go over the [problem](../supp/tut4_Q.pdf). The supplementary can be found [here](../supp/tut4_supp.pdf).

* * * 

Note: This time, there is only one problem.

* a. [Yes] QQ plot for checking Gaussian assumption (p. 80).

"A qqplot is a graph for which the expected plot would reasoonably be astraight line plot if the Gaussian model is a good fit." Hence the assumption is reasonable.

* b. **Confidence interval** for $\mu$.

  1. $Z/G$ if $\sigma / \sigma^2$ is known. 
      $$\bar{y}\pm z\_{1-\frac{\alpha}{2}} \frac{\sigma}{\sqrt{n}}$$
  2. $t$ if $\sigma / \sigma^2$ is unknown.
      $$\bar{y}\pm t_{1-\frac{\alpha}{2}, ~df} \frac{s}{\sqrt{n}}$$
  
* c. **Hypothesis testing** for $H\_o:\mu=50$ v.s. $H\_a:\mu\ne 50$. 

  - Defn 38 (p. 182)
  - Equation 4.6 and 4.7 (p. 152)
  - (p. 188), but since $\sigma$ is known, can use $Z$ instead of $t$.
  
Note: Essentially here, p-value: $P(D\geq d|H_o)$, $D$ is a pivotal quantity.

* d. **Find the p-value** 

  1. Solve the numeric values into the discrepancy measure/test statsitics formula.
  
  2. Find the p-value (Note: The assumtion here is under $H_o$ and the alternative is **2-sided test**)

* e. **Evidence of p-value**
  
See Table 5.1 (p. 184)

* f. **Decision Making**

Comparison between our p-value with the significant level.
  
* g. **Using confidence interval...**

If the null value (value under $H_o$, in this case, $\mu=50$) is not within the $(1-\alpha) \%$ CI, then $\mu=50$ is probably not likely to be true.

* h. 

Same as f.

* i.

Basically repeating the entire procedure once again, but since the CI is **Wider**, so $\mu_o=50$ is **included**. Hence, the same conclusion as in h.

* * * 

If you have questions, feel free to ask me after class. Also I welcome your feedbacks. :)