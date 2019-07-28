# SharedPreferencesStoryDelegate
Property delegate for store in SharedPreferences

## Usage: 
```kotlin
object Settings {
    var storedVariable: Long by SharedPreferencesStoreDelegate("VARIABLE2", 283)
    val readOnlyVariable: String by SharedPreferencesStoreDelegate("VARIABLE1", "defaultValue")
}
```
