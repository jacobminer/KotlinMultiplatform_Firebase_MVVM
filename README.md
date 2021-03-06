# Kotlin-Multiplatform MVVM Firebase (Android & iOS)
![kotlin-version](https://img.shields.io/badge/kotlin-1.3.50-orange)
<a target="_blank" href="https://androidweekly.net/issues/issue-410"><img src="https://androidweekly.net/issues/issue-410/badge"></a>

Example of application using Kotlin Multiplatform and MVVM pattern for both platforms (Android & iOS) and FirestoreKMP to get data from Firebase. To achieve it the libraries used are:

- [FirestoreKMP](https://github.com/touchlab/FirestoreKMP): Library wrapping the Firestore SDK for Kotlin Multiplatform with clients for Android and iOS. Shared common code can run methods that get delegated to the platform specific SDKs.
- [moko-mmvm](https://github.com/icerockdev/moko-mvvm): This is a Kotlin Multiplatform library that provides architecture components of Model-View-ViewModel for UI applications. Components are lifecycle-aware on Android.
- [Serialization](https://github.com/Kotlin/kotlinx.serialization): to De/Serializing JSON 
- [Kodein-DI](https://github.com/Kodein-Framework/Kodein-DI): Dependency injector
- [kotlinx.coroutines](https://github.com/Kotlin/kotlinx.coroutines): Library support for Kotlin coroutines with multiplatform support

<img src="https://github.com/jarroyoesp/KotlinMultiplatform_Firebase_MVVM/blob/master/images/KMP_MVVM_Firebase_schema.png">

### Android App

<img src="https://github.com/jarroyoesp/KotlinMultiplatform_Firebase_MVVM/blob/master/images/androidAppResult.png" width="200">

### iOS App

<img src="https://github.com/jarroyoesp/KotlinMultiplatform_Firebase_MVVM/blob/master/images/iOSAppResult.png" width="200">

If you want to know a bit more without checl all the code, you can take a look at this post on ProAndroidDev.com:
https://proandroiddev.com/kotlin-multiplatform-firebase-mvvm-4cdcddd98893


