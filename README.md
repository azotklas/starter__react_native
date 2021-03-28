## Installation project

Install the dependencies and devDependencies and start the server.

```sh
npm i
```

Go to /ios and run:

```sh
pod install
```

## First tab: Start Metro (Packager)

> Вам может потребоваться сбросить или очистить кеш упаковщика React Native.
> Для этого вы можете передать стартовому скрипту флаг --reset-cache

```sh
npx react-native start --reset-cache
```

## Second Tab: Run App

How to run ANDROID:
Before starting the APP, you must open the project (./android) in the Android Studio and run any emulator

```sh
npx react-native run-android
```

How to run IOS:

```sh
npx react-native run-ios
```

## Cleaning

ios

```sh
cd ios && xcodebuild clean && cd ../
```

android

```sh
cd android && ./gradlew clean && cd ../
```

## License

MIT

## Author

Denis Pytlyak <azot952@gmail.com>
