# GREENMAN PHONE BASELINE

Date: 2026-08-13

Baseline source APK: `GREENMAN_HEDGEWITCHERY_GOLD_ICON_SHORT_LABEL.apk`

Baseline build artifact: `GREENMAN_HEDGEWITCHERY_GITHUB_PHONE_BASELINE.apk`

APK SHA-256: `af58df2ae1b9000e154242782501744b9b93d177f5d82f1dbac79934fb9eb706`

## Incense base update

This baseline adds the new incense base pack to the exact GOLD ICON / SHORT LABEL phone APK rather than transplanting the change onto an older app build.

Base Blend now contains 50 scrolls:

- 8 Sabbat
- 4 Moon
- 12 Zodiac
- 4 Element
- 8 Planet
- 6 General / Ritual
- 8 God & Goddess

The 38 newly reconstructed blends are added without forcing every base to the same ingredient count.

Drawer filters are attached where agreed. Sabbat, Zodiac, Element, most Planet, purpose-specific General / Ritual, and deity bases narrow the optional ingredient drawer. Neptune and Universal remain unfiltered. Existing Moon bases retain their previous broad drawer behaviour.

Protected print, Book of Shadows, Grimoire, spell-builder and unrelated cupboard routes were not intentionally altered by this incense-base patch.

## Known retained source data

Yule and Litha still contain the legacy Acorn ingredient from the source phone APK. No replacement was invented silently. They remain for a separate approved replacement decision.

## Test record

- 50 base definitions parsed
- all base ingredients resolved to exact Herb/Oil names in this APK
- final cupboard scripts passed JavaScript syntax checks
- embedded inner script closing tags remained escaped at the outer single-file boundary
- APK ZIP integrity passed
- JAR signature verification passed

## Test signer

The rebuilt test APK uses a new self-signed phone-baseline debug certificate because the private key for the earlier debug signature is not contained in the source APK.

Certificate SHA-256: `1E:B6:81:9D:20:91:04:BF:82:59:DB:12:B0:36:FD:3B:33:91:EF:BC:E8:C3:75:FE:4B:23:4C:FE:F5:8A:94:CD`
