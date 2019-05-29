# Stagehand

Stagehand will generate the given application type into the current directory.

usage: stagehand <generator-name>
    --[no-]analytics    Opt out of anonymous usage and crash reporting.
-h, --help              Help!
    --version           Display the version for stagehand.
    --author            The author name to use for file headers.
                        (defaults to "<your name>")

Available generators:
  console-full        - A command-line application sample.
  flutter-web-preview - A simple Flutter Web app.
  package-simple      - A starting point for Dart libraries or applications.
  server-shelf        - A web server built using the shelf package.
  web-angular         - A web app with material design components.
  web-simple          - A web app that uses only core Dart libraries.
  web-stagexl         - A starting point for 2D animation and games.