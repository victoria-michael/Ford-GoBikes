# FordGo Bikes Exploration and Visualisation
## by Victoria Michael


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. Ford GoBike consists of a fleet of specially designed, sturdy and durable bikes that are locked into a network of docking stations throughout the city. The bikes can be unlocked from one station and returned to any other station in the system, making them ideal for one-way trips. The bikes are available for use 24 hours/day, 7 days/week, 365 days/year and riders have access to all bikes in the network when they become a member or purchase a pass.

The exploration process:
<li> 1. importing necessary packages (pandas to read csv, numpy for numerical analysis, matplotlib for visualization). 
    2. Wrangling Process: I checked what the dataset looked like, using '.info', '.sample', '.describe'. I checked  the value counts for columns that were valuable for the visualisation.
    3. Cleaning Process: Incorrect datatypes were fixed, dropping rows with null values.
    4. Visualisation: Three kinds of visualisations were performed (Univariate, Bivariate and Multivariate visualisations).
</li>    


## Summary of Findings

> The main features I focused on was the "user_type", "member_gender", "start_time", "end_time", and "bike_share"

These showed that FordGo had more male user representation than females and 'others'. More of its users were subscribers/memvbers and few were just customers. It also showed that during the rush hours(9-10am, and 5pm-6pm), the was an increase in usage. there were also less bike share in the dataset. Most trips were taken o Thursdays and Tuesday. Weekend had the least trip record, though longer trip duration. Also, hourly usage for subscribers were higher than regular customers. Average trip duration for Customers were also higher than those of the subscirbers. 

## Key Insights for Presentation

> I used seaborn's countplot to check the hourly and weekly trip frequency. The categorical variables, user_type and member gender were also plotted using pandas plot function. I used different plot functions to differnetiate betwen plots.