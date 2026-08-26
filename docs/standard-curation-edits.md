---
description: A description of the standard data and metadata edits performed by BCO-DMO
---

# Standard Curation Edits

BCO-DMO curates and processes data and metadata to ensure they are findable, accessible, interoperable, and reusable. Our typical processing procedures are described below. Some datasets require a greater or fewer number of processing steps than others, depending on the format and organization of the data files we receive. Refer to individual datasets' metadata landing pages for a description of any additional processing or editing that's been applied beyond the standard steps described here.

### Parameter Naming

BCO-DMO uses the term "parameter" to mean "column name", "column header", or "field". To support data re-use in a wide variety of applications, we routinely adjust submitter-provided parameter names to meet the following naming conventions:

* The only allowed characters in parameter names are A-Z, a-z, 0-9, and underscores (no spaces, hyphens, commas, parentheses, or Greek letters).
* Parameter names must begin with a letter.
* Units typically are not included within parameter names as they are provided as part of the metadata.

### Missing Data Identifiers

A "missing data identifier" is the notation used to indicate there is no data value. Commonly used notations for missing data include -999, NA, nd, NaN, or blank cells.&#x20;

* By default, BCO-DMO represents missing data as blank (null) values when you download the data as a .csv file.&#x20;

### Latitude and Longitude Conversions

* Latitudes are typically reported in decimal degrees north, meaning coordinates in the Southern Hemisphere are negative values.&#x20;
* Longitudes are typically reported in decimal degrees east, meaning coordinates in the Western Hemisphere are negative values.
* BCO-DMO will convert latitude and longitude values to conform with these conventions.&#x20;
* If the data provider prefers to provide latitude and longitude in another format, such as 0-360 degrees, we will provide both formats in separate columns in the dataset.

### Date and Time Conversions&#xD;

* Whenever possible, BCO-DMO publishes dates and times in UTC in ISO8601 format: YYYY-MM-DDThh:mm:ssZ (also represented as %Y-%m-%dT%H:%M:%SZ). In this format,
  * YYYY or %Y represents the 4-digit year
  * MM or %m represents the 2-digit month from 01 to 12
  * DD or %d represents the 2-digit day from 01 to 31
  * T denotes the start of the time string
  * hh or %H represents the zero-padded hour from 0 to 24
  * mm or %M represents the zero-padded minutes from 00 to 59
  * ss or %S represents the zero-padded seconds from 00 to 59
  * Z denotes UTC
* Dates and times provided to BCO-DMO in other formats or time zones will be converted to this convention.&#x20;
* Seconds are optional, and sometimes decimal fractions of a second may be provided.&#x20;
* In cases where the local time is valuable to understanding the data, both local and UTC columns will be provided in the dataset.

### Data File Names

Primary data files in .csv format are named according to the following format:

**(Dataset ID Number)\_(Version Number)**_**\_**_**(Short Description)**.csv&#x20;

For example, _897682\_v1\_particle\_speed.csv_ or _875210\_v1\_gp15\_iron\_ligands.csv_.&#x20;

### Characters Within Data Tables (values in rows):

To support data re-use in a wide variety of applications, we routinely adjust "non-standard" characters with replacements (for example μ -> u).

### "Tidy" Data Tables

In general, "tidy data" meet the following requirements:

* Each variable ("parameter") is a column.
* Each observation is a row.
* Every box or cell holds one single number or word.
* Values do not contain units. Rather, units should be specified in the supporting documentation for the dataset.
* There should be no extraneous information (footnotes, table titles, etc.).
* There is a single row of column headers (parameter names).
* Each type of observational unit forms a table.

BCO-DMO typically processes data tables to conform with the above requirements. Exceptions are made for non-tabular data, like gridded data types or matrices.&#x20;

### Metadata Entry and Formatting

BCO-DMO edits or enhances submitter-provided metadata to improve clarity, completeness, or otherwise add to the reusability of a dataset. Standard edits may include the following:

* Correction of spelling or grammatical errors
* Defining acronyms and abbreviations on first use
* Construction of a complete dataset title
* Addition of dataset keywords
* Mapping of submitter-provided instrument descriptions to standard instrument lists
* Mapping of submitter-provided parameter descriptions to standard parameter names
* Addition of complete paper citations, including DOIs whenever possible, for all cited references
* Defining a dataset's geospatial boundaries and temporal extent based on location and date-time values in the data file(s)
* Adding cruise information for vessels that are in R2R (e.g., dates, chief scientist, etc.)
* Assigning a data type to the dataset (e.g., experimental, cruise results, etc.)
* Assigning data types to all dataset parameters (e.g., string, float, integer, etc.)
* Designating formats for date and time parameters
