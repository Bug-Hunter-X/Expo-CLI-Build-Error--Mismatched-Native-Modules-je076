# Expo CLI Build Error: Mismatched Native Modules

This repository demonstrates a common Expo CLI build error related to mismatched native modules or incorrect Expo CLI versions.  The error typically occurs during the build process when using EAS Build or building standalone apps.  The `expoBug.js` file showcases code that might trigger this error (by relying on a native module that isn't compatible with the current Expo setup). The `expoBugSolution.js` file offers a potential solution to fix the issue, focusing on ensuring compatibility between the native modules, Expo CLI version, and the Expo SDK version.