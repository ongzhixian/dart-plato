# Dart CLI tools

1.  stagehand
2.  pub
3.  dart
4.  dart2aot 
5.  dartaotruntime 

## 1.  stagehand

Templates for creating Dart apps:

```
pub global activate stagehand
```

Note: Pub installs executables into:

%APPDATA%\Pub\Cache\bin

So you might want to add that your PATH variable.

## 2.  pub

Package manager

```
pub get
```

## 3.  dart

Run the app from the command line, using Dart VM 

```
dart bin/main.dart
```


## 4.  dart2aot 

Compiler -- AOT (Ahead of Time) compile the program to machine code

```
dart2aot bin/main.dart bin/main.dart.aot
```

## 5.  dartaotruntime 

Runs the compiled AOT program

```
dartaotruntime bin/main.dart.aot
```