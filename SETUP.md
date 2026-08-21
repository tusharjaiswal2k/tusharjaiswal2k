# GitHub profile setup

1. Create or open the public repository whose name exactly matches your GitHub username.
2. Upload this package while preserving the folders:
   - `README.md`
   - `assets/hero.svg`
   - `profile-3d-contrib/`
   - `.github/workflows/profile-3d.yml`
3. Commit the files to the default branch.
4. Open **Actions -> GitHub-Profile-3D-Contrib -> Run workflow**.
5. After the first successful run, refresh your profile. The included placeholder graph will be replaced with your live contribution calendar.

The workflow refreshes the graph every day at approximately 3:00 AM IST. It automatically uses the repository owner's username, and GitHub's default workflow token is sufficient for public contribution data.
