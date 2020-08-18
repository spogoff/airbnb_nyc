# Airbnb Investment Analysis

## Prompt: Which neighborhood is best to invest in for an Airbnb rental in New York?

## Subprompt:Which neighborhoods receive the most positive reviews?

### Suggestion: 

Invest in a townhouse below 59th Street in Manhattan! To be more specific, here…

![Manhattan_map](https://github.com/spogoff/airbnb_nyc/blob/master/Assets/Manhattan_map.png?raw=true)


### Summary of Data Cleaning

• Looked for duplicates
• Deleted errors and columns unnecessary for calculation such as summary and description
• Filtered data to listings with booking only
• Standardized City, State and Neighborhood and Cleansed Columns
• Aggregated to calculate estimated days with booking, estimated revenue per month and estimated total revenue
• Grouped neighborhoods in all boroughs (close to official district boundaries defined by the city)

### Exploratory Data Analysis

#### Airbnb Listings in New York's Boroughs

![Piechart.png](https://github.com/spogoff/airbnb_nyc/blob/master/Assets/Piechart.png?raw=true)

#### Neighborhood Scores Rating: Manhattan vs. Brooklyn

![Barcharts.png](https://github.com/spogoff/airbnb_nyc/blob/master/Assets/Barcharts.png?raw=true)

#### Review Scores and Estimated Total Revenue: A Weak Relationship

![Scatterplot.png](https://github.com/spogoff/airbnb_nyc/blob/master/Assets/Scatterplot.png?raw=true)

#### Top 5 Neighborhood groups in New York (based on estimated revenue)

• Midtown, Theater District, Flatiron District
• Chelsea, Clinton, Hell's Kitchen
• Battery Park City, Financial District, Tribeca
• Chinatown, Greenwich Village, Little Italy, Lower East Side, NoHo, SoHo, West Village, Nolita, Civic Center
• Midtown, Theater District, Flatiron District
• Gramercy Park, Kips Bay, Murray Hill, Stuyvesant Town

![top5neighborhoods.png](https://github.com/spogoff/airbnb_nyc/blob/master/Assets/top5neighborhoods.png?raw=true)

#### Townhouses: Big Revenue, Little Competition 

![Bubblechart.png](https://github.com/spogoff/airbnb_nyc/blob/master/Assets/Bubblechart.png?raw=true)

#### How much revenue is a townhouse in one of the top 5 neighborhoods in NYC estimated to generate?

![Revenue_barchart.png](https://github.com/spogoff/airbnb_nyc/blob/master/Assets/Revenue_barchart.png?raw=true)

## Technologies:

• Excel

## Data Source:

• https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data


