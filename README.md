# Thesis

Copy of thesis "Deep learning for satellite imagery: a climatology of tropical cyclone rainband morphology" submitted as part of the MSc in Earth Sciences at the University of Melbourne, 2018.

## Abstract

Secondary eyewall formation is a common process of structural change in tropical cyclones. Previous work has qualitatively suggested that a secondary eyewall forms from the axisymmetrisation of pre-existing spiral rainbands, in particular the stationary banding complex. However, the evolution of rainband morphology prior to secondary eyewall formation has not been quantified. Limited progress in this area is primarily related a lack of objective methods to describe TC banding structure, and subsequent lack of understanding of the climatological morphology of rainbands.

In this study, we construct an objective system for classifying the structure of a tropical cyclone from 85-92GHz passive microwave satellite imagery. A fully automated implementation of this technique is developed using a novel combination of a convolutional neural network and unsupervised clustering. This classification system is used to compile a climatology of rainband morphology in all tropical cyclones globally between 2012 and 2014, and quantify changes in morphology prior to secondary eyewall formation. 

We find that a stationary banding complex is present in only 37\% of passive microwave images. The geometry of the principal rainband varies widely between storms, with crossing angles (azimuthal extents) ranging from 0.02 to 53.40 degrees (0.49 to 9.89 radians). Of 41 secondary eyewall formation events in the climatology, 79\% of develop from pre-existing stationary banding complexes. Within 6 hours of secondary eyewall formation, the rainband crossing angle (azimuthal extent) is preferentially lower (higher) than the sample average.

The impact of the large scale environmental conditions at each stage of this axisymmetrisation process is discussed. These results are applied together with the rainband climatology to develop a statistical model using gradient boosted decision tree learning to predict secondary eyewall formation events. This model has a probability of detection of 66\% and false alarm rate of 2\%, providing a skilful forecasting tool. 
