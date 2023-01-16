# android_ci Documentation

* open project
* run "gradlew build"
* research how to generate a keystore
* generte new keystore in android studio
* add signingConfigs to build gradle
* build apk with "Build" -> "Build Bundles/APK" -> "Build APK(S)"
* push to repo
* create workflow file with Android Ci

* add "-o" to the terminal comment
* Passwort: "keyphrase" for the key
* add key variables to repository -> Settings -> Secrets and variables -> New repo variable
* addSigningConfigs
* delete local-properties from repo
* comment out SigningConfigs to import later
* Rebuild -> AndroidX
* add secret to repository
