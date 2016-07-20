## TWRP device tree for Galaxy On5 (T-Mobile & MetroPCS)

Add to `.repo/local_manifests/on5ltetmo.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/on5ltetmo" name="android_device_samsung_on5ltetmo" remote="TeamWin" revision="android-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

Kernel sources are available at: https://github.com/jcadduono/android_kernel_samsung_exynos3475/tree/twrp-6.0

