# flutter_ui_test

Flutter UI Test multiple file using [flutter-runner](https://github.com/prongbang/flutter-runner/)

## Getting Started

- [config.yaml](config.yaml)

```yaml
device:
  android:
    flavor: "automate"
    device_id: "emulator-5554"
    device_name: "Android_13"
  ios:
    flavor: "automate"
    device_name: "iPhone 14 Pro Max"
report:
  name: "report/ui-test-{}.html"
tests:
  - "main_test.dart"
```

- Run Android

```shell
flutter-runner -p android
```

- Run iOS

```shell
flutter-runner -p ios
```