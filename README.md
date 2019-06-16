# AWiki-Android-Notes


## Overview

Most common tools for creating Android / Java applications. Source will contains libraries location, small description, benefits and some explanation, why you should choose one over another. 



## Tools


### 1. Google Jetpack & Common
* [Google Jetpack](https://developer.android.com/jetpack/) is a collection of Android software components to make it easier for you to develop great Android apps. These components help you follow best practices, free you from writing boilerplate code, and simplify complex tasks, so you can focus on the code you care about. 

<p align="center">
<img src="https://raw.githubusercontent.com/GensaGames/AWiki-Android-Tools/master/images/Android_Common.png" width="750" height="450" />
</p>
</br>


### 2. Networking

 * [[OkHttp](http://square.github.io/okhttp/)] - Square's underlying networking library. Sync and Asynchronous requests. Setting custom serealization. Supports Interceps, WebSockets, and more. Complete Guide - [[Codepath](https://github.com/codepath/android_guides/wiki/Using-OkHttp)]
 
 * [[Retrofit](https://square.github.io/retrofit/)] - A type-safe REST client for Android which intelligently maps an API into a client interface using annotations. Very powerfull tools built over previous OkHttp. Complete Guide - [[Codepath](https://github.com/codepath/android_guides/wiki/Consuming-APIs-with-Retrofit)]


### 3. Testing

 * [[Espresso](https://developer.android.com/training/testing/espresso/)] - Espresso is a UI test framework (part of the Android Testing Support Library) that allows you to create automated UI tests for your Android app. Complete Guide - [[Codepath](https://github.com/codepath/android_guides/wiki/UI-Testing-with-Espresso)] 
 
 * [[Mockito](https://site.mockito.org/)] - Mockito is a mocking framework that tastes really good. It lets you write beautiful tests with a clean & simple API. Mockito doesn’t give you hangover because the tests are very readable and they produce clean verification errors.
 
 * [[PowerMock](https://github.com/powermock/powermock)] - Writing unit tests can be hard and sometimes good design has to be sacrificed for the sole purpose of testability. Often testability corresponds to good design, but this is not always the case. For example final classes and methods cannot be used, private methods sometimes need to be protected or unnecessarily moved to a collaborator, static methods should be avoided completely and so on simply because of the limitations of existing frameworks.
 
 * [[Robolectric](http://robolectric.org/)] - Efficient unit testing for Android. Robolectric is a unit testing framework that allows Android applications to be tested on the JVM without an emulator or device. Complete Guide - [[Codepath](https://github.com/codepath/android_guides/wiki/Unit-Testing-with-Robolectric)]
 
 * [[LeakCanary](https://github.com/square/leakcanary)] - A memory leak detection library for Android and Java. “A small leak will sink a great ship.” - Benjamin Franklin 

 
### 4. Images Loading / Preprocessing

 * [[Glide](https://github.com/bumptech/glide)] - Glide is an Image Loader Library for Android developed by bumptech and is a library that is recommended by Google. Complete Guide - [[Codepath](https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Glide-Library)]
 
 * [[Fresko](https://frescolib.org/)] - Fresco’s image pipeline will load images from the network, local storage, or local resources. To save data and CPU, it has three levels of cache; two in memory and another in internal storage.
 
 * [[UIL](https://github.com/nostra13/Android-Universal-Image-Loader)] - Android library #1 on GitHub. UIL aims to provide a powerful, flexible and highly customizable instrument for image loading, caching and displaying. It provides a lot of configuration options and good control over the image loading and caching process.




### 5. Persistence

 * [[ActiveAndroid](http://www.activeandroid.com/)] - Not very fast, but quite convenient and proven over time solution. Using the ActiveAndroid ORM makes managing client-side models extremely easy in simple cases. For more advanced or custom cases, you can use SQLiteOpenHelper to manage the database communication directly. Complete Guide - [[Codepath](https://github.com/codepath/android_guides/wiki/ActiveAndroid-Guide)] 
 
 * [[greenDAO](https://github.com/greenrobot/greenDAO)] - It is flexible and convenient to use one-to-many communication, but very unpleasant code generation, as a result of which your classes will be filled with a bunch of methods and comments. In addition, you need to connect the Gradle plug-in, which greatly increases the build time.
 
 * [[ORMLite](http://ormlite.com/sqlite_java_android_orm.shtml)] - It does not save much from the boilerplate code, however one of the fastest libraries out there is built-in caching and delayed initialization, good documentation. 
 
 * [[Realm](https://github.com/realm/realm-java)] - Object orientated database, with very easy setup and developing. Excellent documentation. Realm is a mobile database that runs directly inside phones, tablets or wearables. This repository holds the source code for the Java version of Realm, which currently runs only on Android.
 
 * [[Room](https://developer.android.com/topic/libraries/architecture/room.html)] - An interesting solution presented on Google I / O 2017 as optimal for working with the database on Android OS. Despite the fact that it is necessary to use explicit sql-requests, the library turned out to be quite convenient and I liked it personally. 



### 6. Logging

 * [[Timber](https://github.com/JakeWharton/timber)] - This is a logger with a small, extensible API which provides utility on top of Android's normal Log class. I copy this class into all the little apps I make. I'm tired of doing it. Now it's a library.
 
 * [[SLF4J](https://github.com/qos-ch/slf4j)] - The Simple Logging Facade for Java (SLF4J) serves as a simple facade or abstraction for various logging frameworks (e.g. java.util.logging, logback, log4j) allowing the end user to plug in the desired logging framework at deployment time. 





## Resources

Check out the following resources for finding libraries:

 * [Android Codepath](https://github.com/codepath/android_guides/wiki/Must-Have-Libraries#advanced-pack)
 * [Android Aresenal](http://android-arsenal.com)
 * [Wasabeef Core Libraries](https://github.com/wasabeef/awesome-android-libraries)
 * [Wasabeef UI Libraries](https://github.com/wasabeef/awesome-android-ui)
 * [Ultimate Android Library Reference](https://github.com/aritraroy/UltimateAndroidReference/blob/master/README.md)
 * [Snowdream Android Library Repository](https://snowdream.github.io/awesome-android/)
 * <http://appdevwiki.com/wiki/show/HomePage>
 * <http://www.libtastic.com>
 * [Android Libhunt](https://android.libhunt.com/)

## References

