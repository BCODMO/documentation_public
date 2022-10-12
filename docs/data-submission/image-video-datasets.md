---
description: Guidance for submitting images and datasets derived from images.
---

# Image/Video Datasets

You may be wondering if you need to share images or video produced through the course of your research. These types of media, when associated with hypothesis-driven scientific research, are considered project output and valuable to the scientific community through their potential reuse. As such, many funding agencies will expect these data types to be shared through a repository. When in doubt you should reach out to your funding manager for confirmation.

BCO-DMO can publish your videos and images as well as data derived from those videos or images (e.g. coral reef quadrat photos and derived percent cover calculations). The information we ask you to include when you submit data will vary depending upon the instrumentation, methods, and software that produced your images and data. &#x20;

## Submitting image/video files

You can create a "Data Submission" using our [Submission Tool](../submission-tool/submitting-data.md), completing all the required metadata fields and uploading files in the Files section as you would for a tabular data submission.&#x20;

{% hint style="info" %}
Note that you can upload entire folders of files to our Submission Tool's files section. However, we request that you limit the size of any individual file to 10GB.
{% endhint %}

However, we realize imaging datasets can be quite large. If you have, or plan to acquire, a dataset greater than 100GB, please contact BCO-DMO in advance of your submission so we can help coordinate your file transfers ([info@bco-dmo.org](mailto:info@bco-dmo.org)).  For large image file transfers while using our Submission Tool, you may skip the Files section, submit the appropriate metadata, and then follow previously determined instructions for the large data transfer. &#x20;

If you already have your files in an online fileshare, you can email us the link (OR include the link in the notes section??) and we will copy the files and send you a file inventory of what we received so you can confirm we have everything you intended to submit.  Alternatively, we can send you a link to upload files to BCO-DMO's Dropbox account if you prefer this transfer method.

Typically BCO-DMO publishes your media (e.g. images/videos) by bundling them using zip or tar protocols (.zip with zip64 support, or .tar.gz). We can preserve any folder hierarchy your data type requires.&#x20;

{% hint style="warning" %}
**Note that any critical metadata encoded in folder or file names should (must?) also be in an accompanying file inventory table or in the main data table**. For example, images stored in folders with names by year and site, should also have an accompanying file inventory table with data columns for "year" and "site" or be present in the main data table (more detail below).
{% endhint %}

## Image and video file formats

**The format of the images/video you submit to BCO-DMO should be one with the most reuse potential.**  If your community would benefit from raw images (this is often TIFF format), you can submit them in this form, however in these cases, we recommend submitting raw in addition to any processed formats.

