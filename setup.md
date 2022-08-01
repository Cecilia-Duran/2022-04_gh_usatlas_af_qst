---
title: Setup
---
This lesson describes a quick tutorial about starting your work at UChicago Analysis Facility

# Quick Start

Be sure to have your X509 Proxy Certificate. You will need to use it e.f. to access ATLAS Data.
You can use the same you copied on lxplus (in case you already did it) or download it from this CERN page:

<a href="https://cafiles.cern.ch/cafiles/">https://cafiles.cern.ch/cafiles/</a>


Create a directory for the examples (optional)
~~~
mkdir htcondor_module && cd htcondor_module
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
> - Good pratices
>
{: .callout}
{: .language-bash}


{% include links.md %}
