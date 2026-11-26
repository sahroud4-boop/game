# Hamle Tasi Android wrapper

This is a lightweight native Android WebView shell for the offline HTML game.
The GitHub Actions workflow copies the root HTML game into the APK assets and
builds a debug APK using Java 17 and Gradle 8.7. Android Studio is not required.

Build:
- Run the workflow named **Build Hamle Tasi Android APK** from the Actions tab.
- Download the **HamleTasi-Android-debug** artifact from the completed run.
- Extract the ZIP to get `app-debug.apk`.

The game stores progress locally in WebView DOM storage. This is a debug APK;
a release APK should be signed before public distribution.
