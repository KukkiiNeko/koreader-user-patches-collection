# KOReader Catified User Patches and more

This is a Collection of patches I use and have catified. Author credit goes to the respective users.

The base patches are from [SeriousHornet](https://github.com/SeriousHornet/KOReader.patches/tree/main). These customizations are an **addition** to those patches. Please follow the instructions in that repo, to install PT patches.

In addition you may also enjoy the [black cat supremacy iconspack](https://www.reddit.com/r/koreader/comments/1os7n7d/comment/nnvfdll/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) from AggravatingDebt4621 on Reddit

## How to use these patches
Please [check the guide here.](https://koreader.rocks/user_guide/#L2-userpatches)

---

## 🐾 Catified look
<img width="450" height="600" alt="FileManager_2025-11-10_210630" src="https://github.com/user-attachments/assets/a6e03afa-9d37-482a-9e74-6b47b3952325" />

This includes the black cat supremacy pack for the menu icons

---

## 🐾 2-new-status-icons.lua catified
- Download [2-new-status-icons.lua](https://github.com/SeriousHornet/KOReader.patches/blob/main/2-new-status-icons.lua) into `koreader/patches`
- replace the `dogear` svgs with the cat version in [catIcons](https://github.com/KukkiiNeko/koreader-user-patches-collection/tree/main/icons%20catified) into `koreader/icons`
- For bigger Icon size, adjust in `2-new-status-icons.lua` the line `local corner_mark_size = math.floor(math.min(self.width, self.height) / 8)` to any smaller divider.
  I am using 7.
  - `local corner_mark_size = math.floor(math.min(self.width, self.height) / 7)`

---

## 🐾 2-percent-badge.lua catified
- Download [2-pages-badge.lua](https://github.com/SeriousHornet/KOReader.patches/blob/main/2-pages-badge.lua) into `koreader/patches`
- replace the `percent.badge.svg` with the cat version in [catIcons](https://github.com/KukkiiNeko/koreader-user-patches-collection/tree/main/icons%20catified) into `koreader/icons`
- For better placement and size, adjust in `2-percent-badge.lua`
  - `text_size` = 0.26
  - `move_on_x` = -5
  - `move_on_y` = -13
  - `badge_w` = 75
  - `badge_h` = 42

You may need to tweak this based on the screensize you are using.

---

## Bookmark Screensaver
These are transparent PNGs which show up like a bookmark in your book. Just add any of [Bookmark_Screensaver](https://github.com/KukkiiNeko/koreader-user-patches-collection/tree/f8eee80620608f5901a1de0dd8ea0d5691ecb03d/Bookmark_Screensaver) to your dedicated screensaver folder and select them in KOReader.

You have permission to change the mark color of the grey ribbon bookmarks, but you cannot redistribute these. Personal use only!!

<img width="1500" height="919" alt="Bookmarks" src="https://github.com/user-attachments/assets/8e584b8a-9cba-4c47-a191-c5cbd54e9167" />

---

## Disclaimer
I did not write any of those patches, I only customized them visually mainly. Any feature improvement is done by the original authors
