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

* add release apk to repo
* fix errors with keystore.jks with removing properties and fixing the path
* after the workflow there is now a an "Artifacts" section visible with the "Application-release.apk"

### Questions answered

* Q: Was fällt Ihnen beim vorgegebenen Android CI Workflow auf? Kann dabei schon von Continuous Delivery gesprochen werden? 
* A: eigentlich schon ja, da bei jeden push oder pull-request der gradlew build ausgeführt wird

* Q: Testen Sie erneut das Bauen der APK. Wo erscheint die APK nach erfolgreichem Durchlauf des Workflows? Kann die APK gebaut werden? 
* A: die APK erscheint im angegbenen Pfad den man bei "path" hinzugefügt hat
