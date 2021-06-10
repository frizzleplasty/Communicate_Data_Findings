# Flight Data Exploration
## by Blake Osborn


## Dataset

> There are 521,194 records in the data set with 20 descriptive columns (21 after adding PeriodOfDay).  I've eliminated columns that concern flight arrival because I'm gong to focus on flight departures.

There are five columns that describe why flights were delayed
- **CarrierDelay:** Caused by the air carrier
- **WeatherDelay:** Caused by inclement weather
- **NASDelay:** Caused by the NAS (National Airspace System)
- **SecurityDelay:** Caused by evacuation of a terminal or concourse, re-boarding of aircraft because of security breach, inoperative screening equipment and/or long lines in excess of 29 minutes at screening areas
- **LateAircraftDelay:** Caused by a delay in the arrival from an aircraft from another airport

## Summary of Findings

> I set out to explore departure data in this data set.  After analyzing the types of delays, I determined that each type of delay essentially effected all air carriers the same.  Some air carriers had instances on longer delays than other carries, but the average for all carriers was about the same.

> I also looked at how time of year and time of day effected delays.  I theorized that most delays would happen during the winter months because Chicago can get severe snowstorms in the winter and that's what I saw in the data.  However, there were also spikes during the peak summer months as well.


## Key Insights for Presentation

> Looking at the distribution of flight delay lengths, delay lengths definitely trend towards the short end of the spectrum.  However, we do see some extremely long delays that happen less often.

> One surprising stat I found is that the three carriers with the least total minutes in delays had the highest percentage of flights delayed.

> Overall, the mean delay length was approximately the same for all air carriers. However, some of the carriers had more extreme delay lengths than the other carriers.
