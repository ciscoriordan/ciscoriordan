## [Open Greek](https://github.com/open-greek)

Open source Greek NLP, corpora, and typography, developed under the [Open Greek](https://github.com/open-greek) organization on [GitHub](https://github.com/open-greek) and [Hugging Face](https://huggingface.co/open-greek).

<table>
<tr>
<td width="50%" valign="top">

### [dilemma](https://github.com/open-greek/dilemma)

[![Stars](https://img.shields.io/github/stars/open-greek/dilemma?style=flat&logo=github)](https://github.com/open-greek/dilemma/stargazers)
[![Release](https://img.shields.io/github/v/release/open-greek/dilemma?display_name=tag)](https://github.com/open-greek/dilemma/releases)
[![Last commit](https://img.shields.io/github/last-commit/open-greek/dilemma)](https://github.com/open-greek/dilemma/commits)

<div align="center"><a href="https://github.com/open-greek/dilemma"><img src="https://raw.githubusercontent.com/open-greek/dilemma/main/scripts/social.jpg" width="360" alt="Dilemma Greek lemmatizer, POS tagger, dependency parser"></a></div>

Diachronic Greek NLP package spanning Ancient (Classical, Homeric, Hellenistic), Medieval/Byzantine (vernacular and literary), and Modern Greek (Demotic and Katharevousa). A four-layer lemmatizer that falls back in priority order, from a 12.5M-form lookup (the largest compiled for Greek) through rule-based stripping and dialect normalization to a character-level transformer for unseen forms, plus a POS tagger and dependency parser.

</td>
<td width="50%" valign="top">

### [open-greek-corpus](https://github.com/open-greek/open-greek-corpus)

[![Stars](https://img.shields.io/github/stars/open-greek/open-greek-corpus?style=flat&logo=github)](https://github.com/open-greek/open-greek-corpus/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/open-greek/open-greek-corpus)](https://github.com/open-greek/open-greek-corpus/commits)

<div align="center"><a href="https://github.com/open-greek/open-greek-corpus"><img src="https://raw.githubusercontent.com/open-greek/open-greek-corpus/main/assets/social/github-social.png" width="360" alt="Open Greek Corpus"></a></div>

An open, comprehensive corpus of ancient Greek literature: openly-licensed digital editions, plus state-of-the-art OCR of public-domain editions for the texts the open corpora don't yet cover. A public, freely-usable counterpart to the major subscription corpora.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [lemma](https://github.com/open-greek/lemma)

[![Stars](https://img.shields.io/github/stars/open-greek/lemma?style=flat&logo=github)](https://github.com/open-greek/lemma/stargazers)
[![Release](https://img.shields.io/github/v/release/open-greek/lemma?display_name=tag)](https://github.com/open-greek/lemma/releases)
[![Last commit](https://img.shields.io/github/last-commit/open-greek/lemma)](https://github.com/open-greek/lemma/commits)

<div align="center"><a href="https://github.com/open-greek/lemma"><img src="https://raw.githubusercontent.com/open-greek/lemma/main/images/lemma_banner.png" width="360" alt="Lemma dictionary for Kindle"></a></div>

Free Modern Greek-English dictionary for Kindle e-readers. 31K headwords, 568K inflected-form lookups, built from Wiktionary data. Generator written in Rust.

</td>
<td width="50%" valign="top">

### [dragoman](https://huggingface.co/open-greek/dragoman)

[![HF likes](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fmodels%2Fopen-greek%2Fdragoman&query=%24.likes&label=%F0%9F%A4%97%20likes)](https://huggingface.co/open-greek/dragoman)
[![HF downloads](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fmodels%2Fopen-greek%2Fdragoman&query=%24.downloads&label=%F0%9F%A4%97%20downloads)](https://huggingface.co/open-greek/dragoman)

<div align="center"><a href="https://huggingface.co/open-greek/dragoman"><img src="https://huggingface.co/open-greek/dragoman/resolve/main/thumbnail.png" width="360" alt="Dragoman Greek word alignment model"></a></div>

Diachronic word-alignment model for Ancient Greek, Modern Greek, and English. Fine-tuned from [UGARIT/grc-alignment](https://huggingface.co/UGARIT/grc-alignment) on Iliad parallel text with contrastive alignment training. Powers the word-tap alignment in [Iliad Aligned](https://iliadaligned.com).

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [greek-majuscule-fonts](https://github.com/open-greek/greek-majuscule-fonts)

[![Stars](https://img.shields.io/github/stars/open-greek/greek-majuscule-fonts?style=flat&logo=github)](https://github.com/open-greek/greek-majuscule-fonts/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/open-greek/greek-majuscule-fonts)](https://github.com/open-greek/greek-majuscule-fonts/commits)

<div align="center"><a href="https://github.com/open-greek/greek-majuscule-fonts"><img src="https://raw.githubusercontent.com/open-greek/greek-majuscule-fonts/main/assets/banner.png" width="360" alt="Greek Majuscule Fonts"></a></div>

Five Greek majuscule fonts, each in the scribal hand of a different Oxyrhynchus papyrus (P.Oxy. 2162, 2174, 2181, 2256, 2506). Type uppercase Greek and the letters render in the actual hand of an ancient scribe. Ships in OTF, TTF, and WOFF2.

</td>
</tr>
</table>

## Public Repos

<table>
<tr>
<td width="50%" valign="top">

### [kindling](https://github.com/ciscoriordan/kindling)

[![Stars](https://img.shields.io/github/stars/ciscoriordan/kindling?style=flat&logo=github)](https://github.com/ciscoriordan/kindling/stargazers)
[![Release](https://img.shields.io/github/v/release/ciscoriordan/kindling?display_name=tag)](https://github.com/ciscoriordan/kindling/releases)
[![Last commit](https://img.shields.io/github/last-commit/ciscoriordan/kindling)](https://github.com/ciscoriordan/kindling/commits)

<div align="center"><a href="https://github.com/ciscoriordan/kindling"><img src="https://raw.githubusercontent.com/ciscoriordan/kindling/main/images/kindling_social.jpg" width="360" alt="Kindling Kindle toolkit"></a></div>

The missing Kindle toolkit. Dictionaries, books, and comics, built as a single static Rust binary with no dependencies. Reverse-engineered MOBI generator that replaces Amazon's deprecated *kindlegen*: ~7,000x faster on a heavily-inflected Modern Greek dictionary, and ~40x faster on a 2M-entry French dictionary.

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

### [svg-flags](https://github.com/ciscoriordan/svg-flags)

[![Stars](https://img.shields.io/github/stars/ciscoriordan/svg-flags?style=flat&logo=github)](https://github.com/ciscoriordan/svg-flags/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/ciscoriordan/svg-flags)](https://github.com/ciscoriordan/svg-flags/commits)

<div align="center"><a href="https://github.com/ciscoriordan/svg-flags"><img src="https://raw.githubusercontent.com/ciscoriordan/svg-flags/main/social.png" width="360" alt="svg-flags"></a></div>

Clean, Xcode-compatible SVG flags with official colors in multiple shapes: circle, square, full-size, and simplified full-size. Fixes three issues with *circle-flags*: no Xcode support, circles only, and a reduced 11-color palette.

</td>
</tr>
</table>

## iOS Apps

<table>
<tr>
<td width="50%" valign="top">

### [Klisy](https://klisy.app)

<div align="center"><a href="https://klisy.app"><img src="https://klisy.app/assets/icon.svg" width="200" alt="Klisy Greek conjugations and declensions"></a></div>

Greek conjugations and declensions for iOS. The 10,000 most common Modern and Ancient (Attic) Greek lemmas and their inflected forms, scheduled with FSRS-6 spaced repetition. [klisy.app](https://klisy.app)

</td>
<td width="50%" valign="top">

### [Tonos](https://tonospolytonic.com)

<div align="center"><a href="https://tonospolytonic.com"><img src="https://tonospolytonic.com/assets/og-image.png" width="360" alt="Tonos polytonic Greek keyboard"></a></div>

A polytonic Greek keyboard for iOS 18+. Dedicated diacritic row, plus autocorrect and typeahead powered by [dilemma](https://github.com/open-greek/dilemma). Supports Classical, Koine, Byzantine, and Katharevousa orthographies. [tonospolytonic.com](https://tonospolytonic.com)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Iliad Aligned](https://iliadaligned.com)

<div align="center"><a href="https://iliadaligned.com"><img src="https://iliadaligned.com/og-image.jpg" width="360" alt="Iliad Aligned"></a></div>

iOS app presenting Homer's *Iliad* in parallel columns: Ancient Greek, Modern Greek (Polylas-Riordan), and English (Murray-Riordan). Tap any word for morphological analysis and dictionary definitions from Cunliffe, LSJ, and Wiktionary. [iliadaligned.com](https://iliadaligned.com)

</td>
<td width="50%" valign="top">

### [CCWCalc](https://ccwcalc.com)

<div align="center"><a href="https://ccwcalc.com"><img src="https://ccwcalc.com/assets/og-image-b2c25e53c8e056ae9a69fd11b9828758730704933881b2cffcad4a5636da4262.jpg" width="360" alt="CCWCalc concealed carry laws"></a></div>

iOS app and web reference for concealed-carry laws and reciprocity across 50 states, DC, PR, GU, USVI, AS, CNMI, 365 Indian reservations, 169 military installations, and 176 on-base hotels. [ccwcalc.com](https://ccwcalc.com)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Flex](https://flexlanguage.app)

<div align="center"><a href="https://flexlanguage.app"><img src="images/flex.png" width="360" alt="Flex Spanish conjugation app"></a></div>

Spanish verb conjugation app with full voseo coverage, FSRS spaced repetition, and GPU-accelerated speech recognition. 5,064 verbs, every tense and mood, free. [flexlanguage.app](https://flexlanguage.app)

</td>
</tr>
</table>
