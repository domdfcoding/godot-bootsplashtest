# Boot Splash Test

The custom boot logo should show up when running in the editor (but not the editor window itself).
It should also show up when running the exported executable in this directory.
But copying the executable to a different directory means the logo won't show up, with the following error:

```
ERROR: Error opening file 'res://art/pbs-logo.png'.
   at: load_image (core/io/image_loader.cpp:90)
ERROR: Non-existing or invalid boot splash at 'res://art/pbs-logo.png'. Loading default splash.
   at: setup_boot_logo (main/main.cpp:3185)
```
