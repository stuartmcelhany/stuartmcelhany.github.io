---
layout: post
title: Song City
thumbnail: /images/songcity/cities_G.png
---

Web scraper that finds the number of references in music to the 1,000 most populated cities in the US.

![References from artists starting with "G"]({{ site.baseurl }}/images/songcity/cities_G.png)

Have you ever wondered how many times your city gets referenced in song? This python code scanned thousands of artists' song lyrics found on [azlyrics.com](https://www.azlyrics.com/) and counted each time a US city was referenced in the song. Additionally, to make a fair comparison, the number of references per city was divided by the population of the city. Artists' names starting with each letter of the alphabet are currently being run sequentially. This web scraping was done with ethics in mind, as layed out in [this](https://blog.soshace.com/responsible-web-scraping-gathering-data-ethically-and-legally/) blog post.

There are some stipulations, however. First, nicknames of cities are not accounted for - such as "Philly". Additionally, some city names are common words that get mentioned out of context of the city. For example, Sparks, NV.

[GitHub](https://github.com/stuartmcelhany/song-city)
