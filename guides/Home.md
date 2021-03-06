# Android Guidenotes

Welcome to the open-source Android Guidenotes! Our goal is to become the **central crowdsourced resource** for complete and up-to-date practical Android developer guides for any topic. [[Just take me to the notes|Home#getting-started]]!

[![Teocci](http://i.imgur.com/aVmvzfC.png)](http://teocci.com)

We have Android guides for everyone whether you are a **beginner, intermediate or expert**. Want to learn how to [[use the ActionBar|Defining the ActionBar]] or the [[ins and outs of fragments|Creating and Using Fragments]]? We got that. Want to learn [[about automated unit testing|Unit Testing with Robolectric]] or how to [[build flexible user interfaces for multiple devices|Flexible User Interfaces]]? We got you covered. We don't waste time with the "theoretical approach" you might get from a book. We cover **exactly the things we use every day** as we are developing apps for contracts.

## Motivation

Ever been **frustrated finding information on outdated one-off blog posts and tutorials** that have long since become irrelevant? How many times have you been googling to find your answer only exists on an obscure **2 year old StackOverflow post**? We believe there's got to be a better way. Why not have the community work together to create useful and detailed documentation for every aspect of Android (or any platform)? There's absolutely no reason that we should have to make do with vague and outdated content anymore.

Read about our [[mission to change the way engineers learn new technologies|teocci-Goal]] and check out how you can [[get involved|teocci-Goal#how-do-i-help]]! In addition, we are at present a fledgling startup so if you like this guide and what we are trying to do, please consider following us on twitter [@teocci](https://twitter.com/teocci)!

## Overview

The Guidenotes below are **categorized by their topic**, so you can easily find guides on related topics whether that is views, styling, testing, or using sensors. If you see an error, incorrect explanation or deprecated solution, **why not contribute back** and make these guidenotes better for the next person? That in a nutshell is the core spirit of this initiative. Check out the [list of contributors](https://github.com/teocci/android_guides/blob/master/README.md#contributors) to this project.

**Disclaimer:** We have scoured the web endlessly for content while creating these guides and adapted content from many source including the [Google Official Docs](http://developer.android.com/guide/components/index.html), [Vogella Tutorials](http://www.vogella.com/android.html) and countless other sources that had hidden gems of information. At the bottom of each guide, there are citations for the content we used. **We don't claim the content is original** (although we did develop quite a bit ourselves), but unlike those other sources listed, it is freely community editable. We have openly adapted, modified and brought together this content from all the sources we could find for the benefit of every engineer.

Read more about [[us and our vision for teocci|teocci-Goal]]. If you want to **contribute to this guide**, please read the [[Contributing Guidelines]].

## Interested in Android Courses or Events?

Located in the San Francisco Bay Area and interested in learning with others in a more structured program? Check out our local [Android](http://www.meetup.com/Learning-Android-Development) or [iOS](http://www.meetup.com/Learning-iOS-Development-SF/) meetup events. We have free evening events and at-cost 1-day workshops to make learning social and connect you with others passionate about mobile.

If you are an experienced engineer with 2+ years of professional experience in software development and are serious about learning Android, check out our [free evening 8-week Android bootcamp](http://teocci.com/androidbootcamp). Learn how to build mobile apps while collaborating with other engineers. Find a role as an Android developer, work on solving important problems for non-profits, or launch your own app ideas to the store with our free 8-week evening accelerated mobile bootcamp.

**Not in the United States?** We are committed to bringing our unique form of high-quality technical classes to as many people as possible through a distributed and scalable approach to running local classes. Please [fill out our application of interest form](https://www.surveymonkey.com/r/teocci_interest_intake) and we’ll notify you as classes become available in your area powered by local organizers.

## Getting Started

**Totally new to Android?** Start here.

* [Getting Started as a Developer](http://courses.teocci.com/snippets/intro_to_android/non_coders) (New to programming?)
* [[Getting Started with Android|Beginning Android Resources]] (Detailed Post With Many Links)
* [Setting up Android Studio](http://goo.gl/X2SVFR) (Installation Slides) or [[Setting up IntelliJ IDEA]]
* [[Installing a Faster Emulator|Genymotion-2.0-Emulators-with-Google-Play-support]] (Genymotion Guide)
* [[Running Apps on Your Device]] (Hardware device setup)
* [Developing our First App Using Android Studio](http://goo.gl/8R7Mty) (Step-by-Step Todo App)
* [Architecture of Mobile Apps](http://goo.gl/AAsGLx) (Concept Slides)
* [[Mobile Screen Archetypes]] (Common mobile app screen categories)
* [[Todo App Guide|Basic Todo App Tutorial]] (Todo App steps in guide format)
* [[Sample Android Apps]] (Code repositories)
* [[Keeping Updated with Android]] (Podcasts, blogs, newsletters)
* [[Using Kotlin for Android development]] (Alternative syntax to Java)

**Debugging Android**. Debug and troubleshoot issues.

* [[Debugging Exceptions within your App]] (App crashing?)
* [Debugging Android App Slides](https://docs.google.com/presentation/d/1DUigTm6Uh43vatHkB4rFkVVIt1zf7zB7Z5tpGTy2oFY/edit?usp=sharing)
* [[Troubleshooting Common Issues]] (Running into problems?)

**External Resources**. Great external content to explore.

* [[Android Resources List|Beginning Android Resources#beginning-android-resources]]
* [Google Android Interactive Codelabs](https://codelabs.developers.google.com/?cat=Android)
* [Google Android Glossary](https://developers.google.com/android/for-all/vocab-words/) (Defining Common Terms)
* [Android Learning Resources](https://github.com/CodementorIO/Android-Learning-Resources)
* [[Free Android Curriculum]] (Additional Android resources and slides)

**Using Eclipse?** See below.

* [Setting up Eclipse ADT](http://goo.gl/Ml9YN) (Detailed Slides)
* [Developing our First App Using Eclipse ADT](http://goo.gl/pBKfYP) (Step-by-Step Todo App)
* [[Troubleshooting Eclipse Issues]] (Running into eclipse problems?)

## Structure

Exploring the core of app development:

* [[Using Context]] (What is context and how is it used?)
* [[Android Directory Structure]] (Files and Folders for Android apps)
* [[Organizing your Source Files]] (Cleaning up source of your apps)
* [[Architecture of Android Apps]] (Understanding how apps should be structured)
* [[Understanding App Resources]] (Understanding Strings and Resources)
* [[Understanding the Activity Lifecycle|Activity Lifecycle]] (How does an activity work?)
* [[Handling Configuration Changes]] (Screen Rotation)
* [[Migrating to the AppCompat Library]] (Using the Support Libraries)
* [[App Permissions|Understanding App Permissions]] (How to request the permissions you need)
* [[Managing Runtime Permissions with PermissionsDispatcher]]
* [[Replacing Enums with Enumerated Annotations]] (StringDef, IntDef for validated types)

## Views and Layouts

Exploring the gritty details of views, layout, styling and common UI patterns:

* [[Constructing View Layouts]] (How to layout views)
* [[Defining Views and their Attributes]] (Gravity, Margin, Padding, etc)
* [[Working with the TextView]] (Properties, Drawables, Custom Fonts)
* [[Working with the EditText]] (Properties)
* [[Working with the ImageView]] (Drawables, Size and Scale, Density, Raw Bitmaps)
* [[Working with Input Views]] (Spinner, RatingBar, etc)
* [[Working with the Soft Keyboard]]
* [[Working with the WebView]]
* [[Working with the ScrollView]]
* [[Applying Data Binding for Views]] (Data binding library)

### Designing and Styling Views

* [[Drawables]] (and how to polish UI views)
* [[Styles and Themes]] (Consolidating view styles)
* [[Animations]] (Animating views, layouts, activities and more)
* [[Polishing a UI Tips and Tools]] (Links to key resources)
* [[Android Design Guidelines]] (Overview of Android design standards)
* [[Styling UI Screens FAQ]] (Answers to common questions around building screens)
* [[Cloning a Login Screen Layout Guide]] (Creating attractive UIs, Q&A)
* [[Developing Custom Themes]] (Integrating drawables, styles and themes)
* [[Material Design Primer]] (Lollipop Design Overview)
* [[Dynamic Color using Palettes]] (Adaptive colors, Android 5.0)
* [[Ripple Animation]] (Android 5.0)
* [[Shared Element Activity Transition]] (Android 5.0)
* [[Circular Reveal Animation]] (Android 5.0)
* [[Design Support Library]] (Material Design Library)
* [[Chrome Custom Tabs]]

### AdapterViews

* [[Using an ArrayAdapter with ListView]] (with custom list items)
* [[Endless Scrolling with AdapterViews and RecyclerView]] (Infinite pagination)
* [[Implementing Pull to Refresh Guide]]
* [[Implementing a Horizontal ListView Guide]] (Scrolls horizontally)
* [[Implementing a Heterogenous ListView]] (with different item types)
* [[Using the RecyclerView]] (Android 5.0)
* [[Heterogenous Layouts inside RecyclerView]] (Android 5.0)
* [[Using the CardView]] (Android 5.0)
* [[Using a BaseAdapter with ListView]] (alternate to ArrayAdapter)

### Custom Views

* [[Basic Painting with Views]] (Simple drawing app tutorial)
* [[Defining Custom Views]] (**Needs Attention**)
* [[Extending SurfaceView]] (**Needs Attention**)
* [[Drawing with OpenGL and GLSurfaceView]] (**Needs Attention**)
* [[Building a Custom Animated Progress Bar|Progress-Bar-Custom-View]] (Exercise)

## Interaction

Exploring how to allow user interaction and navigation within an app:

* [[View Event Listeners|Basic Event Listeners]] (Clicks, Key Presses, Updates)
* [[Creating Custom Listeners]] (Defining, setting and triggering events)
* [[Displaying Toasts]] (Quick notices and includes custom views)
* [[Displaying the Snackbar]] (Quick notices with actions)
* [[Exploring the ActionBar|Defining the ActionBar]] (Includes adding ActionItems)
* [[Extended ActionBar Guide]] (Split-bar, Custom ActionBar, etc)
* [[Gestures and Touch Events]] (Swipe, Shake, or Dragging Events)
* [[Menus and Popups]] (Context Menu, PopupMenu, PopupWindow)
* [[Dialogs with DialogFragment|Using DialogFragment]] (Displaying a content overlay)
* [[Implementing a Rate Me Feature]] (For getting Play Store ratings)
* [[Repeating Periodic Tasks]] (Handler, ScheduledThreadPoolExecutor)
* [[Using the App Toolbar]] (ActionBar Replacement)
* [[Floating Action Buttons]] (Android 5.0, Promoted Action)
* [[Handling Scrolls with CoordinatorLayout]] (Collapsing toolbars)

## Navigation

* [[Navigating Activities with Intents|Using Intents to Create Flows]] (Communicating between Activities)
* [[Common Navigation Paradigms]] (Tabs, Swipe-able Views, Pull-out Drawer)
* [[Common Implicit Intents]] (Making a Call, Sending a Text, Opening a URL)
* [[Navigation and Task Stacks]] (Controlling the behavior of the task stack)
* [[Sharing Content with Intents]] (and ShareActionProvider)
* [[Using Parcelable]] (Pass data fast between activities)
* [[Book Search Tutorial]] (Toolbar with SearchView and sharing content)

## Networking and Models

Diving into the networking and model layers for data-driven apps:

* [[Sending and Managing Network Requests]] (API Calls, Image Downloading)
* [[Displaying Images with the Picasso Library]] (Remote Image Downloading)
* [[Converting JSON to Models]] (JSON to Objects Deserialization)
* [[Leveraging the Gson Library]] (JSON deserialization library)
* [[Creating and Executing Async Tasks]] (Long-running Background Tasks)
* [[Handling ProgressBars]] (with Long-Running Tasks)
* [[Rotten Tomatoes Networking Tutorial]]
* [[Networking with the Volley Library]]
* [[Displaying Images with the Fresco Library]]
* [[Building Data-driven Apps with Parse]]
* [[Configuring a Parse Server]]
* [[Building Simple Chat Client with Parse]]
* [[Troubleshooting Common Issues with Parse]]
* [[Consuming APIs with Retrofit]]
* [[Sending and Receiving Data with Sockets]]
* [[Building Data driven Apps with Firebase]]

## Persistence

Exploring the strategies for data persistence:

* [[Persisting Data to the Device]] (Preferences, Files, SQLite, ORMs)
* [[ActiveAndroid ORM Guide|ActiveAndroid Guide]] (and Q&A)
* [[Storing and Accessing SharedPreferences]]
* [[Local Databases with SQLiteOpenHelper]]
* [[Populating a ListView with a CursorAdapter]]
* [[Settings with PreferenceFragment]]
* [[Loading Contacts with Content Providers]] (CursorLoader, LoaderManager)
* [[Interacting with the Calendar]] (CalendarProvider)
* [[Creating Content Providers]] (**Needs Attention**)
* [[Clean Persistence with Sugar ORM]] (Installation, Queries, Migrations)
* [[DBFlow ORM Guide|DBFlow-Guide]] (Installation, Queries)
* [[Easier SQL with Cupboard]]
* [[Powerful Persistence with JDXA ORM]]

## Fragments

Understanding how to build powerful and flexible views using Fragments:

* [[Creating and Using Fragments]]
* [[Displaying a DialogFragment|Using DialogFragment]]
* [[Google Play Style Tabs using TabLayout]]
* [[Sliding Tabs with PagerSlidingTabStrip]]
* [[ViewPager with FragmentPagerAdapter]]
* [[Fragment Navigation Drawer]]
* [[Flexible User Interfaces]] (with Fragments)
* [[ActionBar Tabs with Fragments]] (Deprecated)

## Sensors and Device SDKs

Exploring sensors and components available via the Android SDK:

* [[Accessing the Camera and Stored Media]] (Camera, Photo Roll)
* [[Retrieving Location with LocationServices API]] (Location)
* [[Listening to Sensors using SensorManager]] (Light, Accelerometer)
* [[Audio Playback and Recording]] (MediaPlayer)
* [[Video Playback and Recording]] (VideoView)
* [[Google Maps Setup Guide|Google Maps Fragment Guide]] (and [[Setup Genymotion|Google-Maps-Fragment-Guide#installing-genymotion]])
* [[Google Maps API v2 Usage]] (Markers, InfoWindow)
* [[Connectivity using the Bluetooth API]] (**Needs Attention**)
* [[Streaming Youtube Videos with YouTubePlayerView]]

## Services

Digging into how to run background services or leverage Android system services:

* [[Starting Background Services]] (with IntentService and Receivers)
* [[Notifications]] (Persistent Notices on the Dashboard)
* [[Push Messaging]] (Parse Push and Broadcast Receiver Overview)
* [[Google Cloud Messaging]] (Detailed GCM Implementation)
* [[Real-time Messaging]] (**Needs Attention**)
* [[Managing Threads and Custom Services]] (Looper, Handler, ThreadPoolExecutor)

## Testing

Covering automated testing frameworks and tools for Android:

* [[Android Testing Options]]
* [[Unit Testing with Robolectric]]
* [[UI Testing with Espresso]]
* [[UI Testing with Robotium]] (**Needs Attention**)
* [[Android Testing Framework]] (**Needs Attention**)

## Libraries

Covers usage of more advanced third-party libraries and SDKs that save time and improve the maintainability of your code:

* [[Must Have Libraries]] (Networking, Persistence, Compatibility, Convenience, etc)
* [[Popular External Tools]] (Analytics, Crash Reporting)
* [[Dependency Injection with Dagger 2]]
* [[Reducing View Boilerplate with Butterknife]] (View Annotations)
* [[Communicating with an Event Bus]] (Using EventBus to publish and receive events)
* [[Using Parceler]] (Creating Parcelable objects)
* [[RxJava Intro|RxJava]] (Intro to Reactive programming)
* [[RxJava and RxBinding]] (Reactive programming with Android views)

## Production

Covers guides specifically related to developing and publishing robust Android applications:

* [Publishing to the Play Store](http://goo.gl/mUlGL1) (Slides)
* [[Publishing with Android Studio|Publishing-to-the-Play-Store]]
* [[Debugging and Profiling Apps]] (**Needs Attention**)
* [Android Best Practices](https://github.com/futurice/android-best-practices)

## Workflow

Focused on issues like deployment, dependency management, etc:

* [[Getting Started with Gradle]]
* [[Using Android Studio]]
* [[Installing Android SDK Tools]]
* [[Building Gradle Projects with Jenkins CI]]
* [[Setting up Travis CI]]
* [[Collaborating on Projects with Git]] (Git, Team)
* [[Presenting an Android Device]] (Cast Device to Laptop)
* [[Recording Video of an Android Device]]
* [[Configuring ProGuard]]
* [[Lambda Expressions]] (Retrolambda and Java 8)

## Contributing

* [[Contributing back to Android]]
* [[Building your own Android Library]]
* [[Open Source projects for Android Development]]
