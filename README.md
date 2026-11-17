# RebornGames website

Hosted free by GitHub Pages at https://profictionstudios.github.io

## Privacy policies (one page per app)

| App | Package | Policy URL (use this in Play Console) |
|---|---|---|
| Retro Dice | `com.reborngames.retrodice` | https://profictionstudios.github.io/privacy-policy.html |
| Space Impact: The Last Signal | `com.reborngames.spaceimpact` | https://profictionstudios.github.io/space-impact-privacy.html |

**Never change or rename an existing policy file.** Its URL is entered in Google Play and inside the
app. Edit the text and update the effective date instead.

### Adding the next app
1. Copy `templates/app-privacy-template.html` to `<app-name>-privacy.html` (lowercase, hyphens).
2. Replace every `[PLACEHOLDER]`, rewrite the sections that describe what that app stores and which
   SDKs it uses (ads, analytics, in-app purchases), and delete the `noindex` line.
3. Add a section with the link to `index.html` and a row to the table above.
4. Commit to `main`. The page is live a minute or two later.
5. Paste the URL into Play Console (App content → Privacy policy, and Store listing) and link it inside the app.

## app-ads.txt
`app-ads.txt` lists the AdMob publisher ID, which is the same for all apps under one AdMob account.
It only needs to change if you use another ad network or AdMob account.
