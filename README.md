# Final Project - *My Hobby*

**My Hobby app** is an android app that allows a user to view the hobbies one is interested in, and connect with people who share the same hobbies. 
Users can upload the videos/images/recordings.

Time spent: **** hours spent in total

## User Stories

The following **required** functionality is completed:

* [x]	User can **sign in to the app** using OAuth login, via Facebook, Google+ or Email.
* [x]	User can **view videos/media from their home timeline**
  * [x] User is displayed the username, name, and body for each recent activity.
  * [x] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each media uploaded. 
  * [x] User can view more media as they scroll with [infinite pagination](http://guides.codepath.com/android/Endless-Scrolling-with-AdapterViews-and-RecyclerView). Number of tweets is unlimited.
* [x] User can **compose and upload a new media**
  * [x] User can click a “Compose” icon in the Action Bar on the top right
  * [x] User can then enter a new media and post this to Facebook
  * [x] User is taken back to home timeline with **new media visible** in timeline

The following **optional** features are implemented:

* [x] User can **click a link within the app ** on hobby details view. The click will launch the web browser with relevant page opened.
* [x] User can **pull down to refresh media timeline**
* [x] Persisted in SQLite information that the user post on the app are.
* [x] Refreshed on every application launch. While "live data" is displayed when app can get it from Facebook API, it is also saved for use in offline mode.
* [x] User can tap a media to **open a detailed media view in browser**
* [x] User can **select share from detail view to respond to a media**
* [x] Improve the user interface and theme the app to feel "app branded"

The following **bonus** features are implemented:

* [x] User can see embedded image media within the media detail view
* [x] User can watch embedded video within the media detail view
* [x] Compose a media  functionality is build using modal overlay
* [x] Use Parcelable instead of Serializable using the popular [Parceler library](http://guides.codepath.com/android/Using-Parceler).
* [x] [Leverage RecyclerView](http://guides.codepath.com/android/Using-the-RecyclerView) as a replacement for the ListView and ArrayAdapter for all lists of tweets.
* [x] Move the "Compose" action to a [FloatingActionButton](https://github.com/codepath/android_guides/wiki/Floating-Action-Buttons) instead of on the AppBar.
* [ ] On the Home timeline, leverage the [CoordinatorLayout](http://guides.codepath.com/android/Handling-Scrolls-with-CoordinatorLayout#responding-to-scroll-events) to apply scrolling behavior that [hides / shows the toolbar](http://guides.codepath.com/android/Using-the-App-ToolBar#reacting-to-scroll).
* [x] Replace all icon drawables and other static image assets with [vector drawables](http://guides.codepath.com/android/Drawables#vector-drawables) where appropriate.
* [x] Leverages the [data binding support module](http://guides.codepath.com/android/Applying-Data-Binding-for-Views) to bind data into layout templates.
* [x] Replace Picasso with [Glide](http://inthecheesefactory.com/blog/get-to-know-glide-recommended-by-google/en) for more efficient image rendering.
* [ ] Enable your app to [receive implicit intents](http://guides.codepath.com/android/Using-Intents-to-Create-Flows#receiving-implicit-intents) from other apps.  When a link is shared from a web browser, it should pre-fill the text and title of the web page when composing a tweet.

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:



<[Video Walkthrough} />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Picasso](http://square.github.io/picasso/) - Image loading and caching library for Android
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2016] [Swati Singh]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
