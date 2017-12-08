# <img src="/app/src/main/web_hi_res_512.png" width="64" /> FaceGrok

Want to detect human faces on a camera preview stream in real time? FaceGrok is an application that uses the FaceDetector library to do just that.

<img src="/screenshot01.png" width="200" />

<img src="/screenshot02.png" width="400" />


## Google Play
https://play.google.com/store/apps/details?id=com.facegrok


## FaceGrok is a Proof-of-Concept

This app just recognizes faces, in a similar way that any modern camera app would. nothing more, nothing less. No storage of facial recognition data on disk, no other functionality.

FaceGrok is a proof-of-concept that tracker SDKs can be inserted into an app, that the app will pass Google Play app store publishing (even when blatantly announcing trackers are in the app), and to compare with the tracker scans from Exodus.

See https://privacylab.yale.edu/trackers for context and how FaceGrok fit into the November 24, 2017 announcement by Yale Privacy Lab and Exodus Privacy about hidden trackers in Google Play apps.

See the Exodus report on the Google Play version of FaceGrok: https://reports.exodus-privacy.eu.org/reports/search/com.facegrok

This repository doesn't include the tracker SDKs, of course, and is the clean version.


## Privacy
Please see `PRIVACY.md` for more information, including what trackers are included in the Google Play version of FaceGrok.


## License

```
FaceDetector is copyright 2017 Fotoapparat.
FaceGrok modifications are copyright 2017 Sean O'Brien.
Material Design icons are copyright 2017 Google.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
