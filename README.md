<div align="center"> <h1>👋 Hi! I'm Betowalker</h1> </div> 

```kotlin
/**
 * 👤 Roberto Ramirez Rios (betowalker)
 * 📱 Native Android Developer
 * 🌎 Puebla, Mexico
 */

object BetowalkerProfile {
    val aboutMe = "Native Android developer with 3 years of experience building innovative and high-performing mobile
        applications. Passionate about technology and always eager to learn new tools, frameworks, and trends in
        mobile development. Specialized in Kotlin, Jetpack Compose, and modern architectures, I strive to
        continuously improve the quality and user experience in every project.".trimIndent()

    data class Contact(
        val email: String,
        val location: String,
        val linkedin: String,
        val googleDev: String
    )

    val contact = Contact(
        email = "roberto.ramirez162627@gmail.com",
        location = "Puebla, Mexico",
        linkedin = "https://www.linkedin.com/in/roberto-ramirez-rios-033825238/",
        googleDev = "https://developers.google.com/profile/u/betowalker/edit?authuser=1&hl=es-419"
    )

    val technicalSkills = listOf(
        "Kotlin", "Jetpack Compose", "Java", "Git/GitHub",
        "JavaScript", "PHP", "MySQL", "C/C++"
    )

    val softSkills = listOf(
        "Teamwork", "Adaptability", "Problem Solving", "Communication",
        "Continuous Learning", "Proactivity"
    )

    val education = "Software Engineer - UPAEP (2019-2024)"
    val languages = listOf("Spanish (Native)", "English (Intermediate)")

    fun printProfile() {
        println("About Me: $aboutMe")
        println("Technical Skills: ${technicalSkills.joinToString()}")
        println("Soft Skills: ${softSkills.joinToString()}")
        println("Education: $education")
        println("Languages: ${languages.joinToString()}")
        println("Contact: ${contact.email} | ${contact.location}")
        println("LinkedIn: ${contact.linkedin}")
        println("Google Developers: ${contact.googleDev}")
    }
}

fun main() {
    BetowalkerProfile.printProfile()
}
```
## Technical Skills

- **Kotlin** ![Kotlin](https://img.shields.io/badge/Kotlin-white?logo=kotlin)
- **Jetpack Compose** ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?logo=jetpackcompose&logoColor=white)
- **Java** ![Java](https://img.shields.io/badge/Java-red?logo=java)
- **Git/GitHub** ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github)
- **JavaScript** ![JavaScript](https://img.shields.io/badge/JavaScript-black?logo=javascript)
- **PHP** ![PHP](https://img.shields.io/badge/PHP-white?logo=php)
- **MySQL** ![MySQL](https://img.shields.io/badge/MySQL-white?logo=mysql)
- **C/C++** ![C/C++](https://img.shields.io/badge/C%2FC++-00599C?logo=cplusplus&logoColor=white)

## Contact

- Email: roberto.ramirez162627@gmail.com
- Location: Puebla, Mexico
- [LinkedIn](https://www.linkedin.com/in/roberto-ramirez-rios-033825238/)
- [Google Developers Profile](https://developers.google.com/profile/u/betowalker/edit?authuser=1&hl=es-419)

---
