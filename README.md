This repository provides easy access to ZoomUs android sdk.

You can check JitPack link [jitpack-zoom-us](https://jitpack.io/#zoom-us-community/jitpack-zoom-us)

Library includes sdk archives:
- commonlib.aar
- mobilertc.aar

### Usage

```gradle
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

Now you can add dependency:
```gradle
dependencies {
    implementation 'com.github.zoom-us-community:jitpack-zoom-us:5.9.6.4777'
}
```

Available tags:
```
5.9.6.4777
5.9.1.3674
5.9.1.3662
5.7.1.1268
5.7.1
```

Note: You can use commit hash instead of Tag.

### Links
- [publishing](./docs/DEV.md)
