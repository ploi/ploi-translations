# Ploi translations 🚀

The future is now - so stop the hassle, you’re running behind. Quick and easy site deployment with Ploi. Awesome features for awesome developers. Check it out at https://ploi.io

## Translations

This package contains all the translations used at ploi.io

You are free to create a pull request with a new translation:

`{locale}.json`

For example, if you are from germany create a `de.json` and copy over the contents from another json file to translate.

We recommend to use the **nl.json** file to copy from as that is usually the one that is most up to date.

The base translations are always english in the JSON files and the values inside represent your translations.

1 line command to copy over your file to another translation (make sure to replace **{locale}** with your country language code:

`cp lang/nl.json lang/{locale}.json`

Example contents:
```json
{
  "Dashboard": "Dashboard",
  "Manage": "Beheer",
  "Search..": "Zoeken..",
  "Overview": "Overzicht",
  ...
}
```

A example file for the JSON files can be found at: `src/resources/lang/nl.json`.

## Contributors
- sl by @morpheus7CS
- zh-CN by @mingyoung
- da by @peterbrinck
- pt-BR by @rmundel
- bg by @MrGKanev