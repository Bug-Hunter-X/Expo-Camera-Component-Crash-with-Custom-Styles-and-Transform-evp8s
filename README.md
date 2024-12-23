# Expo Camera Transform Bug

This repository demonstrates a bug in Expo's Camera component related to using custom styles with a `transform` property. The bug can manifest as crashes or unexpected rendering behavior.

## Bug Description

Applying a `transform` style (such as scaling or rotation) to the Camera component can lead to crashes or visual glitches. This is inconsistent and may only appear on certain devices or Expo versions.

## Reproduction Steps

1. Clone this repository.
2. Run `npm install`.
3. Run `expo start`.
4. Observe the camera rendering.  It may crash immediately or render incorrectly. 