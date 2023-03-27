---
description: Guidance on submitting large data files to BCO-DMO.
---

# Large Data Files

If you have or plan to acquire a dataset greater than 100GB, please contact BCO-DMO in advance of your submission so we can help coordinate your file transfers ([info@bco-dmo.org](mailto:info@bco-dmo.org)).

{% hint style="info" %}
Note that you can upload entire folders of files to our Submission Tool's files section. However, we request that you limit the size of any individual file to 10GB.
{% endhint %}

When you are ready to submit data to us, create a "Data Submission" using our [Submission Tool](../contribute/contributing-data-via-submission-tool.md), completing all the required metadata fields and uploading files in the "Files" section.&#x20;

If your data are too large to upload using a web browser, we can coordinate a file transfer with you using a Dropbox file request from our account, or if you already have your files in an online fileshare (Google Drive, Globus, Box, etc.), you can provide the link.\
\
If submitting files from an online fileshare, proceed with filling in the appropriate metadata by creating a dataset submission in the [Submission Tool](../contribute/contributing-data-via-submission-tool.md).  You may skip the "Files" section of the form, and instead include a description of the data you have to send us in the comment box on the last page of the form ("Submit" page).   We will email you to coordinate the file transfer.

We will copy the files and send you a file inventory of what we downloaded so you can confirm we have everything you intended to submit.  Alternatively, we can send you a link to upload files to BCO-DMO's Dropbox account if you prefer this transfer method.

If your data are not tabular (e.g. images, video, netcdf gridded data), typically BCO-DMO publishes your files by bundling them into file bundles (.zip with zip64 support, or .tar.gz). We can preserve any folder hierarchy your data type requires.&#x20;

If your data are in tables (e.g. tsv, csv, Excel), BCO-DMO will import them into our data system and then provide data access in a variety of interoperable formats.

For datasets with many files, we suggest making a file inventory table with the filename and any relevant collection information:

What to include in a **file inventory table**:

* **date and time** (or DateTime) &#x20;
  * Don't forget the **time zone**! You can include it in your date-time values directly (e.g. ISO DateTime with Time Zone) or document your time zone in the description of the date-time column(s) in your metadata.
  * If purely **laboratory-based** and you only have elapsed time since the start of an experiment, you should indicate in the metadata when the experiments took place.
* \[if field collections] include **depth, latitude, longitude**
* \[if applicable] cruise\_id, station, sampling metadata (e.g. cast, sample\_id, net\_id)
* \[if your files are stored in different folders]  include the **folder name**(s).&#x20;
* \[optional] filesize, checksum (e.g. md5,sha1)

{% hint style="warning" %}
**Any critical metadata encoded in folder or file names must also be in a file inventory table or main data table**. For example, images stored in folders with names by year and site should also have data columns for "year" and "site" in a file inventory table or main data table.&#x20;
{% endhint %}
