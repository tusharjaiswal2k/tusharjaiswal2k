# GitHub profile setup

This repository is ready to be used as the public profile repository for `tusharjaiswal2k`.

## Publish

1. Push the repository to the default branch on GitHub.
2. Confirm that the repository is public and that its name exactly matches the GitHub username.
3. Open **Actions → Refresh contribution profile → Run workflow**.
4. Grant read/write workflow permissions under **Settings → Actions → General → Workflow permissions** if the first run cannot push generated assets.
5. Refresh the public profile after the workflow completes.

## Automation

`.github/workflows/profile-3d.yml` refreshes the contribution artwork every day at approximately **3:00 AM IST** and can also be run manually.

The workflow:

- uses the repository owner's username automatically;
- requires only GitHub's default workflow token for public contribution data;
- writes only generated files under `profile-3d-contrib/`;
- skips the commit when nothing changed.

The README uses the restrained `profile-night-green.svg` variant inside a collapsed details section so the engineering work remains the primary focus.
