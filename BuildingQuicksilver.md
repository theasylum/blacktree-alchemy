# How to build the Quicksilver trunk #

For those of you that like living on the bleeding edge, here are the required steps to get a working Quicksilver from trunk :
  * Get the source from trunk as usual (see [checkout instructions](http://code.google.com/p/blacktree-alchemy/source/checkout))
  * Edit Configuration/Developer.xcconfig, and set QS\_SOURCE\_ROOT to the directory you've checked the source to.
  * Relaunch Xcode. It seems to have issue refreshing its build settings when they are not changed from the Build Settings.
  * Hack away !