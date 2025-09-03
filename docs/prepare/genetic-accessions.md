---
description: Guidance for submitting genetic and other types of 'omics-related data
icon: dna
---

# 'Omics-related Data

## Advantages of Sharing 'Omic Data Links through BCO-DMO <a href="#page-title" id="page-title"></a>

'Omics is a term that refers collectively to a group of rapidly evolving multi-disciplinary fields, each seeking to quantify and describe an entire collection of biological molecules of a particular type (e.g., genome). Ocean ecosystem investigators are increasingly using ‘omic tools (e.g. genomic, transcriptomic, proteomics, and metabolomic) in their research due to their ability to document the environment status in time and space.&#x20;

We want to make data generators aware of the benefits of submitting 'omics data links to BCO-DMO. While there are dedicated repositories for 'omics data (Table 1), discoverability and accessibility of metadata and environmental data are often major obstacles to reusing 'omic datasets. This is generally because the specialized 'omics repositories are designed for biomedical research and often lack the ability to connect to environmental research and associated metadata.&#x20;

Although BCO-DMO does not host raw sequence or mass spectrometry data, we can easily link to the repositories that do. In doing so BCO-DMO can allow researchers to discover your data and place it in its appropriate environmental context. Because BCO-DMO datasets are connected to their expeditions, environmental data associated with the meta’omic sample locations can be easily connected. Similarly, BCO-DMO connects data to grants and/or projects, allowing laboratory experimental data to be associated with 'omic data. BCO-DMO’s site is optimized for data discovery using search engines, and specific data types can be searched for within BCO-DMO’s holdings (Figure 1).&#x20;

With a minor effort in submission, all the hard work you have put into collecting your dataset can be used to help other researchers throughout the world better discover and interpret your data. You, the data generator, will benefit from submission through increased citations and collaborations.

**Table 1: Repositories linked by BCO-DMO**

| Repository                      | Data types                              |
| ------------------------------- | --------------------------------------- |
| NCBI (SRA, Bioproject)          | DNA, RNA sequence                       |
| EBI                             | DNA, RNA sequence                       |
| PRIDE                           | Mass Spectra (proteomics, metabolomics) |
| MassIVE                         | Mass Spectra (proteomics, metabolomics) |
| ProteomeXChange (PX consortium) | Mass Spectra (proteomics, metabolomics) |
| MetaboLights                    | Metabolomics database                   |

<figure><img src="../.gitbook/assets/image (56).png" alt=""><figcaption><p><strong>Figure 1.</strong> Example of a BCO-DMO project page that connects 'omics data with environmental datasets and sample collection metadata. The star symbol indicates a datasets within this larger project that is illustrated in Figures 2 &#x26; 3.</p></figcaption></figure>

## Contributing Genetic Accessions  <a href="#page-title" id="page-title"></a>

