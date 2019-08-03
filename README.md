# SharedPreferencesStoryDelegate
Property delegate for store in SharedPreferences

## Usage: 
```kotlin
object Settings {
    var storedVariable: Long by SharedPreferencesStoreDelegate("VARIABLE1", 283)
    val readOnlyVariable: String by SharedPreferencesStoreDelegate("VARIABLE2", "defaultValue")
    
    var storedStringList: List<String> by SharedPreferencesStoreDelegateList("VARIABLE_LIST1", emptyList(), String::class)
}
```
