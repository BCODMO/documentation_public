---
description: Metadata BCO-DMO requires for data curation
---

# Metadata for Datasets

Each dataset at BCO-DMO ([www.bco-dmo.org](https://www.bco-dmo.org)) needs to be accompanied by metadata (information describing the data) in order for a user to understand and effectively reuse the data. Therefore, each dataset needs to have its own metadata page, specifically describing how the data were generated. Below is a description the necessary metadata at BCO-DMO.

Gathering the necessary metadata for a specific dataset can seem cumbersome, but a robust [data management plan](data_management_plan.md) at the start of the project can help alleviate the burden.&#x20;

### Project and Funding

Provide the project title and the award numbers that directly funded the data. Refrain from adding all broadly related awards and projects.&#x20;

When adding an NSF Collaborative Reasearch project, all award numbers can be added if they all contributed to the generation of the data, but this is not required. The awards listed should be only those that contributed to the specific dataset.

### People

Identify all people that need to be acknowledged and their contact details. This can include individuals other than the PI and co-PI of the project itself. We can assign the following roles on datasets, in addition to PI and Co-PI: Scientist, Student, Analyst, or Technician. Please indicate the people and the roles that will need to be added to each dataset.&#x20;

The affiliation/institution of each person at the time of data acquisition is also required.

### Abstract

Provide an abstract that describes your data. In terms of length and level of detail, your dataset abstract should be similar to an abstract you might write for a publication. Avoid using an award or paper abstract with information not related to the exact data you are submitting to BCO-DMO.

It should describe the _what, where, when, why, how,_ and _who_ of the specific dataset you're submitting. If relevant, describe how the data are related to any larger studies and how the data might be of interest to the science community.

To support metadata interoperability and discovery, BCO-DMO publishes metadata in compliance with the [DataCite Metadata Schema](https://schema.datacite.org/meta/kernel-4.2/index.html), which limits HTML markup in the Abstract field. This means your Abstract will be published as plain text only (i.e. no italics, bold text, hyperlinks, etc.).

### Keywords

We suggest 3-5 keywords but you can provide more or less (e.g. ocean acidification, coral reefs, calcification). These keywords can be any terms you feel are appropriate for the data and they will aid in data discovery when users perform dataset searches.

### Methods and Sampling Description

We require a written dataset-specific description of the sample acquisition methods or experimental methods used in generating the dataset. We can link out to an article describing the methods in depth, but a summary of one to several paragraphs should be provided for each dataset.&#x20;

### Data Processing Description

We also require details on how the data were processed, if relevant. Again, we can link out to an article describing the methods in depth, but we require a written description that will be displayed on the public metadata landing page to provide users with a basic understanding of how the dataset was collected.

### Deployment

Deployments refer to cruises, moorings, or other types of instruments/vessels involved in data collection. We need the following information for each deployment associated with a dataset:

* Name or ID of the deployment. Typically follows the ID assigned by the ship operator.
* Start and end date of the deployment
* Chief Scientists of the deployment
* The name of the platform/vessel
* General location of the deployment
* Any additional description to better describe or understand the deployment (Optional)
* For cruises in R2R ([https://www.rvdata.us/](https://www.rvdata.us/)), a link to the cruise page in R2R page will suffice

### Instruments

Please include the name and a description of all sampling equipment and instrumentation involved in generating the dataset. Include equipment/instrument manufacturer names, model numbers (where relevant), and calibration information for individual sensors.

### Parameters

Parameter names are the column headers in tabular data. Please provide a description for each parameter, units of measurement, and missing data identifiers (e.g. NaN, nd)

![Example of parameter descriptions needed to complete the dataset metadata.](<../.gitbook/assets/image (25).png>)

### Related items

Please include the full citations of any related publications, references, or related datasets. If you have supplemental files to provide, such as instrument calibration documents or a manual of laboratory procedures, please include those, too, preferably in PDF format (or with the citation and DOI if one is available).

&#x20;
