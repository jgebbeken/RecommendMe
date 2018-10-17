# Recommend Me Restaurants
Ever been with friends or co-workers and can't decide a place to eat at? Thrown ideas at each other, but everyone is still undecided? Give Recommend Me a try. A roulette restaurant app where you customize your food types and have the app recommend restaurants based on what you set. The app finds your location and customizes your search based on the filters you have set. It will give a listing of restaurants and even give you details of the place like reviews or the hour it is open till. You can even share the listing with friends, call the restaurant if you need more information and even locate the restaurant on the map. Give Recommend Me a try today!

<img src="https://github.com/jgebbeken/RecommendMe/blob/master/google-play-badge.png" width="150">

https://play.google.com/store/apps/details?id=dragons.android.recommendme


# Features
* Saves your favorites and food types in a SQLite database
* Randomly generates the food type choice and lists the restaurant based on location and how expensive you are willing to pay for
* Ability to call the restaurant
* See restaurant closing time
* Intent to your favorite map app to see the location of the restaurant

# Technical Features
* Uses Android Architecture Components - LiveData, ViewModels, and Room. Manages your app's lifecycle with little effort, survives configuration changes, avoid memory leaks, and loads data to the UI.
  * Room - Removes boilerplate code and converts SQL data into Java Objects. Provides compile-time checks.
* Uses Google Play Services API for fusedLocationProviderClient to get a users location
* Crashlytics to get real-time crash reports on the Firebase console.
* Firebase Cloud Functions to protect Yelp's Third-Party API from any kind of abuse.
* A widget to display your favorite restaurants
* Butterknife for Databinding
* Repositories for Best Practice between the ViewModel and the Database Module
* Constraint Layout to adjust the UI to the screensize of the user's device
* Admob for Firebase Ad Banners that are displayed on every 5th view on the RecyclerView.


# Library Used

## Following first-party libraries used
* firebase-ads (Admob)
* firebase-core
* com.crashlytics.sdk.android:crashlytics
* Gson
* android.arch.lifecycle.livedata
* android.arch.persistence.room
* RecyclerView
* com.google.android.gms:play-services-location

## Following third party libraries used
* Butterknife http://jakewharton.github.io/butterknife/
* Gson http://jakewharton.github.io/butterknife/
* Picasso http://square.github.io/picasso/
* Indicator Seeker Bar https://github.com/warkiz/IndicatorSeekBar
* Airbnb Lottie https://airbnb.design/lottie/


Live interactive visual storyboard prototype of Recommend Me in the design phase. Powered by Adobe XD CC
https://xd.adobe.com/view/1e879338-58f0-41d1-7d2e-cd446e464329-68b6/



# ScreenShots


## Main Screen
<img src="https://github.com/jgebbeken/RecommendMe/blob/master/Screenshot_1539220639.png" width="400">

## Search Screen

<img src="https://github.com/jgebbeken/RecommendMe/blob/master/Screenshot_1539220649.png" width="400">

## Restaurant Details
<img src="https://github.com/jgebbeken/RecommendMe/blob/master/Screenshot_1539220654.png" width="400">




Google Play and the Google Play logo are trademarks of Google LLC.
