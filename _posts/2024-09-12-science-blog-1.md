---
layout: post
title: "Science #1: Organ aging signatures in the plasma proteome track health and disease"
date: 2024-09-24
categories: [science]
tags: [featured] 
image: /images/interorgan-onlinelead.jpg
published: true
comments: true
---
[![Figure from Faulty communication between organs could make use old](/images/interorgan-onlinelead.jpg)](https://www.science.org/content/article/faulty-communication-organs-make-us-old#:~:text=Researchers%20have%20uncovered%20other%20instances,physical%20decline%20or%20speeds%20aging.)

[Faulty communication between organs could make use old](https://www.science.org/content/article/faulty-communication-organs-make-us-old#:~:text=Researchers%20have%20uncovered%20other%20instances,physical%20decline%20or%20speeds%20aging.)

## An objective summary of the paper

In this incredibly important report, [Oh et al., (2023)](https://www.nature.com/articles/s41586-023-06802-1) used plasma proteomics - a method to investigate proteins are circulating in the blood, their levels, and from which organs they are derived. This was done via a blood test and a fancy bit of technology called [SomaScan](https://www.somascan.org/). The rationale behind plasma proteomics is that depending on an individual's health status, healthy or diseased, cells from specific organs produce proteins which are then secreted into the blood. Using plasma proteomics allows us to then extrapolate an individual's health status. It's important to note that the organ-specific proteins in this article were defined as proteins that have **4x RNA expression in one organ compared to any other organ** - a definition proposed by [Uhlén et al., (2015)](https://www.science.org/doi/10.1126/science.1260419).
   
The authors then developed organ-specific machine learning models to predict an individual's age based on their plasma proteome. This allowed them to calculate the organ age gap, that is the difference between chronological age and predicted age of an individual (see below). 

### Understanding the organ age gap

<p align="center">
  <img src="/images/organ_age_gap.jpg" alt="Image of the organ age gap">
</p>
Let's assume the chronological age correlates linearly with predicted age in our population. For every person in the study, organ specific models will give a prediction for their biological age (predicted age), remember this was based on their organ-specific proteins. They can then look at individuals who have the same chronological age, and ask how far does your predicted age deviate from the mean of everyone else. This difference is the **age gap**, and they did this for each organ in their study. 

To summarise, this machine learning approach allowed the authors to find individuals who are outliers based on their organ-specific proteome. Then you can ask fun (maybe not so fun) questions like, "If you have a large brain organ age gap, are you more likely to develop dementia? If so, which brain specific proteins are driving the difference in the brain organ age gap?".

### What did the authors find?

Going into this, the assumption was that all organs age at the same rate. However, these machine learning models identified that individuals who have the same conventional age may otherwise have different organ age gaps - the implication being that **not all organs age at the same rate**. **This was unexpected**.

The authors then proceeded to demonstrate that in ~20% of all individuals, in at least one organ, the organ age gap was much greater than expected. They found that organs in these individuals have undergone accelerated ageing. These extreme organ-agers were associated with age-related diseases i.e, if an individual had diabetes - **they had a large kidney organ age gap**, or if they had a heart attack, **they had a large heart organ age gap**.

Incredibly, in individuals with no prior history of heart failure, the heart organ age gap could predict the risk of developing congestive heart failure, **15 years from baseline**. In other words, 15 years before individuals develop congestive heart failure, when they could be otherwise healthy, their hearts were producing proteins that may have potentially made them susceptible to heart failure in the future. At least this was what the heart organ age gap model was suggesting. Likewise, and strinkingly, heart, artery, brain, pancreas, immune, liver, muscle, and intestinal organ age gaps could **predict future mortality risk**. These models can predict risk of developing age-related diseases which is incredibly important and exciting. **That means from a simple blood test, we could potentially intervene before diseases develop**. 

The authors developed an elegant and simple method to track and predict many diseases from a blood test.

## My thoughts

When I first saw this paper I was amazed. It’s an idea that has being on my mind for a while, and I was glad to see it so beautifully written. However, after a deep and critical read of this paper I was left a little disappointed. The concepts introduced in this paper are somewhat revolutionary but they lie on shaky foundations. Limitations being:

- The definition of organ-specific proteins relies on RNA expression. We know that RNA abundance does not necessarily correlate with protein abundance. Protein synthesis and degradation pathways are incredibly complex, and using such a reductionist approach for organ enrichment might not be helpful. Alternatively, one could look at protein expression rather than RNA expression - tissue specific databases have been published already.
- Some organ-specific models were built on relatively low numbers of proteins, i.e. the Adipose Organ model was trained on 5 proteins. I’m not here to argue the finer points of developing machine learning models as I’m not an expert, but I have my doubts as to whether 5 proteins trained on 1500 individuals from similar backgrounds was sufficient enough to model health and disease.
- Please have a look at Ben Osburn’s pre-print for more limitations [(Orsburn, 2024)](https://osf.io/preprints/osf/xyzqw).

Regardless of the limitations, I think the work produced by [Oh et al., (2023)](https://www.nature.com/articles/s41586-023-06802-1) has the potential to revolutionise personalised medicine, and in a world where ageing diseases will be the biggest economic burden, predictive methodologies like this will be of the utmost importance to preventative medicine.

## How does this work benefit society?

Fortunately, this part was easy. Hamilton Oh, Jarod Rutledge, and Tony Wyss-Coray have gone on to become co-founders and scientific advisors to Teal Omics - a biotech startup based in Cambridge, Massachusetts (<https://www.tealomics.com/>). Teal Omics is looking to reshape healthcare by developing new approaches to treating age-related diseases. Alternatively, I wonder if the work from [Oh et al., (2023)](https://www.nature.com/articles/s41586-023-06802-1) **could be used to discover novel factors to prevent age-related diseases?**. Using the same principles and models, we now look for individuals who have organs that are ageing **slower** than expected (see below). We can then ask what factor(s) in that individual might be protective? In a perfect world, we would discover something miraculous like [GLP-1 receptor agonists](https://www.nature.com/articles/d41586-024-03078-x)!

<p align="center">
  <img src="/images/super_agers.jpg" alt="Image of the organ age gap but for super agers">
</p>
So instead of looking for individuals who have organs that are ageing **faster** than expected, we look for individuals who have organs that are ageing **slower** than expected. What is it about these individuals that allowed them to age slower? 


