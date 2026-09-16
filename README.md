# Transform Web Pages

Public website and legal pages for the Transform Android application (Google Play package: Gender Swap: Age Filter).

- Website: https://durdenk.github.io/transform_web/
- Privacy policy: https://durdenk.github.io/transform_web/privacy-policy.html
- Terms of use: https://durdenk.github.io/transform_web/terms-of-use.html
- Authorized seller declaration: https://durdenk.github.io/transform_web/app-ads.txt
- Google Play package: `com.cukkacreatives.transform`

The implementation-derived Play Console worksheet is in
[`PLAY_CONSOLE_DATA_SAFETY.md`](./PLAY_CONSOLE_DATA_SAFETY.md). Review it again
against the production backend and SDK console settings before submitting the
Data Safety form.

## Publishing

The files in this directory are designed to be placed at the root of the
[`durdenk/transform_web`](https://github.com/durdenk/transform_web) repository
and published from the `main` branch with GitHub Pages.

The `app-ads.txt` file must remain at the root of the published website. Use the
GitHub Pages URL as the developer website in Google Play Console so advertising
systems can discover it.

After an app permission, SDK, backend field, retention rule, or data recipient
changes, update both the privacy policy and the Play Console worksheet before
publishing the Android release.
