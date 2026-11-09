# vict0rnguyen.github.io

Homepages and privacy policies of Vict0rNguyen's personal apps, published with GitHub Pages at https://vict0rnguyen.github.io/.

| Folder | App | Homepage | Privacy policy |
|---|---|---|---|
| `calendarpromax/` | CalendarProMax | https://vict0rnguyen.github.io/calendarpromax/ | https://vict0rnguyen.github.io/calendarpromax/privacy.html |
| `sochitieu/` | Sổ chi tiêu (SpendBook) | https://vict0rnguyen.github.io/sochitieu/ | https://vict0rnguyen.github.io/sochitieu/privacy.html |
| `songuoithan/` | Sổ Người Thân (People Book) | https://vict0rnguyen.github.io/songuoithan/ | https://vict0rnguyen.github.io/songuoithan/privacy.html |
| none, see below | Sổ Tiêm Chủng (Vaccine Book) | https://vict0rnguyen.github.io/sotiemchung/ | https://vict0rnguyen.github.io/sotiemchung/privacy.html |

Sổ Tiêm Chủng's pages are served from the separate repository [Vict0rNguyen/sotiemchung](https://github.com/Vict0rNguyen/sotiemchung).

## Rules

- This repository is public. Never commit secrets, keys, personal data or plans.
- Each folder is named after the last part of the app's Android package name (`vn.sochitieu` is `sochitieu/`).
- Never add a `sotiemchung/` folder: that address belongs to the sotiemchung repository, and its `catalog.json` address is built into the app.
- Each app folder has `index.html` (what the app does, with a link to its privacy policy) and `privacy.html`, both in Vietnamese and English.
- These addresses are entered as the homepage and privacy policy of each app's Google sign-in setup. Keep them stable, and update `privacy.html` before releasing an app version that uses Google data differently.

## Adding an app

1. Copy an app folder to the new folder name.
2. Edit `index.html` and `privacy.html` to describe the new app.
3. Add the app to the list in the root `index.html`.
4. Push to `main`. GitHub Pages publishes it about a minute later.
