# docker-xamarin-android
Docker image includes mono/java for building Xamarin Android or Xamarin Forms project in a CI container.

[![Docker Build Status](https://img.shields.io/docker/cloud/build/chiticariu/xamarin-android.svg)](https://cloud.docker.com/repository/docker/chiticariu/xamarin-android)

Installed Android SDK's v27 and v28
Installed build tools v27.0.3 and 28.0.3

This image uses the Android SDK so you should agree with the Android SDK license before usage (https://developer.android.com/studio/terms.html°

## Example `.gitlab-ci` file
```Dockerfile
TBD
```
## Extra helper command
- Run docker image in terminal having the code mounted
```
Linux:    docker run -it -v $(pwd):/xamarin_project chiticariu/xamarin-android /bin/bash
Windows:  docker run -it -v %cd%:/xamarin_project chiticariu/xamarin-android /bin/bash
```

References:
https://hub.docker.com/r/nathansamson/xamarin-android-docker
