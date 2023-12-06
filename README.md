# GlamGig3275

User App : https://github.com/shelciajose/User_app

Stylist App : 

Steps to run the apps:

For Windows

1)Install choco using cmd:

@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command " [System.Net.ServicePointManager]::SecurityProtocol = 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"

2)Verify Installation
To verify that Chocolatey is installed

C:\WINDOWS\system32>choco
Chocolatey v0.10.15
Please run 'choco -?' or 'choco  -?' for help menu.

3)To install the Dart SDK:

 choco install dart-sdk
 
4)To upgrade the Dart SDK:

 choco upgrade dart-sdk

5)Flutter installation
Download Flutter:

https://docs.flutter.dev/get-started/install/windows

6) Run flutter
   C:\path-to-flutter-sdk\bin\flutter
   C:\path-to-flutter-sdk\bin\flutter.bat
   C:\path-to-dart-sdk\bin\dart.exe        :: this should go after `C:\path-to-flutter-sdk\bin\` commands
   C:\path-to-flutter-sdk\bin\dart
   C:\path-to-flutter-sdk\bin\dart.bat
   C:\src\flutter>flutter doctor

->Open the app on android studio
->on Terminal
    flutter pub get
    flutter run

7) Reference Links:
     flutter : https://docs.flutter.dev/get-started/install/windows
     dart : https://dart.dev/get-dart
     choco : https://chocolatey.org/install

8) Admin panel

   https://glamgigv1.ideasolved.com/admin/
   user: jshelcia@gmail.com
   password: Glamgig@123
