# List of Acer firmware

| Device | Android | Status | Notes | Link |
|---|---|---|---|---|
| Acer beTouch E110 | Android 1.5 | Works only on AE+ | Phone GPU option has to be disabled | [Mediafire](https://www.mediafire.com/file/zaqz3nere0g7bsw) |
| Acer beTouch E120 | Android 2.1 | Works only on AE+ | Phone GPU option has to be disabled, OS may also crash in random moments | [Mediafire](https://www.mediafire.com/file/kwrxyhqx5rmbwtq) |
| Acer beTouch E130 | Android 2.1 | Works only on AE+ | Phone GPU option has to be disabled, OS may also crash in random moments | [Mediafire](https://www.mediafire.com/file/cauh1rkg4rpcb39) |
| Acer Iconia A100 | Android 3.0 | Doesn't boot | Both vanilla AEmulator and AEmulator+ treat it as Android 2.3, also both of them only start binderd and nothing else (could be misidentification? missing boot.img?) | - |
| Acer Iconia A101 | Android 3.2.1 | Boots only on AE+ (kind of) | On vanilla AEmulator, it's stuck on "Watiting for service SurfaceFlinger...". On AEmulator+, zygote crashes after it completes the first boot. Then when next boot completes, the UI and wallpaper gets rendered but after a moment the whole app crashes. Phone GPU option disabled causes zygote to enter crash loop. | [Mediafire](https://www.mediafire.com/file/vpr2sm648iojl4z) |
| Acer Iconia A210 | Android 4.0 | Doesn't boot | Both vanilla AEmulator and AEmulator+ treat it as Android 2.3, also both of them only start binderd and nothing else (could be misidentification? missing boot.img?) | - |
| Acer Iconia A200 | Android 4.0.3 | Boots (kind of) | On both vanilla AEmulator and AEmulator+, the OS is unusable due to constant Launcher crash. | [Mediafire](https://www.mediafire.com/file/4hxl8w9mk0nnjun) |
| Acer Iconia A510 | Android 4.0.3 | Boots (kind of) | On both vanilla AEmulator and AEmulator+, the OS is unusable due to constant Launcher crash. | [Mediafire](https://www.mediafire.com/file/udg4dzyq79atvn4) | 
| Acer Liquid Gallant E350 | Android 4.0.3 | Doesn't boot | On vanilla AEmulator, everything crashes with various codes. On AEmulator+, it errors with "this firmware has no Android framework and no native MMI/FTM test program to run instead" | - |
| Acer CloudMobile S500 | Android 4.0.4 | Doesn't boot | Doesn't boot on both vanilla AEmulator and AEmulator+ due to boot getting stuck on gsiff_daemon exiting with code 255. | - |
| Acer Iconia A110 | Android 4.1 | Doesn't boot | Both vanilla AEmulator and AEmulator+ treat it as Android 2.3, also both of them only start binderd and nothing else (could be misidentification? missing boot.img?) | - |
| Acer Liquid E1 | Android 4.1.1 | Boots (kind of) | On vanilla AEmulator and AEmulator+, the OS is unusable (the OS doesn't even react to any touch and trying to do anything cause SurfaceFlinger and zygote to crash). | [Mediafire](https://www.mediafire.com/file/a49lr00c1hgl12x) |
| Acer Liquid Z2 | Android 4.1.1 | Boots (kind of) | On vanilla AEmulator and AEmulator+, the OS is unusable (the OS doesn't even react to any touch and trying to do anything cause SurfaceFlinger and zygote to crash). | [Mediafire](https://www.mediafire.com/file/2x4vgwp8wte43wu) |
| Acer Iconia B1-A71 | Android 4.1.2 | Boots only on vanilla (kind of) | Doesn't boot on AEmulator+ as when the OS reports "guest connected", zygote exits with code 137. On vanilla AEmulator, the OS is unusable (the OS doesn't even react to any touch and trying to do anything cause SurfaceFlinger and zygote to crash). | [Mediafire](https://www.mediafire.com/file/fbjnzw6yatatu6j) |
