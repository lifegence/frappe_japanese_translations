# Privacy Policy - Frappe Japanese Translations

Last updated: 2026-09-29

Frappe Japanese Translations ("the app") is an open-source Frappe app published by Lifegence
Corporation. It ships Japanese translations for Frappe, ERPNext and related apps. This policy
explains what data the app handles.

## What the app contains

A single translation file (`translations/ja.csv`) and the minimal files Frappe needs to install an
app. It has no DocTypes, no API methods, no scheduled jobs and no client-side scripts.

## What Lifegence receives

Nothing. The app does not send any data to Lifegence Corporation or to anyone else, and it has no
analytics, telemetry or usage tracking.

## Data sent to third parties

None. The app makes no network requests.

## Data stored in your site

None. Frappe reads the translation file from the app's directory and caches it in the same way as
the translations shipped by any other installed app. The app creates no records in your site's
database.

## Maintainer tooling

The `scripts/` directory of the repository contains tools the maintainers use to build the
translations, some of which send source strings from Frappe and related apps to an AI translation
service. These tools are not part of the installed app and never run on your site.

## Contact

Lifegence Corporation - contact@lifegence.com
