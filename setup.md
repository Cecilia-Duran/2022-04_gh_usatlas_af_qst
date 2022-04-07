---
title: Setup
---
This lesson describes a quick tutorial about starting your work at UChicago Analysis Facility

# Quick Start

Just log in to the UChicago Analysis Facility 
~~~
ssh -Y <your_user_name>@login.af.uchicago.edu
~~~

Create a directory for the examples (optional)
~~~
mkdir htcondor_module
~~~

For this tutorial we will work at the /home area  but remember to move to the /data area when you use bigger data files.

small files (git repositories, source code, text files, configuration files, etc) ---> $HOME
large files (input data, output, etc) ----> $DATA

> ## What will be covered in this tutorial?
>
> - Handling jobs with HTCondor
> 
> - Coffea Casa
>
> - Coffea Casa - ServiceX
>
> - JupyterLab
>
> - XCache
>
> - Good pratices
>
{: .callout}
{: .language-bash}


{% include links.md %}
