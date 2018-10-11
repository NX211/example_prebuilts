## Overview
This is an example repository to show how a repo should look if you want to include additional prebuilts into the RattlesnakeOS build process using the advanced flag `--repo-prebuilts https://<git repo>`. <b>This will not build in its current form as it just has dummy APK files.</b>

## Required Repo Structure
Each app you want to include should:
* Create a subdirectory for the app (e.g. app1), add both the APK file and Android.mk file into this subdirectory.
* Add the LOCAL_MODULE name (e.g. app1) into the `manifest` in the root of the repository.
