* Official rust ffi support: https://docs.rs/ffi-support/0.4.2/ffi_support/ (pretty useful)
* FFI crate: https://crates.io/crates/ffi-support (unsure of its imp to me)
---
### Mozilla Impl-ing FFI
* Their blogpost: https://hacks.mozilla.org/2019/04/crossing-the-rust-ffi-frontier-with-protocol-buffers/
* moz/as: https://github.com/mozilla/application-services
* Useful section of trailing repo [here](https://github.com/mozilla/application-services/tree/72b827c3e0f883163762857fd766df1aeb060725/components/support) 
* Their ultimately orz book :pray: : https://mozilla.github.io/application-services/book 
* An old impl by 'em: https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-21-rust-on-android.html
* They automatically generate FFI bindings, for `crashtest`, see here: https://github.com/mozilla/application-services/blob/main/components/crashtest/
* But they also have handwritten ffi bindings [@glean](https://github.com/mozilla/glean/)(deployed in production): https://github.com/mozilla/glean/blob/main/glean-core/ffi, study this FFI package
* Learn about uniffi: https://mozilla.github.io/uniffi-rs/ 
---
### Others
* Some other blogpost on similar impl: https://blog.svgames.pl/article/running-rust-on-android
* https://dushistov.github.io/flapigen-rs/java-android-example.html


Caveat: Their repository structure is subject to change so make sure you know what you're exactly interested in seraching in the repository! Don't rely on links of submodules provided above, you may have to search it on your own, maybe use [gh1s](https://github.com/conwnet/github1s) then 👀
