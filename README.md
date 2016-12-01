## TWRP device tree for Galaxy J7 (2016 Exynos)

Add to `.repo/local_manifests/j7xelte.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/j7xelte" name="android_device_samsung_j7xelte" remote="TeamWin" revision="android-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

Kernel sources are available at: https://github.com/jcadduono/android_kernel_samsung_exynos7870/tree/twrp-6.0

