Translating
===========
[You can help translate here][1]. If your language isn't on the list, open an
issue and I can add it.

Building
========
To build you will need:

 * A Java compiler compatible with Java 1.6
 * The Android SDK with platform 15 (Android 4.0.3) installed

Building from command-line
--------------------------
 * `android update project --path .` to generate local.properties
 * `ant debug` to build the APK at bin/VanillaMusic-debug.apk
 * Optional: `ant installd` to install the APK to a connected device

Building from Eclipse
---------------------
You can also build from Eclipse. Create a new Android Project, choosing "Create
project from existing source", then set the compiler compliance level to 1.6
in project settings.

Documentation
=============
Javadocs can be generated using `ant doc`

[![Ohloh project page][3]][2]

  [1]: http://crowdin.net/project/vanilla-music/invite
  [2]: https://www.ohloh.net/p/vanilla-music?ref=sample
  [3]: https://www.ohloh.net/p/vanilla-music/widgets/project_thin_badge.gif
