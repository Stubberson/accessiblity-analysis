# Machine Learning and Accessibility in Helsinki Region
This work was submitted as the course work of the Geoinformatics programme's course GIS-E6020.

The notebook in this repo follows the article [Hansen's Accessibility Theory and Machine Learning: a Potential Merger](https://link.springer.com/article/10.1007/s11067-025-09674-2) by Hadjidimitrou et al. (2025). The article is an exploration into the utilization of machine learning (ML) for measuring accessibility in (peri)urban areas. Two ML models – random forest (RF) and a neural network (NN) – are trained and compared in predicting accessibility with limited data.

The article modelled accessibility with [Hansen's (1959)](https://www.tandfonline.com/doi/abs/10.1080/01944365908978307) accessibility model (HAM) in combination with a spatial interaction model (SIM) introduced by [Wilson (1971)](https://doi.org/10.1068/a030001). There's more theory on these in the notebook itself.

**Aim of the Notebook** <br>
The aim of the notebook was to understand and replicate the methodology used by Hadjidimitrou et al. in a different geographical context, namely the Helsinki region. The work of Hadjidimitriou et al. was followed closely with the exception of the data used and a few methodological deviations. The notebook doesn't reach an analytical depth present in the original paper, mainly due to time limitations. In addition, the notebook is more a proof-of-concept with limited sample size rather than a fully-fledged analysis of accessibility in Helsinki. However, with minor modifications and more computing time, it has the potential to act as a data processing pipeline for predicting accessibility.

**TLDR** <br>
There seems to be great potential for machine learning to understand and predict accessibility in geographical areas with limited data. The transferability of the predictive power from a data intensive area to an area with almost no data with machine learning models is promising.

> [!note]
> Student/author: Tuukka Korpela <br>
> Supervisor: Henrikki Tenkanen <br>
> Assistant: Subhrasankha Dey