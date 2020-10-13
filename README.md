# Futter Template

Template for new Flutter projects that works out of the box in latest Android Studio (Beta channel), 
including IDE support for native Android code and using the latest Gradle release.

The goal is to start a new project as quickly and frictionless as possible.

## Prerequesites

- Android SDK is installed
- Flutter SDK is installed
- Android Studio 4.1 is installed

## Usage

Go to this project's GitHub page: https://github.com/igorakkerman/flutter-template

Then click on `Use this template` to create a new GitHub repository based on this template.

*Before* opening the project in Android Studio:

- Rename `android/local.properties-template` to `android/local.properties`
  and set the SDK paths according to your local environment.

Open the project in Android Studio.


- Wait until you're prompted for your local Dart SDK.
- Do *not* click the links to select your Dart SDK.
- Instead, select `File > Settings`, 
  go to `Languages & Frameworks > Flutter` and select your local Flutter SDK path.
- Wait until all background processes have run.

Enjoy building your Flutter app!

## Known Issues

After starting Android Studio, you might be shown the following error message, which you can ignore:

```
Unsupported Modules Detected: Compilation is not supported for following modules: flutter-template. Unfortunately you can't have non-Gradle Java modules and Android-Gradle modules in one project.
```

## Single commit in main branch

When creating a project from this template, the Git history of your project should be as clean as possible.
Hence, the main branch contains only a single commit with the latest version at all times. 

For each version of Android Studio, a separate branch holds the full commit history for that IDE version.

It is not guaranteed that branches for older IDE versions will be maintained. 
However, you may create pull requests for these versions, and the changes will be merged into the appropriate branch.

## Contributing

It is always tricky to create a template that works in every environment. Please report any problem you're encountering.

New issues and pull requests are very welcome and highly appreciated.

## Disclaimer

Parts of the code in this repository are generated using the Flutter tool by running the `flutter create` command. 
Please verify all legal requirements or restrictions on the Flutter website: https://flutter.dev .
The license of this repository applies to this project's additions made to the generated code.
