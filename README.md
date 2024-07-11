# KDE Frameworks 6 Vietnamese Localization - Experimental Caligraph Branch

This repository contains the experimental, daily commits of the KDE Frameworks 6 translation in Vietnamese, unofficially maintained by Caligraph. It serves as a playground for Caligraph's pioneering automatic translation technology, incorporating glossary building and incremental changes.

## Why?

We believe that localizing open-source, libre software will significantly increase adoption and help bridge the "digital divide" in disadvantaged and elderly populations for non-English speaking users, especially in developing countries. Moreover, having user interfaces available in specific languages encourages users to read, write, and preserve their language and traditions.

Open-source software localization often suffers from a limited number of translators and time constraints. There's an insufficient supply of people willing to work on less popular languages with numerous strings to translate manually. When a language is not well-supported, it results in an incomplete UI due to partial localization, causing confusion and a lack of polish. This further discourages users from using the localized version and contributing back to the project.

Contributing to such software requires significant technical know-how to set up tooling and development environments, which not everyone (especially a regular linguist) is able or willing to do. This creates a classic chicken-and-egg problem: not having enough users leads to a lack of translators, which in turn leads to incomplete localizations and further disinterest. The absence of frequent contributors also results in inconsistencies across translations.

To illustrate the issue, as of July 2024 when this repository was created, it's estimated that over 100,000 strings—comprising approximately 85% of all User Interface text—remain either untranslated or incomplete in the Vietnamese localization. This situation has not changed significantly in years.

We firmly believe that Large Language Models (LLMs) and Generative AI are now more than capable of overcoming these limitations. They can produce highly polished translations that require minimal manual maintenance and editing. This, in turn, gives the UI a polished feel that encourages people to switch to their native language. By solving the chicken-and-egg problem, we expect to drive up adoption significantly.


## Upstreaming Approach

We're actively sending patches to the KDE Vietnamese localization team. However, due to the slow review process, we've decided to publish our changes here first to avoid overloading the review pipeline. We're committed to collaborating with the Vietnamese localization team and contributing our knowledge to their wiki and databases in the true open-source spirit.

## How to Test

We're in the process of developing pipelines that will allow you to test these translations on your KDE Neon User Edition build. Stay tuned for updates on how to implement and evaluate our localization efforts.

## How to build

Please install `msgfmt` tool to build individual translation files for applications. Please follow the [testing instructions in the Vietnamese Localization wiki](https://community.kde.org/KDE_Localization/vi/checking) for more information.