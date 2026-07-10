Kraken Kernel v4 — Redwood Update

Device: POCO X5 Pro 5G / Redmi Note 12 Pro Speed — "redwood"

Changelogs:
- Rework GPU target frequency calculation for high refresh rates to reduce overly aggresive frequency requests in some games.
- Added support for SusFS 2.2
- Upstream KernelSU-NEXT to v3.3.0.
- Optimize LZ4 dictionary compression performance for zram.
- Remove all traces for defconfig
- fix the temperature when charging your cell phone
- Fix memory leaks
- UI improvements
- Add 150Mhz for battery saver
- Merge tag 'LA.UM.9.14.r1-25800-LAHAINA.QSSI15.0'
"LA.UM.9.14.r1-25800-LAHAINA.QSSI15.0"
- Merge tag 'LA.UM.9.14.r1-25800-LAHAINA.QSSI15.0'
- Merge CLO tag LA.UM.9.14.6.r1-02800-QCM6490.QISI14.0 into redwood
- techpack: audio-kernel: Update to CLO tag LA.UM.9.14.6.r1-02800-QCM6490.QISI14.0
- Enable SKhynix UFS HPB driver
- Merge tag 'LA.UM.9.14.1.r1-21100-QCM6490.QISI15.0' of redwood
- switch s2idle to deep for better idle drain
- recalculating the energy power for redwood
-----------------------------------------------

Kraken Kernel v3 — Redwood Update

Device: POCO X5 Pro 5G / Redmi Note 12 Pro Speed — "redwood"

Changelogs:
- set 560 MHz máx frequency for games 
- set 180 MHz minimum frequency for idle
- Updated Awinic AW882xx v2.0.0 driver
- Updated Vibration properties from CAF
- Merge CLO tag LA.UM.9.14.6.r1-02800-QCM6490.QISI14.0
- Fixed The cell phone wouldn't "turn off". (There was a bug when "turning off" the cell phone; it would restart the device.
- Improved Memory leaks 
- Add OverlayFS
- Idle drain improved 
- improvements in temperature (The cell phone was overheating.)
- Added F2FS optimizations
- Undervolt GPU
- Optimized CPU boost for LITTLE cores
• Fixed Cpufreq memory leaks
• Global wakelock timeout added
• Power-efficient workqueues enabled system-wide


any bugs, tag me in my group in telegram.


-----------------------------------------------

Kraken Kernel v2 — Redwood Update

Device: POCO X5 Pro 5G / Redmi Note 12 Pro Speed — "redwood"

Changelogs:
- debloated defconfig size to 15mb
- Fixes C6 BANK (br) It doesn't work
- improvements in excessive memory consumption
- disabling all debugs in defconfig
- improvements in screen response
- KernelSU-Next 3.2 includes
- Drop 90hz
- Introducing LZ4 COMPRESSION
- Improvements in TCP congestion
- Drop logs in firmware, techpack, awinic vibrator etc
- Improvements to the idle drain
- Fixed touch support for both FTS and GTX
- Added GPU low-power pwrlevel tuning / 180 MHz experiments
- Disabled watchdog for less unwanted watchdog behavior
- Reduced wakelock/sleep overhead
- Display patches to avoid panel dead restart loops
- Scheduler / latency / responsiveness tweaks
- Minor power and idle optimizations


any bugs, tag me in my group in telegram.


-----------------------------------------------
Kraken v1 initial realese - 27/04/'26
Changelogs:
- Fix Black screen when flashing the kernel.
- Fix kernel rebooting to fastboot.
- Removing the yellow line when activating battery saver or low brightness.
- Fix TOUCH FTS (gtx not tested).
- Fix haptics in kernel.
- Fix Audio for the entire system. (thanks rdx and anupam)
- Fix Bluetooth it didn't work on ROM ports.
- Fix camera It didn't record video or audio.
- Tweaky memory for 6/8
- Improvements for idle drain
- Improvements in device performance
- Optimize F2FS filesystem performance
- Enable UFS performance optimizations
- Restrict perf event sampling CPU time to 5%
- PM / freezer: Reduce freeze timeout to 1 second for Android
- Fix and silence excessive spam in dmesg
- Kill IRQ logspam
- Added support to KernelSU-NEXT (1.1.1)

This is an initial build; I hope you like my work. It took two to three months of effort. 
