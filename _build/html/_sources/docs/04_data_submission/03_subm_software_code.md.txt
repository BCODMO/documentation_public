# Software and Code

## Submitting Code, Software, and Models <a id="page-title"></a>

If you have code or software you developed as part of your project we can serve it from a supplemental files section of relevant Dataset Landing Pages. If your code has already been documented and archived \(e.g. citable with a Zenodo DOI\) then we can link to it as a Related Publication from your Dataset Landing Page.  

Check your funding agency's requirements for making your code public.  If you were funded by NSF's OCE division you are required to make your code public within two years of developing it.

You can send us your code any way you choose, whether by attaching files to an email, sending us a repository link \(e.g. github\), or sending us a Zenodo DOI.

Code and software should be documented and commented to an extent that it is understandable to others. Full reproducibility isn't always possible but you should include enough detail that someone could follow along with what was done and be able to understand how it works and how the results were produced.   The goal is transparency and transferable knowledge.  The knowledge gained and techniques employed should be reproducible even if the exact workflow can't be.

### What to include in documentation

Please include these topics in your code documentation to the extent possible:

* Provide a general description of what all your code does and how it works.
* Describe dependencies and prerequisites. Don't forget to include the version of the programming language you used.
* Provide information about settings, and configurations if applicable.
* Provide a description to go along with each file.  
  * Describe what the file does if it is code. 
  * If it is an input data file, describe where it came from, what is in it \(e.g. CTD data from cruise KN1818 obtained from R2R, DOI: \#\#\#\#\), and provide parameter names descriptions, and units \(e.g. NH4, Pore water dissolved ammonium, micromolar \(uM\).\)

For more information and examples, you can refer to "How to Write Good Documentation": [https://guides.lib.berkeley.edu/how-to-write-good-documentation](https://guides.lib.berkeley.edu/how-to-write-good-documentation).  

### What to include in metadata for datasets produced with your code

* Include a general description of how your dataset was produced using your code.
* Supply the settings, and configurations used to produce your dataset.  
* If you have input/config files we can serve these as supplemental files attached to the dataset.
* Document the version of your code used to produce the dataset you are submitting to BCO-DMO.  This lets us connect the exact version of your code to the exact data version we serve at BCO-DMO.  
  * Provide a version number, commit, release, or DOI. This lets us connect the exact version of your code to the exact data version we serve at BCO-DMO.
  * If it is related code used to analyze \(or plot\) your dataset for a subsequent journal publication, state what version of the code was used for the journal publication.

### Making code citable

We do not require you to get a DOI for your code before submitting to BCO-DMO.  However, if you would like to make your code persistent and citable you can archive and DOI your code using Zenodo.  

You can upload your files directly to Zenodo or link your Github repository if you have one.  Here is information on how to do that if you have your code in a github repository: "Making Your Code Citable" [https://guides.github.com/activities/citable-code/](https://guides.github.com/activities/citable-code/).  Make sure to pay attention to the part of the guidance that explains to link Zenodo to your github repository before making a github release.  

### For modeling projects

Please include these topics in your documentation to the extent possible:

* Provide a general description of what the model does.
* Supply input data and files, settings, and configurations.
* Describe results and outputs of model runs.
  * Describe the format of the output files, what kind of data is in them, and the parameter descriptions and units \(e.g. temperature of the surface layer, degrees Celsius\).
* If you used a Community-developed model \(e.g. ROMS\) please cite the model you used along with the version number if possible. Provide a link where documentation can be found for the model. 
* If you developed your model as part of your project refer to the above guidance for submitting software/code to BCO-DMO.  

### ‌How much model output should we serve at BCO-DMO?

We can serve the full set of output files. However, if the full output can be easily recreated from the files and methodology you provide, it would be fine to only serve one output file as an example. If serving the full output would be valuable to your community to make things easier for others' research, that would be another reason to serve the full output.

### Is GitHub an archive?

No.  Github \([https://github.com/](https://github.com/)\) is a code repository but not an archive.  Even if you make a repository public, it is not persistent since it can be taken down at any time.  If you archive your GitHub repository using Zenodo it will be preserved and you will get a digital object identifier \(DOI\) for your code.  See "Making Your Code Citable" [https://guides.github.com/activities/citable-code/](https://guides.github.com/activities/citable-code/)

Bitbucket \([https://bitbucket.org/](https://bitbucket.org/)\) is not an archive either. While Zenodo does not have the same support for connecting to Bitbucket as it does for GitHub, you can still archive a copy of your bitbucket repository at Zenodo by uploading your repository files directly.  It is a good idea to make a tag in bitbucket to document your code version and include the version information in your documentation when creating a Zenodo DOI.

