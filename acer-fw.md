# List of Acer firmware

| Device | Android | Status | Notes |
|---|---|---|---|
| Acer beTouch E110 | Android 1.5 | Works only on AE+ | Phone GPU option has to be disabled |
| Acer beTouch E120 | Android 2.1 | Works only on AE+ | Phone GPU option has to be disabled, OS may also crash in random moments | 
| Acer beTouch E130 | Android 2.1 | Works only on AE+ | Phone GPU option has to be disabled, OS may also crash in random moments | 
| Acer Iconia A100 | Android 3.0 | Doesn't boot | Both vanilla AEmulator and AEmulator+ treat it as Android 2.3, also both of them only start binderd and nothing else (could be misidentification? missing boot.img?) |
| Acer Iconia A101 | Android 3.2.1 | Boots only on AE+ (kind of) | On vanilla AEmulator, it's stuck on "Watiting for service SurfaceFlinger...". On AEmulator+, zygote crashes after it completes the first boot. Then when next boot completes, the UI and wallpaper gets rendered but after a moment the whole app crashes. Phone GPU option disabled causes zygote to enter crash loop. |
