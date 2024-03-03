## OZTURK Umbrel App Store

This repository contains the OZTURK Umbrel App Store. This app store is a community app store that is not maintained by the Umbrel team. It is maintained by 1kemalozturk.

## UI How to

How to add the App Store:

https://github.com/1kemalozturk/umbrel-apps/assets/1289128/74a64d5e-a83f-4629-83a9-c70f11d9bb2d

## CLI How to

To add an app store:

```
sudo ~/umbrel/scripts/repo add https://github.com/1kemalozturk/umbrel-apps.git
```

To update an app store:

```
sudo ~/umbrel/scripts/repo update
```

To install an app from the app store

```
sudo ~/umbrel/scripts/app install ozturk-example-app
```

To remove an app store:

```
sudo ~/umbrel/scripts/repo remove https://github.com/1kemalozturk/umbrel-apps.git
```
