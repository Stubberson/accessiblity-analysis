# Machine Learning for Accessibility in Helsinki Region

The notebook in this repo follows the article [Hansen's Accessibility Theory and Machine Learning: a Potential Merger](https://link.springer.com/article/10.1007/s11067-025-09674-2) by Hadjidimitrou et al. (2025). The article is an exploration into the utilization of machine learning (ML) for predicting accessibility in (peri)urban areas. Two ML models – random forest (RF) and a neural network (NN) – are trained and compared in predicting accessibility with limited data.

The article modelled accessibility with [Hansen's (1959)](https://www.tandfonline.com/doi/abs/10.1080/01944365908978307) accessibility model (HAM) in combination with a spatial interaction model (SIM) introduced by [Wilson (1971)](https://doi.org/10.1068/a030001). More theory on these in the notebook itself.

**Aim of the Notebook** <br>
The aim of the work was to closely study and understand the methodology used by Hadjidimitrou et al., and to apply the methods in a different geographical context – the Helsinki region – for predicting accessibility. The goal was not to create a carbon copy of the work, and so exceptions were made in the used data, exact methods, and analytical depth, but the main gist was attempted to keep intact. The notebook is more a proof-of-concept with limited sample size rather than a fully-fledged analysis of accessibility in Helsinki. However, with minor modifications and more computing time, it presents a data processing pipeline for predicting accessibility on a larger scale in Helsinki.

**TLDR** <br>
There's potential for machine learning to understand and predict accessibility in geographical areas with limited data. The transferability of the predictive power from a data intensive area to an area with almost no data with machine learning is promising.

> [!note]
> Student/author: Tuukka Korpela <br>
> Supervisors: Henrikki Tenkanen, Subhrasankha Dey <br>
> This work was submitted as the course work for the Geoinformatics programme's course GIS-E6020.