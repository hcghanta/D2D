# Data Entry Analysis

## 1. Problems in Data Set

* Blank values in temperature, density, colony diameter.
* Excel files cannot be compared over Data field as there are no common dates. 
* Averages of Cuni and Chippo can either be moved to the last row or can be included in a new sheet.
* Max depth and max secchi can cause disturbance in value comparision between excel files.
* Depth specified as z in Pond excel sheet.
* Since various observations are made in a single day, time field can be included for easy understanding.
* Zoom-temp and zoop-temp-main contain same fields so can be clubbed together.
* Temperature measurement is not specified. Assumed to be degree Celsius.

## 2. New table format for future data collections
Pond

| Date     | Time | Depth | Density | Temperature | Diameter | Species |
|----------|------|-------|---------|:-----------:|----------|---------|
| 6/5/2010 | 0200 | 0.5   | 76      | 15.2        | 3.22     | cuni    |
| 6/5/2010 | 0100 | 0.5   | 70      | 15.2        | 3.46     | chippo  |

ZoomTemp

| Date     | Time | Depth | Cuni #/L | Cuni ColonySize | Chippo #/L | Chippo ColonySize | Chla | Temperature |
|----------|------|-------|----------|:---------------:|------------|-------------------|------|-------------|
| 6/7/2011 | 0200 | 0.5   | 87       | 2.4             | 49         | 2.8               | 3.2  | 18.2        |
| 6/9/2011 | 0100 | 0.5   | 86       | 2.33            | 46         | 2.79              | 3.7  | 17          |

* None can be used in place of blank values
* Max depth and max secchi can be moved to a new sheet.
* Rename z to Depth in Pond data set.
* Add time column
