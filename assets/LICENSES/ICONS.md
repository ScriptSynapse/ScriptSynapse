# Fonts, icons and images used in the profile SVGs

All artwork is embedded inside each SVG (base64), so nothing is fetched when GitHub renders the images.

## Fonts (SIL Open Font License 1.1)

| Font | Use | Source | License |
|---|---|---|---|
| Unbounded (weights 800 and 500, static instances) | Display headings | google/fonts `ofl/unbounded/Unbounded[wght].ttf` | `OFL-Unbounded.txt` |
| JetBrains Mono (weights 400 and 700, static instances) | Mono / body text | google/fonts `ofl/jetbrainsmono/JetBrainsMono[wght].ttf` | `OFL-JetBrainsMono.txt` |

The variable fonts were instanced and subset to Latin + a few symbols, then saved as WOFF2. Neither font declares a Reserved Font Name; the embedded families are renamed per file (`hr-Display`, `hr-Mono`, …) anyway.

## Brand icons

| Icon | Source | License / terms |
|---|---|---|
| Python, C, JavaScript, Wireshark, Splunk, scikit-learn, Linux, Git, Flask, MySQL, GitHub, Instagram | Simple Icons v16.35.0 (`simple-icons/simple-icons`, commit `4d29a35`) | CC0 1.0 (`SIMPLE-ICONS-CC0.md`). Shown in brand colour; Python, MySQL, Wireshark, Splunk and GitHub use the monochrome (off-white) variant because their brand colour falls below 4:1 contrast on the dark node; GitHub and Instagram are also monochrome on the connect cards. |
| Zeek | Official logo, `zeek/zeek` → `doc/images/zeek-logo.png` (commit `25c490d`) | Zeek project mark, shown unmodified on a light plate. Repo license in `ZEEK-COPYING.txt`. Not in Simple Icons. |
| YARA | Official logo, `VirusTotal/yara` → `extra/logo.svg` (commit `ecfe1cf`); the red symbol paths only, unmodified | Repo license in `YARA-COPYING.txt`. Not in Simple Icons. |
| LinkedIn | Not in Simple Icons (removed at LinkedIn's request), and LinkedIn's brand-asset site was not reachable from the build environment. Used Devicon's reproduction of the official "in" bug, `devicons/devicon` → `icons/linkedin/linkedin-original.svg` (commit `6a37858`), unmodified. | Devicon is MIT (`DEVICON-MIT.txt`); the LinkedIn mark is a trademark of LinkedIn Corporation. Swap in the file from brand.linkedin.com if you prefer the first-party download. |
| XGBoost | Official logo, `xgboost-ai/xgboost-ai.github.io` → `images/logo/xgboost-logo-trimmed.svg` (commit `cb39762`), unmodified | Project mark (DMLC/XGBoost). Not in Simple Icons. |

## Generic glyphs (drawn for this profile, not brand marks)

| Item | Why |
|---|---|
| SQL | A query language, not a product; no brand mark exists. Database glyph. |
| Sysmon | Not in Simple Icons and Microsoft publishes no openly licensed Sysinternals/Sysmon mark; a monitor-with-signal glyph is used and the label says "Sysmon". |
| Random Forest | An algorithm, not a product; tree glyph. |
| Portfolio | Personal website; globe glyph. |

All trademarks belong to their owners and are used only to identify the tools.

## Photos

`id.png` and `right_pointing.png` are the owner's own images. They are embedded as downscaled PNGs (Lanczos resize only, alpha channel kept); nothing was redrawn, masked or retouched.
