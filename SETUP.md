# amrra05 GitHub profile setup

## Files

- `README.md` — your cyberpunk profile page.
- `.github/workflows/snake.yml` — generates and publishes the contribution snake.

## 1. Create the profile repository

1. Sign in to GitHub as `amrra05`.
2. Create a **public** repository named exactly `amrra05` (same spelling and capitalization as your username).
3. Initialize it with a README, or create it empty.
4. Upload this package's `README.md` to the repository root.
5. Upload `.github/workflows/snake.yml`, preserving the folder structure.

Your profile README will appear at `https://github.com/amrra05`.

## 2. Enable the snake workflow

1. Open the `amrra05` repository.
2. Go to **Settings → Actions → General**.
3. Under Workflow permissions, allow workflows to have read and write permissions to the repository contents. Save if you change it.
4. Open the **Actions** tab.
5. Select **Generate contribution snake** and click **Run workflow**.
6. Wait for the workflow to finish successfully. It creates/updates an `output` branch containing the SVG files.

The README references the generated SVG on the `output` branch. It may take a minute or two after the first successful run to appear.

## 3. Customize

- Replace the Figma link if you want a different design link.
- Add the ECommerceApi repository URL when you publish that repository.
- Add any additional technologies you actually use.
- You can change the header colors in the `capsule-render.vercel.app` URL.

## Notes

- GitHub statistics, streak, typing text, skill icons, and header graphics are served by external services. They may occasionally be slow or unavailable.
- The GitHub stats cards show public GitHub activity and language estimates; they are not a measure of code quality.
- The snake workflow needs the repository's Actions write permission to publish to its `output` branch.
