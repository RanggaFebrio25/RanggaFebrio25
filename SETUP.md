# Setup GitHub Profile — Rangga Febrio

1. Ensure your GitHub username really is **RanggaFebrio25**. Create a **public** repository whose name exactly matches the username: `RanggaFebrio25/RanggaFebrio25` if one does not exist.
2. Copy `README.md`, the **entire** `assets/` folder, and `.github/workflows/snake.yml` to the root of the profile repository. Keep those paths intact.
3. Commit and push to the default branch (this package's workflow assumes it is named `main`; change `push.branches` if necessary).
4. Go to the repository's **Actions** tab → **Generate Contribution Snake** → **Run workflow**. After a successful run, GitHub creates an `output` branch containing the animated SVGs. The snake is expected to show a broken image until that first run completes.
5. If publishing fails because of permissions, check repository Settings → Actions → General → Workflow permissions. Ensure GitHub Actions is permitted to write repository contents, and any branch protection rules allow the bot to create/update `output`.
6. Open your GitHub profile and check the README rendering. Images from external services (typing text, Shields badges, skill icons, stats) need an internet connection and their providers can fail or rate-limit; the included banner and wave GIFs are self-contained.
7. No HTML `<style>`, CSS animation, or JavaScript is needed. GitHub sanitizes those inside READMEs. This profile intentionally uses GIF, external SVG cards, and GitHub Actions-generated SVG animation.

## What to edit
- Personal links and project copy: edit `README.md`.
- Banner source/design: replace `assets/hero-cyber-samurai.gif` (keep its filename), optionally also `assets/hero-cyber-samurai.png`.
- Snake colors or schedule: edit `.github/workflows/snake.yml`.
- All project and technology details are illustrative descriptors based on the supplied existing profile, not verified public-repository URLs. Project CTAs intentionally open your portfolio or repository list rather than inventing project-specific links.

## References
- https://github.com/Platane/snk
- https://streak-stats.demolab.com/
- https://github.com/vn7n24fzkq/github-profile-summary-cards
