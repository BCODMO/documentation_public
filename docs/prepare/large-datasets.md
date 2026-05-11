---
description: Guidance on submitting large data files to BCO-DMO
---

# Large Datasets

### Transferring Files

If you have or plan to acquire a dataset greater than 100GB, please contact BCO-DMO in advance of your submission so we can help coordinate your file transfers ([info@bco-dmo.org](mailto:info@bco-dmo.org)).

### Make a Data Submission and complete your metadata

When you are ready to submit data to us, create a "Data Submission" using our Submission Tool ([https://submit.bco-dmo.org](../contribute/submitting-data-with-submission-tool.md)), and complete all the required metadata fields. You can skip the "Files" section of the form and instead include a description of the data you'll be sending us in the comment box on the last page of the form ("Submit" page). We will email you to coordinate the file transfer separately.

{% hint style="info" %}
Note that you can upload entire folders of files to our Submission Tool's files section using a web browser. However, we request that you limit the size of any individual file to 10GB.
{% endhint %}

If your data are too large to upload using a web browser, we will coordinate a file transfer with you using a Globus, or if you already have your files in an online fileshare (Google Drive, Globus, Box, etc.), you can share the link with us and we will retrieve the files.

After your metadata submission form is complete, **press the "Submit" button in the last section**.

For further help with the Submission Tool see "[Submitting Data with Submission Tool](../contribute/submitting-data-with-submission-tool.md)" and "[Submission Tool FAQs](../contribute/submission-tool-faqs.md)."

#### Providing a link to your online fileshare

If you provide a link to your dataset in an online fileshare (Box, Google Drive, Dropbox, etc), we will copy the files and send you a file inventory of what we downloaded so you can confirm we have everything you intended to submit. Alternatively, we can send you a link to upload files to us using Globus if you prefer this transfer method.

If your data are not tabular (e.g. images, video, netcdf gridded data), typically BCO-DMO publishes your files by bundling them into file .zip bundles (with zip64 support). We can preserve any folder hierarchy your data type requires.&#x20;

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
