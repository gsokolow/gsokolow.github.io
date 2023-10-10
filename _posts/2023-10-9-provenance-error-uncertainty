As children, we may be taught that maps tell truths. As geographers, we are taught that maps lie.
Just like any other model, maps simplify the world around us so that we may better understand it.
Any choice we make to simplify necessarily creates the opportunity for bias and uncertainty.
In Chapter 6 of **Geographic information systems and science** (Langley et al, 2008), 
the following figure is presented as a 'conceptual view of uncertainty.
The three filters, U1, U2, and U3 can distort the way in which the complexity of the real world is conceived, 
measured, represented, and analyzed in a cumulative way.'
![Conceptual Model of Uncertainty](file:///Users/gracesokolow/Desktop/Open%20Source/Screenshot%202023-10-09%20at%208.14.31%20PM.png "Longley et. al, 2008. Figure 1")

This figure represents how uncertainty can manifest at every stage of abstraction and analysis.
It begins to describe the ways in which these errors propogate through the course of an analysis,
influencing all subsequent decisions and calculations in it.
However, it could do a better job visually representing the potential for errors to magnify, or at least, to interact. 
If the size of the purple wave ast any stage is related to the magnitude of uncertainty at that stage in the analysis,
then the current configuration suggests that the risk of uncertainty grows at the stages of conception and measurement, 
but shrinks at the final stage of analysis.
A radial model, in which total uncertainty grows as a function of progression through the analysis, might be able to make this figure even better.

In another course I took at Middlebury (Remote Sensing & Land Use with Niwaeli Kimambo, Fall 2022), 
we used machine learning to classify land use types from satellite imagery of Madagascar. 
We started by defining our land cover classes, which is where we encountered conceptual uncertainty.
None of the students had visited our study site, so we were at a loss when it came to defining the different land cover classes in ways that 
were meaningfully differentiated and functionally descriptive. 
Using our impefect class definitions, we generated a set of training points. 
We input the training points into our machine learning model to communicate the characteristics we associated with each class.
In this way, any uncertainty from **our** class definition was carried through to the model, where it likely interacted with uncertainty inherent in the model's operation.
Once we used our model to classify the land cover types in our study region, we conducted an error analysis.
We generated a stratified sample of points in each land class and manually classified them independent of the model's classification.
This gave us a sense of the uncertainty in our classification scheme, but remained imperfect due to the conceptual uncertainty underlying the project.
Even when we were manually classifying points, our limited understanding of the landscape introduced uncertainty into the 'ground truth' points we used to measure our model's error.
Similarly, the stratified sample we took in order to generate these ground-truthing points was based on our limited understanding of land cover in the region, 
and was thus influenced by the very uncertainty we were using them to understand. 
This internal dependency feels a little like using a word you are trying to define in it's definition. 
It doesn't give a very full picture.

This is not to say that our error analysis wasn't worth doing. 
if nothing else, attempting to describe and quantify error makes us more aware of its presence in our work.
Conceptual uncertainty is a major challenge to address because it can be difficult to quantify, 
but clearly stating the thought process used to conceive of the study and its components goes a long way towards
making it possible for others to understand and critique the conceptual foundation of a given study.
Some conceptual and indeed measurement or representational uncertainties may be explored through simulated repetition (ie Monte Carlo simulation).
A simulation is able to repeat an analysis many many times, randomly altering certain parameters in an effort to replicate the subjectivity
of a researcher's decision making or the instability of a given set of variables. 
The aggregate results of this simulation reveal trends within the data that can help determine the uncertainty associated with the original findings.

In addition to **testing** for uncertainty, it is important also to communicate it - numerically, verbally, and cartographically, when applicable.
One way to do this is to create a bivariate mapping scheme, in which hue is used to represent the findings themselves, 
and fuzziness is used to represent the uncertainty associated with a given measure (Tate, 2013). 
If uncertainty is *not* communicated, studies may mislead readers into believing that an association or trend is stronger, more explanative, or more certain than it really is.
This could lead to misconceptions about the world around us, and the misallocation of energy and funds towards addressing and better understanding the study phenomenon.


References:
Longley, P. A., M. F. Goodchild, D. J. Maguire, and D. W. Rhind. 2008. Geographical information systems and science 2nd ed. Chichester: Wiley.
Chapter 6: Uncertainty, (pages 127-153)

Tate, E. 2013. Uncertainty Analysis for a Social Vulnerability Index. Annals of the Association of American Geographers 103 (3):526–543. DOI:10.1080/00045608.2012.700616.
