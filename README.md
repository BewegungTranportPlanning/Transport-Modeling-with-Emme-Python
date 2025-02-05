# Transport-Modeling-with-Emme-Python
Welcome to the Tutorial for Transport Modeling with Emme and Python. This repository provides a step-by-step guide to learning how to use several tools in Transport Planning. The Tutorial is based on the traditional 4-Step modelling (see Ortuzar and Willumsen, 2024). Here, we will try to create several scripts based on existing python packages as well as using Emme. This is a contribution to students, consultants, and researchers to learn how to bridge the gap between theory and practice with simple examples. This is a long-term project, in which we will navigate transportation engineering at a slow but continuous pace through various areas of knowledge. Some topics will have more depth than others, due to my academic and professional background. That's why it's essential to interact with the public in order to improve the content. This tutorial will be built by everyone.

## Table of Contents
1. [Zones and Networks](#zones-and-networks)
2. [Trip Generation](#trip-generation)
3. [Trip Distribution](#trip-distribution)
4. [Modal Split and Direct Demand Models](#Modal-Split-and-Direct-Demand-Models)
5. [Discrete Choice Models](#Discrete-Choice-Models)
6. [Static Assignment](#Static-Assignment)
7. [Dynamic Assignment](#Dynamic-Assignment)
8. [User Equilibrium](#User-Equilibrium)
9. [Complementary Techniques](#Complementary-Techniques)
10. [Activity-based Models](#Activity-based-models)
11. [Key Parameters, Planning Variables, and Value Functions](#Key-parameters)
12. [Pricing and Revenue](#Pricing-and-Revenue)
13. [Modeling the less common](#Modeling-the-less-common)


## 1. Zones and Network
### 1.1 Zones
Zoning is the process of dividing a study area into smaller units (zones) for analysis. These zones serve as the spatial framework for aggregate models such as trip generation, distribution, and assignemnt. A well-designed zoning system ensures that the model reflects a real-world travel patterns and behaviors. However, a trade-off between zone size and resolution is required. On one hand, smaller zones provide more detail but increase model complexity. On the other hand, larger zones simplify the model, but may obscure local variations. A usual rule of thumb is to consider smaller zones in areas with high activity (e.g., city centers) and larger zones in areas with low activity (e.g., rural areas).

Other aspects are also considered during the zoning process such as natural barriers (e.g., rivers, mountains, lakes), man-made barriers (e.g., bridges, highways, parks), administrative boundaries, land-use homogeneity/heterogeneity. To the best of our knwoledge, it's a very handmade job, difficult to implement by code. In most cases, a zoning system is defined during the development of Mobility Plans or household surveys. It is therefore common for cities to make the zoning system available in files in spatial formats (e.g., .shp or .gpkg). However, in many cases, they don't have any attributes such as population, jobs, enrollment and other information that can be used to plot maps, for example. Examples of code on including socio-demographic information in zones can be found here. 


### 1.2 Networks
## 2. Trip Generation

