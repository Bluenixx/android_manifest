# Bluenixx build guide

---

Create directory for bluenixx
```
mkdir ~/bluenixx
cd ~/bluenixx
```
```
repo init -u https://github.com/Bluenixx/android_manifest.git -b 23.2
repo sync
```

Bluenixx flags

```
BLUENIXX_MAINTAINER := Unknown
```
```
LINEAGE_BUILDTYPE := OFFICIAL
```
```
WITH_GMS_COMMS_SUITE := true
```

Build
```
lunch lineage_$codename-bp4a-user # or userdebug
```

```
m bacon
```
