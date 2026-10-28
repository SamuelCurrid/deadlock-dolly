### Deadlock Dolly v0.6.80-alpha

**0.6.80-alpha**

- **Bone camera vertical aim lock.** *Before:* Bone and Weapon views could tilt as a player aimed up or down. *After:* an opt-in per-camera lock keeps the chosen vertical angle steady. Detach and Snap again when changing it. Thanks to [@ExoCalibra](https://github.com/ExoCalibra) for the original contribution.

- **Experimental replay repair.** *Before:* some locally recorded demos crashed Deadlock while loading. *After:* Dolly can make a separate experimental copy for one specific resource-loading problem; the original stays untouched and the copy still needs a playback test.

- **More accurate video color.** *Before:* compressed exports could appear with shifted colors in editing software. *After:* SDR color recordings and alpha layers use Rec. 709 conversion and color information.

- **QuickTime recording.** *Before:* choosing MOV could be rejected when recording through FFmpeg. *After:* compressed MOV exports are accepted and carry the correct color information.
