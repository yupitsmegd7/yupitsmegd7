# Put this on your GitHub profile

1. Create a **public** repository named exactly **yupitsmegd7** under your account: https://github.com/new?name=yupitsmegd7&description=Gourav%20Dutta%20%7C%20Profile&visibility=public
2. Extract this ZIP. Upload `README.md` and the `assets` folder to the repository root. Do not upload the ZIP itself or nest everything inside a `github-profile` directory.
3. Add the workflow at the exact path `.github/workflows/snake.yml`. If your upload dialog hides `.github`, use **Add file → Create new file**, type that full path, paste the supplied workflow, and commit to `main`.
4. Open **Actions → Contribution Snake → Run workflow**. If the initial workflow upload already triggered a run, wait for it instead. A successful run creates the `output` branch with both snake SVGs.
5. Open https://github.com/yupitsmegd7 — your README is the profile front page. The snake appears after its first successful run; GitHub image caching may delay it briefly.

## What you get

- Original dark terminal banner stored in your own repository.
- HTML, CSS, JavaScript, Python, Node.js, MySQL, ML/scikit-learn, LeetCode, and additional technology icons.
- Four featured project cards and links to three more repositories.
- Links to the Vatavarnam and Signal deployments listed in their READMEs.
- Daily contribution snake in light and dark themes, plus workflow status and follower badges.

The snake is an animated image of your real contribution graph, not a keyboard-playable game. GitHub READMEs do not run embedded JavaScript games. Generation uses Platane/snk; publishing uses crazy-max/ghaction-github-pages. Publishing here only writes an `output` branch; GitHub Pages hosting is not required.

## Optional personalisation

- Change the LeetCode link from `https://leetcode.com/` to your own profile URL. Your LeetCode username was not supplied, so no username, rank, or solved count was invented.
- Add your Fridge Quest and Fieldwork deployment URLs to their project cards. Their repositories did not list live URLs when this package was prepared.
- Add LinkedIn or your preferred public contact address if desired.
- Edit `assets/header.svg` to adjust your heading or colours.
- The skill icons and badges use third-party image services; the banner and generated snake are hosted in your own repository.

## Troubleshooting the snake

- **Missing image:** Check Actions for a completed run and the `output` branch for the two SVGs. Re-run after fixing any error.
- **403 publishing error:** The workflow already requests `contents: write`. Check whether repository or organisation Actions policies restrict that permission or third-party actions.
- **Workflow is absent:** Confirm `.github/workflows/snake.yml` exists on `main`.
- **Updates stop after inactivity:** GitHub may disable scheduled workflows in inactive public repositories after 60 days. Re-enable the workflow from Actions.
- **Contribution totals look different:** The image uses GitHub's contribution data and visibility rules, not a count of every local commit.

No personal access token is needed: the workflow uses GitHub's automatic `GITHUB_TOKEN`.

## References

- Profile requirements: https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme
- Snake generator: https://github.com/Platane/snk
- Icons: https://github.com/tandpfun/skill-icons
- Badges: https://shields.io/

Prepared from your public project READMEs. The workflow must run on GitHub to verify generation and publishing; it has not been run as part of this package.
