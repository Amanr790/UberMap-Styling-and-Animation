Uber Styled Map with Path Animation
===================================================

This sample goes hand in hand with a tutorial for the Google Maps Android API:
[Adding a Styled Map](https://developers.google.com/maps/documentation/android-api/styling).

![](Media/UberMapStyle.gif)

Getting started
---------------

This sample uses the Gradle build system.

1. Download the samples by cloning this repository or downloading an archived
  snapshot. (See the options at the top of the page.)
1. In Android Studio, create a new project and choose the "Import non-Android Studio project" or
  "Import Project" option.
1. If prompted for a gradle configuration, accept the default settings.
  Alternatively use the "gradlew build" command to build the project directly.
1. Add your API key to your app's `gradle.properties` file and in MapsAnimatorRaw Activities getDirectionsUrl method .
  (For information on getting an API key, see the
  [documentation](https://developers.google.com/maps/documentation/android-api/signup).)
1. You can do some changes in the map by importing json file present at raw folder at Map Styling Wizard :
[Map Styling Wizard](https://mapstyle.withgoogle.com/)
1. The style json and static Map Url is present in the Files folder. 

Note
----
Google's Billing account will be required for directions API to work  