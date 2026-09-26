# press/pukingcat/

Images for inline embedding in the Puking Cat Devpost submission (and other
external write-ups). They live HERE, in the public personal-site repo, rather
than in `evanca/pukingcat` beside the rest of the press kit, for one reason:
on 2026-09-22 GitHub stopped serving Pages for this account's PRIVATE repos,
and `happycode.studio/pukingcat/` went to 404 site-wide — root included — with
the Pages build still reporting `built` and no error. Public repos on the same
domain kept serving. Moving the files here was the fix that needed no repo to
change visibility. If `pukingcat` is ever made public, these can move back and
the URLs change again, so check what the live submission points at first.

    https://happycode.studio/press/pukingcat/<file>

Embed with `![alt](that url)`. A new file takes a minute or two to appear while
Pages rebuilds. Keep filenames lowercase with no spaces.

| File | What it shows | Source |
| --- | --- | --- |
| `win_kitchen.png` | Win panel: rewarded "watch ad to double your Puke Coins" card next to REMOVE ADS — the whole free-player monetisation surface in one frame. Upscaled art (`HIRES_ART=true`), simulator/debug frame, so no frame-rate claims. | `puking_cat` repo, `docs/launch/video/ios_demo_2026-09-20/stills/` |
| `tutorial-books-before-after-4k.png` | The tutorial room book stack: the original raster prop next to the hand-traced SVG that replaced it (`a3435dca`). | `puking_cat` repo, `shipaton/video/` |
| `22-made-for-foldables.png` | Made for foldables card: the level filling a Fold panel, the half-folded Flex Mode layout with the room at the hinge and controls below it, and a Flip cover-screen wallpaper (not cover-screen gameplay). | `puking_cat` repo, `shipaton/video/ux/` |
| `02-anatomy-of-a-shot.png` | Anatomy of a shot: the kitchen HUD with nine callouts — home, Puke Coins, angle dial, room plaque, pause/sound, shots left, launch button, the cat, the splat. | `puking_cat` repo, `shipaton/video/ux/` |
| `06-gameplay-ui.webp` | Gameplay UI sheet: the cat-muzzle launch button in its idle, pressed, angle-locked and disabled states, plus the angle dial, power meter, cat-head shot counters, stars and coins. All vector. | `puking_cat` repo, `shipaton/video/ux/` |
| `noise-new-customers-aug-sep.png` | RevenueCat Charts, New Customers, daily, 15 Aug – 15 Sep 2026, with the `Noise: Maximum views` annotation over 29 Aug – 1 Sep. | RevenueCat console screenshot, also in `puking_cat` at `shipaton/evidence/noise/2026-09-22-new-customers-aug15-sep15.png` |
| `shop-wardrobe-japanese.png` | The costume shop in Japanese on v2.8.0: candy title as ショップ in live layered text, きがえ / ゲロカラー tabs, costume names and 所持 / 使用中 buttons, over the Halloween shop art. Evidence that headings and UI translate without being redrawn. | `puking_cat` repo, `docs/launch/screenshots/2_8_0/ja/shipaton/07_shop_wardrobe.png` |

## Additional judge notes

| File | What it shows | Source |
| --- | --- | --- |
| `16-dialogs.png` | Four rendered dialog states: standard win/fail and their optional rewarded-ad offers, together for comparison. | `puking_cat` repo, `shipaton/video/ux/16-dialogs.png` |
| `14-inside-the-shop.png` | Slime palette previews and themed particles, a costume purchase confirmation, and the shop button states. | `puking_cat` repo, `shipaton/video/ux/14-inside-the-shop.png` |

These existing sheets were copied without image changes on 2026-09-26. The additional
notes also reuse `22-made-for-foldables.png`, already hosted above. Static sheets
show appearance and layout; they do not establish animation smoothness or frame rate.

## Focused judge collages (2026-09-26)

The owner requested new compositions rather than reuse of the general UX sheets.

| File | Contents |
| --- | --- |
| `judges-ad-dialogs.png` | Coin-doubling offer, extra-shot offer, Earn Puke Coins guide, reward confirmation. |
| `judges-galaxy-flex.png` | Fold7 and Flip7 Flex Mode, from release-emulator captures. |
| `judges-costumes-palettes.png` | Costume shop and slime palette previews side by side. |

Sources and reproducible HTML/CSS layout: `puking_cat/shipaton/judge_sheets/`.
Screenshot text and artwork are preserved; these are new layouts of existing captures.
Previous image files remain available for existing links.
