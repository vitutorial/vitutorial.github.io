---
layout: single
author_profile: true
title: About
---


Neural networks are taking NLP by storm. Yet they are mostly applied in contexts where we have complete supervision. Many real-world NLP problems require unsupervised or semi-supervised models, however, because annotated data is hard to obtain. This is where generative models shine. Through the use of latent variables they can be applied in missing data settings. Furthermore they can complete missing entries in partially annotated data sets. 


So, [we](contributors/) have designed a *tutorial on variational inference and deep generative models for NLP audiences*. 
All of our tutorial's material is publicly available on [github](https://github.com/philschulz/VITutorial). 

This tutorial is about how to use neural networks inside generative models, thus giving us Deep Generative Models (DGMs). The training method of choice for these models is variational inference (VI). We start out by introducing VI on a basic level. From there we turn to DGMs that employ discrete and/or continuous latent variables. We justify them theoretically and give concrete advise on how to implement them. For continuous latent variables, we review the variational autoencoder and use Gaussian reparametrisation to show how to sample latent values from it. For discrete latent variables, for which no reparametrisation exists, we explain how to use the score-function or REINFORCE gradient estimator. 


And [we are on tour](tour/)!
