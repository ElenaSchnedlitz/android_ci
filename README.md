# android_ci Documentation
open project
run "gradlew build"
research how to generate a keystore
generte new keystore in android studio
add signingConfigs to build gradle
build apk with "Build" -> "Build Bundles/APK" -> "Build APK(S)"
push to repo
create workflow file with Android Ci

anhängen von "-o" bei Befehl
Passwort: "keyphrase" für den key
add key variables to repository -> Settings -> Secrets and variables -> New repo variable
addSigningConfigs
delete local-properties from repo
comment out SigningConfigs to import later
add secret to repository
