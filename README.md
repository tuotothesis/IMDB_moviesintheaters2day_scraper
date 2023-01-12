# MoviesinTheaters2day
An **EXTREMELY** preliminary web scraping program that presents you movies in theaters of your location at current time, and exports the information as a csv file for further use.
Each row of the csv file represents one movie playing, and that movie has attributes such as their rankings, their descriptions, and one featured review. (More information: Data Dictionary below) The documents are not automatically updated, unfortunately, so they only reflect the movies available when you run the program.


# Data Dictionary
|  Attribute Name  | Type  |  Discription  |
|  :----  | :----  | :----  |
| title  | string | Title of the movie |
| content_rating  | string | Content rating of the movie |
| duration_min  | numeric | Duration of the movie, measured in minutes |
| users_rating  | numeric | Users-attributed rating, on a scale of 10 |
| users_count  | numeric | The count of users that rated the movie |
| metascore  | numeric | Rating based on critic reviews provided by Metacritic.com, on 100 point scale |
| description  | string | Brief movie description, may contains storyline, director, writers and stars |
| featured_review  | string | The featured review shown on the movie's IMDb page |
| genre  | string | genre of the movie |
| url  | string | the url linked to the movie's IMDb page |
