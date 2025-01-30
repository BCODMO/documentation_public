---
description: Instructions on contributing model output, software, and code to BCO-DMO
---

# Models, Software, and Code

## What to do with Code, Software and Models? <a href="#page-title" id="page-title"></a>

If you have code or software you developed as part of your project, check your funding agency's requirements for making your code public. If you were funded by NSF's OCE division you are required to make your code public within two years of developing it.

**We recommend and strongly encourage archiving and getting a dedicated DOI** **for your code**. This is becoming a widely accepted best practice for code and software output from funded research. However, if for some reason this is not possible, we can include it as a Supplemental File to a relevant BCO-DMO Dataset Page and it will be archived in the same package as your data. We consider this a sub-optimal option as it does not follow current recommended practice. The attached code will not be citable or discoverable on its own and will not have an appropriate software license applied to it (see more about [LICENSES](software-and-code.md#dont-forget-to-add-a-license)).

If your code has already been documented and archived (i.e. citable with a DOI), we can link to it as a Related Publication from your Dataset Landing Page (see section below [Making code citable with an archive](software-and-code.md#making-code-citable-with-an-archive)). &#x20;

You can send us your code any way you choose, whether by attaching files to an email, uploading them to the submission tool ([https://submit.bco-dmo.org/](https://submit.bco-dmo.org/)), sending us a repository link (e.g. GitHub), or sending us a DOI.

Code and software should be **documented and commented to an extent that it is understandable** to others. Full reproducibility isn't always possible but you should include enough detail that someone could follow along with what was done and be able to understand how it works and how the results were produced. The **goal is transparency and transferable knowledge**. The knowledge gained and techniques employed should be reproducible even if the exact workflow can't be.

{% hint style="info" %}
**Do I need GitHub or to know version control to follow this guidance?**

While we encourage the use of version control (e.g. git), and a GitHub online repository, you don't need to use either to get your code archived and document it for long-term preservation.  The sections below provide guidance with and without a github repository.
{% endhint %}

## Code documentation: What to include

Whether you upload your files to an archive like Zenodo or submit them to us with your BCO-DMO dataset, you will have to include the following in your documentation to the greatest extent possible in order to ensure proper reusability of your code:

* Provide a general description of what your code does and how it works.
* Describe dependencies and prerequisites. Don't forget to include the version of the programming language you used.
* Provide information about settings and configurations, if applicable.
* Provide a description to go along with each file. &#x20;
  * Describe what the file does if it is code.&#x20;
  * If it is an input data file, describe where it came from, what is in it (e.g. CTD data from cruise KN1818 obtained from R2R, DOI: ####), and provide parameter names descriptions, and units (e.g. NH4, Pore water dissolved ammonium, micromolar (uM)).

For more information and examples, you can refer to "How to Write Good Documentation": [https://guides.lib.berkeley.edu/how-to-write-good-documentation](https://guides.lib.berkeley.edu/how-to-write-good-documentation). &#x20;

{% hint style="info" %}
Comment lines within code are a recommended best practice, however, they do not take the place of the above recommendations.
{% endhint %}

**Where do you put documentation?**  If you have a GitHub repository you can put documentation in your README.md file. Or you can put it in a supplemental file archived with your code. You can also provide it to BCO-DMO along with your data submission's methodology section or as a supplemental file.

* Example of documentation as part of the GitHub README.md file: a [README.md ](https://github.com/ldykman/FD_EPR/blob/v1.0.0/README.md)archived at Zenodo with package DOI: [10.5281/zenodo.4625160](https://doi.org/10.5281/zenodo.4625160\)))
* Example of documentation provided as a supplemental file at Zenodo (DOI: [10.5281/zenodo.7129648)](https://doi.org/10.5281/zenodo.7129648)
* Example of documentation as a supplemental file attached to a BCO-DMO dataset: "OysterFutures simulation model" [https://www.bco-dmo.org/dataset/875301](https://www.bco-dmo.org/dataset/875301).

## My code is in GitHub, why does it need to go somewhere else?

[GitHub](https://github.com/) and[ Bitbucket](https://bitbucket.org/) are code repositories but not archives. Code repositories are great for sharing and collaborating, but they can be taken down at any time by the authors or the repository.

If you **archive** your code repository using Zenodo (or another archive), it will be **preserved** and you will get a digital object identifier (**DOI**) for your code. See "Making code citable with an archive" below.

Once you have your code archived you can supply the **formal citation and DOI to journal publications and BCO-DMO** along with dataset submissions.

While Zenodo does not have the same support for connecting to Bitbucket as it does for GitHub, you can still archive a copy of your Bitbucket repository at Zenodo by uploading your repository files directly. It is a good idea to make a tag in Bitbucket to document your code version and include the version information in your documentation when creating a Zenodo DOI.

## Making code citable with an archive

If you would like to make your code persistent and citable you can archive your code using an archive such as Zenodo.  You will then have a **DOI and formal citation** for your code.  Make sure to document your code well for optimal reuse, see the above topic [code documentation](software-and-code.md#code-documentation-what-to-include).

Adding software to Zenodo can be done by uploading files directly, or by linking a github repository.&#x20;

*   **Connect your GitHub repository to Zenodo** to archive code releases:

    See Github's "**Making Your Code Citable**" [https://guides.github.com/activities/citable-code/](https://guides.github.com/activities/citable-code/). &#x20;

    * Make sure to pay attention to the part of the guidance that explains to connect Zenodo to your GitHub repository **before** making the next GitHub release you want to archive. &#x20;
    * After you connect a repository to Zenodo, each time you make a release in github it will automatically get archived and DOI'ed at Zenodo.
* If you don't have a GitHub repository, you can **upload your files directly to Zenodo**.  \
  Step-by-step through on how to upload files directly to Zenodo: [https://help.zenodo.org/docs/deposit/create-new-upload/](https://nam02.safelinks.protection.outlook.com/?url=https%3A%2F%2Fhelp.zenodo.org%2Fdocs%2Fdeposit%2Fcreate-new-upload%2F\&data=05%7C01%7Cksoenen%40whoi.edu%7C8143922666854cd1c57c08dbcff46e29%7Cd44c5cc6d18c46cc8abd4fdf5b6e5944%7C0%7C0%7C638332420977877855%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C3000%7C%7C%7C\&sdata=8AVXlBE7C6uMEdxOyGX%2ByYjMcre%2B7pm%2FhKHa8hH3AXo%3D\&reserved=0)

Examples of GitHub releases archived at Zenodo:

* Dykman, L. (2021). ldykman/FD\_EPR: GitHub repository release associated with Dykman et al. (2021) Ecology (Version v1.0.0). Zenodo. [https://doi.org/10.5281/zenodo.4625160](https://doi.org/10.5281/zenodo.4625160)&#x20;
* Schenck, F. R. (2022). _schenckf/BWE\_Experiment: The effect of warming on seagrass wasting disease depends on host genotypic identity and diversity - Analyses_ (Version V2.0.0) \[Computer software]. Zenodo. [https://doi.org/10.5281/zenodo.7129500](https://doi.org/10.5281/zenodo.7129500)

## Don't forget to add a LICENSE

Code licenses **provide specific boundaries** on how others are allowed to reuse your code and credit. The [**MIT license**](https://opensource.org/license/mit/) is often used for open-source software. Whichever license you use, make sure that the license will satisfy funder sharing requirements.&#x20;

* To **add a** **license directly to a Zenodo submission** by creating a text file (typically named LICENSE or LICENSE.txt), copy the text of the license into the file (make sure to replace the year to the current year the names of the copyright holders) and upload it to Zenodo with your code.
* To **add a license to your code in GitHub**, follow this walk through to add a license.\
  [https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository)

When BCO-DMO publishes code as supplemental files along with a dataset. The data and code are published with the same license, [**Creative Commons Attribution 4.0**](https://creativecommons.org/licenses/by/4.0/).

## I'm using someone else's code that isn't public or archived

We understand the reality that datasets are sometimes produced using code that isn't publicly available. Whether it is **proprietary software from an instrument manufacturer** or if you used code **provided by a colleague** that isn't published in a way that follows best practice recommendations for long-term archiving.

When you submit a dataset to BCO-DMO provide whatever information you have about the code.&#x20;

* Who are the authors? Provide real names not just usernames if you have them.
* Briefly describe what the code does.
* How do you get the code/software? Is it publicly accessible? If so, where can it be found? Or is it available upon request or purchase from the authors or company?
* What version of the code did you use? Or lacking that, what date did you use the code? If it is public on GitHub, provide the link to the repository and the version (or commit) you used if available.

If you know the authors of public, but not archived code, encourage them to publish their code with documentation, a release, and a license. (See "Making Your Code Citable" [https://guides.github.com/activities/citable-code/](https://guides.github.com/activities/citable-code/)). They get a formal citation they can put on their CV after archiving it which is a great incentive, not to mention enhanced discoverability and usage.

## Models

Please include these topics in your documentation to the greatest extent possible:

* Provide a general description of what the model does.
* Supply input data and files, settings, and configurations.
* Describe the results and output of model runs.
  * Describe the format of the output files, what kind of data are in them, and the parameter descriptions and units (e.g. temperature of the surface layer, degrees Celsius).
* If you used a community-developed model (e.g. ROMS), please cite the model you used along with the version number, if possible. Provide a link where documentation can be found for the model.&#x20;
* If you developed your model as part of your project, refer to the above guidance for submitting software/code to BCO-DMO. &#x20;

### ‌How much model output should we publish at BCO-DMO?

We can publish the full set of output files. However, if the full output can be easily recreated from the files and methodology you provide, it would be fine to only publish one output file as an example. If publishing the full output would be valuable to your community to make things easier for others' research, that would be another reason to publish the full output.

## Metadata for datasets produced with your code

* Include a general description of how your dataset was produced using your code.
  * Example: "_..the column Functional Guild was generated by hierarchical clustering in R using the function gowdis in the package FD as described in Dykman et al. (2021). Scripts to run these analyses are available at Zenodo (Dykman, 2021, DOI:_ [_10.5281/zenodo.4625160_](https://doi.org/10.5281/zenodo.4625160)_)."_
* Document the version of your code used to produce the dataset you are submitting to BCO-DMO. This lets us connect the exact version of your code to the exact data version we publish at BCO-DMO. &#x20;
  * Provide a version number, commit, release, or DOI. This lets us connect the exact version of your code to the exact data version we publish at BCO-DMO.
  * If it is related code used to analyze (or plot) your dataset for a subsequent journal publication, state what version of the code was used for the journal publication.
  * Example: "_...All code was written and run in R (version 3.6.1,_ [_www.R-project.org_](http://www.r-project.org/)_). Github repository_ [_https://github.com/schenckf/BWE\_Experiment_](https://github.com/schenckf/BWE_Experiment) _**V2.0.0** archived at Zenodo (DOI:_ [_10.5281/zenodo.7129500_](https://doi.org/10.5281/zenodo.7129500)_). A general description of the code is included in the repository release in file "Analysis Description.docx."_
* Supply any settings and configurations used to produce your dataset.
  * Document the versions of the language and packages you used.\
    &#x20;e.g. `R version 3.4.1 (2017-06-30), packages;`` `_`vegan v2.5.4 (Oksanen et al. 2019), ggplot2 v3.2.1 (Wickham 2016).`_&#x20;
  * \[If applicable] Provide input/config files. We can publish these as supplemental files attached to the dataset.

#### Citing Packages and Sofware Versions

Where possible, provide the exact package and software version numbers you used to generate your data and the recommended citation for your software.&#x20;

Example of citing the language version:

> These data were produced using code run with **R version 3.4.1 (2017-06-30)**.

Example of software cited in methodology text:\
From the dataset "Tidal study of seawater microbial communities" [https://www.bco-dmo.org/dataset/783679](https://www.bco-dmo.org/dataset/783679)

> _To understand the variability in microbial communities over time at all sites, Bray-Curtis dissimilarity was calculated between each sample in the R package **vegan v2.5.4 (Oksanen et al. 2019)** and illustrated using non-metric multidimensional scaling (NMDS) in the R package, **ggplot2 v3.2.1 (Wickham 2016)**._

References:

* Wickham H (2016). ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York. ISBN 978-3-319-24277-4, https://ggplot2.tidyverse.org. [https://doi.org/10.1007/978-3-319-24277-4](https://doi.org/10.1007/978-3-319-24277-4)
* Oksanen J, Blanchet FG, Friendly M, Kindt R, Legendre P, McGlinn D, Minchin PR, O’Hara RB, Simpson GL, Solymos P, Stevens HH, Szoecs E, Wagner H (2019) Vegan: Community Ecology Package. R package version 25-4. Available from https://cran.r-project.org/package=vegan [https://cran.r-project.org/src/contrib/Archive/vegan/vegan\_2.5-4.tar.gz](https://cran.r-project.org/src/contrib/Archive/vegan/vegan_2.5-4.tar.gz)

{% hint style="info" %}
Note that the reference Wickham (2016) for ggplot2 doesn't include the version, but the methods text does include the exact version number that was used to produce the dataset.
{% endhint %}

{% hint style="info" %}
If you have a lot of installed packages, you can supply a supplemental file with the packages and version numbers you used instead of citing them all in your methods text.
{% endhint %}

#### Getting versions in R

To print the R version associated with a project in RStudio:

<pre><code><strong>> R.version.string
</strong>[1] "R version 4.1.0 (2021-05-18)"
</code></pre>

To get the version of a package you imported (dplyr is the name of an example package) :

```
> packageVersion("dplyr")
[1] ‘1.0.7’
```

To print package information about all loaded packages (including package version), use the installed.packages() function.&#x20;

This function returns a matrix containing one row per loaded package. The matrix shows  `"Package"`, `"LibPath"`, `"Version"`, `"Priority"`, `"Depends"`, `"Imports"`, `"LinkingTo"`, `"Suggests"`, `"Enhances"`, `"OS_type"`, `"License"` and `"Built".`

Since this is a matrix, you can specify which columns, and therefore which metadata is returned. For example, if you want the package name and the version for each package, you would run:&#x20;

<pre><code>> package_metadata &#x3C;- as.data.frame(installed.packages()[,c(1,3:4,11)])
<strong>> rownames(package_metadata) &#x3C;- NULL
</strong>> package_metadata &#x3C;- package_metadata[is.na(package_metadata$Priority),1:2,drop=FALSE]
<strong>> print(package_metadata, row.names=FALSE)
</strong>
Package    Version       
askpass        1.1    
assertthat      0.2.1     
backports      1.2.1     
base64enc      0.1-3            
BH   1.75.0-0
</code></pre>

To print all high-level system information in RStudio:

```
> sessionInfo()

R version 4.1.0 (2021-05-18)Platform: x86_64-apple-darwin17.0 (64-bit)
Running under: macOS Big Sur 11.4

Matrix products: default
LAPACK: /Library/Frameworks/R.framework/Versions/4.1/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base

other attached packages:
[1] fuzzyjoin_0.1.6  stringr_1.4.1    dplyr_1.0.7      lubridate_1.7.10
[5] readxl_1.3.1  

loaded via a namespace (and not attached): 
[1] Rcpp_1.0.9       rstudioapi_0.13  magrittr_2.0.3   tidyselect_1.1.1 
[5] R6_2.5.1         rlang_1.0.6      fansi_0.5.0      tools_4.1.0      
[9] utf8_1.2.1       cli_3.4.1        DBI_1.1.1        ellipsis_0.3.2  
[13] assertthat_0.2.1 tibble_3.1.2     lifecycle_1.0.3  crayon_1.5.2    
[17] purrr_0.3.5      vctrs_0.3.8      glue_1.6.2       stringi_1.7.8   
[21] compiler_4.1.0   pillar_1.6.1     cellranger_1.1.0 generics_0.1.0  
[25] pkgconfig_2.0.3
```

In this output, the standard or base packages are listed under "attached base packages." These packages are loaded by R by default and do not need to be called into the project.

"Other attached packages" are those that are loaded into a project using the library() function.&#x20;

Packages listed under "loaded via a namespace" are those imported automatically by R as dependencies of "other attached packages."

#### Getting versions in Python

To get your Python version using the command line:

<pre class="language-shell-session"><code class="lang-shell-session"><strong>$ python3 --version
</strong>Python 3.10.6
<strong>or
</strong><strong>$ python --version
</strong><strong>Python 2.7.18
</strong></code></pre>

To get your Python version from within a notebook (jupyter, colab, etc)<img src="../.gitbook/assets/image (23).png" alt="" data-size="original">

To get the version of a package you imported you can use `packagename.__version__`

```python
>>> import numpy
>>> print(numpy.__version__)
1.21.5
```

There are several ways to get all package versions in your environment.  See pip "list" "freeze"  or "show" in [pip documentation.  ](https://pip.pypa.io/en/stable/cli/pip_list/#examples)&#x20;

#### Getting versions in Matlab

You can get the version of Matlab and installed packages with [the command `ver`](https://www.mathworks.com/help/matlab/ref/ver.html):

<pre class="language-matlab"><code class="lang-matlab"><strong>ver
</strong></code></pre>

```
ans = 
-------------------------------------------------------------------------------------------------------
MATLAB Version: 8.2.0.29 (R2013b)
MATLAB License Number: 234567
Operating System: Microsoft Windows 7 Version 6.1 (Build 7601: Service Pack 1)
Java Version: Java 1.7.0_11-b21 with Oracle Corporation Java HotSpot(TM) 64-Bit Server VM mixed mode
-------------------------------------------------------------------------------------------------------
MATLAB                                                Version 8.2        (R2013b)             
Simulink                                              Version 8.2        (R2013b)      
Control System Toolbox                                Version 9.6        (R2013b)       
```
