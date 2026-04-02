# Root GitHub Pages Site

This folder is a deployable static site for the root GitHub Pages host:

- `https://celebritypunks.github.io/`
- `https://celebritypunks.github.io/app-ads.txt`
- `https://celebritypunks.github.io/binaural-mind-privacy/`
- `https://celebritypunks.github.io/binaural-mind-privacy/terms.html`

## Publish

1. Create a public GitHub repository named `celebritypunks.github.io` under the `CelebrityPunks` account.
2. Copy the contents of this folder into that repository root.
3. In the repo settings, enable GitHub Pages:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/(root)`
4. Wait for GitHub Pages to deploy.

## Verify

After deployment, confirm these URLs return `200 OK`:

- `https://celebritypunks.github.io/app-ads.txt`
- `https://celebritypunks.github.io/binaural-mind-privacy/`
- `https://celebritypunks.github.io/binaural-mind-privacy/terms.html`

Then use the privacy URL in App Store Connect and re-run AdMob verification.
