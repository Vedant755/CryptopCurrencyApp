# CryptopCurrencyApp
This is a crypto currency application which tells about whether the currency is active and many other things with it's complete information.

1. MVVM architecture is used to design these application. MVVM is known as Model-View-ViewModel, this architecture pattern is highly recommended by google and compiled to use over other architectures.

2. Retrofit2 is used to get data through APIs which used to fetch data from remote database.

3. The https://lnkd.in/drK8mu2u Api is used to get the remote data.

4. The app only runs when there is connectivity with the Internet as the Live currency track is must. If I wanted to cache the data then I would have used Room database for the same. 

5. Jetpack Compose which a widely spreading UI design tool for Android Studio is being used. Even though 80per of apps are still in XML style, but the popularity and dynamic nature of Jetpack Compose would lead it ahead in the race with XML. 

6. There are 3 main layers in these Application architecture.

    a. Data: It consists of all the classes which are used to get the data in raw format from the APIs, for this data classes are used.   
   
    b. Domain: It consists of all the classes which refined the data so that only the parameterized data which is needed for Presentation layer can be made available. 
  
    c. Presentation: It consists all the UI related components.
