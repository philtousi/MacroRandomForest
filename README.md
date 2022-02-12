# MacroRandomForest

Ever wanted the power of a random forest with the interpretability of a linear regression model? Well now you can...

This code base is the Python implementation of "The Macroeconomy as a Random Forest" by Philippe Goulet Coulombe. It has, at it's core, a linear macro equation. Unlike a regular regression though, variable and window size selection are made via a random forest. This has the nice side effect that our linear coefficient then nests information about variable selection, time-variation, regime-switching and structural breaks. This parameter is directly interpretable and can provide value not only to economic forecasters, but also to economic policy makers.


The full paper corresponding to the implementation can be found here: https://arxiv.org/abs/2006.12724. 
