# Setup — Mahnoor's GitHub profile

## 1. Create the special profile repository

1. Sign in to GitHub as `mahnoorshafiq557`.
2. Create a **public** repository named exactly `mahnoorshafiq557`.
3. GitHub will identify it as your profile repository because the repository name matches your username.
4. If GitHub asks, initialize it with a README only if you want; you can replace that README with the one in this package.

## 2. Upload the files

Upload these paths to the root of `mahnoorshafiq557/mahnoorshafiq557`:

- `README.md`
- `assets/banner-dark.svg`
- `assets/banner-light.svg`
- `.github/workflows/snake.yml`

Keep the folder structure exactly as shown. Commit the changes to the default branch (usually `main`).

## 3. Enable the contribution snake workflow

1. Open the profile repository → **Settings** → **Actions** → **General**.
2. Under **Workflow permissions**, select **Read and write permissions**.
3. Save the setting.
4. Open the **Actions** tab → **Generate contribution snake** → **Run workflow**.
5. Wait for the workflow to finish successfully. It creates/updates the `output` branch.
6. Refresh the profile README. The snake image may take a minute to appear.

The workflow uses the repository's built-in `GITHUB_TOKEN`. Do not create, paste, or share a personal access token for this setup.

## 4. Check the profile

Open: https://github.com/mahnoorshafiq557

If the snake does not appear:
- Confirm the workflow completed successfully in Actions.
- Confirm the `output` branch exists and contains the two SVG files.
- Confirm the repository is public and the README paths are unchanged.

## 5. Optional personalization

The README intentionally leaves out private contact details and unverified claims. Add an email, LinkedIn, portfolio URL, or other social link only if you want it public and can confirm the exact URL.

The stats cards are loaded from third-party public endpoints and may occasionally be unavailable or rate-limited. The profile README itself does not depend on them.
