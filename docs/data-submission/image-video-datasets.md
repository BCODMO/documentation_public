---
description: Guidance for submitting images and dataset derived from images.
---

# Image/Video Datasets

BCO-DMO can publish both your videos, images, and datasets derived from images (e.g. coral reef quadrat photos, and derived percent cover calculations).  What to include in data and metadata when you submit to us will vary depending upon the instrumentation, methods, and software that produced your data. &#x20;

## Submitting image/video files

Imaging datasets are often quite large.  If have or plan to acquire a dataset greater than 100GB please contact BCO-DMO in advance of your submission so we can help coordinate your submission (info@bco-dmo.org).

You should create a "Data Submission" and complete all the metadata we require using our [Submission Tool](../submission-tool/submitting-data.md).  You can upload files in the Files section, or skip the files section, submit your metadata and email us to coordinate a large data transfer. &#x20;

{% hint style="info" %}
Note that you can upload entire folders of files to our Submission Tool's files section. However, we request that you limit the size of any individual file to 10GB.
{% endhint %}

If you already have your files in an online fileshare you can email us the link and we will copy the files and send you a file inventory of what we received so you can confirm we have everything you intended to submit.  \
\
We can also send you a link to upload files to BCO-DMO's dropbox account if you request that.

Typically BCO-DMO publishes your media (e.g. images/videos) by bundling them into file bundles (.zip with zip64 support, or .tar.gz).  We can preserve any folder hierarchy your data type requires.&#x20;

{% hint style="warning" %}
**Any critical metadata encoded in folder or file names should also be in a file inventory table or main data table**. For example, images stored in folders with names by year and site should also have data columns for "year" and "site" in a file inventory table or main data table.  (more on that below)
{% endhint %}

## Data and metadata to include along with images/video files

Make sure you include the following parameters in a data table in your data submission.  They can be included in a file inventory, or incorporated into your main data table if you have one.

### Field collections

If your images or samples were collected in the field, provide collection information for where and when the samples/images were acquired:

* **date,time (or DateTime), depth, lat, lon.**  Don't forget the time zone! You can include it in your datetime values directly or describe your time zone in the description of the date/time column(s).
* \[if applicable] cruise\_id, station, sampling metadata (e.g. cast, sample\_id, mocness net\_id)
* \[if applicable] any other ancillary measurements taken concurrently with your samples (e.g. salinity, temperature, PAR)

### **Laboratory experiments**

If your images or samples have no field locations, and are purely **laboratory-based,** we still suggest having date and time information in your dataset to provide context. However, if you only have elapsed time since start of an experiment, you should indicate in the metadata when the experiments took place.

### **Identifications**

**Check your taxonomic names** before submitting your dataset to make sure they are correct.

If including taxonomic names, we suggest including the Lifescience Identifier (LSID) or a taxonomic identifier your community recommends (e.g. AphiaID, TSN, etc.).  Either directly in your main data table, or in a supplementary species list for your dataset.\
\
If you used codes in your dataset instead of taxonomic names, please provide a supplementary species list with the code, and the taxonomic name.  We suggest including a taxonomic identifier in your species list.

{% hint style="info" %}
One way to check your taxonomic names for typos is to run your data table through the [World Register of Marine Species "Taxa Match"](https://marinespecies.org/aphia.php?p=match) tool (works with csv, tsv, Excel).  The match tool will also provide information about whether your name exactly matches a known name or not. \
\
Correct any typos in taxonomic names before submitting to BCO-DMO.  You can also add a column to your dataset with the matched LSID, and/or AphiaID using this tool.
{% endhint %}

## Plankton/Particle Imaging Data

These recommendations are an effort to consolidate (meta)data requirements from taxonomic and morphological and ancillary information acquired from imagery of zooplankton, phytoplankton and other particles. These are often collected by imaging instruments such as Imaging FlowCytobot (IFCB), FlowCam, ZooScan, UVP, and LISST-Holo.

Include whatever data is needed for reuse by your community. Data managers are available to discuss your submission with you to decide together what would be best to publish (email info@bco-dmo.org).

Resources for particle and plankton best practices:&#x20;

* Neeley, A., Beaulieu, S., Proctor, C., Cetinić, I., Futrelle, J., Soto Ramos, I., Sosik, H., Devred, E., Karp-Boss, L., Picheral, M., Poulton, N., Roesler, C., and Shepherd, A.. 2021: Standards and practices for reporting plankton and other particle observations from images. 38pp. [DOI: 10.1575/1912/27377](https://darchive.mblwhoilibrary.org/handle/1912/27377).





## Example Datasets

Your images and related data may become one or more "Datasets" at BCO-DMO depending upon the kind of data and structure of it. \
\
In some cases it makes sense to have a dedicated dataset metadata page for just the images themselves and file inventory/collection information which will have its own DOI. Then associated data is served from separate dataset metadata pages each page getting a DOI. A data manager can help decide how many dataset metadata pages make the most sense for your case when you submit your data or reach out to share details of what you have.

ZooSCAN images and related data:

* ZooSCAN images of zooplankton collected during BATS MOCNESS tows... [https://www.bco-dmo.org/dataset/853440](https://www.bco-dmo.org/dataset/853440)
  * this contains the images and image collection metadata including mocness net id.
* ZooSCAN output for the objects in the images [https://www.bco-dmo.org/dataset/857891](https://www.bco-dmo.org/dataset/857891)
* Biovolume:biomass conversion provides validation for the analysis of the ZooScan images [https://www.bco-dmo.org/dataset/854077](https://www.bco-dmo.org/dataset/854077)

Particles from sediment traps:

* Images of particles collected in sediment traps for quantitative analysis from multiple platforms from 2016-2017 [https://www.bco-dmo.org/dataset/749412](https://www.bco-dmo.org/dataset/749412)
* Images and associated metadata of individually classified particles imaged and quantified in sediment trap gel layers collected on four research cruises conducted between 2015 and 2018 [https://www.bco-dmo.org/dataset/860725](https://www.bco-dmo.org/dataset/860725)&#x20;
