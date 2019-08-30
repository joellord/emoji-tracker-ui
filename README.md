# Emoji Tracker UI
This is a UI for the emoji tracker API that can be found at [github.com/joellord/emoji-tracker](https://github.com/joellord/emoji-tracker).

## Demo
Live demo can be found on [OpenShift](http://nginx-example-emoji-tracker.b9ad.pro-us-east-1.openshiftapps.com/)

## Installation instructions
Follow the instruction on [emoji-tracker](https://github.com/joellord/emoji-tracker). Then install the UI in the same minishift project.

* Start minishift
  * `minishift start`
* Login to minishift and create a new project
  * `oc login`
  * `oc new-project emoji-tracker`
* Deploy the application
  * `oc new-app https://github.com/joellord/emoji-tracker-ui.git --image-stream=nginx`