# app-automation
This is project to test how app automation works

## Tech-stack used for
- Fastlane 
- Firebase app distribution
- Jenkins

## Steps to init _fastlane_ 
- Come into the root of project
- Type _fastlane init_
- Set package name (*com.androiddev.appautomation*)
- Set path to secret json file
- Install next plugins:
    - firebase_app_distribution
    - fastlane-plugin-increment_version_code
    - fastlane-plugin-versioning_android
- Configure fastlane pipe to firebase app distribution
---

## Steps to inti _firebase app distribution_
- Create firebase app project
- Connect it to firebase app distribution
- Add testers email

## Configure Google cloud console account
- Create _Service Account_
- Use key from this account as _GOOGLE_CREDENTIAL_ for fastlane to distribute app

## Configure Google 