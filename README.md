# ADB_Server_Client

Server run in the Android device, develop in Android Studio.

Client run in Windows, develop in Visual Studio 2015 using C++.

Type "adb forward tcp:8000 tcp:9000" command in Windows CMD before start the program.

Because transmission speed by ADB socket via USB is too slow(< 5MB/S)for stream, so we change to WIFI connection, hope more fluent.
