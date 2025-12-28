## Status Report
**Data generated**: Around 24th Dec 2025

**Station fixing report (from the code output):**
* 0 total errors
* 0 total warnings
* 0 unique error stations
* 0 unique warning stations
* 0 ignored buses

**GTFS review report** (from [transport.data.gouv.fr](https://transport.data.gouv.fr/))
https://transport.data.gouv.fr/validation/536872?token=5293160a-2881-426a-b912-86c54ffe063f

## Users
Coming soon :)
(Please open an issue/PR to add your project here using this data)

## Known issues
* Timings for the buses are not accurate (source for start time is not available).
* Since bus timetable isn't available, an approximation is used to generate the trips.
* Assumes that:
  * Each route (up & down separate) has only 1 bus.
  * Trips start at 9 AM and no trips take place after 9 PM
* This is definitely incorrect but source data does not provide any better info.