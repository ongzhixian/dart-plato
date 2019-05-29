# Flutter

## Create app

```
flutter create <dir_name>
flutter create csi
```


## Reference

C:\src\github.com\ongzhixian\dart-plato\csi>flutter help
Manage your Flutter app development.

Common commands:

  flutter create <output directory>
    Create a new Flutter project in the specified directory.

  flutter run [options]
    Run your Flutter application on an attached device or in an emulator.

Usage: flutter <command> [arguments]

Global options:
-h, --help                  Print this usage information.
-v, --verbose               Noisy logging, including all shell commands executed.
                            If used with --help, shows hidden options.

-d, --device-id             Target device id or name (prefixes allowed).
    --version               Reports the version of this tool.
    --suppress-analytics    Suppress analytics reporting when this command runs.
    --bug-report            Captures a bug report file to submit to the Flutter team.
                            Contains local paths, device identifiers, and log snippets.

    --packages              Path to your ".packages" file.
                            (required, since the current directory does not contain a ".packages" file)

Available commands:
  analyze                  Analyze the project's Dart code.
  attach                   Attach to a running application.
  bash-completion          Output command line shell completion setup scripts.
  build                    Flutter build commands.
  channel                  List or switch flutter channels.
  clean                    Delete the build/ and .dart_tool/ directories.
  config                   Configure Flutter settings.
  create                   Create a new Flutter project.
  devices                  List all connected devices.
  doctor                   Show information about the installed tooling.
  drive                    Runs Flutter Driver tests for the current project.
  emulators                List, launch and create emulators.
  format                   Format one or more dart files.
  help                     Display help information for flutter.
  install                  Install a Flutter app on an attached device.
  logs                     Show log output for running Flutter apps.
  make-host-app-editable   Moves host apps from generated directories to non-generated directories so that they can be edited by
                           developers.
  packages                 Commands for managing Flutter packages.
  precache                 Populates the Flutter tool's cache of binary artifacts.
  run                      Run your Flutter app on an attached device.
  screenshot               Take a screenshot from a connected device.
  stop                     Stop your Flutter app on an attached device.
  test                     Run Flutter unit tests for the current project.
  trace                    Start and stop tracing for a running Flutter app.
  upgrade                  Upgrade your copy of Flutter.
  version                  List or switch flutter versions.

Run "flutter help <command>" for more information about a command.
Run "flutter help -v" for verbose help output, including less commonly used options.


-------------

C:\src\github.com\ongzhixian\dart-plato\csi>flutter create
No option specified for the output directory.
Create a new Flutter project.

If run on a project that already exists, this will repair the project, recreating any files that are missing.

Usage: flutter create <output directory>
-h, --help                     Print this usage information.
    --[no-]pub                 Whether to run "flutter packages get" after the project has been created.
                               (defaults to on)

    --[no-]offline             When "flutter packages get" is run by the create command, this indicates whether to run it in offline
                               mode or not. In offline mode, it will need to have all dependencies already available in the pub
                               cache to succeed.

    --[no-]with-driver-test    Also add a flutter_driver dependency and generate a sample 'flutter drive' test.
-t, --template=<type>          Specify the type of project to create.

          [app]                (default) Generate a Flutter application.
          [package]            Generate a shareable Flutter project containing modular Dart code.
          [plugin]             Generate a shareable Flutter project containing an API in Dart code with a platform-specific
                               implementation for Android, for iOS code, or for both.

-s, --sample=<id>              Specifies the Flutter code sample to use as the main.dart for an application. Implies --template=app.
                               The value should be the sample ID of the desired sample from the API documentation website
                               (http://docs.flutter.io).

    --list-samples=<path>      Specifies a JSON output file for a listing of Flutter code samples that can created with --sample.
    --[no-]overwrite           When performing operations, overwrite existing files.
    --description              The description to use for your new Flutter project. This string ends up in the pubspec.yaml file.
                               (defaults to "A new Flutter project.")

    --org                      The organization responsible for your new Flutter project, in reverse domain name notation. This
                               string is used in Java package names and as prefix in the iOS bundle identifier.
                               (defaults to "com.example")

    --project-name             The project name for this new Flutter project. This must be a valid dart package name.
-i, --ios-language             [objc (default), swift]
-a, --android-language         [java (default), kotlin]

Run "flutter help" to see global options.