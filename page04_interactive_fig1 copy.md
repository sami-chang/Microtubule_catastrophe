---
layout: page
title: Poisson: CDF vs ECDF
permalink: interactive_a
sidebar: true
interactive: poisson_CDF_ECDF.html
---
---

## Figure Description
We can analytically derive a probability distribution for the two poisson process model with a joint exponential probability distribution because for a catastrophic event to take t time, we would need the first event to take t_1 time AND the second event to take t_2 time
By overlaying the analytical CDF with the ECDF curve, we can confirm that the two curves mostly match over a range of beta_2/beta_1 ratios from 0.1 to 3. We can feel good about our previous method for calculating the experimental results using the two exponential distributions. 

<!-- The below line includes the interactive figure. Do not change! -->
<center>

{% include_relative interactives/{{page.interactive}} %}

</center>


