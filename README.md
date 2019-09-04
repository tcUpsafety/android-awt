
## android-awt

### This is a fork of [windwardadmin/android-awt](https://github.com/windwardadmin/android-awt)

This project provides java.awt and javax.imagio since we can't use 
these classes on Android. Code is taken from Apache Harmony, Apache Commons Imaging and [witwall/appengine-awt](https://github.com/witwall/appengine-awt).

### Import

```
repositories {
    maven { url "https://jitpack.io" }
}
```

```
dependencies {
	implementation 'com.github.andob:android-awt:1.0.0'
}
```


### You can use this library in order to make [OpenPDF](https://github.com/LibrePDF/OpenPDF) [work on Android](https://github.com/LibrePDF/OpenPDF/issues/118)

```
repositories {
    maven { url "https://jitpack.io" }
}
```

```
dependencies {
	implementation 'com.github.librepdf:openpdf:1.3.8'
	implementation 'com.github.andob:android-awt:1.0.0'
}
```

### Licensed under Apache License
