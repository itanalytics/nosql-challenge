# nosql-challenge

## Description
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Analysis
**Questions Answered:**  
>1. Which establishments have a hygiene score equal to 20?
>- There are 41 establishments with a hygiene score of 20

>2. Which establishments in London have a `RatingValue` greater than or equal to 4?
>- There are 34 establishments in London with a Rating Value greater than or equal to 4

>3. What are the top 5 establishments with a `RatingValue` rating value of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

>4. How many establishments in each Local Authority area have a hygiene score of 0?
>- {'_id': 'Thanet', 'count': 1130}
>- {'_id': 'Greenwich', 'count': 882}
>- {'_id': 'Maidstone', 'count': 713}
>- {'_id': 'Newham', 'count': 711}
>- {'_id': 'Swale', 'count': 686}

### Contributors
Ivan Villa

### Additional Notes
UK Food Standards Agency (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GB. Contains public sector information licensed under the Open Government Licence v3.0
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).