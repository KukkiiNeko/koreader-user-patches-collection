# KOReader Catified User Patches

This is a Collection of patches I use and have catified. Author credit goes to the respective users.

The base patches are from [SeriousHornet](https://github.com/SeriousHornet/KOReader.patches/tree/main). These customizations are an **addition** to those patches. Please follow the instructions in that repo, to install PT patches.

## How to use these patches
Please [check the guide here.](https://koreader.rocks/user_guide/#L2-userpatches)

---

## 2-new-status-icons.lua catified
- Download [2-new-status-icons.lua](https://github.com/SeriousHornet/KOReader.patches/blob/main/2-new-status-icons.lua) into `koreader/patches`
- replace the `dogear` svgs with the cat version in [catIcons](https://github.com/KukkiiNeko/koreader-user-patches-collection/tree/main/icons%20catified) into `koreader/icons`
- For bigger Icon size, adjust in `2-new-status-icons.lua` the line `local corner_mark_size = math.floor(math.min(self.width, self.height) / 8)` to any smaller divider.
  I am using 7.
  - `local corner_mark_size = math.floor(math.min(self.width, self.height) / 7)`

---

## 2-percent-badge.lua catified
- Download [2-new-status-icons.lua](https://github.com/SeriousHornet/KOReader.patches/blob/main/2-new-status-icons.lua) into `koreader/patches`
- replace the `percent.badge.svg` with the cat version in [catIcons](https://github.com/KukkiiNeko/koreader-user-patches-collection/tree/main/icons%20catified) into `koreader/icons`
- For better placement and size, adjust in `2-percent-badge.lua`
  - `text_size` = 0.26
  - `move_on_x` = -5
  - `move_on_y` = -13
  - `badge_w` = 75
  - `badge_h` = 42

You may need to tweak this based on the screensize you are using.

---

## Disclaimer
I did not write any of those patches, I only customized them visually mainly. Any feature improvement is done by the original authors
