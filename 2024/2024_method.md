**Carbon Footprint of ImageEngine**

This document explains the model used to arrive at an estimated carbon footprint of running ImageEngine.

The model is based on the “Sustainable Web Design” ([SWD](https://sustainablewebdesign.org/calculating-digital-emissions/)) model and uses the recommended default values if the actual value is unknown.

For some components the actual electricity use and data transfer is known, while for others (the majority) the estimate is based on traffic served by ImageEngine (after optimization) during a representative period. 

The estimate for 2024 is then based on historical data, but expected changes in traffic patterns and known changes to the infrastructure are considered in the estimate.

From the SWD model, it is assumed that  0.81 kWh/GB is required. This number is adjusted for ImageEngine's for the share of traffic where electricity consumption is known.

Compared to 2023, both data traffic and electricity use has increased. 

The yearly electricity consumption is estimated to ~ 750000 kWh across all data-centres.

When the carbon intensity is not known, the default 442 g/kWh is used. Data from AWS and other public data is used to define the carbon intensity of each data center location. 

AWS reports that all data centres where ImageEngine has presence [ran on 100% renewable energy in 2022](https://sustainability.aboutamazon.com/products-services/the-cloud?energyType=true). Our estimate assumes that this has not changed. 

Still, we have increased the carbon intensity of green energy from 20g Co2e/Kwh in 2023 to 50g Co2e/Kwh in 2024.

Shifting global traffic patterns among ImageEngine customers, AWS progress towards their goal of 100% renewable energy by 2025 along with our own efforts contributes to a carbon intensity of 57g CO2e/Kwh. A significant improvement since last period.

750000 kWh x 57 g Co2e/kWh = ~ 42750000 g = 43 MT Co2e per year.

The unavoidable carbon footprint of 43 MT Co2e is offset by purchasing verified offsets from [Terrapass](https://terrapass.com/product/terrapass-climate-green-e-offsets/). 

Please find the [evidence of the 2024 carbon offset purchase here](voucher-VMQYPR3M-tpus-966034.pdf).

You'll also always find [updated references directly in responses from ImageEngine itself, thanks to the carbon.txt effort](https://support.imageengine.io/hc/en-us/articles/16495514108813-carbon-txt-What-is-it-and-Why-is-it-Important) supported by ImageEngine.


