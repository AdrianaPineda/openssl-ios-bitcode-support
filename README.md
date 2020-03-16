# openssl-ios-bitcode-support
Spec repo for openssl with bitcode support

# Versioning
Versioning is the same as: https://github.com/FredericJacobs/OpenSSL-Pod

```
Because OpenSSL's version numbers are not compatible with the CocoaPods version numbering, we will agree on the following.

OpenSSL version: A.B.CD will become A.B.C*100 + place of D in the alphabeth.

Example: OpenSSL 1.0.1h => OpenSSL 1.0.108
```
# Config
Versions that work:

* gem 'cocoapods', '= 1.3.0'
* gem 'cocoapods-downloader', '1.2.0'
* Xcode 11.3.0
* System Ruby	ruby 2.6.3p62 (2019-04-16 revision 67580) [universal.x86_64-darwin19]

# Unable to find simulator (due to fourflusher + XCode 10.2+)
- https://github.com/CocoaPods/CocoaPods/issues/8163#issuecomment-507658956

# pod trunk
- Needs version 1.4.0

https://github.com/CocoaPods/cocoapods-trunk/issues/142

# For versions 1.1.x
Not supported yet. Check out discussions:
- https://github.com/openssl/openssl/issues/2194
- https://github.com/openssl/openssl/issues?q=is%3Aissue+ios+x86_64
- https://github.com/openssl/openssl/issues/9999
- https://github.com/x2on/OpenSSL-for-iPhone
