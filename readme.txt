WeatherLogger Application

This app used MVP Design Pattern with generic Retrofit2 library. 

The libraries I used for the project are as follows
 -> implementation 'com.google.android.material:material:1.0.0-rc01'
 
 -> implementation 'com.squareup.retrofit2:retrofit:2.1.0'
 
 -> implementation 'com.google.code.gson:gson:2.8.5'
 
 -> implementation 'com.squareup.retrofit2:converter-gson:2.1.0'
 
 -> implementation 'com.squareup.retrofit2:converter-scalars:2.1.0'
 
 -> implementation 'com.github.Yalantis:Context-Menu.Android:1.1.4'
 
 -> implementation 'com.tbuonomo.andrui:viewpagerdotsindicator:2.1.2'
 
 -> implementation 'com.squareup.picasso:picasso:2.71828'
 
 -> implementation 'com.makeramen:roundedimageview:2.3.0'
 
 -> implementation 'com.github.bumptech.glide:glide:4.10.0'
 
 -> annotationProcessor 'com.github.bumptech.glide:compiler:4.10.0'
 
 -> implementation 'joda-time:joda-time:2.10.5'


This app provide some features. These features are listed in detail.

 -> Default city is Riga. When the application is installing first time, default city is Riga. 

 -> When click toolbar home button, user go to SelectedCityList Activity. This activity has 4 city. Riga, Ankara, Antalya and Istanbul

 -> When click another city, application remove all data and send new request to OpenWeatherAPI, handle current weather and forecast weather data.

 -> User click save button, application save current and forecase data to Local Storage. And than never request to API

 -> Application create 3 Activity and 3 Fragments

 -> First activity is SplashScreen. 

 -> Second activity is ViewPager Activity and this activity has 3 fragment. CurrentWeatherFragment, DailyWeatherFragment and WeatherSummaryFragment

 -> CurrentWeather fragment has current weather data according to current city

 -> DailyWeather fragment has 5 days forecast weather data and list in RecyclerView data..

 -> WeatherSummary fragment has just one item. This item is current city temperature, date and icon.

 -> Last Activity is SelectCityActivity. This activity has just 4 city. If user select any city, than send a new request.

I added a comment line for each function in application code. 