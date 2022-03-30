---
title: "Coffe Casa ServiceX"
teaching: 5
exercises: 15
questions:
- "What is ServiceX?"
objectives:
- "Learn to use ServiceX"

keypoints:
- "Remember to check Columnar data analysis with DAOD_PHYSLITE on the link above."

---

> ## About ServiceX
>
> - <a href="#servicex">ServiceX</a>
>
> - <a href="#columnar">Columnar data analysis with DAOD_PHYSLITE</a>
>
{: .callout}

ServiceX, a component of the IRIS-HEP Intelligent Data Delivery Service, is an experiment-agnostic service to enable on-demand columnar data delivery tailored for nearly interactive, high performance, array-based Pythonic analyses. It provides a uniform backend interface to data storage services and an intuitive frontend for users to enable columnar transformations from multiple different data formats and organizational structures.

Columnar data delivery
ServiceX seeks to enable on-demand data delivery of columnar data in a variety of formats for physics analyses. It provides a uniform backend to data storage services, ensuring the user doesn't have to know how or where the data is stored, and is capable of on-the-fly data transformations into a variety of formats (ROOT files, Arrow arrays, Parquet files, ...) The service offers preprocessing functionality via an analysis description language called func-adl that allows users to filter events, request columns, and even compute new variables. This enables the user to start from any format and extract only the data needed for an analysis.

<h2 id="servicex">ServiceX</h2>
![image info](./../fig/servicex_1workflow.png)
![image info](./../fig/servicex_2globus.png)
![image info](./../fig/servicex_3dash.png)
![image info](./../fig/servicex_4profile.png)

<h2 id="columnar">Columnar data analysis with DAOD_PHYSLITE example</h2>
Check the example <a href="https://github.com/nikoladze/agc-tools-workshop-2021-physlite">here</a>

{% include links.md %}
