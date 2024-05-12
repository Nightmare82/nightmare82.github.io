# Tool Localization

The tool can completely be localized.

## Create a new localization

To create new localizations you can execute the following steps:

- Download and launch POEdit
- Choose File->New from POT/PO File
- Select the file `\internationalization\locales\rpg_tools.pot`
- Localize all entries
- Choose File->Compile to MO and choose the correct folder for the localization, e.g. `locales\de\LC_MESSAGES` for the german localization.

## Modify an existing localization

To modify an existing localizations you can execute the following steps:

- Download and launch POEdit
- Choose File->Open
- Select the `po` file for the locale you want to edit, e.g. `locales\de\LC_MESSAGES\RpgTools.po` for the German localization
- Localize all entries you want to adjust
- Choose File->Compile to MO and choose the same folder for the localization and save it as `RpgTools.mo` (The tool will read this file)

