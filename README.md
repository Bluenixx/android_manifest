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
LINEAGE_BUILDTYPE := OFFICIAL
```

Build
```
lunch bluenixx_$codename-bp4a-user # or userdebug
```

```
m bluenixx
```
