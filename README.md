# GeoHam
🗺️ UrbanHacks 2018 Winner! 🏆 Explore your community, even the parts not on Google Maps

<img width="31%" src="https://github.com/qhyun2/GeoHam/raw/master/demo/gallery1.jpg"> <img width="31%" src="https://github.com/qhyun2/GeoHam/raw/master/demo/gallery2.jpg"> <img width="31%" src="https://github.com/qhyun2/GeoHam/raw/master/demo/gallery3.jpg">
 
### [Devpost](https://devpost.com/software/geoham)

## Inspiration
When looking at the urban development issues affecting Hamilton, we found that the city has a lot of great services and amenities. However, awareness of these services is quite limited - especially for those that don't appear on Google Maps. We aim to fix this, by merging Google Maps with Hamilton's Open Data, and adding a touch of gamification to encourage residents to explore their city.

## What it does
GeoHam aims to let Hamilton residents discover the amazing parks, sports amenities and services across their city - even the ones that Google maps doesn't know about, by combining Google Map's location services with the city of Hamilton's Open Data. For example, while Google Maps shows baseball pitches as fields, GeoHam is able to show users exactly where they are.

The app makes it really easy for users to visit these places, by providing live data about public transport, and incentivises users to visit places by allowing them to earn points

## How we built it
The Android app is built using Android studio. It integrates the Google Maps Android SDK, WebViews and a ton of other stuff to create a great user experience.

Certain aspects of the app, such as the additional information was developed as a WebView. This makes it really easy for us to update this in the future, without requiring users to update the app.

We used Hamilton's Open Data to create our own API, which can be queried to get all the info the app needs, but without all the bloat of raw CSVs provided by Hamilton. This was developed with PHP, with the data stored in a MySQL database.


## Challenges we ran into
> Standardising the data proved to be quite difficult. While the Open Data is in a somewhat standard format, there's some quirks with how it was categorised that needed fixing. Additionally, Google Map's API was at times a bit tricky to deal with, since it requires multiple API queries for things that really should only need one. **-Jack**

> Parsing JSON was more difficult than I expected as this was the first time I used GSON. I also found importing libraries and learning Android Studio to have a steep learning curve. **-Howard**

> Getting Android Studio to work was difficult - especially on the slow WiFi. **-Miguel**

## Accomplishments that we're proud of
> I think we've ended up with a really solid MVP. It's a service which I can see benefiting many people if further developed, its UX is surprisingly nice and the app is really stable. **-Jack**

> Getting nicely detailed and coloured pins on the map, and getting the map working in general was great. I also really like our score system used for gamification. **-Howard**

> I'm really proud that we managed to create something really good, even though it was out first time developing for Android. **-Miguel**
## What we learned
> I learned the basics of Android Development, some of the challenges associated with it. **-Jack**

> I learned the Android framework and how to use Google Cloud Platform as well as integrating web APIs into an Android app. **-Howard**

> I learned about the basics of Android development, and especially how constants work. **-Miguel**

> I learned how to standardize data and create an API **-Rome**

## What's next for GeoHam
The gamification aspects of the app could definitely be expanded upon - perhaps we could add an achievement system of some sort. Cleaning up bits of the UI, and making more services available in the map would be good too.
