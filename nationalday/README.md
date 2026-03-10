# National Day

National Day recipe for TRMNL - data from https://nationaldaycalendar.com

![national-day-plugin](./nationalday_preview_full.jpg)

## Intro
This recipe displays today's National Days as listed on National Day Calendar website. Data is supplied in our GitHub repo to normalize and prevent changes to data format breaking displays.

Day changes happen at Midnight UTC time.

## Data Source and Self-Implementation
if you want to implement this yourself (vs using the recipie at https://usetrmnl.com/plugins )

Set your strategy to POLLING
the Polling URL to: https://raw.githubusercontent.com/jvivona/tidbyt-data/refs/heads/main/nationalday/nationalday.json
paste the appropriate markup code from the html files in this folder
Set your Refresh Rate to 4x daily (just to cover midnight change overs)