We recommend that **sequence data** be submitted to national biological archiving services such as the [National Center for Biotechnology Information (NCBI](http://www.ncbi.nlm.nih.gov/)) GenBank or the [European Nucleotide Archive (ENA)](https://www.ebi.ac.uk/ena/browser/) where they can be unified under a BioProject in NCBI or Study in ENA. Related metadata and supporting environmental data should be submitted to BCO-DMO to further enable discovery and re-use (see [Advantages of Sharing 'Omic Data Links through BCO-DMO](genetic-accessions.md#page-title-1)). &#x20;

Data submitted to these archives can be seamlessly connected to their associated environmental data stored in BCO-DMO by unifying all sequence projects under a BioProject in NCBI or Study in ENA (Figure 2). Thus, the BioProject structure provides a single accession key which can be used to find all of the data associated with a single research expedition or experimental project. Within the larger NCBI BioProject (ENA Study), NCBI BioSamples (ENA Sample) should be assigned for each field sample or experimental treatment condition. BioProjects and BioSamples contain and associate both the raw and post-processed sequencing data. The raw sequencing data should be deposited into NCBIs corresponding Sequence Read Archive (SRA), organized into an SRA Study (which links to an overall NCBI BioProject) with individual SRA Samples (akin to the BioSample; Figure 3). All genetic sequencing data types can be organized into this broader organizational structure, whether they are metagenomic sequencing, cultured isolates, 16S amplicon sequencing, etc.. The BioProject ID and associated BioSample IDs can then be linked with data stored in BCO-DMO facilitating data discovery and access.

<figure><img src="../.gitbook/assets/image (57).png" alt=""><figcaption><p><strong>Figure 2.</strong> An example of a physical marine sample found within the Fundamental Coral-Microbiome Project in BCO-DMO. An individual physical sample has associated environmental data within BCO-DMO. Additionally, an accession for a BioSample associated<br>with this physical sample is found within BCO-DMO which facilitates linkage to the nucleotide sequencing data for this sample found within the NCBI repository. Additional sequencing information can be obtained for this genomic data within the NCBI repository based upon this accession link via the BioSample.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (58).png" alt=""><figcaption><p><strong>Figure 3.</strong> Example of data structures from the Coral-Microbial Association Dataset #661942 found within BCO-DMO and the genomic data associated with the samples found within the NCBI repository where the sequencing data is maintained. Within NCBI, the sequencing data is organized under an overarching BioProject, with raw sequencing data maintained within the SRA database in the depicted structure. Note, only 2 biosamples are depicted in this figure whereas the dataset actually has 10 separate BioSamples.</p></figcaption></figure>

We also recognize that sequence assemblies are particularly valuable data resources that are often not accepted by raw sequence repositories as described above, and that these resources are either not being archived or are in impermanent locations (**dropbox and lab websites** etc) that are difficult to discover and whose links could change. If you have assemblies that are of potential community use, you can work with the BCO-DMO data managers to explore a means to archive it, such as using Zenodo or BCO-DMO’s servers.

For **mass spectra datasets** (e.g. proteomics and metabolomics) links to raw data repositories (e.g. PRIDE and MassIVE) can be shared and smaller processed datasets (protein or metabolite concentrations) can be hosted at BCO-DMO. The mass spectrometry community has created a consortium (The PX consortium) to “provide a common framework and infrastructure for the cooperation of proteomics resources by defining and implementing consistent, harmonized, user-friendly data deposition and exchange procedures among the members”. As a result, data deposited in one of the four participating repositories (PRIDE, PeptideAtlas, MassIVE, and jPost) are discoverable throughout the ProteomeXchange system using universal PX identifiers. We encourage submissions of raw data to this consortium following its standards. The identifier and weblink can then be hosted with valuable metadata and environmental data at BCO-DMO.

### What to send to BCO-DMO

If you have metadata and additional **data related to your genetic accessions (collection date, latitude, longitude, taxon names, treatment descriptions, environmental measurements, etc.),** please submit them to us along with any **relevant accession numbers (e.g. BioSample, SRA run id, etc)**. Note that submitting your accession numbers and related data in a tabular format (e.g. Excel, comma- or tab-delimited) will expedite our processing of your data. We will then create a Dataset Landing Page at BCO-DMO that is linked to your Project Page.

To submit accessions and related data, use our online Submission Tool at [https://submit.bco-dmo.org/](https://submit.bco-dmo.org/) to enter your metadata and upload data files. See the "[Submitting Data](../contribute/submitting-data-with-submission-tool.md)" page for more information on using the Submission Tool.

(If you cannot use the online Submission Tool, you can complete the [DATASET.rtf](https://www.bco-dmo.org/files/bcodmo/DATASET.rtf) metadata form and send it to [info@bco-dmo.org](mailto:info@bco-dmo.org) along with relevant data files.)

If applicable, please include the following information with your submission to BCO-DMO:

* BioProject number
* taxonomic names
* description of the types of sequences
* locations where species were collected (including latitude and longitude and cruise ID numbers, if known/applicable)
* sequencing and analysis methods (including instrument names and models)
* any other relevant information that will enable others to understand and re-use the data (e.g. published papers)

**Example Datasets:**

* Substrate-specific metabolic responses of model marine bacteria: [https://www.bco-dmo.org/dataset/916134](https://www.bco-dmo.org/dataset/916134)
* ezRAD libraries of Pocillopora spp. collected in 2019: [https://www.bco-dmo.org/dataset/881853](https://www.bco-dmo.org/dataset/881853)
* Accession numbers for metagenome-assembled genomes (MAGs): [https://www.bco-dmo.org/dataset/868323](https://www.bco-dmo.org/dataset/868323)
* Hurricane Harvey Coral Gene Expression: [https://www.bco-dmo.org/dataset/817298](https://www.bco-dmo.org/dataset/817298)    &#x20;

On these dataset landing pages, click the "View Table" or "Get Data" button at the top of the page to see the data published by BCO-DMO. Note that the related NCBI pages (like BioProject) are listed in a "Related Datasets" section on the landing page.

If you have any questions about how to submit data, please contact us at [info@bco-dmo.org](mailto:info@bco-dmo.org).



