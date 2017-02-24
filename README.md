# Access IIS Express APIs from Android emulator

I would like to show you the way I access IISExpress Web APIs from my Android Emulator.
I'm using Visual Studio 2015. And I call the Android Emulator from Android Studio.

*Requirement: you must run Visual Studio as Administrator.
[This post](http://stackoverflow.com/a/12859334/2520509) gives a perfect way to do this
*

## See the result:

**From a browser on my PC**

![Image of browser](https://raw.githubusercontent.com/thetukiet/Access-IIS-Express-API-from-Android-Emulator/master/b5.png)

**From my Android Emulator:**

![Image of emulator](https://raw.githubusercontent.com/thetukiet/Access-IIS-Express-API-from-Android-Emulator/master/b3.png)



## The test API

![Image of emulator](https://raw.githubusercontent.com/thetukiet/Access-IIS-Express-API-from-Android-Emulator/master/b2.png)

Adding more configuration to App_Start/WebApiConfig to get Json format

![Image of emulator](https://raw.githubusercontent.com/thetukiet/Access-IIS-Express-API-from-Android-Emulator/master/b6.png)



## And this is how this work to me

**Edit the file "applicationhost.config" in your solution folder**

You can find it in the folder [yourSolutionFolder]/.vs/config. Beware the folder .vs is hidden.

![Image of emulator](https://raw.githubusercontent.com/thetukiet/Access-IIS-Express-API-from-Android-Emulator/master/b1.png)

**Check your IP Address**

And use this IP address to access your API from IIS Express. (See the result above)

<div style="width:100%;"><img style="float:center;" src="https://raw.githubusercontent.com/thetukiet/Access-IIS-Express-API-from-Android-Emulator/master/b4.png"/></div>



## Reference

* [The port on stackoverflow about forcing Visual Studio to always run as an Administrator](http://stackoverflow.com/questions/12257110/can-you-force-visual-studio-to-always-run-as-an-administrator-in-windows-8/12859334#12859334)
* [The post about IIS Express external request](http://stackoverflow.com/questions/3313616/iis-express-enable-external-request/15809698#15809698)
