AndroidWithArtifactoyExample
=============================

This repository is a sample of Android gradle project using artifactory repository. 
Currently, this does not work correctly.

## Structure
Project structure:
```
Top Project
  |-app: Android app project
  |-common-lib: Java library project
```

Dependency graph:
```
app -> common-lib
common-lib -> artifactory repository (gradle-demo)
```
