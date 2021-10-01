# Flutter Desktop App for Linux

A getting started project for desktop application development using Flutter

## Flutter Installation on Linux

There is no need to install Android or iOS SDK if you want to just build it for Linux Desktop.

https://flutter.dev/docs/get-started/install/linux#linux-setup

## Create a Flutter App

```console
flutter create sample_app
cd sample_app
```

## Desktop Version

### Run in Debug Mode

```console
flutter run
```

If you have multiple devices enabled for your app you can specifically run it for Linux desktop using this command:

```console
flutter run -d linux
```

### Build the Release

```console
flutter build linux
```

### Run the Release

Supposed that you built the app for x86_64.

```console
./build/linux/x64/release/bundle/sample_app 
```

## Web Version

Just for comparison with desktop release.

### Build and Run

```console
flutter build web
cd build/web 
python -m http.server 8000
```
Open [localhost:8000](http://localhost:8000/) in browser.

If you have Chrome browser installed, you can use just this command to run the web app in debug mode:

```console
flutter run -d chrome
```
