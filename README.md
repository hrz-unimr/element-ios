# Element iOS - with University Marburg modifications

Element iOS is an iOS [Matrix](https://matrix.org/) client provided by [Element](https://element.io/). It is based on [MatrixSDK](https://github.com/matrix-org/matrix-ios-sdk).

## Beta testing 

You can try last beta build by accessing our [TestFlight Public Link](https://testflight.apple.com/join/lCeTuDKM). For questions and feedback about latest TestFlight build, please access the Element iOS Matrix room: [#element-ios:matrix.org](https://matrix.to/#/#element-ios:matrix.org).

## Build instructions

If you have already everything installed, opening the project workspace in Xcode should be as easy as:

```
$ xcodegen                  # Create the xcodeproj with all project source files
$ pod install               # Create the xcworkspace with all project dependencies
$ open Riot.xcworkspace     # Open Xcode
```

Else, you can visit our [installation guide](./INSTALL.md). This guide also offers more details and advanced usage like using [MatrixSDK](https://github.com/matrix-org/matrix-ios-sdk) in its development version.

## Copyright & License

Copyright (c) 2014-2017 OpenMarket Ltd  
Copyright (c) 2017 Vector Creations Ltd  
Copyright (c) 2017-2021 New Vector Ltd

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License in the [LICENSE](LICENSE) file, or at:

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
