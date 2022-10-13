<div align="center">

  <h1>Select a Car</h1>
  
  <p>
    Car selection app by picking up data of manufacturer, main type and build date 
  </p>
  
  
<!-- Badges -->
![kotlin](https://img.shields.io/badge/Kotlin-1.6.10-white.svg?style=for-the-badge&labelColor=7E57C2)
![compose](https://img.shields.io/badge/Compose-1.2.0-white.svg?style=for-the-badge&labelColor=5C6BC0)
![Hilt](https://img.shields.io/badge/Hilt-2.40-white.svg?style=for-the-badge&labelColor=42A5F5)
![Coroutines](https://img.shields.io/badge/Coroutines-1.6.0-white.svg?style=for-the-badge&labelColor=26C6DA)
![minSdkVersion](https://img.shields.io/badge/MinSdkVersion-21-white.svg?style=for-the-badge&labelColor=26A69A)
![targetSdkVersion](https://img.shields.io/badge/TargetSdkVersion-31-white.svg?style=for-the-badge&labelColor=66BB6A)
![MVI](https://img.shields.io/badge/CleanCode-MVI-white.svg?style=for-the-badge&labelColor=FFCA28)
   
</div>

<br />

<!-- Table of Contents -->
# Table of Contents

- [About the Project](#about-the-project)
  * [Screenshots](#screenshots)
  * [Tech Stack](#tech-stack)
  * [Color Reference](#color-reference)
- [Architecture](#Architecture)
- [Architecture Diagram](#Architecture-Diagram)
- [FAQ](#faq)

  

<!-- About the Project -->
## About the Project


<!-- Screenshots -->
### Screenshots

<div align="center"> 
  <img src="https://drive.google.com/uc?export=view&id=1oG-oo9OEOGlT-hPSv3v52t6U2Jj_7RLN" alt="screenshot" />
</div>


<!-- TechStack -->
### Tech Stack
    
* [Kotlin](https://kotlinlang.org/docs/home.html)
* [Compose](https://developer.android.com/jetpack/compose/documentation)
* [Hilt](https://developer.android.com/training/dependency-injection/hilt-android)
* [State](https://developer.android.com/reference/kotlin/androidx/compose/runtime/MutableState)
* [Moshi](https://github.com/square/moshi)
* [Coroutines](https://developer.android.com/kotlin/coroutines) 
* [Retrofit](https://square.github.io/retrofit/) 
* [Mockk](https://mockk.io/)
* [Truth](https://truth.dev/)
* [Custom Pagination]()

Mutable state is used in this project instead of Flows.


## Installation

**Download:**

    $ git clone https://github.com/ishida/android-studio-project-with-lvl-sample

Import Project by Android Studio Menu > File > Import Project.

**Release:**

This app is production ready only need to add your keystore path, password and alias in keystore.properties located under the app folder.

<!-- Color Reference -->
### Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Primary Color | ![#222831](https://via.placeholder.com/10/222831?text=+) #222831 |
| Secondary Color | ![#393E46](https://via.placeholder.com/10/393E46?text=+) #393E46 |
| Accent Color | ![#00ADB5](https://via.placeholder.com/10/00ADB5?text=+) #00ADB5 |
| Text Color | ![#EEEEEE](https://via.placeholder.com/10/EEEEEE?text=+) #EEEEEE |


<!-- Architecture -->
## Architecture

**AppModule:**

Used layer-base clean architecture in which include data, domain and presentation layer.

- **Data layer -** Manages application data eg. retrieve data from the network, manage local data cache

- **Domain layer -** Contains business logic with separate usecases

- **Presentation layer -** Presents data to a screen and handle user interactions

**BuildSrc:**

Puts every dependencies in one place with respect to its classes, and use it by calling the dependency with its class.


<!-- Architecture Diagram -->
## Architecture Diagram

<div align="center"> 
  <img src="https://drive.google.com/uc?export=view&id=1oG-oo9OEOGlT-hPSv3v52t6U2Jj_7RLN" alt="screenshot" />
</div>


<!-- FAQ -->
## FAQ

- Question 1

  + Answer 1

- Question 2

  + Answer 2
  
  
<!-- Project tree -->
## Project tree

```text
.
├── CarApp
├── app
    ├── carapp
        ├── carSelect
            ├── data
                ├── di
                    ├── CarDataModule
                ├── intercepter
                    ├── QueryInterceptor
                ├── mapper
                    ├── CarMapper.kt
                ├── remote
                    ├── dto
                        ├── CarResponse
                    ├── CarApi
                ├── repository
                    ├── CarRepositoryImp
            ├── domain
                ├── di
                    ├── CarDomainModule
                ├── model
                    ├── Type
                ├── repository
                    ├── CarRepository
                ├── usecase
                    ├── BuiltDataUsecase
                    ├── CarUseCase
                    ├── MainTypeUsecase
                    ├── ManufacturerUsecase
            ├── presentation
                ├── component
                    ├── ActionAppBar.kt
                    ├── ComposeBorderText.kt
                    ├── ComposeButton.kt
                    ├── ComposeTextWithBackground.kt
                    ├── ComposeVerticalList.kt
                    ├── DummyList.kt
                    ├── LinePlaceHolder.kt
                    ├── SearchTextField.kt
                    ├── ShimmerAnimation.kt
                ├── CarEvent.kt
                ├── CarScreen.kt
                ├── CarSummaryScreen.kt
                ├── carUiState
                ├── CarViewModel
                ├── sheetContentScreen.kt
            ├── utils
                ├── DefaultPaginator
                ├── Paginator
                ├── UiEvent
                ├── UiText
        ├── ui
            ├── theme
                ├── Color.kt
                ├── Dimensions.kt
                ├── FontSize.kt
                ├── Shape.kt
                ├── Theme.kt
                ├── Type.kt
        ├── CarApp
        ├── MainActivity
├── buildSrc
    ├── AndroidX
    ├── Build
    ├── Compose
    ├── Coroutines
    ├── DaggerHilt
    ├── Google
    ├── Kotlin
    ├── Moshi
    ├── ProjectConfig
    ├── Retrofit
    ├── Testing
└── .gitignore

```  


<!-- License -->
## License

Distributed under the no License. See LICENSE.txt for more information.


<!-- Contact -->
## Contact

Syed Ammar Sohail - ammarsohail321@gmail.com


<!-- Acknowledgments -->
## Acknowledgements

Use this section to mention useful resources and libraries that you have used in your projects.

 - [Shields.io](https://shields.io/)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#travel--places)
 - [Readme Template](https://github.com/othneildrew/Best-README-Template)
