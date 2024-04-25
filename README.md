# European Football (The "Real" Football :blush:) Analysis

Inspired by the Kaggle notebook [European Soccer Database](https://www.kaggle.com/datasets/hugomathien/soccer). The author of the notebook provides a *.sqlite* file containing various data (matches, players, team stats, etc.) from 2008 to 2016. In addition to this data, I tried to incorporate any other relevant data that I wanted to leverage.

For example, I was interested in getting a dataset on Champions League :star2:, hoping to build some sort of a model that can predict whether a team qualifies for the Champions League. I used BeautifulSoup to web scrape from this [website](https://fbref.com/en/comps/8/2015-2016/schedule/2015-2016-Champions-League-Scores-and-Fixtures), which seemed like the :soccer: version of the [:baseball:-reference website](https://www.baseball-reference.com/) which I visit quite regularly.

* For the web scraping process, all I do is take the distinct team names beginning from the tournament round, so that we can see which teams were in the Champions League tournament each year. I think web scraping is quite simple once you get the hang of how it works, but it does take a bit of time really trying to get into the HTML code and figuring things out with all the different tags. Thankfully, I was able to figure out what I needed after doing a few hours of searching on the internet.
