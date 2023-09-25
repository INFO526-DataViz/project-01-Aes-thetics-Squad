# Data
-   **Tornado's Dataset**: The data-set contains information about tornadoes in the United States. It has 69683 rows and 27 columns. This dataset was taken from the Storm Prediction Center of NOAA. The period of the data ranges from 1950 to 2022.

# Codebook for [chosen] Dataset

## Variable Names and Descriptions:

|variable     |description  |
|:------------|:------------|
|om           |Tornado number. Effectively an ID for this tornado in this year.|
|yr           |Year, 1950-2022. |
|mo           |Month, 1-12.|
|dy           |Day of the month, 1-31. |
|date         |Date. |
|time         |Time. |
|tz           |[Canonical tz database timezone](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones).|
|datetime_utc |Date and time normalized to UTC. |
|st           |Two-letter postal abbreviation for the state (DC = Washington, DC; PR = Puerto Rico; VI = Virgin Islands). |
|stf          |State FIPS (Federal Information Processing Standards) number. |
|mag          |Magnitude on the F scale (EF beginning in 2007). Some of these values are estimated (see fc). |
|inj          |Number of injuries. When summing for state totals, use sn == 1 (see below). |
|fat          |Number of fatalities. When summing for state totals, use sn == 1 (see below). |
|loss         |Estimated property loss information in dollars. Prior to 1996, values were grouped into ranges. The reported number for such years is the maximum of its range. |
|slat         |Starting latitude in decimal degrees. |
|slon         |Starting longitude in decimal degrees. |
|elat         |Ending latitude in decimal degrees. |
|elon         |Ending longitude in decimal degrees. |
|len          |Length in miles. |
|wid          |Width in yards. |
|ns           |Number of states affected by this tornado. 1, 2, or 3. |
|sn           |State number for this row. 1 means the row contains the entire track information for this state, 0 means there is at least one more entry for this state for this tornado (om + yr). |
|f1           |FIPS code for the 1st county. |
|f2           |FIPS code for the 2nd county. |
|f3           |FIPS code for the 3rd county. |
|f4           |FIPS code for the 4th county. |
|fc           |Was the mag column estimated? |

## Data Types:

|variable     |class     |
|:------------|:---------|
|om           |integer   |
|yr           |integer   |
|mo           |integer   |
|dy           |integer   |
|date         |date      |
|time         |time      |
|tz           |character |
|datetime_utc |datetime  |
|st           |character |
|stf          |integer   |
|mag          |integer   |
|inj          |integer   |
|fat          |integer   |
|loss         |double    |
|slat         |double    |
|slon         |double    |
|elat         |double    |
|elon         |double    |
|len          |double    |
|wid          |double    |
|ns           |integer   |
|sn           |integer   |
|f1           |integer   |
|f2           |integer   |
|f3           |integer   |
|f4           |integer   |
|fc           |logical   |



