### Report Type

| Code  | Meaning                                            |
|-------|----------------------------------------------------|
| METAR | Periodic or routine report, generated once an hour or half hour. |
| SPECI | Special report issued when conditions have significantly changed. |


### Speed Unit

| Code | Meaning           |
|------|-------------------|
| KT   | Knots             |
| MPS  | Metres per second |
| KMH  | Kilometres per hour|


### Length Unit

| Code  | Meaning          |
|-------|------------------|
| Metre | Metre, standard unit |
| Foot  | Foot, used by FAA for RVR |
| Mile  | Mile, more formally statute mile, used by FAA |


### Wind Variable Direction

| Field    | Explanation                                      |
|----------|--------------------------------------------------|
| wvdLeft  | The left extreme of the wind direction in degrees.|
| wvdRight | The right extreme of the wind direction in degrees.|


### Wind Speed

| Field   | Explanation            |
|---------|------------------------|
| wsUnit  | Wind speed unit        |
| wsValue | Value of the wind speed in the unit. |


### Wind

| Field       | Explanation                                      |
|-------------|--------------------------------------------------|
| wDirection  | Mean true direction in degrees rounded off to the nearest 10 degrees from which the wind is blowing, when absent the direction is variable. |
| wSpeed      | Mean speed of the wind over the 10-minute period immediately preceding the observation. |
| wGust       | Maximum gust wind speed if relevant.             |
| wVariation  | Variable wind direction if relevant.             |


### Visibility Tendency

| Code      | Meaning                                            |
|-----------|----------------------------------------------------|
| Down      | Visibility is decreasing.                          |
| Up        | Visibility is increasing.                          |
| NoChange  | No significant change in visibility.               |


### Visibility Distance

| Field      | Explanation                                      |
|------------|--------------------------------------------------|
| vdUnit     | Distance unit                                    |
| vdValue    | Distance value in the unit.                       |
| vdFraction | Distance fraction in the unit, e.g., (1, 4) for a 1/4. |


### Runway Designator

| Field      | Explanation                                      |
|------------|--------------------------------------------------|
| RunwayDesignator | Runway designator, 2 digits possibly appended with L(eft), C(entral), or R(ight) for parallel runways. |


### Extreme RVR

| Code   | Meaning                                            |
|--------|----------------------------------------------------|
| Lower  | Indicates an extreme lower value of runway visual range. |
| Higher | Indicates an extreme higher value of runway visual range. |


### Runway Visual Range

| Field                   | Explanation                                      |
|-------------------------|--------------------------------------------------|
| rvrDesignator           | Runway designator.                               |
| rvrMeanVisibility       | Mean visibility in meters.                       |
| rvrOutsideMeasuringRange| Present only if the RVR values are outside the measuring range of the observing system. |
| rvrVisibilityTendency   | Visibility tendency.                             |


### Visibility

| Field            | Explanation                                      |
|------------------|--------------------------------------------------|
| vPrevailing      | Prevailing horizontal visibility in meters; 9999 indicates visibility over 10 km. |
| vLowest          | Lowest visibility if reported.                   |
| vLowestDirection | Direction of the lowest visibility.               |
| vRunways         | Visual range for each runway.                     |


### Weather Qualifier

| Code            | Meaning                                            |
|-----------------|----------------------------------------------------|
| LightWeather    | Light weather.                                     |
| HeavyWeather    | Heavy weather.                                     |
| InVicinityWeather| In vicinity, i.e., not on location but within 8000 m. |


### Weather Descriptor

| Code         | Meaning |
|--------------|---------|
| Shallow      |         |
| Patches      |         |
| Partial      |         |
| Drifting     |         |
| Blowing      |         |
| Showers      |         |
| Thunderstorm |         |
| Freezing     |         |


### Weather Phenomenon

| Code                | Meaning                                            |
|---------------------|----------------------------------------------------|
| Drizzle             |                                                    |
| Rain                |                                                    |
| Snow                |                                                    |
| SnowGrains          |                                                    |
| IceCrystals         |                                                    |
| IcePellets          |                                                    |
| Hail                |                                                    |
| SmallHail           |                                                    |
| UnknownPrecipitation|                                                    |
| Mist                | Visibility > 1000 m.                               |
| Fog                 | Visibility < 1000 m.                               |
| Smoke               |                                                    |
| VolcanicAsh         |                                                    |
| WidespreadDust      |                                                    |
| Sand                |                                                    |
| Haze                |                                                    |
| Spray               |                                                    |
| Dust                | Well-developed dust/sand whirls.                   |
| Squall              |                                                    |
| FunnelCloud         | Tornado, waterspout are always +FC, i.e., heavy FunnelCloud. |
| Sandstorm           |                                                    |
| DustStorm           |                                                    |


