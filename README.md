<img src="/assets/cv_icon.png" align="right" width="128px" />

# Ferran Buireu's CV

This repository holds **my professional data** as a [MAC](./CV/MAC.json) (Manfred Awesomic CV), an open-source, machine-readable CV format. It mirrors [my Manfred profile](https://getmanfred.com/profile/ferran-buireu): the two are synchronized in both directions by the [Manfred GitHub Connector](https://github.com/apps/manfred-github-connector), so editing either one updates the other.

<div align='center'>
  <img src='https://img.shields.io/static/v1?label=CV%20Last%20Sync&message=2025-06-20 06:46 UTC&color=brightgreen&style=for-the-badge'>
  <a href='https://github.com/getmanfred/mac'>
    <img src='https://img.shields.io/static/v1?label=MAC%20Version&message=0.5&color=brightgreen&style=for-the-badge'>
  </a>
  <a href='#license'>
    <img src='https://img.shields.io/badge/GDPR%20Compliant-40479B?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAMAAACdt4HsAAAAA3NCSVQICAjb4U/gAAAACXBIWXMAAAG7AAABuwE67OPiAAAAGXRFWHRTb2Z0d2FyZQB3d3cuaW5rc2NhcGUub3Jnm+48GgAAAThQTFRF////QUebQUebQUebQUebQkibQ0maREmaRUqaRUuZRkuZR0yZSE2YSU6YSk6YTFCXTlKWVFeUVVeUVliUV1mTV1mUWFqTWVqTW1ySXF2SXV6RXl+RYGCQYGCRYWGQamiNbWuMb2yLcG2LcW6Lc2+KdXGJdnKJeHSIeXSIe3aHfHeHfXeHfXiGfnmGf3mGg3yFg32Eh4CDiICDioKCjoaAj4aAkYh/lYt+npJ7oJR7ppl4ppl5qZx3q513rp92r6B1sKF1sqN0s6N0tKR0tqZzt6Zzuahyuqlyvatxv61wwK5vw7FuxbJuxrNty7dszLdsz7pr0Ltq1L5p2sNm2sNn3MVm3cZl4Mhk4Mhl48pk5cxj5sxj6M5i6tBh7NFh7tNg8dZf89de9dle9tpd+t1c+95b/N9b/+FaZsCVrgAAAAR0Uk5TAKH3+IOyXJkAAAGHSURBVFjD7dbZUsIwGAVgwFPbWgUEFQQXFgFRWcQNFVRAqLsimwsqspj3fwPvEMfWJnR0BoZz90+bL03apDEYRhllOGI0jemIyWiAzgwAYNEJOC76BjYA4PDlo7TUrViAhdib3w7wdbILwO5/iy2wAcEGqTgBcyawB8BZIY0g4xDKtXRPla6VGYfA+ThvT+nlfBw9ILpUVJdIBYgRWVLqjpPkiEgDyIQ8TisAs0+EyDQA3+qEFEew3mnxNIAt7g4rAmvuuG0QVyM7EIr/cnteE+CPSg/HUyrNw6ckH9V6Ag8hq2r9S7ekOKkFrFydRVVHcJ280ZwDARBUAeHntb95jWqTOEUJLKdUgNQyFZCrN+9sCs3nis16jgYwt4jyHhwjLTMN4MhubSsCO1tZxz8uJiHzrcwIjEDivH3i+fq+T9rnCTbAWiWFcQDiJgCMF0jVyvhfKB3IAIL7z7EZAPJBiWOcAwkSgMA7ubR0qz52JOH1PqlrS5uY5xYH/oykCeg+aI4yynDkEwtqUWMkn99xAAAAAElFTkSuQmCC'>
  </a>
</div>

## Layout

- [`CV/`](./CV) holds the CVs. There is one, [`MAC.json`](./CV/MAC.json), in English. The format allows further instances and languages as `MAC[_instance][_language].json`.
- [`assets/`](./assets) holds this README's icon. Certifications and pictures would go here too; none are checked in.

## Editing it

Change [`CV/MAC.json`](./CV/MAC.json) here, or the profile at Manfred: the connector propagates whichever side moved, and updates the *Last Sync* badge above in a commit of its own. That badge line is the only thing the connector rewrites, so the rest of this file is safe to edit.

A CV has to stay [a valid MAC document](https://github.com/getmanfred/mac/blob/master/schema/schema.json) to sync. Valid JSON is not enough: an invented `studyType`, for instance, parses and then fails validation, and the sync stops with an email rather than a failing check anywhere in this repository.

## License

The CVs here are my personal and professional data, and may not be processed automatically without my explicit permission, under the [GDPR](https://gdpr-info.eu/).

The [MAC format](https://github.com/getmanfred/mac) is free and open-source, under [CC BY-SA 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/). This repository itself is released under [the Unlicense](./LICENSE).
