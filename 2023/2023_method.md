**Carbon Footprint of ImageEngine**

This document explains the model used to arrive at an estimated carbon footprint of running ImageEngine.

The model is based on the “Sustainable Web Design” (SWD) model (https://sustainablewebdesign.org/calculating-digital-emissions/) and uses the recommended default values if the actual value is unknown.

For some components the actual electricity use and data transfer is known, while others (the majority) the estimate is based on traffic served by ImageEngine (after optimization) during a representative period. From the SWD model, it is assumed that  0.81 kWh/GB is required.

The estimated yearly electricity consumption is ~ 720000 kWh.

When the carbon intensity is not known, the default 442 g/kWh is used. Data from AWS and other public data is used to define the carbon intensity of each data center location.

| Data center | Traffic share	| carbon intensity (co2e/GB) | Relative carbon intensity |Comment|
| --- | --- | --- | --- | --- | --- |
|DC 1	|44.19%	|41.1|	18.2| >95% green|
|DC 2	|14.82%	|41.1	|6.1| >95% green|
|DC 3	|13.81%	|442	|61.1|
|DC 4	|10.20%	|41.1	|4.2| >95% green|
|DC 5	|7.29%	|442	|32.2|
|DC 6	|7.26%	|41.1	|3.0| >95% green|
|Other|2.44%|442|10.8|
|Across all locations| | |135.5|

720000 kWh x 135.5 g Co2e/kWh = ~ 98000000 g = 98 MT Co2e per year.

The carbon footprint is compensated by supporting VCS and Gold Standard verified projects listed here:

* https://www.carbonfootprint.com/carbonoffsetprojects.html
* https://treesforall.nl/en/projects/#current-project 
