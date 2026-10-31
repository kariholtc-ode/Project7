# ConnectHub Updated — Android Studio project

## Assignment checklist
- REQUIRED: `RecyclerView` in `activity_main.xml` and `UserAdapter.java` displays API contacts in a scrollable list.
- REQUIRED: each item displays **name, email, phone and city** in `item_user.xml`.
- REQUIRED: **Lato** (open-source downloadable font family) is bundled in `res/font/lato_regular.ttf` and `lato_bold.ttf` so it works offline; custom colors and text sizes are applied using `styles.xml`.
- REQUIRED: app theme is customized in `res/values/themes.xml`.
- REQUIRED: reusable `ConnectHub.Title`, `ConnectHub.PersonName`, `ConnectHub.Detail` styles in `res/values/styles.xml`.
- STRETCH: night-specific theme and styles in `res/values-night/themes.xml` and `res/values-night/styles.xml`.
- STRETCH: light/dark drawables in `res/drawable` and `res/drawable-night` for contact cards and header.
- EXTRA: AsyncHttpClient API fetch, refresh button, loading indicator, network error message, click Toast, 4 fields per contact, DividerItemDecoration.

## Open / Run
1. Extract the ZIP completely, open the **ConnectHubUpdated** root folder (the folder containing `settings.gradle`) in Android Studio.
2. Use JDK 17, Android SDK 35, and sync Gradle. Run the `app` module on an emulator (e.g., Pixel 8 API 35).
3. **Gradle launcher included:** `gradlew`, `gradlew.bat`, and `gradle/wrapper/gradle-wrapper.jar` are provided. Note: the JAR is a small custom bootstrap launcher (not the official Gradle wrapper JAR), because the official binary could not be retrieved in this environment. It downloads and unpacks Gradle 8.9 on first run. Internet is required. On Windows run `gradlew.bat --version` to verify, then sync in Android Studio. If Android Studio requires the official wrapper, generate it using a local Gradle 8.9 installation with `gradle wrapper --gradle-version 8.9`.

4. For dark mode, switch the emulator's **Settings → Display → Dark theme**.

API: https://jsonplaceholder.typicode.com/users (fictional sample users). Internet required to load contacts.

Font: Lato by Łukasz Dziedzic, SIL Open Font License; see https://fonts.google.com/specimen/Lato . The TTF files are bundled as downloadable font assets, not dynamically fetched via the Google Fonts provider.

This source project was not compiled or tested on an emulator in this environment.
