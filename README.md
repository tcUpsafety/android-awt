
## android-awt

### This is a fork of [windwardadmin/android-awt](https://github.com/windwardadmin/android-awt)

This project provides java.awt and javax.imagio since we can't use 
these classes on Android. Code is taken from Apache Harmony, Apache Commons Imaging and [witwall/appengine-awt](https://github.com/witwall/appengine-awt).

### Import

```
repositories {
    maven { url "http://www.andob.info" }
}
```

```
dependencies {
	implementation 'ro.andob.androidawt:androidawt:1.0.2'
}
```


### You can use this library in order to make [OpenPDF](https://github.com/LibrePDF/OpenPDF) [work on Android](https://github.com/LibrePDF/OpenPDF/issues/118)

```
repositories {
    maven { url "http://www.andob.info" }
}
```

```
dependencies {
	implementation 'com.github.librepdf:openpdf:1.3.8'
	implementation 'ro.andob.androidawt:androidawt:1.0.2'
}
```

### Proguard

```
-dontwarn org.bouncycastle.**
-dontwarn java.lang.invoke.**
```

### Licensed under Apache License