For NSF-OCE funded projects, the Data Sharing Policy states:\
_The Division of Ocean Sciences requires that metadata files, full data sets, derived data products and physical collections must be made publicly accessible within two (2) years of collection._ [https://www.nsf.gov/pubs/2017/nsf17037/nsf17037.jsp](https://www.nsf.gov/pubs/2017/nsf17037/nsf17037.jsp)

## Data and metadata to include along with images/video files

Make sure you include the following parameters in a table. They can be included in a file inventory table or incorporated into your main data table if you have one.

* **Filename**, the full name of your file including the file extension (e.g. myimage.jpg, myvideo.mp4)
* \[if applicable] **folder name(s)** if your files are stored in subfolders that you would like preserved when we publish your files.

{% hint style="info" %}
If you need help making a file inventory table, contact us at info@bco-dmo.org.  We can get you started with a basic file inventory table to which you can add other data columns (described in the following sections) to provide important context for your data.
{% endhint %}

### Field observations

If your images or samples were collected in the field, provide collection information for the location, date, and time the samples/images were acquired:

* **date, time (or DateTime), depth, latitude, longitude.**  Don't forget the time zone! You can include it in your datetime values directly or describe your time zone in the description of the date/time column(s).
* \[if applicable] cruise\_id, station, sampling metadata (e.g. cast, sample\_id, mocness net\_id)
* \[if applicable] any other ancillary measurements taken concurrently with your samples (e.g. salinity, temperature, PAR)

### **Laboratory experiments**

If your images or samples have no field locations and are purely **laboratory-based,** we still recommend including date and time information in your dataset to provide context. However, if you only have the elapsed time since the start of an experiment, you should indicate in the metadata when the experiments took place.

If your experimental design included treatments and controls, do not forget to add data column(s) to indicate which treatment the image or video was from.

### **Identifications**

**Check any taxonomic names** before submitting your dataset to make sure they are correct.

\[optional] If including taxonomic names, we recommend including the Lifescience Identifier (LSID) or a taxonomic identifier familiar to your community (e.g. AphiaID, TSN, etc.). This can be included either directly as a column in your main data table or in a supplementary species list for your dataset.\
\
If you used codes in your dataset instead of taxonomic names, please provide a supplementary species list with the codes and the taxonomic names. We recommend including taxonomic identifiers in your species list.

{% hint style="info" %}
One way to check your taxonomic names for typos is to run your data table through the [World Register of Marine Species "Taxa Match"](https://marinespecies.org/aphia.php?p=match) tool (which accepts csv, tsv, Excel). The match tool will also provide information about whether your name exactly matches a known name or not. \
\
Correct any typos in taxonomic names before submitting to BCO-DMO. You can also add a column to your dataset with the matched LSID, and/or AphiaID using this tool.
{% endhint %}

## Plankton/Particle Imaging Data

These recommendations are an effort to consolidate (meta)data requirements from taxonomic, morphological, and ancillary information acquired from imagery of zooplankton, phytoplankton, and other particles. These data are often collected by imaging instruments such as Imaging FlowCytobot (IFCB), FlowCam, ZooScan, UVP, and LISST-Holo.

Include whatever data is needed for reuse by your community. BCO-DMO data managers are available to discuss your submission with you to decide together what would be best to publish (email [info@bco-dmo.org](mailto:info@bco-dmo.org)). BCO-DMO aligns with the best practices for reporting particle and plankton as presented in Neeley et al. (2021).&#x20;

**References:**

* Neeley, A., Beaulieu, S., Proctor, C., Cetinić, I., Futrelle, J., Soto Ramos, I., Sosik, H., Devred, E., Karp-Boss, L., Picheral, M., Poulton, N., Roesler, C., and Shepherd, A.. 2021: Standards and practices for reporting plankton and other particle observations from images. 38pp. [DOI: 10.1575/1912/27377](https://darchive.mblwhoilibrary.org/handle/1912/27377).

## Example Datasets

Your images and related data may become one or more "Datasets" at BCO-DMO depending upon the type of data and their structure.\
\
In some cases, it makes sense to have a dedicated dataset metadata page for just the images themselves and a file inventory or collection information, which will have its own DOI. Then associated data is served from separate dataset metadata pages each page getting a DOI. A Data Manager can help decide how to organize your data into metadata landing pages when you submit your data or when you reach out in advance of your submission.

**ZooSCAN images and related data:**

* ZooSCAN images of zooplankton collected during BATS MOCNESS tows [https://www.bco-dmo.org/dataset/853440](https://www.bco-dmo.org/dataset/853440)
  * this contains the images and image collection metadata including MOCNESS net id.
* ZooSCAN output for the objects in the images [https://www.bco-dmo.org/dataset/857891](https://www.bco-dmo.org/dataset/857891)
* Biovolume:biomass conversion provides validation for the analysis of the ZooScan images [https://www.bco-dmo.org/dataset/854077](https://www.bco-dmo.org/dataset/854077)

**Particles from sediment traps:**

* Images of particles collected in sediment traps for quantitative analysis from multiple platforms from 2016-2017 [https://www.bco-dmo.org/dataset/749412](https://www.bco-dmo.org/dataset/749412)
* Images and associated metadata of individually classified particles imaged and quantified in sediment trap gel layers collected on four research cruises conducted between 2015 and 2018 [https://www.bco-dmo.org/dataset/860725](https://www.bco-dmo.org/dataset/860725)&#x20;
