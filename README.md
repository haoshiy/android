[![](https://www.jitpack.io/v/haoshiy/android.svg)](https://www.jitpack.io/#haoshiy/android)

# How to

To get a Git project into your build:

**Step 1.** Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

```
allprojects {
    repositories {
        ...
        maven { url 'https://www.jitpack.io' }
    }
}
```

**Step 2.** Add the dependency

```
dependencies {
    ...
    implementation 'com.github.haoshiy.android:library:version'
    kapt 'com.github.haoshiy.android:library-compiler:version'
    kapt "androidx.lifecycle:lifecycle-compiler:2.2.0"
    kapt "androidx.room:room-compiler:2.2.5"
    kapt "com.github.bumptech.glide:compiler:4.11.0"
    // If use router
    kapt "com.alibaba:arouter-compiler:1.2.2"
}
```

# Demo

[Demo](https://github.com/haoshiy/kotlin_wanandroid)
