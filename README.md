

# EdgeMobileClient
​
EdgeMobileClient library can help you interact with mimik edgeEngine framework with the following APIs:
​
 * `startEdge`
 * `startEdgeSynchronously`
 * `stopEdge`
 * `stopEdgeSynchronously`
 * `setStaticEdgePort`
 * `getEdgePort`
 * `isEdgeReady`
 * `clearEdgeData`
 * `clearEdgeDataSynchronously`
 * `deployEdgeMicroservice`
 * `removeEdgeMicroservice`
 * `getDeployedImages`
 * `getDeployedContainers`
 * `loginWithDeveloperToken`
 * `requestPhoneNumberVerification`
 * `authorizeWithPhoneNumber`
 * `requestEmailVerification`
 * `authorizeWithEmail`
 * `loginWithEmail`
 * `resetPasswordWithEmail`
 * `resetPasswordWithEmailVerification`
 * `changePasswordWithEmail`
 * `getInfo`
​
 Please see the in-code documentation for more details.
​
## Supported Platforms, Targets
* `64-bit Android devices supporting SDK 26 and above`
​
**Android Emulators are NOT supported**
​
## Requirements
```
Android SDK 26 (Android OS 8.0)
```
​
## Before you start
​
[Explore developer-documentation](developer.mimik.com)
​
[Sign up and create a mimik developer console account](https://developer.mimik.com/console/create_account)
​
## Download 
​
To include EdgeMobileClient in your project:
​
Gradle:
​
```
allprojects {
    repositories {
        maven {
            url "https://s3-us-west-2.amazonaws.com/mimik-android-repo"
        }
    }
}
```
​
```
dependencies {
    implementation 'com.mimik.edgesdk-android-client:edgemobileclient-core:0.2.1'
}
```
​
## Tutorial
​
Visit this [tutorial](https://devdocs.mimik.com/tutorials/04-index) to learn more about the mimik client library and how to integrate it into your Android project.
​
## Author
​
mimik
```
https://mimik.com/
```
 
## Community & Support  
​
Contact the developer support team @ devcommunity.support@mimik.com
​
## License
​
The aforementioned mimik client and service libraries are available under the MIT license. See the LICENSE file for more information.
