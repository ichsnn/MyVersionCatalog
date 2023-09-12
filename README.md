#  Gradle Versions Catalog

reference: [Migrate your build to version catalogs](https://developer.android.com/build/migrate-to-catalogs#migrate-plugins)

There is an issue with the Gradle version lower than 8.1. The issue is [Version catalog accessors for plugin aliases shown as errors in IDE Kotlin script editor](https://github.com/gradle/gradle/issues/22797). So to fix it just change or upgrade the Gradle version to 8.1+, by checking the project structure settings (File > Project Structure > Project > Gradle Version)
