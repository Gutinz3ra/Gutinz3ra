Hi there, thanks for stopping by, this is **Gutinz3ra**.



```Kotlin
data class gutinzera(
     val askMeAbout: List<String> = listOf(
       "Kotlin", "Java" "Android Studio", "JDK"
     )
     val toLearn: () -> Unit = {
       "Jetpack Compose" to "Future"
     }
     val dailyLife: Unit = (0..end).reduce { acc, new ->
        study(new)
        coding(new)
        project(new)
        sumUp(acc) + haveFun(new)
     }
)
