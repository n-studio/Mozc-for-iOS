Mozc-for-iOS [![Build Status](https://img.shields.io/travis/kishikawakatsumi/Mozc-for-iOS/master.svg?style=flat)](https://travis-ci.org/kishikawakatsumi/Mozc-for-iOS)
============

Mozc for iOS build

### Credits

https://code.google.com/p/mozc/

### References

https://code.google.com/p/mozc/

### System Requirements

    Mac OS X 10.9+
    Xcode 6.0+
    iOS SDK 8.0+


### Get the Code

```
$ git clone git@github.com:kishikawakatsumi/Mozc-for-iOS.git mozc_ios
```

### Build Instructions

#### Configuration

```
$ cd mozc_ios/src
$ python build_mozc.py gyp
```

#### Compilation

```
$ python build_mozc_ios.py
```

#### Artifacts

See `src/out_ios/Release-iphoneos`

### Limitation

Device build only, cannot run on the simulator.


### Sample Project

See https://github.com/kishikawakatsumi/JapaneseKeyboardKit

 
[Apache]: http://www.apache.org/licenses/LICENSE-2.0
[MIT]: http://www.opensource.org/licenses/mit-license.php
[GPL]: http://www.gnu.org/licenses/gpl.html
[BSD]: http://opensource.org/licenses/bsd-license.php

## License

Mozc for iOS build is available under the [Apache license][Apache] (same as the original). See the LICENSE file for more info.
