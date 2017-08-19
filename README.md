# Editor open & close handling

[![Build Status](https://travis-ci.org/jansorg/intellij-plugin-base.svg?branch=master)](https://travis-ci.org/jansorg/intellij-editor-open-close)

The build configuration uses Gradle with enabled Jacoco test coverage reports.

# Sample code
- See `src/main/java/com/plugindev/editor/EditorStatusComponent` for a component which adds a UI element to newly created editors.

# Directory structure

- `src/main/java`: Java sources
- `src/main/resources`: Java resource files
- `src/test/java`: Java test case sources
- `src/test/resources`: Java test case resource files

# Continous integration builds

`.travis.yml` configures a [Travic-ci.org](https://travis-ci.org/) build.

# Documentation
- Post about this sample code: https://www.plugin-dev.com/intellij/editor-open-close/
- Introduction to plugin development: https://www.plugin-dev.com/intellij/introduction/
- IntelliJ DevGuide: http://www.jetbrains.org/intellij/sdk/docs/welcome.html
- Gradle build plugin: http://www.jetbrains.org/intellij/sdk/docs/tutorials/build_system.html
