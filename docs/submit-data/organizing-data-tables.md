---
description: Organize data within a spreadsheet for inclusion in the BCO-DMO data system.
---

# Organizing Data Tables

This page offers some suggestions on how to organize data within a spreadsheet for inclusion in the BCO-DMO data system. We will accept your data in whatever form and format you provide, but we may make requests related to how data tables are structured so data are compliant with our system and with FAIR data principles.&#x20;

BCO-DMO wants to make it as easy as possible for researchers to submit their data so others can use them for further studies. There are ways of setting up a spreadsheet and entering the data that can make it significantly easier for us to process and publish. If possible, please try to follow as many of these guidelines as you can.

## Required data

### Position (location) data

BCO-DMO serves latitude and longitude data as decimal degrees. North latitude and east longitude are represented by positive values, and south latitude and west longitude are represented by negative values. We will convert any latitude and longitude format to decimal degrees.

**Quick guide for submitters**

* Use constant latitude and longitude formats
* Do not use degree, minute, or second symbols in cell values

****

**Background**

Whenever possible, data should be accompanied by position information so that others can put the data in a geographical context and compare them to other data. Position information can be detailed at the dataset level (referred to as the geospatial extent of a dataset), and at the observation level (per each row) within a data table. The geospatial extent of a dataset is derived from observation level lat/long details.&#x20;



### Dates and times

BCO-DMO serves date times in YYYY-MM-DD HH:SS format, and in both UTC and local time when possible. We will convert any other provided format into YYYY-MM-DD HH:SS, and will add UTC date time columns where needed.

**Quick guide for submitters**

* Use consistent formats when representing dates, times, and date times
* Include the time zone of each time related column of your data table in the column header or in your parameter metadata

****

**Background**

Entering date and time information is as important as entering the position information. While arguments still persist as to how date and time should be displayed, consistency is the overriding rule of thumb. If you have a choice, it would be best to provide date and time as UTC (some refer to this as GMT) \[See Note 1].&#x20;

The values can be entered in separate columns, as year, month, day, and time, or as a single long entry like mm-dd-yyyy hh:mm:ss where mm is the month (January is 01), dd is the day of the month, yyyy is the four digit year, hh is the hour (13 is 1:00pm), mm is minutes, and ss is seconds. The order isn’t important, just be consistent. If you have time zone (or time difference) information, please provide that too, either as a number or abbreviation (e.g. time zone of -8 is UTC - 8 for Pacific Standard Time \[PST] and time zone of -7 is UTC -7 for Pacific Daylight Time \[PDT].) Some like to provide date and time information as a single value, starting at some arbitrary point in time or at the beginning of the year, so that 1.5 would represent January 1 at 12:00pm. Others start counting with 0, so that 1.5 is January 2 at 1200. We can manage almost any format, but as mentioned above, please be consistent and describe the format you are using.  If you provide date and time as a single value, please don’t forget to include the year information in a separate column or in the header or in a separate document.

If local time is provided, you must be clear in your parameter metadata about a) is it local ship’s time or local time based on the longitude of the measurement, and b) provide the time zone. If local time is provided, we will add a UTC column to the data table(s). Time zone information can be provided in the metadata or as a separate column, within the parameter documentation you provide with your data table(s), or it can be inferred by looking at the longitude value. Note that local ship's time is not necessarily the same as the local time based on the longitude value.. &#x20;

__

**Additional Details about UTC and GMT**

Coordinated Universal Time (**UTC**) is used as the official world reference for time.  Coordinated Universal Time replaced the use of Greenwich Mean Time (GMT) in 1972. You will sometimes see time zones represented as UTC - 5h or GMT - 5h. In this example the (-5h) refers to that time zone being five hours behind UTC. UTC+5h or GMT +5h would refer to that time zone being five hours ahead of UTC or GMT.

UTC and GMT typically displays time using a twenty four hour clock, and is based on the 0° longitude meridian, referred to as the Greenwich meridian in Greenwich, England.

Coordinated Universal Time is based on cesium-beam atomic clocks, with leap seconds added to match earth-motion time, whereas Greenwich Mean Time is based on the Earth's rotation and celestial measurements. Coordinated Universal Time is also known as Zulu Time or Z time.



