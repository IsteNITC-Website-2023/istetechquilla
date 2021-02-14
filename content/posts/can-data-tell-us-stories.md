+++
author = "Abhishek Jain"
cover = "/images/can.jpg"
date = 2021-02-13T19:30:00Z
description = "Predicting the type of a particle using a classification algorithm."
designer = "M. Jashwanth"
tags = []
title = "Can data tell us stories?"

+++
From generating pictures of black holes to detecting dark matter in the universe, applied artificial intelligence makes a massive contribution to modern-day Physics. Every new facet of ML has been used candidly, including LSTM’s, GAN’s and various neural network architectures. Supercomputers of unprecedented computing power have been used to drive forward research backed by sound modelling of artificial intelligence.

And it's no surprise that to perform such feats, you need an incredible amount of data. CERN produces over 120 petabytes of data every year, and to put that into perspective, that's roughly over 122760000000 minutes of music. This much data is no joke, and fuels algorithms to make pinpoint predictions.

The ATLAS (A Toroidal LHC Apparatus) experiment conducted at CERN was one such experiment. It was designed to detect particles with heavier masses than those already known. This supercollider ran for almost a year in the first run and produced humongous amounts of data, which can be used for various studies, including the detection of particles.

**_![](/images/can1.png)(1. ATLAS)_**

The data, which we obtain from the CERN open data portal, will be used to classify particles. We try to classify 5 particles - electron, proton, muon, kaon, pion and ghost. Ghost is a particle of some other type than the first five or a detector noise. A good question here would be what detector is being used. For this analysis, using the data collected from the ATLAS experiment, we will study the following detectors:

1. Tracking System: Responsive to electrons, muons and pions, but not to photons and neutrons.
2. Electromagnetic Calorimeter: Responsive to all.
3. Ring Imaging Cherenkov Detector (RICH): Differently responsive to all.
4. Hadron Calorimeter: Responsive to muons, pions and kaons.
5. Kaon system: Responsive to kaons.

**_![](/images/can2.png)(2. Responses of particles to detectors)_**

The data contains responses of different particles to these detectors, like reconstructions through a detector, deviation angles, and momentum after deflections. We use a neural network to create interdependencies among the independent variables. We also use a simple architecture, as the data isn't too complex.

**_![](/images/can3.png)(3. Network used, scaled down by a factor of 4, for first 3 layers)_**

This model performs fairly well on the data and gives us a log loss of 0.6096 and an accuracy of 91.60% over 35 epochs. However, as people well-versed in machine learning know, accuracy on test data isn't the best parameter to judge the validity of the model. We use around 60,000 data points (0.05% of the total data) as a validation data set, and get a log loss of 0.65 and an accuracy of 88.87%.

**_![](/images/can4.png)(4. Model performance after 35 epochs)_**

This thus improves our confidence in the model and can be used for practical purposes. To get a further idea, let's have a look at the ROC (Receiver Operating Characteristic) curve, which shows us the performance of the model at regular thresholds.

**_![](/images/can5.png)(5. ROC curve, with the respective area under curve values for our particles.)_**

This shows that our model is doing quite well, and false positives decrease as efficiency increases.

This simple example, when non-differential non-linearities are absent, shows us how modern-day research makes use of machine learning algorithms. It is being used not just to make predictions, but also to improve astronomical imaging and simulate gravitational lensing. A recent study was also able to model dark matter distributions in space. Machine learning opens up a huge set of possibilities which were earlier thought to be impossible, especially in the ever-evolving field of Physics. This was one small example demonstrating the same.

> _Abhishek Jain_