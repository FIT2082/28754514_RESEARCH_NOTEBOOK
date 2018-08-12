Week 3

Had a look at the data set, and made a note of the parameters available in each set of data. We also realised that it is missing chunks of data (some files only had 6 months worth of data rather than a year but this isn’t necessarily a huge issue). 

It was suggested that we plot the data for a smaller time frame first (e.g. a week or even a day rather than a year). There are a few important pieces of information that the data set provides. The first is the date and time stamp, as these enable us to plot the data as a function of time. The other important pieces of information are the room temperature and the set point. The set point is the temperature that the AC unit has been set to, and the AC unit will work to bring the room temperature to that set point. As a result, the room temperature will fluctuate over time, and we are interested to see if there are any regularities or patterns in the way that the temperature fluctuates. As Cristoph explained to us in the meeting, what we want to find/measure is the slope of the function as the temperature goes up or down.  

Over the past week, I’ve read a few different papers that related to this issue. Many papers discussed the use of artificial neural networks in their attempts to build a predictive model that would simulate AC behaviour. Though some of it may not relate directly to our project, it was very interesting to see the many different approaches that have been used to tackle a similar topic.

Notes from readings:

Prediction of indoor temperature in an institutional building:

•	AC temp optimisation – in relation to energy efficiency/energy conservation 

•	ANN – good for dealing with time series 

•	Important to pick the best suited training model + sort input parameters 

Simplified thermal & hygric building models:

•	Black box models (parameters have no direct physical meaning, no need for knowledge of physical properties) – e.g. neural network models, linear parametric models 

•	Considering important input parameters and where they should be included (White box models – e.g. lumped capacitance model)

To-do before next meeting: Try and plot the data for a smaller time frame 

