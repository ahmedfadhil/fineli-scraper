Fineli scraper
==============

Tools for scraping data from Fineli, the Finnish Food Composition Database.

Usage
-----

    > parse_food_ids | xargs -n1 parse_food > foods.txt

`foods.txt` will contain the Fineli foods in the following format:

    Name;Calories;Carbohydrates;Fat;Protein;Alcohol

Dependencies
------------

In addition to the obvious, the following must be in the path:

* curl
* iconv
* jkwery (from npm)
