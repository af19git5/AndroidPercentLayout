

# Android Percent Layout Library

[繁體中文文檔](README_ZH.md)

## About

This Library help you easy to make percent layout.

## Using Library In Your Application

Add this in your app build.gradle file.

```groovy
dependencies {
    implementation 'io.github.af19git5:percent-layout-android:0.0.1'
}
```

And check your application minSdk must be greater than 24.

## How To Use

Example: 

```xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
	xmlns:app="http://schemas.android.com/apk/res-auto"
	android:layout_width="match_parent"
	android:layout_height="match_parent">

	<com.jimmyworks.percentlayout.layout.PercentImageView
		android:layout_width="match_parent"
		android:layout_height="wrap_content"
		android:src="#FF0202"
		app:layout_constraintBottom_toBottomOf="parent"
		app:layout_constraintEnd_toEndOf="parent"
		app:layout_constraintStart_toStartOf="parent"
		app:layout_constraintTop_toTopOf="parent"
		app:layout_constraintWidth_percent=".5"
		app:length_percent="1"
		app:look_with="width" />

</androidx.constraintlayout.widget.ConstraintLayout>
```

Use example you will get this layout preview. 

<img src="images/example.png.png" width="200">

