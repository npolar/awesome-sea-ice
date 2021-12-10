# Awesome Sea Ice

Curated list of publicly available sea ice related datasets. There is no intention to provide a comprehensive list, instead it is a list of frequently used resources.

## Sea ice concentration (SIC)
* [NSIDC, SIC climate data record](https://nsidc.org/data/G02202/versions/3): 25km, both poles, daily/monthly.
* [OSI-SAF SIC](https://osi-saf.eumetsat.int/products/sea-ice-products): 10km, both poles, daily/monthly.
* [MET Norway](https://cryo.met.no/): Operational ice charts. 40m to 10km varying resolution, working days only, PDFs and images.
* [ASI-SIC](https://seaice.uni-bremen.de/sea-ice-concentration/amsre-amsr2/): Daily Arctic and Antarctic SIC maps in TIF, HDF and NetCDF formats. 6.250 and 3.125km spatial resolution.

## Sea ice extent (SIE)
* [MASIE](https://nsidc.org/data/G02186/versions/1): 1km and 4km sea ice extent, North and South poles[^1].
* [Arctic Sea Ice Frequency](https://data.npolar.no/dataset/a89b2682-e1f8-44b5-ab73-e6ba65f3a7a7): 25km, 30 years occurence frequencies based on NSIDC SIC climate data records.

---
Pull requests with additions of mature datasets with persistent address/DOI are welcome.

---

[^1]: Information received through email correspondance with National Snow & Ice Data Center (nsidc), Dec 9, 2021: It (MASIE sea ice product) is based on the IMS product from the US National Ice Center. The IMS product relies on analysts integrating data from a variety of sources (derived ice charts, modeled ice conditions, and surface observations, as well as visible, passive and active microwave satellite resources) and using their knowledge and experience to create the best representation of sea ice cover. So, analysts seek to depict (they use drawing tools, imagery, in situ and satellite observations) ice edges as they exist in reality as close to a 1 km resolution as possible. I should note that originally, in earlier years, the analysis was carried out at 4 km resolution and a 4 km cell was considered ice covered if the analyst judged it to have more then 40% ice coverage. Regarding your question about which sea ice product is appropriate for your work, I reached out to two of our scientists. In short, the the most appropriate product depends on how you are doing your analysis and exactly what questions you are trying to answer. Based on the information you provided, they had the following comments: Of the products that we archive, MASIE, is probably the best to use. The note in the user guide about how it is not appropriate to compare recent MASIE values with ones that are more than a few weeks old, it not a hard and fast rule. It is mainly there to dissuade users from using MASIE to draw conclusions about climatological forcing. So, for the type of research you mentioned it is ok to use MASIE when comparing 2 months from 2 recent years. You mentioned the operational sea ice charts from Norweigan meteorological services and both scientists recommended those, as they are probably the most carefully drawn and best of the operational service products for the area you are interested in. Finally, one other source of data could be SAR data, but this would require more analysis and interpretation than the other 2 products mentioned above. But if this is of interest then PolarView is a portal which is good for quickly checking out this type of imagery: https://www.polarview.aq/arctic
