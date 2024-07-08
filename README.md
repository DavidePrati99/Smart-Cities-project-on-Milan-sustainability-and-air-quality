# Smart Cities project on Milan sustainability and air quality

The concept of smart cities embodies a dynamic and evolving approach to urban development, driven by
goals such as environmental sustainability and enhanced quality of life. This paper explores Milan as a
case study in urban transformation, emphasizing initiatives to address climate change, digital innovation,
and sustainable mobility. Milan’s transformation towards a “15-minute city”, where essential services are
easily accessible, highlights the importance of improving air quality and enhancing green spaces to create a
healthier urban environment.

We will analyze air quality data from 12 monitoring stations across the city, sourced from Milan’s open data
and additional community sensors, to identify correlations between air quality and existing green spaces and
buildings. We will try to determine, using ML techniques, the possible values of pollution across the city
in places where currently there are no stations available. We will also determine how much the additional
presence of a new hypothetical green area, as a source of air purification, can improve air quality and con-
sequently the city’s quality of life.

Attention will be given to the challenges of integrating green spaces in degraded areas to ensure they contribute positively to the urban environment. The goal is to promote a sustainable and livable city, addressing
both environmental and social dimensions of urban development.


To do this, we will conduct data research from various sources, explore and prepare them, and augment
them, all using the Python library GeoPandas to work with geospatial data. To consider buildings and
green areas’ positions in the process, with respect to each station they are aggregated in areas considering
both distance and angle.

After the process of data augmentation, we will have more than 400 covariates, undergoing an heavy feature
selection process. Among various ML algorithms, the best one will be chosen on the basis of interpretability
and R2. At this point, based on real and realistic scenarios, we will estimate the air pollution levels that
could be recorded by a station in the Darsena area, and the improvement in air quality that would result
from the creation of a new park at Scalo Farini, as an example to show that our model can be used for such
tasks of prediction and impact assessment.

The Notebooks are organized as follows:
-  1- data exploration and preparation: preliminary data analysis, including filtering, integration, and management of geospatial data formats
-  2- data augmentation for natural data: conversion of geospatial data of green areas into points, following the logic indicated in the report
-  3- data augmentation for buildings: the same but for the buildings
-  4- ML: Machine Learning approaches to achieve the predetermined goals
-  5- Graphs for the report

All further information are available in the report
