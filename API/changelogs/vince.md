# 21-May-2022

- Shipped with Unitrix kernel 4.9.315
- Bump to May raven fp.
- Fixed USB Tethering.
- Fixed Wifi display / Cast lag.
- Fixed display blank while AOD on/off screen.
- Fixed deprecated display power-profile items.
- Fixed zram init process for zram writeback.
- Added offline charging LED indicator.
- Added APN config from Pixel 5 (RQ3A.210905.001).
- Added blur support (To disable blur go to Settings > Display > Allow window-level blurs).
- Enabled VoLTE for supported carriers.
- Enabled rotation in all directions.
- Disabled unsupported perf resources.
- Updated Perf blobs from LA.UM.9.6.2.r1-04200-89xx.0
- Updated msm_irqbalance from LA.UM.9.6.2.r1-04200-89xx.0
- Updated surfaceflinger props.
- Updated some privapp and IMS related permissions.
- Restored Dalvik configurations from vince-user-8.1.0-OPM1.171019.019-V11.0.2.0.OEGMIXM-release-keys.
- Removed confusing options in network settings (Preffered network type).
- Removed configstore & renderscript implementation.
- Removed some bloats from gapps variant to reduce zip size.
- Whitelisted System apps for Applock.
- Addressed some sepolicy denials.
- Adjusted maximum no. of visible notification & system icons.
- Switched to QTI Health implementation.
- Moved some props from vendor to system, product, odm partitions.
- Many Under the hood fixes and Performance improvement.

- Note: Enabling blur will lag your device in some cases. It is therefore not recommended to use blur/transparent qs for now. I added blur feature so as not to lose the beauty of transparent qs added from the source but our device can't handle blur smoothly.