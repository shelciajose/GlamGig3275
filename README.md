# GlamGig3275

For Windows

>>>>>>>>>>>>>Install choco using cmd:

@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command " [System.Net.ServicePointManager]::SecurityProtocol = 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"

>>>>>>>>>>>>>>Verify Installation
To verify that Chocolatey is installed, we will use the choco command.

C:\WINDOWS\system32>choco
 Chocolatey v0.10.15
 Please run 'choco -?' or 'choco  -?' for help menu.

 >>>>>>>>>>>>>To install the Dart SDK:

 choco install dart-sdk
 
>>>>>>>>>>>>>>>>>To upgrade the Dart SDK:

 choco upgrade dart-sdk

 >>>>>>>>>>>>>>>>>> Flutter installation
Download Flutter:

https://docs.flutter.dev/get-started/install/windows

where flutter dart
  C:\path-to-flutter-sdk\bin\flutter
  C:\path-to-flutter-sdk\bin\flutter.bat
  C:\path-to-dart-sdk\bin\dart.exe        :: this should go after `C:\path-to-flutter-sdk\bin\` commands
  C:\path-to-flutter-sdk\bin\dart
  C:\path-to-flutter-sdk\bin\dart.bat

run flutter:

C:\src\flutter>flutter doctor

>>>>>>>> Open the app on android studio
>>>>>>>> on Terminal
flutter pub get
flutter run
