# Bluenixx build guide

![banner](banner/banner.png)

---

Create directory for bluenixx
```
mkdir ~/bluenixx
cd ~/bluenixx
```
```
repo init -u https://github.com/Bluenixx/android_manifest.git -b lineage-23.2
repo sync
```

Bluenixx flags

```
BLUENIXX_MAINTAINER := Unknown # Yourname
```
```
LINEAGE_BUILDTYPE := OFFICIAL # UNOFFICIAL
```
```
WITH_GMS_COMMS_SUITE := true # false
```

Build
```
lunch lineage_$codename-bp4a-user # or userdebug
```

```
m bacon
```
