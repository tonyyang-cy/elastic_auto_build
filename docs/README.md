# How to build
## Requirements
1. Flutter SDK
Download from [here](https://docs.flutter.dev/get-started/install)
2. Java SDK
Download from [here](https://www.oracle.com/java/technologies/downloads/)
3. Inno Setup
Download from [here](https://www.jrsoftware.org/isinfo.php)

## Build the app
1. Clone the repository
2. Open the repository in your IDE
3. Run `flutter build windows`

## Build the installer
1. Run `dart run inno_bundle:build --envs --no-hf`
2. Run `dart run inno_bundle:build --release`
3. The installer will be in the `build/windows/x64/installer/Release` directory