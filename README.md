```kotlin
data class AndroidDeveloper(val firstName: String,
                            val lastName: String,
                            val age: Int,
                            val school: String?,
                            val company: String?,
                            val location: String,
                            val social: ArrayList<String>?)

val androidDeveloper = AndroidDeveloper(
                firstName = "Furkan",
                lastName = "Aşkın",
                age = 23,
                school = "Istanbul Kultur University",
                company = "Kuka Apps",
                location = "Istanbul, TR",
                social = arrayListOf("https://medium.com/@askinfurkan", "https://twitter.com/askinnfurkan"))
```
