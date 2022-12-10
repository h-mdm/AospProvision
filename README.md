# Headwind MDM Provisioning Utility

This app is a fork of https://android.googlesource.com/platform/packages/apps/Provision and it helps to integrate Headwind MDM into the AOSP image.

In your AOSP build, replace the packages/apps/Provision package with this package, add the Headwind MDM APK in the ROM, and build AOSP. Your device will be provisioned with Headwind MDM.

Notice: replace values in Const.java to your custom values (server URL, device identification strategy, etc.).
