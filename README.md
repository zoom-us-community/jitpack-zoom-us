This repository provides easy access to ZoomUs android sdk.

[![](https://jitpack.io/v/zoom-us-community/jitpack-zoom-us.svg)](https://jitpack.io/#zoom-us-community/jitpack-zoom-us)

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
    implementation 'com.github.zoom-us-community:jitpack-zoom-us:5.16.10.17706'
}
```

Note: You can use commit hash instead of Tag.


### Available Versions

| Tag           | Dependencies     | Notes                                                                    |
| :-----------: |:-----------------| :----------------------------------------------------------------------  |
| 5.16.10.17707 | exoplayer:2.17.1 | Rebuild 5.16.10.17706 `BROKEN`                                           |
| 5.16.5.17050  | exoplayer:2.17.1 | `BROKEN`                                                                 |
| 5.16.2.16555  | exoplayer:2.17.1 |                                                                          |
| 5.15.12.10095 | exoplayer:2.17.1 | `BROKEN`                                                                 |
| 5.15.7.15567  | exoplayer:2.17.1 | `BROKEN`                                                                 |
| 5.14.11.14322 | exoplayer:2.17.1 |                                                                          |
| 5.13.10.12580 | exoplayer:2.17.1 | Rebuild 5.13.10.12577                                                    |

### Links
- [publishing](./docs/DEV.md)
