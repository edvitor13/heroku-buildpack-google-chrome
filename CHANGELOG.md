# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
- Roolback -> Removed support for Cedar-14 and Heroku-16.
- Switched to CircleCI
- Corrected `$GOOGLE_CHROME_SHIM` and `$GOOGLE_CHROME_BIN` to use correct paths both at runtime and during tests.
- Added `$GOOGLE_CHROME_SHIM` variable to prevent users from needing to hard-
  code the shim location.
