# What is a dataset?

## What is a Dataset?

Describing a BCO-DMO dataset is based on the data type and format.&#x20;

Most often, a dataset is a logical collection of information organized into columns and rows. Usually, one dataset will have been produced as a result of a specific sampling event or series of events, from a particular instrument or group of instruments.

For example, a dataset may be:

* CTD data from one cruise;
* CTD data from several cruises that have been processed and analyzed in the same way;
* Water quality parameters collected by hand using a multimeter, handheld fluorometer, and nitrate sensor from the same location, such as a pier, over a period of time;
* Species names, sampling locations and dates, and specimen size and sex determined using a microscope from samples collected by various nets during several cruises pertaining to a research project;
* Trace metal concentrations in water samples collected by Niskin bottles, McLane pumps, and ice corers deployed during a cruise;
* Water biogeochemistry determined using several instruments from samples collected at sea, along with NCBI accession numbers of sequences obtained from biological samples collected at those same locations during the cruise;
* Carbonate system parameters and oyster growth measurements resulting from a laboratory experiment on ocean acidification.

Some types of datasets we receive might not exactly fit the description above but are datasets nonetheless. For example, a collection of images resulting from a model, along with the input files, and model code would constitute a BCO-DMO dataset.

**One dataset does not necessarily equate to one data file**. A dataset may be made up of multiple data tables with the same organizational structure that are combined into one by the data table manager.

<figure><img src="../.gitbook/assets/WhatsADataset.png" alt=""><figcaption><p>One dataset from multiple data files. </p></figcaption></figure>

A single dataset is described by metadata presented within one BCO-DMO Dataset landing page. Therefore, submissions that describe different types of acquisition methods, processing methods, or parameters, or that were produced by different projects/awards would likely not be a single BCO-DMO dataset.

## Dataset Types

BCO-DMO manages a wide variety of data types and formats. Contents of the datasets change depending on the subject, but what we require for all datasets if this is available is the following information:

* Date , time (+timezone)
* Location data (latitude + longitude)&#x20;

**Tabular data** with biochemical and chemical oceanographic data from in-situ measurements during cruises or field sampling, sediment samples, lab experiments, etc. make up the bulk of the BCO-DMO data holdings. Details on supported format and lay-outs of tabular data can be found [here](../preparing-data-for-submission/organizing-data-tables.md).  &#x20;

**Models, Software & Code** are a rapidly emerging data type, with little community templates or structures. Guidelines that BCO-DMO is using to standardize these data submissions can be found [here](../preparing-data-for-submission/software-and-code.md).

**GEOTRACES data** that is submitted to BCO-DMO need to follow a program specific template. Details on data submission complying with the programs needs can be found [here](../preparing-data-for-submission/geotraces.md).&#x20;

**Genetic Accessions**: Genetic accession are mainly curated in the domain specific repository NCBI. However, BCO-DMO serves the metadata related to these genetic accession data, using the specific identifier as a way to related the data in NCBI and BCO-DMO. Specific information on this data type can be found [here](../preparing-data-for-submission/genetic-accessions.md).&#x20;

**Image Classification Data**

