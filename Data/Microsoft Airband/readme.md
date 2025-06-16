# Microsoft Airband Initiative
The data for this analysis is from multiple sources, including the American Community Survey and the Federal Communications Commission (FCC).

## American Community Survey
The American Community Survey (ACS) ***S2801: Types of Computers and Internet Subscriptions*** table provides data on computer and internet access within households. Specifically, it details the types of computers and internet subscriptions present in households, according to Census Bureau data. This includes information on whether households have desktop or laptop computers, smartphones, tablets, or other types of computers, as well as details on their internet subscriptions, such as dial-up, broadband (including cable, fiber optic, or DSL), or cellular data plans. This data is segmented to the Census Tract level for all of the United States. Data is available from 2017 to 2023.

**Citation**<br>
* U.S. Census Bureau. (n.d.). Types of Computers and Internet Subscriptions. American Community Survey, ACS 5-Year Estimates Subject Tables, Table S2801. Retrieved June 16, 2025, from https://data.census.gov/table/ACSST5Y2023.S2801?q=broadband+Internet&g=010XX00US$1400000.

Here's a more detailed breakdown:
**Types of Computers:**
* Desktop or laptop: This includes traditional computers, such as desktops and laptops.
* Smartphone: This refers to mobile phones with advanced computing capabilities.
Tablet or other portable wireless computer: This category encompasses devices such as iPads and different tablets.
* Other computer: This may include specialized or less common types of computers.
* No computer: Households that do not possess any of the listed computer types. 

**Internet Subscriptions:**
* Dial-up: An older type of internet connection that uses a telephone line.
* Broadband: A high-speed internet connection, including cable, fiber optic, or DSL.
* Cellular data plan: Internet access via a mobile phone network.
* Broadband such as cable, fiber optic, or DSL: This specifies the types of broadband connections.

## Federal Communications Commission (FCC) Broadband Data Collection
Fixed Broadband Availability Data
Each file contains records of the locations for which any service provider reported fixed broadband availability as of the selected date, state, and technology. The Location IDs match those in the Broadband Serviceable Location Fabric. The file includes, for each location, the service availability data reported by the provider, as well as the census block and H3 resolution-8 hexagon within which the area falls. For information on how filers report fixed broadband availability data, see the Data Specifications for the Biannual Submissions of BDC Subscription, Availability, and Supporting Data at [FCC Broadband Data Collection Data Specifications for Biannual Submission of Subscription, Availability, and Supporting Data](https://us-fcc.box.com/v/bdc-availability-spec).
The files are available for download in Comma Separated Value (CSV) format.
Files are available by state, technology, and data as of the specified date in a zip archive with the following file naming structure:
* bdc_{State FIPS}_{Technology}_fixed_broadband_{Data As-of Date}_{Revision Date}.zip

**Citation**<br>
* While not required, when using in your own work content, data, documentation, code, and related materials from fcc.gov or broadbandmap.fcc.gov, we ask that you provide proper attribution of the data. 
  * Source data: FCC Broadband Funding Map
  * Map layer based on FCC BFM
