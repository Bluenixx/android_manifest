# Bluenixx build guide

---

Create directory for bluenixx
```
mkdir ~/bluenixx
cd ~/bluenixx
```
```
repo init -u https://github.com/Bluenixx/android_manifest.git -b main
repo sync
```

Bluenixx flags

```
WITH_GAPPS +: true # false is default
```
```
MAINTAINER_BLUENIXX +: ZedissP
```

Build
```
lunch lineage_$codename-bp4a-user # or userdebug
```

```
m bluenixx
```
