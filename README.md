<div align="center">

  <h1>Heading</h1>
  
  <p>
    Detail! 
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
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Screenshots](#camera-screenshots)
  * [Tech Stack](#space_invader-tech-stack)
  * [Color Reference](#art-color-reference)
- [Architecture](#briefcase-Architecture)
- [Architecture Diagram](#triangular_ruler-archarchitecture-diagram)
- [FAQ](#grey_question-faq)

  

<!-- About the Project -->
## :star2: About the Project


<!-- Screenshots -->
### :camera: Screenshots

<div align="center"> 
  <img src="https://placehold.co/600x400?text=Your+Screenshot+here" alt="screenshot" />
</div>


<!-- TechStack -->
### :space_invader: Tech Stack
    
* [Kotlin]()
* [Compose]()
* [Hilt](https://developer.android.com/training/dependency-injection/hilt-android)
* [State]()
* [Moshi]()
* [Coroutines](https://developer.android.com/kotlin/coroutines) 
* [Retrofit](https://square.github.io/retrofit/) 
* [Mockk for Testing]()
* [Custom Paging]()


<!-- Color Reference -->
### :art: Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Primary Color | ![#222831](https://via.placeholder.com/10/222831?text=+) #222831 |
| Secondary Color | ![#393E46](https://via.placeholder.com/10/393E46?text=+) #393E46 |
| Accent Color | ![#00ADB5](https://via.placeholder.com/10/00ADB5?text=+) #00ADB5 |
| Text Color | ![#EEEEEE](https://via.placeholder.com/10/EEEEEE?text=+) #EEEEEE |


<!-- Architecture -->
## :briefcase: Architecture

<!-- App Module -->
### :bangbang: App Module

This project uses Yarn as package manager

<!-- BuildSrc Module -->
### :bangbang: BuildSrc Module

This project uses Yarn as package manager

<!-- Architecture Diagram -->
## :triangular_ruler: Architecture Diagram

<div align="center"> 
  <img src="https://placehold.co/600x400?text=Your+Screenshot+here" alt="screenshot" />
</div>

<!-- FAQ -->
## :grey_question: FAQ

- Question 1

  + Answer 1

- Question 2

  + Answer 2
  
<!-- Project tree -->
## 🌲 **Project tree**

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
## :warning: License

Distributed under the no License. See LICENSE.txt for more information.


<!-- Contact -->
## :handshake: Contact

Syed Ammar Sohail - ammarsohail321@gmail.com


<!-- Acknowledgments -->
## :gem: Acknowledgements

Use this section to mention useful resources and libraries that you have used in your projects.

 - [Shields.io](https://shields.io/)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#travel--places)
 - [Readme Template](https://github.com/othneildrew/Best-README-Template)
