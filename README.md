## Public Repos

<table>
<tr>
<td width="50%" valign="top">

### [kindling](https://github.com/ciscoriordan/kindling)

[![Stars](https://img.shields.io/github/stars/ciscoriordan/kindling?style=flat&logo=github)](https://github.com/ciscoriordan/kindling/stargazers)
[![Release](https://img.shields.io/github/v/release/ciscoriordan/kindling?display_name=tag)](https://github.com/ciscoriordan/kindling/releases)
[![Last commit](https://img.shields.io/github/last-commit/ciscoriordan/kindling)](https://github.com/ciscoriordan/kindling/commits)

<div align="center"><a href="https://github.com/ciscoriordan/kindling"><img src="https://raw.githubusercontent.com/ciscoriordan/kindling/main/images/kindling_social.jpg" width="360" alt="Kindling Kindle toolkit"></a></div>

The missing Kindle toolkit. Dictionaries, books, and comics, built as a single static Rust binary with no dependencies. Reverse-engineered MOBI generator that replaces Amazon's deprecated *kindlegen* and is roughly 7,000x faster for large dictionaries.

</td>
<td width="50%" valign="top">

### [lemma](https://github.com/ciscoriordan/lemma)

[![Stars](https://img.shields.io/github/stars/ciscoriordan/lemma?style=flat&logo=github)](https://github.com/ciscoriordan/lemma/stargazers)
[![Release](https://img.shields.io/github/v/release/ciscoriordan/lemma?display_name=tag)](https://github.com/ciscoriordan/lemma/releases)
[![Last commit](https://img.shields.io/github/last-commit/ciscoriordan/lemma)](https://github.com/ciscoriordan/lemma/commits)

<div align="center"><a href="https://github.com/ciscoriordan/lemma"><img src="https://raw.githubusercontent.com/ciscoriordan/lemma/main/images/lemma_banner.png" width="360" alt="Lemma dictionary for Kindle"></a></div>

Free Modern Greek-English dictionary for Kindle e-readers. 31K headwords, 568K inflected-form lookups, built from Wiktionary data. Generator written in Rust.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [dilemma](https://github.com/ciscoriordan/dilemma)

[![Stars](https://img.shields.io/github/stars/ciscoriordan/dilemma?style=flat&logo=github)](https://github.com/ciscoriordan/dilemma/stargazers)
[![Release](https://img.shields.io/github/v/release/ciscoriordan/dilemma?display_name=tag)](https://github.com/ciscoriordan/dilemma/releases)
[![Last commit](https://img.shields.io/github/last-commit/ciscoriordan/dilemma)](https://github.com/ciscoriordan/dilemma/commits)

<div align="center"><a href="https://github.com/ciscoriordan/dilemma"><img src="https://raw.githubusercontent.com/ciscoriordan/dilemma/main/social.jpg" width="360" alt="Dilemma Greek lemmatizer"></a></div>

Diachronic Greek lemmatizer spanning Ancient (Classical, Homeric, Hellenistic), Medieval/Byzantine (vernacular and literary), and Modern Greek (Demotic and Katharevousa). Combines a 12.5M-form lookup table, dialect normalization, rule-based morphology, and a small character-level transformer.

</td>
<td width="50%" valign="top">

### [storescreens-cli](https://github.com/ciscoriordan/storescreens-cli)

[![Stars](https://img.shields.io/github/stars/ciscoriordan/storescreens-cli?style=flat&logo=github)](https://github.com/ciscoriordan/storescreens-cli/stargazers)
[![Release](https://img.shields.io/github/v/release/ciscoriordan/storescreens-cli?display_name=tag)](https://github.com/ciscoriordan/storescreens-cli/releases)
[![Last commit](https://img.shields.io/github/last-commit/ciscoriordan/storescreens-cli)](https://github.com/ciscoriordan/storescreens-cli/commits)

<div align="center"><a href="https://github.com/ciscoriordan/storescreens-cli"><img src="https://raw.githubusercontent.com/ciscoriordan/storescreens-cli/main/assets/banner.png" width="360" alt="StoreScreens"></a></div>

Capture App Store screenshots across every required device size in one command. Runs your UI tests on multiple simulators in parallel, organizes output by device and locale, and auto-detects which App Store size each simulator maps to. iPhone, iPad, Apple Watch, and Mac.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [opla](https://github.com/ciscoriordan/opla)

[![Stars](https://img.shields.io/github/stars/ciscoriordan/opla?style=flat&logo=github)](https://github.com/ciscoriordan/opla/stargazers)
[![Release](https://img.shields.io/github/v/release/ciscoriordan/opla?display_name=tag)](https://github.com/ciscoriordan/opla/releases)
[![Last commit](https://img.shields.io/github/last-commit/ciscoriordan/opla)](https://github.com/ciscoriordan/opla/commits)

<div align="center"><a href="https://github.com/ciscoriordan/opla"><img src="https://raw.githubusercontent.com/ciscoriordan/opla/master/opla.jpg" width="360" alt="Opla Greek POS tagger and dependency parser"></a></div>

GPU-optimized diachronic Greek POS tagger and dependency parser. 215x faster than *gr-nlp-toolkit* on real-world text, with identical POS output. Supports Modern, Ancient, and Medieval Greek.

</td>
<td width="50%" valign="top">

### [dragoman](https://huggingface.co/ciscoriordan/dragoman)

[![HF likes](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fmodels%2Fciscoriordan%2Fdragoman&query=%24.likes&label=%F0%9F%A4%97%20likes)](https://huggingface.co/ciscoriordan/dragoman)
[![HF downloads](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fmodels%2Fciscoriordan%2Fdragoman&query=%24.downloads&label=%F0%9F%A4%97%20downloads)](https://huggingface.co/ciscoriordan/dragoman)

<div align="center"><a href="https://huggingface.co/ciscoriordan/dragoman"><img src="https://cdn-thumbnails.huggingface.co/social-thumbnails/models/ciscoriordan/dragoman.png" width="360" alt="Dragoman Greek word alignment model"></a></div>

Diachronic word-alignment model for Ancient Greek, Modern Greek, and English. Fine-tuned from [UGARIT/grc-alignment](https://huggingface.co/UGARIT/grc-alignment) on Iliad parallel text with contrastive alignment training. Powers the word-tap alignment in [Iliad Aligned](https://iliadaligned.com).

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### [svg-flags](https://github.com/ciscoriordan/svg-flags)

[![Stars](https://img.shields.io/github/stars/ciscoriordan/svg-flags?style=flat&logo=github)](https://github.com/ciscoriordan/svg-flags/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/ciscoriordan/svg-flags)](https://github.com/ciscoriordan/svg-flags/commits)

<div align="center"><a href="https://github.com/ciscoriordan/svg-flags"><img src="https://raw.githubusercontent.com/ciscoriordan/svg-flags/main/social.png" width="740" alt="svg-flags"></a></div>

Clean, Xcode-compatible SVG flags with official colors in multiple shapes: circle, square, full-size, and simplified full-size. Fixes three issues with *circle-flags*: no Xcode support, circles only, and a reduced 11-color palette. [Browse the gallery](https://ciscoriordan.github.io/svg-flags)

</td>
</tr>
</table>

## Sites & apps

<table>
<tr>
<td width="50%" valign="top">

### [Iliad Aligned](https://iliadaligned.com)

<div align="center"><a href="https://iliadaligned.com"><img src="https://iliadaligned.com/og-image.jpg" width="360" alt="Iliad Aligned"></a></div>

iOS app presenting Homer's *Iliad* in parallel columns: Ancient Greek, Modern Greek (Polylas-Riordan), and English (Murray-Riordan). Tap any word for morphological analysis and dictionary definitions from Cunliffe, LSJ, and Wiktionary. [iliadaligned.com](https://iliadaligned.com)

</td>
<td width="50%" valign="top">

### [Tonos](https://tonospolytonic.com)

<div align="center"><a href="https://tonospolytonic.com"><img src="https://tonospolytonic.com/assets/og-image.png" width="360" alt="Tonos polytonic Greek keyboard"></a></div>

A polytonic Greek keyboard for iOS 18+. Dedicated diacritic row, plus autocorrect and typeahead powered by [dilemma](https://github.com/ciscoriordan/dilemma). Supports Classical, Koine, Byzantine, and Katharevousa orthographies. [tonospolytonic.com](https://tonospolytonic.com)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [CCWCalc](https://ccwcalc.com)

<div align="center"><a href="https://ccwcalc.com"><img src="https://ccwcalc.com/assets/og-image-b2c25e53c8e056ae9a69fd11b9828758730704933881b2cffcad4a5636da4262.jpg" width="360" alt="CCWCalc concealed carry laws"></a></div>

iOS app and web reference for concealed-carry laws and reciprocity across 50 states, DC, PR, GU, USVI, AS, CNMI, 365 Indian reservations, 169 military installations, and 176 on-base hotels. [ccwcalc.com](https://ccwcalc.com)

</td>
<td width="50%" valign="top">

### [Flex](https://flexlanguage.app)

<div align="center"><a href="https://flexlanguage.app"><img src="https://flexlanguage.app/images/04_StudyView.webp" width="200" alt="Flex Spanish conjugation app"></a></div>

Spanish verb conjugation app with full voseo coverage, FSRS spaced repetition, and GPU-accelerated speech recognition. 5,064 verbs, every tense and mood, free. [flexlanguage.app](https://flexlanguage.app)

</td>
</tr>
</table>
