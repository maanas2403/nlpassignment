The procedure for this assignment is as follows:
1. I used the GNews Scraper in order to retrieve the news. The link for the scraper: https://github.com/ranahaani/GNews
2. I imported the GNews library and intialized GNews model as google_news with the parameters that news is in english language, in country India, start date is 3rd April 2024 and end date is 5th April 2024
3. From the initialized google_news model, I called get_news() method with passing of 'Reliance Industries Ltd' and in return I got a list of dictionary contaning news title and source url
4. I stored the list in reliance_news and copied the result in news.txt
