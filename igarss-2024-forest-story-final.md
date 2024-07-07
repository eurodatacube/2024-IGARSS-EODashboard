## Forests and Climate

Forests cover [31% of the global land area](https://www.fao.org/3/CA8753EN/CA8753EN.pdf) and host more than 75% of the world’s terrestrial [biodiversity](https://www.fao.org/publications/home/fao-flagship-publications/the-state-of-the-worlds-forests/2022/en), offering essential ecosystem services. 

Deforestation, forest degradation and other factors such as  rising temperatures, drier conditions and more frequent and severe fires have drastic impacts on forests with consequences on the carbon cycle and the energy balance. 

Globally,  an annual rate of deforestation of [10 million ha/year](https://www.fao.org/3/CA8753EN/CA8753EN.pdf) was estimated in the most recent five-year period (2015-2020). However, this rate is slowing down. At COP26, 100 countries endorsed the [Glasgow Leaders’s Declaration on Forests and Land Use](https://webarchive.nationalarchives.gov.uk/ukgwa/20230418175226/https://ukcop26.org/glasgow-leaders-declaration-on-forests-and-land-use/), which aims to halt and reverse forest loss and land degradation by 2030. 
 
Satellite Earth Observations play a crucial role in supporting this commitment by providing essential data on forest cover and land use changes, enabling governments to implement and track the progress of policies for forest loss and degradation.

Space agencies such as ESA, NASA and JAXA develop complementary missions carrying various instruments able to capture information about the state of global forests such as the covered area or the amount of biomass, as well serving  as a tool for conservation management, by enabling detections of changes (e.g. from logging or forest regrowth), or by informing on hazard risks such as wildfires.
<center>
<iframe width="649" height="360" src="https://www.youtube.com/embed/42u1E63BLkg?rel=0" frameborder="0" allow="encrypted-media" allowfullscreen></iframe>
</center>

## Role of EO

Several ESA, JAXA and NASA satellites such as the [Copernicus Sentinel missions](https://sentinels.copernicus.eu/web/sentinel), [ALOS-2](https://www.eorc.jaxa.jp/ALOS-2/en/about/palsar2.htm), [MODIS](https://modis.gsfc.nasa.gov/) or [GEDI](https://gedi.umd.edu/), equiped with optical, synthetic aperture radar (SAR) and LiDAR sensors can detect and map forest degradation, supporting conservation management, helping to track fires and to detect illegal logging. ESA's upcoming forest mission, [BIOMASS](https://earth.esa.int/eogateway/missions/biomass), is a P-band SAR satellite with the main objective to determine the global distribution of forest biomass. This satellite is expected to improve the estimates of carbon stocks and fluxes on land associated with land-use change, forest degradation and forest regrowth. 

Data delivered by these missions provides the essential information used in global forest products such as the global Biomass Essential Climate Variable (ECV) of ESA's [Climate Change Initiative](https://climate.esa.int/en/projects/biomass/) (CCI). This product counts with an annual estimate of global above-ground biomass at 100 m spatial resolution over five years based on ESA’s C-band (Sentinel-1 A and -B) and JAXA’s L-band SAR on board of ALOS-2 PALSAR-2 with additional information from Space borne LIDAR (such as NASA’s Global Ecosystem Dynamics Investigation Lidar GEDI). 

<center>
<iframe src="https://www.esa.int/content/view/embedjw/559869" width="640" height="360" frameborder="0"></iframe>

	*Above ground biomass 2020. ESA (Data source: CCI Biomass project)*
</center>

NASA’s GEDI mission has released several [novel data products](https://gedi.umd.edu/data/products/), such as a first near-global estimate of aboveground forest biomass and the carbon it stores. Such products are essential as they help fill key gaps in climate research, enabling new insights into how Earth’s forests are changing, what role they play in mitigating climate change, and the regional and global impacts of planting and cutting down trees. 

<center>
<video src="https://svs.gsfc.nasa.gov/vis/a010000/a013000/a013090/GEDI_beauty_waveform_youtube_1080.mp4" width="640">
</center>

*Animation of the Global Ecosystem Dynamics Investigation (GEDI) instrument, as installed on the ISS. Source: https://svs.gsfc.nasa.gov/13090.*

JAXA also offers global 25m resolution SAR mosaics and forest/non-forest maps, based on ALOS PALSAR, ALOS-2 PALSAR-2 and the JERS-1 SAR. In addition, “[JICA-JAXA Forest Early Warning System in the Tropics](https://www.eorc.jaxa.jp/jjfast/)" (JJ-FAST) is now operating for monitoring early deforestation in tropical forests globally collaboration with the Japan International Cooperation Agency (JICA) and JAXA. 

## Map Tour Example <!--{ as="eox-map" mode="tour" }-->

### <!--{ layers='[{"type":"Tile","properties":{"id":"Overlay labels"},"source":{"type":"XYZ","urls":["//s2maps-tiles.eu/wmts/1.0.0/overlay_base_bright_3857/default/g/{z}/{y}/{x}.jpg"]}},{"type":"Tile","properties":{"id":"PALSAR-2/PALSAR Forest/Non-Forest Map"},"source":{"type":"WMTS","urls":["https://ogcpreview1.restecmap.com/examind/api/WS/wmts/JAXA_WMTS_Preview?"],"layer":"FNF-PALSAR2-World-2020-Yearly","format":"image/png","matrixSet":"12d1db38-9354-4569-bbb4-efef0359fa54","tileGrid":{"resolutions":[156543.03392804097,78271.51696402048,39135.75848201024,19567.87924100512,9783.93962050256,4891.96981025128,2445.98490512564,1222.99245256282,611.49622628141,305.748113140705,152.8740565703525,76.43702828517625,38.21851414258813,19.109257071294063],"projection":"EPSG:3857","matrixIds":["156543d03392804097x-20,037,508d343x18,807,214d097","78271d51696402048x-20,037,508d343x18,807,214d097","39135d75848201024x-20,037,508d343x18,807,214d097","19567d87924100512x-20,037,508d343x18,807,214d097","9783d93962050256x-20,037,508d343x18,807,214d097","4891d96981025128x-20,037,508d343x18,807,214d097","2445d98490512564x-20,037,508d343x18,807,214d097","1222d99245256282x-20,037,508d343x18,807,214d097","611d49622628141x-20,037,508d343x18,807,214d097","305d748113140705x-20,037,508d343x18,807,214d097","152d8740565703525x-20,037,508d343x18,807,214d097","76d43702828517625x-20,037,508d343x18,807,214d097","38d21851414258813x-20,037,508d343x18,807,214d097","19d109257071294063x-20,037,508d343x18,807,214d097"],"origin":[-20037508.342789244,18807214.09674771]}}},{"type":"Tile","properties":{"id":"Terrain light"},"source":{"type":"XYZ","urls":["//s2maps-tiles.eu/wmts/1.0.0/terrain-light_3857/default/g/{z}/{y}/{x}.jpg"]}}]' zoom="2.4918530963296748" center=[0,38.65849000952366] animationOptions={duration:500}}-->
#### JAXA Forest Non-Forest Map

![](https://raw.githubusercontent.com/eurodatacube/eodash-assets/main/collections/FNF_Palsar/FNF_legend.png)

This map illustrates JAXA's Global PALSAR-2/PALSAR Forest/Non-Forest Map for 2020. It shows the worldwide forest distribution from year to year, and has a 25-meter resolution. Such interannual forest distribution maps provide essential information for forest monitoring activities, including climate change countermeasures. 
	
To explore the time series from 2017-2020 [see the dataset on EO Dashboard](https://www.eodashboard.org/explore?search=World%3A+Forest%2Fnon-forest+map+PALSAR2&x=5065036.83109&y=-2298331.0934&z=2.64386&poi=World-FNF).

## StacInfo example <!--{as="eox-stacinfo" for="https://eurodatacube.github.io/eodash-catalog/trilateral/FNF_Palsar/collection.json" featured='["description","providers","assets","links"]'  properties='["satellite","sensor","agency","extent"]' header='["title"]' tags='["tags"]' footer='["sci:citation"]' }-->

## Boreal forests

<center>
<img src="https://raw.githubusercontent.com/eurodatacube/eodash-assets/main/stories/forest_story/BorealForest.png" width=50%>
</center>

Boreal forests comprise [44% of Earth’s remaining intact forest landscapes](https://intactforests.org/shp/IFL_readme_2021.pdf) and stretch across Canada, Scandinavia, Russia, and China. According to the UN’s Intergovernmental Panel on Climate Change (IPCC), vast areas of the boreal forest could experience warming of up to 6 to 11 degrees Celsius by 2100, with the potential to hit a [tipping point](https://www.sciencedaily.com/releases/2015/08/150820144722.htm). 

Changes in the boreal forest vary accross latitudes. In the southern latitudes, scientists observe a decline in the tree cover, whereas at northern latitudes they observe transitions into tundra, which is a biome characterised by lower albedo, less vegetation and lower biomass. These shifts of the above-ground biomass in boreal forests (a key biophysical ecosystem variable describing all living biomass above the soil including stem, stump, branches, bark, seeds and foliage) can be measured by radar satellites at higher wavelenghts (L-band) such as JAXA's ALOS-PALSAR or the upcoming ESA mission ROSE-L. 

The shift to tundra along with the [more frequent wildfires](https://alaskabeacon.com/2023/03/03/extreme-wildfires-are-turning-worlds-largest-forest-ecosystem-from-carbon-sink-into-net-emitter/) may contribute to more carbon being released from organic soils in boreal forests than the ecosystems can absorb. Boreal forests may thus turn from being carbon sinks into [emitters][https://climate.nasa.gov/news/2905/boreal-forest-fires-could-release-deep-soil-carbon/]. In fact, in 2021 boreal fires emissions accounted for nearly one quarter of global carbon emissions, setting a record-high CO2 emissions from boreal fires.

## Map Tour Example 2 <!--{ as="eox-map" mode="tour" }-->
### <!--{ layers='[{"type":"Tile","properties":{"id":"Overlay labels"},"source":{"type":"XYZ","urls":["//s2maps-tiles.eu/wmts/1.0.0/overlay_base_bright_3857/default/g/{z}/{y}/{x}.jpg"]}},{"type":"Tile","properties":{"id":"N2_CO2_mean-2022-02-13T00:00:00Z"},"source":{"type":"XYZ","urls":["https://openveda.cloud/api/raster/cog/tiles/WebMercatorQuad/{z}/{x}/{y}?resampling_method=nearest&bidx=1&colormap_name=rdylbu_r&rescale=0.000408,0.000419&url=s3://veda-data-store/co2-mean/xco2_16day_mean._2022-02-13.tif"]}},{"type":"Tile","properties":{"id":"Terrain light"},"source":{"type":"XYZ","urls":["//s2maps-tiles.eu/wmts/1.0.0/terrain-light_3857/default/g/{z}/{y}/{x}.jpg"]}}]' zoom="2.4918530963296748" center=[-0.15625000000000316,-9.949613673872904] animationOptions={duration:500}}-->
#### Mean Carbon Dioxide from NASA's OCO-2
This map illustrates the global mean CO2 for 2022-02-13. To explore the full time series of this daily product, [go to dataset](https://www.eodashboard.org/explore?indicator=N2_CO2_mean&x=-3838671.80698&y=565580.50339&z=2.90689)

### <!--{ layers='[{"type":"Tile","properties":{"id":"Overlay labels"},"source":{"type":"XYZ","urls":["//s2maps-tiles.eu/wmts/1.0.0/overlay_base_bright_3857/default/g/{z}/{y}/{x}.jpg"]}},{"type":"Tile","properties":{"id":"CO_3_daily-2023-08-12"},"source":{"type":"TileWMS","urls":["https://services.sentinel-hub.com/ogc/wms/0635c213-17a1-48ee-aef7-9d1731695a54"],"params":{"layers":"AWS_VIS_CO_3DAILY_DATA","styles":"","format":"image/png","time":"2023-08-12"}}},{"type":"Tile","properties":{"id":"Terrain light"},"source":{"type":"XYZ","urls":["//s2maps-tiles.eu/wmts/1.0.0/terrain-light_3857/default/g/{z}/{y}/{x}.jpg"]}}]' zoom="2.4918530963296748" center=[-57.444473266601555,54.32992974677299] animationOptions={duration:500}}-->
#### Carbon Monoxide from ESA's Sentinel-5p TROPOMI
This map illustrates the CO total column which shows enhancements by strong sources such as wildfires. This map illustrates the Canadian wildfires in summer of 2023 (date: 2023-08-12). To explore the full time series [go to dataset](https://eodashboard.org/explore?indicator=N1_CO&x=-6394689.51293&y=7232890.3214&z=2.49185)

## Amazon rainforest

<center>
<img src="https://raw.githubusercontent.com/eurodatacube/eodash-assets/main/stories/forest_story/AmazonForest.png" width=50%>
</center>

Whether stemming from localised deforestation impacts or broader global climate shifts, scientific consensus asserts a future for the Amazon characterised by increased warmth and aridity. As a result, the Amazon rainforest is gradually losing its unique ability to ‘bounce back’ after disruptive occurrences, like droughts or other extreme events, leading to a downward spiral where rainforest could shift into a [savanna](https://www.nature.com/articles/s41558-022-01287-8) - which is less efficient than tropical forests at sequestering carbon dioxide from the atmosphere.

This map shows ESA Deforested Biomass for 2018 from CCI RECCAP-2. [Go to dataset](https://eodashboard.org/explore?indicator=RECCAP2_6&x=-6958864.24521&y=-464868.90214&z=4.94776). 
## Map Example <!--{as="eox-map" style="width: 100%; height: 500px;" layers='[{"type":"Tile","properties":{"id":"Overlay labels"},"source":{"type":"XYZ","urls":["//s2maps-tiles.eu/wmts/1.0.0/overlay_base_bright_3857/default/g/{z}/{y}/{x}.jpg"]}},{"type":"Tile","properties":{"id":"RECCAP2_6_deforested_biomass-2018"},"source":{"type":"XYZ","urls":["https://reccap2.api.dev.brockmann-consult.de/api/tiles/cop28~reccap2-9x108x139-0.0.1.zarr/deforested_biomass/{z}/{y}/{x}?crs=EPSG:3857&time=2018&vmin=0&vmax=5&cbar=YlOrRd"]}},{"type":"Tile","properties":{"id":"EOxCloudless 2021"},"source":{"type":"XYZ","urls":["//s2maps-tiles.eu/wmts/1.0.0/s2cloudless-2021_3857/default/g/{z}/{y}/{x}.jpg"]}}]' zoom="4.947763015049761" center=[-62.512541115854795,-4.172296030218746] }-->

However, there remains no definitive agreement on a tipping point leading to widespread rainforest depletion and the proliferation of savanna species (Cerrado) from the biome. Given the intricate interplay between regional land-use alterations and global climate shifts, scientists are working to gain more understanding about this potential tipping point for the Amazon rainforest. The threshold has been estimated to occur when deforestation reaches 20-25%. Currently, the Amazon has already undergone approximately 17% deforestation, which highlights the urgency of conservation efforts to prevent reaching an ecological tiping point.

