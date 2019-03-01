
Provide a readme.md file that documents:

**How to build and run your creation**

It's simple! download the index.html file and drag it into a browser window ( to try it out go to this url: https://jamesjt.github.io/index.html) Everything is contained in one file. 

**Your thought process when creating the solution**

As the project doesn't have as specific use case or user base I created something minimal I might use. I only really ever use weather apps to compare basic aspects of cities. Due to the restrictions of the API and needing just simple information I focused on building something minimalist. A few times I considered pulling from sources outside of OpenWeatherMap but chose to keep it entirely contained within the resources it provides. 

**Any tradeoffs you made**

Staying within the OpenWeatherMap data and sources provided a few problems.
While the data does provide a location based on coordinates without a tool to find timezone, state, region, etc. various aspects of the results are problematic. The API provides the time in GMT, not the local time of the city searched for. It also doesn't specificy which city of its name is getting referenced except by zip code, country, and coordinates. Country didn't feel percise enough to include in many cases, and I except few users to know a zip or coordinate for both cities they are looking for. Especially if they are looking at cities in other countries. 

There is some other potentially interesting data provided by the API, humidity, wind (especially for pilots), zip code, country, etc. Without really designing for a specific use cause I chose to keep it clean rather than data rich. 

Everything is contained within one file to keep with the minimalist approach. If the project became bigger it would be wise to break out the JS and CSS into their own files even with some (small) cost for setting up the project to run. 

**Anything you might implement with more time (features, fixes, technical debt corrections etc)**

There are many ways to improve its functionality, here are a few:  
• Fixing the time issue as mentioned above. 

• Allowing a user to click on day to get additional information about that day, humidity, wind direction, wind speed, etc. 

• Structuring it for mobile such that a city pane is better designed to that experience.  

• Adding additional panes (some tech debt created now by not having the number of panes already be dynamic)

• Dynamic background based on weather conditions of the day

• Improved art

• Utilzing better database access ASAP  is a high priority. So that the project can be restructured for expected uses and tech debt can be avoided while the project is still small.

• Weather trends over a much longer period of time. 

• Customization of basic data displayed for individual users. 

• Improved error messaging and accessibility features

• List options when trying in search, include country, region, airport, and other identification data based on target users.
