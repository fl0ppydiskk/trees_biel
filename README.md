## Biel is becoming mediterranean

This is my first project for the Lede Program 2025. I was asked to find a dataset, analyze it, create a working webpage in HTML and publish it to Github.

For my project I wanted to find out how climate change influences tree species planted by the Department of Greenery of my hometown Biel, a small town in Switzerland. I was also interested in how they knew which species would thrive and which ones wouldn’t.

After talking to them I learned that the climate in Biel is approaching mean temperatures like the ones recorded 50 years ago in Montpellier, in the south of France. I wanted to get evidence for that, so I compared the data – it’s true. The Green Spaces Department has carried out numerous trials with a variety of new tree species that had not previously been part of Biel’s urban landscape and created a list of (non-) heat resistant trees. I analyzed how the shares changed over the years.

Fot the first chart I used weather data from [Open-Meteo](https://open-meteo.com/), where I extracted daily mean temperatures, mean precipitations and mean sunshine duration for both Biel and Montpellier. HIER BEIDE XLS VERLINKEN!!!!

The second chart was a little more complicated. I hoped for more interesting findings in the data. Eventually, I decided to only compare the shares of (non-) heat resistant trees to the total number of planted trees. I downloaded the [tree registry](https://www.biel-bienne.ch/de/baumkataster.html/3466) that the City of Biel publishes on a government-hosted [open-data site](https://opendata.swiss/de/dataset/baumkataster2). I also created a second dataframe in Pandas with (non-) heat resistant trees based on a list of tree species I received by Email and merged the two.

This is my very first data journalism project so I used numerous newly learned skills while making it: especially working with data and cleaning it in Pandas, but also refining charts in Datawrapper and using HTML and CSS to create the page.

The tree registry also contained coordinates for each tree, I would have loved to make a map with trees appearing on the map in different years when they’re planted, possibly with scrollytelling. But I didn’t have enough time and also didn’t want to make my first project too big.
