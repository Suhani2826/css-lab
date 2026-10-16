# CSS Lab – instructions for Claude Code

This folder is a finished CSS lab (index.html + css/styles.css + images). The page should look like final_output.png.

When asked to "publish" or "finish the lab":
1. Do NOT change the CSS rule stacks in css/styles.css – each of the 19 selectors is already matched to its rules.
2. Open index.html and check it renders like final_output.png (fix only broken paths if any).
3. Run `git init` (if needed), commit everything, and create a public GitHub repo named `css-lab` with `gh repo create css-lab --public --source=. --push`.
4. Enable GitHub Pages from the `main` branch root:
   `gh api -X POST repos/{owner}/css-lab/pages -f "source[branch]=main" -f "source[path]=/"`
5. Report back the repo link and the live link (https://<username>.github.io/css-lab/).
6. Remind me to validate the live link at https://validator.w3.org and take a screenshot.
