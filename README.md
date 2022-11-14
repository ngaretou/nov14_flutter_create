This is for troubleshooting a problem with archiving a macOS build in Xcode. 

What's been done here so far: 
- Flutter: New Project in VS Code
- 'flutter pub add shared_preferences'
- Run in VS Code - runs great
- 'flutter build macos'
- Now in Xcode open the Runner.xcodeproj in the macos folder
- Product/Archive or Product/Analyze
- Brings the 'no such module' error on 'shared_preferences_macos' in GeneratedPluginRegistrant in the Flutter folder inside the xcodeproj
- Also tried with url_launcher and same result. 
