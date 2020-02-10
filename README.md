# Top-Zomato-Restaurants-in-Bengaluru:
The basic idea of analysing the Zomato dataset is to get a fair idea about the factors affecting the aggregate rating of each restaurant, establishment of different types of restaurant at different places, Bengaluru being one such city has more than 12,000 restaurants with restaurants serving dishes from all over the world. With each day new restaurants opening the industry hasn’t been saturated yet and the demand is increasing day by day. In spite of increasing demand it however has become difficult for new restaurants to compete with established restaurants. Most of them serving the same food. Bengaluru being an IT capital of India. Most of the people here are dependent mainly on the restaurant food as they don't have time to cook for themselves. With such an overwhelming demand of restaurants it has therefore become important to study the demography of a location. Hence build a model to predict the rating of the each restaurants.

## Features/ Columns:
1. **url:** contains the url of the restaurant in the zomato website
2. **address:** contains the address of the restaurant in Bengaluru
3. **name:** contains the name of the restaurant
4. **online_order:** whether online ordering is available in the restaurant or not
5. **book_table:** table book option available or not
6. **rate:** contains the overall rating of the restaurant out of 5
7. **votes:** contains total number of rating for the restaurant as of the above-mentioned date
8. **phone:** contains the phone number of the restaurant
9. **location:** contains the neighborhood in which the restaurant is located
10. **rest_type:** restaurant type
11. **dish_liked:** dishes people liked in the restaurant
12. **cuisines:** food styles, separated by comma
13. **approx_cost(for two people):** contains the approximate cost for meal for two people
14. **reviews_list:** list of tuples containing reviews for the restaurant, each tuple consists of two values, rating and review by the customer
15. **menu_item:** contains list of menus available in the restaurant
16. **listed_in(type):** type of meal
17. **listed_in(city):** contains the neighborhood in which the restaurant is listed

## Installation

Use the package manager [pip](https://pypi.org/project/numpy/) to install Numpy,pandas,.

```CMD
pip install Numpy
```

## Usage

```python
import numpy as np
import pandas as pd
import seaborn as sns
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
reddyprasade@gmail.com

## License
[MIT License Copyright (c) 2020 REDDY PRASAD ](https://choosealicense.com/licenses/mit/)