****

## The structure or layout of a data table&#x20;

To help ensure your data table is formatted in a way that can be reused across platforms, a basic rule of thumb is that a spreadsheet file (e.g., an Excel file) should be able to be converted to a .csv file without loosing information. CSV exports from Excel save only the text and values as they are displayed in cells of the active worksheet. Formatting, graphics, comments, and other worksheet contents are lost.

**Quick guide for submitters**

* Each spreadsheet should only contain one table
* Each row in the table should represent a single and unique observation&#x20;
* Each column in the table should represent a single parameter (i.e., a variable or measurement) and should have a decipherable column header
* Do not rely on colors or other visual formatting techniques in your Excel files



### **Column headers**

The header row is the first row of a data table and it contains the column headers of a dataset. BCO-DMO does not currently support row headers.

**Quick guide for submitters**&#x20;

* Create decipherable and unique column headers in the first row of your dataset



### Merged cells

Merged cells are data table cells that contain more than one datum. Each cell should only represent a single observation of an individual parameter (with date time as an exception), so BCO-DMO will split merged cells across multiple columns if any exist in a dataset.

**Quick guide for submitters**

* Each cell in a dataset should contain a single observation of an individual parameter

### Blanks, missing data, below detection limit or 0's&#x20;

Blank cells and zeros (0) hold different meanings within a dataset. Blank cells can denote missing or undefined values, wheras zeros (0) denote that a value of zero (0) had been measured.&#x20;

Missing data may also be represented by NaNs, NAs, 99999s, or other data flags.

BCO-DMO will change any values that represent "no data" to "nd" (minus the quotation marks). This will allow all "no data" cells in a data table to appear as blanks in the final data product we serve.&#x20;

**Quick guide for submitters**

* Do not use zeros (0) to indicate missing data points in tables
* Indicate the explicit meanings of any data flags in the parameter details of your dataset metadata .rtf

### Ranges

It is difficult to serve ranges of values within a single cell. If there are ranges, it is better to have two separate columns, one for each end of the range, such as depth\_min and depth\_max. This is because the ranges are interpreted as text and therefore cannot be plotted or easily manipulated. BCO-DMO will split merged cells across multiple columns if any exist in a dataset - this includes ranges.&#x20;

### **Units**&#x20;

Units should not appear in a data cell, (e.g., if "0.5 knots" appeared in a cell value). The cell should contain only the value, 0.5. Units can appear as a separate line underneath the column headers, or in a separate document (such as in the parameter details you provide to BCO-DMO), and/or as part of the column name.

**Quick guide for submitters**

* Include units in the parameter details you provide to BCO-DMO
* Do not include units within cell values

### Comments

Comments **** should appear in a separate column and not be part of data values. For example, if the following cell value existed in a column titled, "Wire\_Out," this would be impossible to serve as a numeric value and difficult to reuse for future analysis.

&#x20;                                          "350 m, towed between Mound 11 and 12"

To improve this, 350 should be in a column called "Wire\_Out\_Depth," and "towed between Mound 11 and 12 should be in a separate column called, "Wire\_Out\_Comment." The unit, m, should either be included in the column name or detailed in the information about parameters you provide to BCO-DMO.&#x20;

**Quick guide for submitters**

* Create comment columns for any observation-level comments

## Statistics

"Statistics" and "data" are sometimes used interchangeably. However, within the context of research data, statistics are summaries or calculated interpretations of raw data.&#x20;

Where possible, BCO-DMO serves the primary measurements statistics are performed on, and statistical tables can be added as supplemental files to these primary datasets.

## Figures and supplemental files (non-tabular data)

BCO-DMO can help you make graphs and images, available to others. There are different strategies we can use, depending on how your data tables and supplemental files are interrelated. These can be served as "data" too, usually as a separate dataset. We can accept images (and movies) in just about any common format, such as gif, tif, jpeg, mov, etc. Long (or short) descriptions are best provided separately, as part of the descriptions of how the data were collected or processed.

## Finding examples of well formatted tables

If you would like to see examples of well formatted data tables, search for dataset types similar to yours within [BCO-DMO's dataset search](https://www.bco-dmo.org/search/dataset).
