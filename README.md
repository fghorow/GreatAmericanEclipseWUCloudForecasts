# GreatAmericanEclipseWUCloudForecasts
A quick-and-dirty Jupyter (Python3) notebook to retrieve from Weather Underground cloudy skies forecasts for the Great American Eclipse of 21 August 2017 at a list of locations.

What the heck is this?

I'm starting to obsess about cloud cover at my selected locations for the Great American Eclipse next week. I've got hotel rooms booked in two different places, and will cancel/go-to one depending on the forecast weather conditions for the time of the eclipse.

As I write this text, we are entering into the 10-day time window where weather forecasts start having some "skill" (i.e. a better chance than random of being right). In particular, the website Weather Underground has hourly forecasts available for 10 days. But, in all honesty, it's a real pain to scroll through their website to find the eclipse time cloud coverage forecast for my list of cities of interest.

So, what's a lazy geek to do?

It turns out that WUnderground has an API, and keys to access the data are free/gratis for relatively infrequent requests to their infrastructure.

SCORE!

So, I wrote this here quick-and-dirty Python 3 code in this here Jupyter notebook to query Weather Underground's infrastructure for my locations of interest, and simply print out the cloud coverage forecast for each location.

What do you need to use this code yourself? Mostly, a Weather Underground API key enabled for their "Anvil" plan at the "Devloper" level. That enables you to use their infrastructure without stealing website hits from anyone else. Enter your key as a string into the API_KEY variable a couple of cells below

Then, you need to populate the locs list a few cells below with the locations you care about. Make sure the times in the cell above that are accurate for your circumstances. The run the cells below this one in sequence, and the final one will print out the cloud coverage forecasts for the places you care about.

It should go without saying that the forecasts are from Weather Underground, not me. My code only makes accessing their results more simple than scrolling through their website.

This is a hack. This is only a hack.

I wish you the best of luck in your quest to see the eclipse, but take no responsibility for your use of Weather Underground's forecasts or this convenience code hack. Period. Full Stop.
