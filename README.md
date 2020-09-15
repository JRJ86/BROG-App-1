# BROG-app
This repo contains the source code for the BRØG app as envisioned by VMAU group 42

## Android
The app targets android sdk version 30 (android 10) but is supported down to sdk version 26
(android 8.0 Oreo). This means that roughly 60% of android devices are supported.

The reason that the minimum android sdk level is set to 26, is that that is the lowest API level
that supports [Companion devices](https://developer.android.com/guide/topics/connectivity/companion-device-pairing)
. This Feature is very likely to be used in this project so as to avoid potential problems at
runtime due to not thinking about this constraint, the support is capped instead. This might change
in the future if we decide to include more devices.