# Access IIS Express APIs from Android emulator

I would like to show you the way I access IISExpress Web APIs from my Android Emulator.
I'm using Visual Studio 2015. And I call the Android Emulator from Android Studio.


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

![Image of emulator](https://raw.githubusercontent.com/thetukiet/Access-IIS-Express-API-from-Android-Emulator/master/b4.png)
