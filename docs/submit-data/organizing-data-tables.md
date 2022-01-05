---
description: Organize data within a spreadsheet for inclusion in the BCO-DMO data system.
---

# Organizing Data Tables

This page makes some suggestions on how to organize data within a spreadsheet for inclusion in the BCO-DMO data system. We will accept your data in whatever format you provide, but these formatting suggestions will help us understand and process your data.&#x20;

BCO-DMO wants to make it as easy as possible for researchers to submit their data so others can use them for further studies. There are ways of setting up a spreadsheet and entering the data that can make it significantly easier for us to process and publish. If possible, please try to follow as many of these guidelines as you can.

## What information should a data table contain?

### Position (location) data

Whenever possible, data should be accompanied by position information so others can put the data in a geographical context and compare them to other data. Ideally, every sample will have a corresponding location from which it was collected.&#x20;

It is most convenient if the latitude and longitude values are submitted as **decimal degrees with south latitude and west longitude entered as negative numbers.** These should be provided in separate columns. If you prefer to provide position information as degrees and decimal minutes or degrees, minutes, seconds, we can accept that as well. Please make separate columns for degrees, minutes, and seconds. Please don’t include the degree, minute, and seconds symbols within the data columns.

### Dates and times

Entering date and time information is as important as entering the position information. While arguments still persist as to how date and time should be displayed, consistency is the overriding rule of thumb. If you have a choice, it would be best to provide date and time as UTC (some refer to this as GMT) \[See Note 1]. The values can be entered in separate columns, as year, month, day, and time, or as a single long entry like mm-dd-yyyy hh:mm:ss where mm is the month (January is 01), dd is the day of the month, yyyy is the four digit year, hh is the hour (13 is 1:00pm), mm is minutes, and ss is seconds. The order isn’t important, just be consistent. If you have time zone (or time difference) information, please provide that too, either as a number or abbreviation (e.g. time zone of -8 is UTC - 8 for Pacific Standard Time \[PST] and time zone of -7 is UTC -7 for Pacific Daylight Time \[PDT].) Some like to provide date and time information as a single value, starting at some arbitrary point in time or at the beginning of the year, so that 1.5 would represent January 1 at 12:00pm. Others start counting with 0, so that 1.5 is January 2 at 1200. We can deal with almost any format, but as mentioned above, please be consistent and describe the format you are using.  If you provide date and time as a single value, please don’t forget to include the year information in a separate column or in the header or in a separate document.

* location (latitude longitude) of samples or sampling sites
*   _Notes:_\
    &#x20;1\. Coordinated Universal Time (**UTC**) is used as the official world reference for time. Coordinated Universal Time replaced the use of Greenwich Mean Time (GMT) in 1972. You will sometimes see time zones represented as UTC - 5h or GMT - 5h. In this example the (-5h) refers to that time zone being five hours behind UTC. UTC+5h or GMT +5h would refer to that time zone being five hours ahead of UTC or GMT.

    UTC and GMT typically displays time using a twenty four hour clock, and is based on the 0° longitude meridian, referred to as the Greenwich meridian in Greenwich, England.

    Coordinated Universal Time is based on cesium-beam atomic clocks, with leap seconds added to match earth-motion time, whereas Greenwich Mean Time is based on the Earth's rotation and celestial measurements. Coordinated Universal Time is also known as Zulu Time or Z time.

**Date/time format**: We will serve date and time in GMT, local time or both GMT and local time. However, if only one time is provided, we would prefer to see UTC (GMT) time.  If local time is provided, you must be clear about a) is it local ship’s time or local time based on the longitude of the measurement, and b) provide the time zone/time difference from GMT. If local time is provided, we will attempt to add UTC time ourselves.  Time zone information can be provided in the metadata or as a separate column, or it can be inferred by looking at the longitude value. Just note that local ship's time is not necessarily the same as the local time based on the longitude value. (Things can get complicated sometimes even when we don't want them to.)

## The lay-out of a data table&#x20;

To set up a data table for reuse, the basic rule of thumb is that **a file should be able to be converted to a .csv file without loosing information.**



### **Header row**

### Text format and color

We cannot directly portray data that is denoted by text formatting or cell color.  For example, different colored text might be used for types of gear. This cannot be displayed in the served data. Please consider this when designing your spreadsheet and include such information in a separate data or comment column.

Merged cells

### Blanks, no data value, below detection limit or 0's&#x20;

There is a difference between a blank cell and a cell with a value of zero (0). A blank cell denotes a missing or undefined value, whereas a value of zero (0) means the value was measured as zero (0). We usually change blank entries to the value of “nd” meaning “no data”. (The quotes are not included.)

### Ranges

It is difficult to serve **ranges** of values within a single cell. If there are ranges, it is better to have two separate columns, one for each end of the range, such as depth\_min and depth\_max.  This is because the ranges are interpreted as text and therefore cannot be plotted or easily manipulated.

### **Units**&#x20;

should not appear in a data cell, such as 0.5 knots. The cell should contain just the value, 0.5. The units can appear as a separate line underneath the column headers, or in a separate document, or as part of the column name.

### Comments

**Comments** should appear in a separate column and not be part of data values. For example,

&#x20;  350 m, towed between Mound 11 and 12

as the value for "Wire Out" is difficult to serve as a number. The units, “m”, go one place (see (1) above), and the comment goes into another column.

## Statistics



## Figures and supplemental files (non-tabular data)

Usually graphs are not included in the served data. It is easier for us to deal with a spreadsheet that does not contain graphs.&#x20;

If you do want to make graphs, or other images, available to others that is fine. These can be served as "data" too, usually as a separate dataset. We can accept images (and movies) in just about any common format, such as gif, tif, jpeg, mov, etc. Long (or short) descriptions are best provided separately, as part of the descriptions of how the data were collected or processed.

## Use examples of well formated tables
