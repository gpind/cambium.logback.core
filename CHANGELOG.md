# cambium.logback.core - TODO and Change Log

## 0.4.5 / 2021-December-16

- Update Logback version to 1.2.8
  - Fixes #2
- Target cambium.core 1.1.1


## 0.4.4 / 2020-September-30

- Drop support for Clojure `1.5.x`
- Update Janino to version `3.1.2`


## 0.4.3 / 2019-May-07

- Upgrade Janino to version `3.0.12`


## 0.4.2 / 2018-March-22

- Upgrade Janino version to `3.0.8`
- Add utility fns in `cambium.logback.core.util` namespace
  - `find-logger-context` to find default logger-context
  - `logger-context-name` to find logger-context name
  - `start-logger-context` to start logger-context
  - `stop-logger-context` to stop logger-context


## 0.4.1 / 2017-October-26

- Marker release (no change) just to sync with cambium.logback.* release


## 0.4.0 / 2017-September-11

- Inherited code from logback-bundle/core-bundle `0.3.0`
  - Old repo: https://github.com/kumarshantanu/logback-bundle
- [BREAKING CHANGE] Rename base namespace to `cambium.logback.core`
- Add support for Java 6
