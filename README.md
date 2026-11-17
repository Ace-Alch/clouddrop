<div align="center">
<img src="portfolio-assets/cover.svg" width="100%" alt="CloudDrop project cover">

# CloudDrop

**Share and manage files through a Telegram bot with links, QR codes and expiry controls.**

Telegram � Google Drive � OAuth � QR codes

[Overview](#overview) � [Design](portfolio/DESIGN.md) � [Setup](portfolio/SETUP.md) � [Validation](portfolio/VALIDATION.md) � [Evidence](portfolio/EVIDENCE.md)
</div>

<p align="center"><a href="https://ace-alch.github.io/work/clouddrop/"><img alt="View project" src="https://img.shields.io/badge/View%20project-38bdf8?style=for-the-badge&logo=githubpages&logoColor=white"></a> <a href="portfolio/DESIGN.md"><img alt="Explore design" src="https://img.shields.io/badge/Explore%20design-30363d?style=for-the-badge&logo=readthedocs&logoColor=white"></a> <a href="portfolio/SETUP.md"><img alt="Setup guide" src="https://img.shields.io/badge/Setup%20guide-30363d?style=for-the-badge&logo=github&logoColor=white"></a> <a href="portfolio/EVIDENCE.md"><img alt="Evidence" src="https://img.shields.io/badge/Evidence-30363d?style=for-the-badge&logo=readthedocs&logoColor=white"></a></p>
<p align="center"><strong>Telegram bot</strong> � <a href="https://ace-alch.github.io/">Engineering portfolio</a></p>



## Overview

| Item | Record |
| :-- | :-- |
| Project type | Telegram bot |
| Field | Software |
| Material in this package | Documentation package; original source not included |
| Documentation review | 17 November 2026 |

## Scope

Share and manage files through a Telegram bot with links, QR codes and expiry controls.

### Main elements

- Telegram request
- Bot command handling
- Drive storage
- Share link
- Expiry control

## Start here

1. Read the [design record](portfolio/DESIGN.md) for the system elements and boundaries.
2. Follow the [setup record](portfolio/SETUP.md) for available entry points.
3. Use the [validation plan](portfolio/VALIDATION.md) to record reproducible results.
4. Check the [evidence register](portfolio/EVIDENCE.md) before reusing claims.

## Technical limits

OAuth grants, bot tokens, Drive credentials and private share links must be supplied through private configuration. A generated QR code does not change the access rules of its target file. Confirm expiry at the file and link layer.

## Source status

This package contains project documentation and visual assets. Original code, CAD, data and test records have not been added. The setup record lists the files needed for a reproducible release.

## Next work

- [ ] Latest source revision
- [ ] Dependency file
- [ ] Token-free configuration
- [ ] OAuth and expiry tests

## Credits and reuse

Project record: Mehdi Moallemkolaei. Specific third-party and course contributions must retain their original notices.

Existing license terms remain in effect. This package does not grant a new license over source code, course material, models or datasets. See [reuse and contribution notes](portfolio/CONTRIBUTIONS.md).
