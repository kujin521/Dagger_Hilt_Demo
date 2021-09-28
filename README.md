# Dagger_Hilt_Demo
学习Dagger—Hilt

## 创建android Compose 项目

导入依赖

project：build.gradle

```groovy
classpath 'com.google.dagger:hilt-android-gradle-plugin:2.38.1'
```

app：build.gradle

```groovy
plugins {
    id 'com.android.application'
    id 'kotlin-android'

    id 'kotlin-kapt'
    id 'dagger.hilt.android.plugin'
}


```

```groovy
//Dagger-Hilt
implementation "com.google.dagger:hilt-android:2.28-alpha"
kapt "com.google.dagger:hilt-android-compiler:2.28-alpha"

//view-model
implementation 'androidx.hilt:hilt-lifecycle-viewmodel:1.0.0-alpha02'
kapt "androidx.hilt-comiler:1.0.0-alpsha02"
implementation "androidx.activity:activity-ktx:1.1.0"
```

