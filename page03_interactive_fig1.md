---
layout: page
title: Poisson Process Intuition
permalink: interactive_a
sidebar: true
interactive: poisson_process.html
---
---

## Figure Description
To better understand what we might expect the data to look like if microtubule catastrophe is indeed best modeled by arrival of two successive poisson processes, we generate random distributions based off of the proposed model to see how these distributions change based on the input parameters. 
Typically, 150 microtubule catastrophe events were observed, so we generate 150 of these events and plot the ECDFs. We will use use the sum of two exponential distributions with individual rates to model this biochemical process. We fixed the value of beta_1 at 1 and created a beta ratio slider widget to model different beta_2/beta_1 ratios.

<!-- The below line includes the interactive figure. Do not change! -->
<center>

{% include_relative interactives/{{page.interactive}} %}

</center>


