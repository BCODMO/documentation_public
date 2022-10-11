# Large Data Files

If you have or plan to acquire a dataset greater than 100GB, please contact BCO-DMO in advance of your submission so we can help coordinate your file transfers ([info@bco-dmo.org](mailto:info@bco-dmo.org)).

You should create a "Data Submission" and complete all the metadata we require using our [Submission Tool](../submission-tool/submitting-data.md). You can upload files in the Files section or skip the Files section, submit your metadata, and email us to coordinate a large data transfer. &#x20;

{% hint style="info" %}
Note that you can upload entire folders of files to our Submission Tool's files section. However, we request that you limit the size of any individual file to 10GB.
{% endhint %}

If you already have your files in an online fileshare, you can email us the link and we will copy the files and send you a file inventory of what we received so you can confirm we have everything you intended to submit.  \
\
We can also send you a link to upload files to BCO-DMO's Dropbox account if you request that.

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
**Any critical metadata encoded in folder or file names should also be in a file inventory table or main data table**. For example, images stored in folders with names by year and site should also have data columns for "year" and "site" in a file inventory table or main data table.&#x20;
{% endhint %}
