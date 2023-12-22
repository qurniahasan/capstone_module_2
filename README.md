![Link Name](https://ichef.bbci.co.uk/news/976/cpsprodpb/B38D/production/_109556954_airbnb.png)

# Overview
Airbnb (ABNB) is an online marketplace that connects people who want to rent out their homes with people looking for accommodations in specific locales. The company has come a long way since 2007, when its co-founders first came up with the idea to invite paying guests to sleep on an air mattress in their living room. According to Airbnb's latest data, it now has more than 7 million listings, covering some 100,000 cities and towns in 220-plus countries and regions.

**Bangkok**, city, capital, and chief port of Thailand. It is the only cosmopolitan city in a country of small towns and villages and is Thailand’s cultural and commercial centre.
<br>**Bangkok**, the lively and famous city in Thailand, is one of the most sought-after places in the world. Many people from abroad come here, making Bangkok a favorite destination. In 2019, the city welcomed around 67 million visitors! That's why Bangkok is very popular on platforms like Airbnb, where people can find unique and diverse places to stay.

# Business Problems

Business Problem Introduction:

In the bustling city of Bangkok, where tourism is thriving and cultural experiences abound, the availability and pricing of accommodations play a pivotal role in shaping the travel experiences of visitors, especially for Indonesian tourists enjoying the convenience of a 30-day free visa. This analysis aims to address key business questions tailored for Indonesian travelers seeking accommodation on Airbnb in Bangkok.

Key Business Questions:

1. **How many active listings are there in Bangkok?**
<br>  For Indonesian tourists planning a trip to Bangkok, knowing the total number of active Airbnb listings provides valuable insights into the breadth of accommodation options available in the city.

2. **How many listings are there in specific areas of Bangkok, and what about the prices?**
<br> Indonesian travelers may have preferences for specific areas in Bangkok. Analyzing listings in these areas, coupled with pricing information, enables tourists to make informed decisions based on their desired locations and budget considerations.

3. **Do hosts predominantly rent out their entire home or just a room?**
<br> Understanding whether hosts in Bangkok typically offer entire homes or individual rooms helps Indonesian travelers tailor their accommodation choices based on personal preferences and the nature of their travel companions.

By addressing these business questions, this analysis serves as a valuable resource for Indonesian tourists exploring Airbnb options in Bangkok. The insights derived from the data aim to empower travelers to make well-informed choices that align with their preferences, budget, and the unique experiences during their 30-day visa-free vacation in this vibrant and dynamic city.


## Data
The data being used consists of various listings of AirBnB in Bangkok, Thailand. This dataset includes information such as listing name, host details, neighborhood of listing, room type, pricing, reviews, and more. 

#### Airbnb Listings Bangkok Data Dictionary

| **Feature**                    | **Description**                                                   |
|--------------------------------|-------------------------------------------------------------------|
| id                             | Airbnb's unique identifier for the listing.                       |
| name                           | Name of the listing.                                              |
| host_id                        | Airbnb's unique identifier for the host/user.                     |
| host_name                      | Name of the host. Usually, just the first name(s).                |
| neighborhood                   | The neighborhood is geocoded using the latitude and               |
|                                | longitude against neighborhoods as defined by open or public      |
|                                | digital shapefiles.                                               |
| latitude                       | Uses the World Geodetic System (WGS84) projection for             |
|                                | latitude and longitude.                                           |
| longitude                      | Uses the World Geodetic System (WGS84) projection for             |
|                                | latitude and longitude.                                           |
| room_type                      | [Entire home/apt \|Private room\| Shared room\| Hotel]            |
|                                | All homes are grouped into the following three room types:        |
|                                | Entire place                                                      |
|                                | Entire places are best if you're seeking a home away from         |
|                                | home. With an entire place, you'll have the whole space to        |
|                                | yourself. This usually includes a bedroom, a bathroom, a          |
|                                | kitchen, and a separate, dedicated entrance. Hosts should         |
|                                | note in the description if they'll be on the property or not (ex: |
|                                | "Host occupies the first floor of the home") and provide further  |
|                                | details on the listing.                                           |
|                                | Private rooms                                                     |
|                                | Private rooms are great for when you prefer a little privacy,     |
|                                | and still value a local connection. When you book a private       |
|                                | room, you'll have your private room for sleeping and may          |
|                                | share some spaces with others. You might need to walk             |
|                                | through indoor spaces that another host or guest may occupy       |
|                                | to get to your room.                                              |
|                                | Shared rooms                                                      |
|                                | Shared rooms are for when you don't mind sharing a space          |
|                                | with others. When you book a shared room, you'll be sleeping      |
|                                | in a space that is shared with others and share the entire        |
|                                | space with other people. Shared rooms are popular among           |
|                                | flexible travelers looking for new friends and budget-friendly    |
|                                | stays.                                                            |
| price                          | Daily price in local currency. Note, the $ sign may be used       |
|                                | despite the locale.                                               |
| minimum_nights                 | The minimum number of night stays for the listing (calendar       |
|                                | rules may differ).                                                |
| number_of_reviews              | The number of reviews the listing has.                            |
| last_review                    | The date of the last/newest review.                               |
| calculated_host_listings_count | The number of listings the host has in the current scrape in      |
|                                | the city/region geography.                                        |
| availability_365               | avaliability_x. The calendar determines the availability of the   |
|                                | listing x days in the future. Note a listing may be available     |
|                                | because it has been booked by a guest or blocked by the           |
|                                | host.                                                             |
| number_of_reviews_ltm          | The number of reviews the listing has (in the last 12 months).    |

