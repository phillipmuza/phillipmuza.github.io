---
layout: post
title: "Science #1: Organ aging signatures in the plasma proteome track health and disease"
date: 2024-09-12
categories: [science]
tags: [featured] 
image: /images/interorgan-onlinelead.jpg
published: false
---
[![Figure from Faulty communication between organs could make use old](/images/interorgan-onlinelead.jpg)](https://www.science.org/content/article/faulty-communication-organs-make-us-old#:~:text=Researchers%20have%20uncovered%20other%20instances,physical%20decline%20or%20speeds%20aging.)

[Faulty communication between organs could make use old](https://www.science.org/content/article/faulty-communication-organs-make-us-old#:~:text=Researchers%20have%20uncovered%20other%20instances,physical%20decline%20or%20speeds%20aging.)

**An objective summary of the paper**

In this incredibly important report, (Oh et al., 2023) used simple plasma proteomics to develop organ-specific machine learning (ML) models to predict the organ age gap, that is the difference between chronological age and predicted age of an individual. These organ-specific proteins were defined as proteins that have 4x RNA expression in one organ compared to any other organ - a definition proposed by Uhlén et al., (2015). Interestingly, these ML models identified that individuals who have the same conventional age may otherwise have different organ age gaps - the implication being that not all organs age at the same rate. Oh et al., (2023) then proceeded to demonstrate that ~20% of their investigated population have accelerated ageing in at least one organ, and that this accelerated ageing is associated with age-related diseases and, importantly, these models can predict risk of developing age-related diseases and mortality. The authors developed an elegant and simple method to track and predict disease from a plasma proteomic sample.

**My thoughts**

When I first saw this paper I was amazed. It’s an idea that has been on my mind for a while, and I was glad to see it so elegantly written. However, after a deep and critical read of this paper I was left a little disappointed. The concepts introduced in this paper are somewhat revolutionary but they lie on shaky foundations. Limitations been:

- The definition of organ-specific proteins relies on RNA expression. We know that RNA abundance does not necessarily correlate with protein abundance. Protein synthesis and degradation pathways are incredibly complex, and using such a reductionist definition for organ enrichment might not be helpful. Alternatively, one could look at protein expression rather than RNA expression - tissue specific databases have been published already.
- Some organ-specific models were built on relatively low numbers of proteins, i.e. the Adipose Organ model was trained on 5 proteins. I’m not here to argue the finer points of developing ML models as I’m not an expert, but I have my doubts as to whether 5 proteins trained on 1500 individuals from similar backgrounds is sufficiently enough to model health and disease.
- Please have a look at Ben Osburn’s pre-print for more limitations [(Orsburn, 2024)](https://paperpile.com/c/4quc7N/FbOH).

Regardless of the limitations, I think the work produced by Oh et al., (2023) has the potential to revolutionise personalised medicine, and in a world where ageing diseases will be the biggest economic burden, predictive methodologies like this will be of the utmost importance to preventative medicine.

**How does this work benefit society?**

Fortunately, this part was easy. Hamilton Oh, Jarod Rutledge, and Tony Wyss-Coray have gone on to become co-founders and scientific advisors to Teal Omics - a biotech startup based in Cambridge, Massachusetts (USA; <https://www.tealomics.com/>). Teal Omics is looking to reshape healthcare by developing new approaches to treating age-related diseases. Alternatively, I wonder if the work from **Oh et al., (2023) could be used to discover novel factors to prevent age-related diseases?**. Using the same principles and models, we now look for individuals who have organs that are ageing slower than an individual’s chronological age - what factor(s) in that individual might be protective? In a perfect world, we would discover something miraculous like GLP-1 receptor agonists.

**References**

[Oh, H.S.-H. _et al._ (2023) ‘Organ aging signatures in the plasma proteome track health and disease’, _Nature_, 624(7990), pp. 164–172.](http://paperpile.com/b/4quc7N/F9Bx)

[Orsburn, B.C. (2024) ‘Better than flipping a coin? Organ specific plasma proteins are not confidently identified by gene expression data’, _https://osf.io › preprints › osf › xyzqwhttps://osf.io › preprints › osf › xyzqw_. Available at: https://doi.org/](http://paperpile.com/b/4quc7N/FbOH)[10.31219/osf.io/xyzqw](http://dx.doi.org/10.31219/osf.io/xyzqw)[.](http://paperpile.com/b/4quc7N/FbOH)