### Cloud Type

| Code            | Meaning           |
|-----------------|-------------------|
| Cumulonimbus    |                   |
| ToweringCumulus |                   |


### Cloud Amount Type

| Code      | Meaning                      |
|-----------|------------------------------|
| Few       | Few amount of clouds.        |
| Scattered | Scattered amount of clouds.  |
| Broken    | Broken amount of clouds.     |
| Overcast  | Overcast amount of clouds.   |


### Cloud Amount

| Field   | Explanation                                     |
|---------|-------------------------------------------------|
| caType  | Type of cloud amount.                           |
| caHeight| Height of cloud base in hundreds of feet.       |
| clType  | Type of clouds if relevant.                     |


### Vertical Visibility

| Field    | Explanation                                      |
|----------|--------------------------------------------------|
| vvExtent | Extent of vertical visibility in hundreds of feet above field elevation. |


### No Cloud Observed

| Code             | Meaning                               |
|------------------|---------------------------------------|
| NoCloudBelow1500 | No clouds observed below 1500 feet.    |
| NoCloudBelow3600 | No clouds observed below 3600 feet.    |
| SkyClear         | Sky clear; no clouds observed.          |


### Clouds

| Variant       | Explanation                                 |
|---------------|---------------------------------------------|
| CloudAmounts  | Cloud amount observations.                   |
| ObscuredSky   | Obscured sky observations.                   |
| NoneObserved  | No clouds observed conditions.               |


### Pressure Unit

| Code      | Meaning               |
|-----------|-----------------------|
| Hpa       | hPa (standard).       |
| InchesHg  | inches of mercury (US)|


### Pressure

| Field  | Explanation          |
|--------|----------------------|
| pUnit  | Pressure unit.       |
| pValue | Pressure value.      |


### Report Modifiers

| Field           | Explanation                                       |
|-----------------|---------------------------------------------------|
| reportCorrected | Whether the report was corrected.                 |
| reportAuto      | Whether the report contains fully automated observations without human intervention. |
| reportMissed    | Whether the report corresponds to a missing report.|


### Aerodrome Report

| Field             | Explanation                                        |
|-------------------|----------------------------------------------------|
| reportType        | Type of the report.                                |
| reportModifiers   | Modifiers (cor, auto, nil).                        |
| reportStation     | ICAO code for the observing station (an aerodrome).|
| reportDate        | When the observation was made.                     |
| reportWind        | Wind related observations.                         |
| reportVisibility  | Visibility related observations.                   |
| reportWeather     | Weather related observations.                      |
| reportClouds      | Clouds related observations.                       |
| reportTemperature | Temperature rounded to nearest whole degree Celsius.|
| reportDewPoint    | Dew point rounded to nearest whole degree Celsius. |
| reportPressure    | Mean sea level pressure (“QNH”).                   |
| reportRemarks     | Report components and miscellaneous abbreviations.|


### Weather Descriptor

| Code | Meaning      |
|------|--------------|
| MI   | Shallow      |
| BC   | Patches      |
| PR   | Partial      |
| DR   | Drifting     |
| BL   | Blowing      |
| SH   | Showers      |
| TS   | Thunderstorm |
| FZ   | Freezing     |


### Weather Phenomenon 

| Code | Meaning             |
|------|---------------------|
| DZ   | Drizzle             |
| RA   | Rain                |
| SN   | Snow                |
| SG   | SnowGrains          |
| IC   | IceCrystals         |
| PL   | IcePellets          |
| GR   | Hail                |
| GS   | SmallHail           |
| UP   | UnknownPrecipitation|
| BR   | Mist                |
| FG   | Fog                 |
| FU   | Smoke               |
| VA   | VolcanicAsh         |
| DU   | WidespreadDust      |
| SA   | Sand                |
| HZ   | Haze                |
| PY   | Spray               |
| PO   | Dust                |
| SQ   | Squall              |
| FC   | FunnelCloud         |
| SS   | Sandstorm           |
| DS   | DustStorm           |


### Clarity Sky

| Code | Meaning                          |
|------|----------------------------------|
| NSC  | NoneObserved NoCloudBelow1500    |
| NCD  | NoneObserved SkyClear            |
| CLR  | NoneObserved NoCloudBelow3600    |
| SKC  | NoneObserved SkyClear            |


