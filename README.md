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
| 5.16.10.17707 | exoplayer:2.17.1 | Rebuild 5.16.10.17706                                                    |
| 5.16.5.17050  | exoplayer:2.17.1 |                                                                          |
| 5.16.2.16555  | exoplayer:2.17.1 |                                                                          |
| 5.15.12.10095 | exoplayer:2.17.1 |                                                                          |
| 5.15.7.15567  | exoplayer:2.17.1 |                                                                          |
| 5.14.11.14322 | exoplayer:2.17.1 |                                                                          |
| 5.13.10.12580 | exoplayer:2.17.1 | Rebuild 5.13.10.12577                                                    |
| 5.13.1.11014  | exoplayer:?      |                                                                          |
| 5.12.8.9901   | exoplayer:?      |                                                                          |
| 5.12.2.9109   | exoplayer:?      |                                                                          |
| 5.11.0.6883   | exoplayer:2.16.1 |                                                                          |
| 5.10.6.6361   | exoplayer:2.16.1 |                                                                          |
| 5.10.3.5614   | exoplayer:2.16.1 | Minimum version after February 4, 2023                                   |
| 5.9.6.4777    | exoplayer:2.13.3 |                                                                          |
| 5.9.1.3674    |                  |                                                                          |
| 5.9.1.3662    |                  | Minimum version after November 5, 2022                                   |
| 5.7.1.1268    |                  |                                                                          |
| 5.7.1         |                  |                                                                          |

### Links
- [publishing](./docs/DEV.md)
