# Accessibility

This repository holds Ferran Buireu's CV as [`CV/MAC.json`](../CV/MAC.json), in Manfred's open
[MAC format](https://github.com/getmanfred/mac), kept in sync with his profile on Manfred.

## What the CV offers

The CV is structured text in English, not a PDF or an image. Every role, date, skill and study is a plain text
field, so a screen reader, a browser's zoom or any tool that reads JSON can reach all of it.

## Known barriers

This repository has no issue tracker, so its known barriers are listed here. Both are in the README, which the
Manfred connector rewrites on every sync, so a fix has to come from Manfred's template rather than an edit here.

- The icon and the three badges at the top have no alt text, so a screen reader announces them as unlabelled
  images.
- The *Magic* image is an animated GIF. GitHub's accessibility settings can stop animated images from playing on
  their own.

## Reporting a barrier

[Open a bug report in the profile repository](https://github.com/fbuireu/fbuireu/issues/new?template=bug_report.yml)
and say it is about the CV. You don't need to say anything about a disability. Include what you were trying to
read, what got in the way, and any assistive technology or settings you use, such as a screen reader, zoom or
reduced motion.

A fix to the CV is made in Manfred or in `MAC.json` and comes off the list above in the same change. No date is
promised for it.

## Ownership

Ferran Buireu maintains the CV and this page. The README belongs to the Manfred connector.
