# 2019 Toyota Mirai — Radio & Apple CarPlay Guide

An independent, mobile-friendly reference site for the U.S.-market 2019 Toyota Mirai factory Entune 3.0 audio system.

## What's included
- Factory radio and JBL audio overview
- Physical audio controls and radio preset guidance
- Bluetooth phone/audio, USB, and AUX overview
- Clear explanation that Apple CarPlay was not listed as a factory feature on the U.S. 2019 Mirai
- Checklist for researching aftermarket CarPlay options
- Links to Toyota documentation and manual references

## GitHub Pages
This repository contains a static index.html site and needs no build step.

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**, then save.
4. Wait for GitHub Pages to publish the site.

Expected URL: https://wonka15.github.io/Toyota-Mirai-2019-Apple-Carplay-/

## Accuracy & safety
This is an independent owner resource, not an official Toyota site. Verify equipment and part compatibility on the actual vehicle. Aftermarket radio fitment, JBL integration, cameras, and steering-wheel controls must be confirmed before purchase or installation. Do not work on high-voltage fuel-cell systems.

## Sources
- [2019 Toyota Mirai eBrochure (PDF)](https://www.refresh.tcuv.tms.aws.toyota.com/content/dam/tcuv/sections/brochures/en/mirai/2019_mirai_ebrochure.pdf)
- [Toyota Owners manuals and resources](https://www.toyota.com/owners/resources/warranty-owners-manuals/)
- [2019 Mirai Audio & Navigation manual reference](https://www.carmanualsonline.info/toyota-mirai-2019-accessories-audio-navigation-in-english-5/)


## Critical warning: unofficial CarPlay modification
The community-reported Mirai method is **not a Toyota-approved 2019 Mirai retrofit**. The Reddit discussion [“Getting Apple Carplay on 2018 Toyota Mirai (How-To)”](https://www.reddit.com/r/Mirai/comments/1705d2k/) (October 5, 2023) reports using files associated with Toyota T-SB-0057-19 / Camry multimedia packages and claims applicability to 2018–2020 Mirai. That Mirai compatibility claim comes from the Reddit poster, not Toyota.

Toyota T-SB-0057-19 is officially listed for 2018 Camry, Camry Hybrid, and Sienna—not Mirai. The bulletin describes a full multimedia-system reformat and explicitly warns that failure to follow its procedure exactly may damage the head unit. [Official bulletin PDF hosted by NHTSA](https://static.nhtsa.gov/odi/tsbs/2019/MC-10161540-9999.pdf).

**Risk disclosure:** Wrong files, a mismatched head-unit model ID, incorrect USB file layout, power interruption, or incompatible software can cause a frozen unit, boot loop, loss of functions, or a bricked head unit. Recovery may require specialist repair or replacement and may be costly. No success or recovery is guaranteed; warranty/dealer coverage is not guaranteed. Anyone considering the modification does so at their own risk. This repository and its contributors accept no responsibility for damage or costs. This is not legal advice.

The repository owner reports that the modification has worked smoothly on their personal vehicle for more than three years. This is an individual report, not proof of universal compatibility or a guarantee for another vehicle.


## Community-reported files and USB format

The original community discussion refers to two Camry multimedia software packages:

1. **T-SB-0057-19 — Camry Audio Plus / Premium**
2. **2018 Camry Premium Audio**

These are package descriptions from the community post, not Mirai-specific Toyota firmware. This repository does not host or redistribute the files. Verify the exact archive names, contents, and head-unit compatibility from the original source before considering any modification.

The community post specifies a **16 GB USB flash drive formatted as FAT32** (not exFAT), with the extracted update files placed at the USB drive's root rather than inside an extra nested folder. Correct formatting and folder placement do **not** make an incompatible package safe. Identify the exact head-unit model ID and software version first. The Toyota bulletin itself lists Camry, Camry Hybrid, and Sienna—not Mirai—and warns that an incorrect procedure can damage the head unit.


## Optional wireless CarPlay adapter

Use the **front center-console USB media/data port** for the CarPlay connection. This is distinct from the rear USB charging ports, which are for charging and are not the CarPlay data connection. After the community software modification has successfully enabled **wired CarPlay**, a wireless CarPlay USB adapter may allow an iPhone to connect to CarPlay over Bluetooth and Wi-Fi instead of being plugged in for every trip.

The adapter itself remains plugged into the Mirai's USB media/data port. It reduces repeated plugging and unplugging of the phone cable; it does not free up or replace the vehicle USB port, and it does not add CarPlay by itself.

**Compatibility is not confirmed for this specific Mirai software modification.** First verify that wired CarPlay works directly through the front center-console USB media/data port. Then obtain written compatibility confirmation from the adapter manufacturer for the exact 2019 Mirai head unit and its modified software before purchasing. A generic wireless CarPlay dongle normally requires an already-working wired CarPlay system. Do not plug it into a charge-only USB socket.
