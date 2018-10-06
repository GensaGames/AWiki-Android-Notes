# AWiki-Android-Tools


|-|-|-|-|
|---|---|---|---|
|[Overview](#overview)|[Standard Pack](#standard-pack)|[Advanced Pack](#advanced-pack)|[Convenience](#convenience)
|[Extensions](#extensions)|[Networking](#networking)|[ListView](#listview)|[RecyclerView](#recyclerview)
|[Easy Navigation](#easy-navigation)|[UI Components](#ui-components)|[Drawing](#drawing)|[Image Processing](#image-processing)
|[Scanning](#scanning)|[Persistence](#persistence)|[Binding](#binding)|[Compatibility](#compatibility)
|[Scrolling And Parallax](#scrolling-and-parallax)|[Debugging](#debugging)|[Resources](#resources)|[References](#references)

## Overview

Most common tools for developing different Android / Java applications. Source will contains libraries location, small description, benefits and some explanation, why you should choose one over another. It's also acceptable to have some common part of code, for it's implementation. Feel free to add your own Pull-Request. Cheers!





### Networking

 * [[OkHttp](http://square.github.io/okhttp/)] - Square's underlying networking library. Sync and Asynchronous requests. Setting custom serealization. Supports Interceps, WebSockets, and more. Complete Guide - [[Codepath](https://github.com/codepath/android_guides/wiki/Using-OkHttp)]
 
 * [[Retrofit](https://square.github.io/retrofit/)] - A type-safe REST client for Android which intelligently maps an API into a client interface using annotations. Very powerfull tools built over previous OkHttp. Complete Guide - [[Codepath](https://github.com/codepath/android_guides/wiki/Consuming-APIs-with-Retrofit)]


### Testing

 * [[Espresso](https://developer.android.com/training/testing/espresso/)] - Espresso is a UI test framework (part of the Android Testing Support Library) that allows you to create automated UI tests for your Android app. Complete Guide - [[Codepath](https://github.com/codepath/android_guides/wiki/UI-Testing-with-Espresso)] 
 
 * [[Robolectric](http://robolectric.org/)] - Efficient unit testing for Android. Robolectric is a unit testing framework that allows Android applications to be tested on the JVM without an emulator or device. Complete Guide - [[Codepath](https://github.com/codepath/android_guides/wiki/Unit-Testing-with-Robolectric)]
 
 * [[LeakCanary](https://github.com/square/leakcanary)] - A memory leak detection library for Android and Java. “A small leak will sink a great ship.” - Benjamin Franklin 

 
### Images Loading / Preprocessing

 * [[Glide](https://github.com/bumptech/glide)] - Glide is an Image Loader Library for Android developed by bumptech and is a library that is recommended by Google. Complete Guide - [[Codepath](https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Glide-Library)]
 
 * [[Fresko](https://frescolib.org/)] - Fresco’s image pipeline will load images from the network, local storage, or local resources. To save data and CPU, it has three levels of cache; two in memory and another in internal storage.
 
 * [[UIL](https://github.com/nostra13/Android-Universal-Image-Loader)] - Android library #1 on GitHub. UIL aims to provide a powerful, flexible and highly customizable instrument for image loading, caching and displaying. It provides a lot of configuration options and good control over the image loading and caching process.
















# OTHER
------------------------------

### ListView

 * [EasyListViewAdapters](https://github.com/birajpatel/EasyListViewAdapters) - Building multi-row-type listview made much cleaner & easier.
 * [GridListViewAdapters](https://github.com/birajpatel/GridListViewAdapters) - Easily build unlimited Grid cards list like play-store. (ListView working as unlimited GridView)
 * [StickyListHeaders](https://github.com/emilsjolander/StickyListHeaders) - An android library for section headers that stick to the top of a ListView
 * [PinnedListView](https://github.com/beworker/pinned-section-listview) - Pinned Section with ListView
 * [ListViewAnimations](https://github.com/nhaarman/ListViewAnimations) - Easy way to animate ListView items (**DEPRECATED**)
 * [Cardslib](https://github.com/gabrielemariotti/cardslib) - Card UI for Lists or Grids
 * [PullToRefresh-ListView](https://github.com/erikwt/PullToRefresh-ListView) - Easy to use pull-to-refresh functionality for ListViews. [Download](https://github.com/erikwt/PullToRefresh-ListView/archive/master.zip) and install as a [library project](https://imgur.com/a/N8baF).
 * [QuickReturn](https://github.com/lawloretienne/QuickReturn) - Reveal or hide a header or footer as the list is scrolled in a direction.
 * [SortableTableView](https://github.com/ISchwarz23/SortableTableView) - The library enables you to display your data in a table and provides numerous customization possibilities. The api was designed very android like so the usage is intuitive for experienced android developers.
 * [Paginated Table](https://github.com/ojinxy/AndroidComponents) - This is a table which allows dynamic paging for any list of objects. Icons can be added to columns as well as custom items such as check boxes and buttons.

### RecyclerView
* [PinnedList-Android](https://github.com/Joseph82/PinnedList-Android) - A library that allows you to create a list of items that are pinned by a floating label (text or image) on the left of the list
* [UltimateRecyclerView](https://github.com/cymcsg/UltimateRecyclerView) - Augmented RecyclerView with refreshing, loading more, animation and many other features.
* [EasyAdapter](https://github.com/mkrupal09/EasyAdapter) - Create your recyclerview adapter in just 3 lines.
* [AdvRecyclerView](https://github.com/h6ah4i/android-advancedrecyclerview) - Extended RecyclerView with swipe to dismiss, and draggable or expanding items. 
* [android-parallax-recyclerview](https://github.com/kanytu/android-parallax-recyclerview) - An adapter which could be used to achieve a parallax effect on RecyclerView.
* [sticky-headers-recyclerview](https://github.com/timehop/sticky-headers-recyclerview) - Sticky Headers decorator for Android's RecyclerView.
* [FastAdapter](https://github.com/mikepenz/FastAdapter) - Simplify and speed up the process of filling your RecyclerView with data
* [FlexibleAdapter](https://github.com/davideas/FlexibleAdapter) - Fast and versatile Adapter for RecyclerView which regroups several features into one library to considerably improve the user experience.
* [ItemAnimators](https://github.com/mikepenz/ItemAnimators) - RecyclerView animators to animate item add/remove/add/move
* [GreedoLayout](https://github.com/500px/greedo-layout-for-android) - Full aspect ratio grid LayoutManager for Android's RecyclerView
* [ChipsLayoutManager](https://github.com/BelooS/ChipsLayoutManager) - RecyclerView's LayoutManager which moves item to the next line when no space left on the current. Can represent google material chips guideline or tags view. 
* [RecyclerViewHelper](https://github.com/nisrulz/recyclerviewhelper) - Provides the most common functions around recycler view like Swipe to dismiss, Drag and Drop, Divider in the ui, events for when item selected and when not selected, on-click listener for items.
* [async-expandable-list](https://github.com/Ericliu001/async-expandable-list) - async-expandable-list provides solutions to displaying header-sub-items structure with simple api and asynchronously loading sub-list into an expandable list.   
* [Epoxy](https://github.com/airbnb/epoxy) - Epoxy is an Android library for building complex screens in a RecyclerView.

### Easy Navigation 

 * [JazzyViewPager](https://github.com/jfeinstein10/JazzyViewPager) - Pager with more animations
 * [ParallaxPager](https://github.com/prolificinteractive/ParallaxPager) - ViewPager with Parallax scrolling effects
 * [ParallaxHeaderViewPager](https://github.com/kmshack/Android-ParallaxHeaderViewPager) - Another ViewPager with Parallax scrolling effects
 * [ParallaxPagerTransformer](https://github.com/xgc1986/ParallaxPagerTransformer) - A pager transformer for Android with parallax effect
 * [SlidingMenu](https://github.com/jfeinstein10/SlidingMenu) - Library that allows developers to easily create applications with sliding menus like those made popular in the Google+, YouTube, and Facebook apps.
 * [Android Satellite Menu](https://github.com/siyamed/android-satellite-menu/) - Radial menu which is configurable reminiscent of the "Path" menu style.
 * [ArcMenu](https://github.com/daCapricorn/ArcMenu) - Alternate radial menu modeled after the "Path" menu style.
 * [AndroidSlidingUpPanel](https://github.com/umano/AndroidSlidingUpPanel) - Sliding Up Panel 
 * [DraggablePanel](https://github.com/pedrovgs/DraggablePanel) - Panels that can be dragged
 * [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer/) - Easily add a Navigation Drawer with Material style and AccountSwitcher

### UI Components
 * [Gravity View](https://github.com/gofynd/gravity-view) - Library for image tilt using sensor
 * [SparkButton](https://github.com/varunest/SparkButton) - Library to create buttons with Twitter's heart like animation.
 * [BetterPickers](https://github.com/derekbrameyer/android-betterpickers) - BetterPickers for easy input selection.
 * [FlipView](https://github.com/davideas/FlipView) - Flipping views like Gmail & beyond.
 * [android-shape-imageview](https://github.com/siyamed/android-shape-imageview) - Custom shaped android imageview components including bubble, star, heart, diamond.
 * [RoundedImageView](https://github.com/vinc3m1/RoundedImageView) - Easily round corners or create oval-shaped images with this popular library.
 * [Android StackBlur](https://github.com/kikoso/android-stackblur) - Dynamically blur images
 * [BlurKit for Android](https://github.com/wonderkiln/blurkit-android) -  Fast blur-behind layout that parallels iOS.
 * [Android Bootstrap](https://github.com/Bearded-Hen/Android-Bootstrap) - Bootstrap UI widgets
 * [PhotoView](https://github.com/chrisbanes/PhotoView) - ImageView that supports touch gestures
 * [ShowcaseView](https://github.com/amlcurran/ShowcaseView) - Highlight the best bits of your app
 * [FadingActionBar](https://github.com/ManuelPeinado/FadingActionBar) - Cool actionbar fade effect
 * [AndroidViewAnimations](https://github.com/daimajia/AndroidViewAnimations) - Easily apply common animations
 * [ProgressWheel](https://github.com/Todd-Davies/ProgressWheel) - Better progress bar
 * [SmoothProgressBar](https://github.com/castorflex/SmoothProgressBar) - Horizontal indeterminate progress
 * [CircularFillableLoaders](https://github.com/lopspower/CircularFillableLoaders) - Beautiful animated fillable loaders
 * [Rebound](http://facebook.github.io/rebound/) - Easy spring dynamics
 * [AndroidImageSlider](https://github.com/daimajia/AndroidImageSlider) - Animated image transitions
 * [FloatingActionButton](https://github.com/makovkastar/FloatingActionButton) - Material design floating buttons made easy
 * [Foursquare-CollectionPicker](https://github.com/anton46/Foursquare-CollectionPicker) - Item Picker which looks like Foursquare Tastes picker
 * [NexusDialog](https://github.com/dkharrat/NexusDialog) - Create form dialogs easily
 * [dialogplus](https://github.com/orhanobut/dialogplus) - Simple, easy dialogs
 * [Iconify](https://github.com/JoanZapata/android-iconify) - Easily embed icons into your app
 * [Android StepsView](https://github.com/anton46/Android-StepsView) - A library to create StepsView for Android
 * [PhotoView](https://github.com/chrisbanes/PhotoView) - A library to pinch zoom in and zoom out and double tap zoom for Android
 * [Android-Iconics](https://github.com/mikepenz/Android-Iconics) - Add many scalable and styleable icons into your app
 * [Scissors](https://github.com/lyft/scissors) - An easy image cropping library developed by Lyft.
 * [Material-SearchView](https://github.com/MiguelCatalan/MaterialSearchView) - Beautiful Material SearchView made simple.
 * [PersistentSearchBar](https://github.com/arimorty/floatingsearchview) - Implementation of a persistent search bar.
 * [Android Material Intro Screen](https://github.com/TangoAgency/material-intro-screen/) - Library for easily adding intro screen to app.
 * [SwipePicker](https://github.com/m4xp1/SwipePicker) - a widget for Android that allows the user to enter different values, such as: time, date, number, without additional dialog windows using the swipe gestures.

### Drawing

 * [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) - A powerful Android chart view / graph view library, supporting line- bar- pie- radar- bubble- and candlestick charts as well as scaling, dragging and animations.
 * [HoloGraphLibrary](https://github.com/Androguide/HoloGraphLibrary) - Newer graphing library
 * [EazeGraph](https://github.com/blackfizz/EazeGraph) - Another newer library with potential
 * [AndroidCharts](https://github.com/dacer/AndroidCharts) - Easy to use charts
 * [AndroidGraphView](http://android-graphview.org/) - library to create flexible and nice-looking diagrams.
 * [AndroidPlot](http://androidplot.com/docs/quickstart/) - plotting library for Android
 * [WilliamChart](https://github.com/diogobernardino/WilliamChart) - Flexible charting library with useful motion capabilities.
 * [HelloCharts](https://github.com/lecho/hellocharts-android) - Charts/graphs library for Android with support for scaling, scrolling and animations.
 * [Leonids](https://github.com/plattysoft/Leonids) - Simple and easy particle effects ([See Tutorial](http://www.plattysoft.com/2014/05/30/leonids-particle-system-lib/))
 * [Confetti](https://github.com/jinatonic/confetti) - Newer particle effects library. 
 * [Konfetti](https://github.com/DanielMartinus/Konfetti) - Alternative light-weight confetti particle system
 * [AChartEngine](http://jaxenter.com/effort-free-graphs-on-android-with-achartengine-46199.html) - This is a charting software library for Android applications

### Image Processing

* [AndroidPhotoFilters](https://github.com/zomato/androidphotofilters) - Library to create interesting effects on any image of your choice. Comes with prebuilt great sample effects.
* [android-gpuimage](https://github.com/CyberAgent/android-gpuimage) - Popular GPU Image Processing
* [android-image-filter](https://github.com/ragnraok/android-image-filter) - Older image filtering library
* [picasso-transformations](https://github.com/wasabeef/picasso-transformations) - Library for processing images via Picasso
* [glide-transformations](https://github.com/wasabeef/glide-transformations) - Process images via Glide
* [ImageEffectFilter](https://github.com/mnafian/ImageEffectFilter) - Sample code for processing images.
* [VidEffects](https://github.com/krazykira/VidEffects) - Apply manipulation effects to videos.

### Persistence

 * [[ActiveAndroid|ActiveAndroid-Guide]] - Not very fast, but quite convenient and proven over time solution.
 * [[DBFlow|DBFlow Guide]] - A robust, powerful, and very simple ORM android database library with annotation processing. One of the fastest write / read operations is the average update / delete speed. 
 * [greenDAO](https://github.com/greenrobot/greenDAO) - It is flexible and convenient to use one-to-many communication, but very unpleasant code generation, as a result of which your classes will be filled with a bunch of methods and comments. In addition, you need to connect the Gradle plug-in, which greatly increases the build time.
 * [SugarORM](http://satyan.github.io/sugar/) - Of the advantages can be noted ease of use, which is not enough in ORMLite, and that's it. Has a separate drawback associated with the approach to implementation - it is not "friendly" with Instant Run, so when working with it you have to disable it.
 * [RxCache](https://github.com/VictorAlbertos/RxCache) - Reactive caching library for Android
 * [Android-Orma](https://github.com/gfx/Android-Orma) - A type-safe ORM for Android as a wrapper of SQLiteDatabase
 * [ORMLite](http://ormlite.com/sqlite_java_android_orm.shtml) - It does not save much from the boilerplate code, however one of the fastest libraries out there is built-in caching and delayed initialization, good documentation. 
 * [SQLBrite](https://github.com/square/sqlbrite) - Lightweight wrapper around SQLiteOpenHelper
 * [[Cupboard|Easier-SQL-with-Cupboard]] - Popular take on SQL wrapper
 * [StorIO](https://github.com/pushtorefresh/storio) - Fresh take on a light SQL wrapper
 * [Realm](https://github.com/realm/realm-java) - Object orientated database, with very easy setup and developing. Excellent documentation. Is, perhaps, one of the best option for storing data on a mobile device at the moment, the minus can only be an increase in the size of the apk-file by 2.5 MB.
 * [NexusData](https://github.com/dkharrat/NexusData)
 * [Hawk](https://github.com/orhanobut/hawk) - Persistent secure key/value store
 * [Poetry](https://github.com/elastique/poetry) - Persist JSON directly into SQLite
 * [JDXA](http://softwaretree.com/v1/products/jdxa/jdxa.html) - The KISS ORM for Android - Simple, Non-intrusive, and Flexible
 * [Schematic](https://github.com/SimonVT/schematic) - Generate the SQLite and ContentProvider code
 * [AORM](https://github.com/Jamling/Android-ORM) - Simple ORM mapping, generate SQLite table
 * [Requery](https://github.com/requery/requery) - Supports different databases, rich functionality. 
 * [Room](https://developer.android.com/topic/libraries/architecture/room.html) - An interesting solution presented on Google I / O 2017 as optimal for working with the database on Android OS. Despite the fact that it is necessary to use explicit sql-requests, the library turned out to be quite convenient and I liked it personally. On performance is in the lead, so I would advise you to choose this particular library. Since this solution, submitted by Google, it will quickly become popular, and, therefore, there will be no problems with finding solutions to problems that occur along with it.

### Binding
 * [RecyclerViewBinding](https://github.com/radzio/android-data-binding-recyclerview) - Library for easily add recycler view data bindings.
 * [CommandDataBinding](https://github.com/radzio/android-data-binding-command) - Library for better handling onClick actions.

### Compatibility

 * [NineOldAndroids](http://nineoldandroids.com/) - Fully compatible animation library that works with all versions of Android. Widely used. [Download](https://github.com/JakeWharton/NineOldAndroids/zipball/master) and install as a [library project](https://imgur.com/a/N8baF).
 * [HoloEverywhere](https://github.com/Prototik/HoloEverywhere) - Backport Holo theme from Android 4.2 to 2.1+
 * [CropImage](https://github.com/biokys/cropimage) - Simple compatible cropping intent for images

### Scrolling and Parallax

This is a list of popular scrolling and parallax libraries:

* [QuickReturn](https://github.com/lawloretienne/QuickReturn) - Reveal or hide a header or footer as the list is scrolled in a direction. (**DEPRECATED**)
* [ParallaxPagerTransformer](https://github.com/xgc1986/ParallaxPagerTransformer) - A pager transformer for Android with parallax effect
* [ParallaxHeaderViewPager](https://github.com/kmshack/Android-ParallaxHeaderViewPager) - Another ViewPager with Parallax scrolling effects
* [Android-ObservableScrollView](https://github.com/ksoichiro/Android-ObservableScrollView) - Android library to observe scroll events on scrollable views.
* [Scrollable](https://github.com/noties/Scrollable) - Automatic scrolling logic when implementing scrolling tabs
* [ParallaxPager](https://github.com/prolificinteractive/ParallaxPager) - ViewPager with Parallax scrolling effects
* [android-parallax-recyclerview](https://github.com/kanytu/android-parallax-recyclerview) - An adapter which could be used to achieve a parallax effect on RecyclerView.
 
### Debugging

* [Stetho](http://facebook.github.io/stetho/) - A debug bridge for Android applications which could be used for multiple purposes not limited to Network Inspection, Database Inspection and Javascript Console.
* [Android Debug Database](https://github.com/amitshekhariitbhu/Android-Debug-Database) - Android Debug Database allows you to view databases and shared preferences directly in your browser in a very simple way.
* [Bugfender](https://github.com/bugfender/bugfender-android-sample/) - Cloud storage for your app logs, track user behaviour to find problems in your mobile apps.
* [Chuck](https://github.com/jgilfelt/chuck) - Chuck is a simple in-app HTTP inspector for Android OkHttp clients. Chuck intercepts and persists all HTTP requests and responses inside your application, and provides a UI for inspecting their content.
* [AnUitor](http://anuitor.scurab.com/) - UI debug tool for Android
* [RxJava2Debug](https://github.com/akaita/RxJava2Debug) - RxJava 2.x extension to provide meaningful Stack Traces

## Resources

Check out the following resources for finding libraries:

 * <http://android-arsenal.com>
 * [Wasabeef Core Libraries](https://github.com/wasabeef/awesome-android-libraries)
 * [Wasabeef UI Libraries](https://github.com/wasabeef/awesome-android-ui)
 * [Ultimate Android Library Reference](https://github.com/aritraroy/UltimateAndroidReference/blob/master/README.md)
 * [Snowdream Android Library Repository](https://snowdream.github.io/awesome-android/)
 * <http://appdevwiki.com/wiki/show/HomePage>
 * <http://www.libtastic.com>
 * [Android Libhunt](https://android.libhunt.com/)

## References

