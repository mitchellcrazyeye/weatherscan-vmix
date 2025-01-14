## This is a basic list of text products that will be produced as a result of each run.

### The idea is that a script will feed data into a ChatGPT template and ChatGPT will spit out a cleaned up response. This result will then be fed into an ElevenLabs AI Transcription engine to output a voice. I'm likely going to use one of the generic voices from there - even though I'd love to use Jim Cantore, I don't have the rights to clone his voice.

#### Weather Alert:

*Create a weather channel-like narration (example: "There's a weather alert for LaPorte County: Severe Thunderstorm Warning, hail; half an inch, wind 60 miles per hour, tornado; possible." with the info below. Discard any unimportant info. Type out abbreviations like mph = miles per hour. Only respond with the narration text. Do not type anything else:*

(Weather Alert Data)

#### Current Conditions:

*Create a weather channel-like narration (example: "Currently in our area: 79 degrees with rain and windy conditions - chance of rain, 80%" with the info below. Discard any unimportant info. Type out abbreviations like mph = miles per hour. Only respond with the narration text. Do not type anything else:*

(Current Weather Data)

#### Radar:

**Your current dopplar radar**

#### Today's Forecast (Early Morning to mid-afternoon):

*Create a weather channel-like narration (example: "For today, expect a high of 79 degrees with rain and windy conditions - chance of rain, 80%, tonight, expect a low of 50 degrees - clear with no chance of rain" with the info below. Discard any unimportant info. Type out abbreviations like mph = miles per hour. Only respond with the narration text. Do not type anything else:*

(Weather Data "Today and Tonight")

#### Today's Forecast (Mid-afternoon to midnight)

*Create a weather channel-like narration (example: "For rest of tonight, expect a low of 79 degrees with rain and windy conditions - chance of rain, 80%" with the info below. Discard any unimportant info. Type out abbreviations like mph = miles per hour. Only respond with the narration text. Do not type anything else:*

(Weather Data "Tonight")

#### 7 Day Forecast

*Create a weather channel-like narration (example: "Your week ahead. Early in the week will remain quiet and peaceful, with afternoon showers expected on Tuesday. Thunderstorms roll in Wednesday, causing a cooldown for the rest of the week." with the info below. Discard any unimportant info. Type out abbreviations like mph = miles per hour. Only respond with the narration text. Do not type anything else:*

(Weather Data "7 Day Outlook")

#### Air Quality Report (Pollen, Allergen, Smoke)

*Create a weather channel-like narration (example: "Your Air Quality Report. Smoke from the Canadian Wildfires are affecting visibility but is still safe to breathe. Pollen counts are up today." with the info below. Discard any unimportant info. Type out abbreviations like mph = miles per hour. Only respond with the narration text. Do not type anything else:*

(Weather Data "Air Quality / Wildfire Smoke")

#### Traffic Report

***I'm hopeful I can make this work, but I'd need to find a way to pull a text product from something like Google Maps Traffic. This is definitively harder since we don't utilize large highways like cities do.***

*Create a weather channel-like narration (example: "Your traffic report. Highway 6 remains closed today. There's a notable delay on highway 421 into Michigan City, and highway 2 remains closed." with the info below. Discard any unimportant info. Type out abbreviations like mph = miles per hour. Only respond with the narration text. Do not type anything else:*

(Local Traffic Data)
