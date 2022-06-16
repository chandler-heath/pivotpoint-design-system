# PivotPoint Design System

Headless design system tokens generated from Figma using the Figma Tokens plugin.

## Editing tokens

Use Figma to edit the tokens. You'll need the [Figma Tokens](https://docs.tokens.studio/) plugin installed, and configured to sync with this GitHub repo.

1. [Install](https://www.figma.com/community/plugin/843461159747178978/Figma-Tokens) the Figma Tokens plugin
2. Generate a new Personal Access Token in [GitHub Developer Settings](https://github.com/settings/tokens) with scope `repo`
3. Copy the access token (you can only see it once)
4. In the Figma Tokens plugin, under `Settings > Token Storage > GitHub`, add new credentials:
     - Name: `PivotPoint Design System`
     - Personal Access Token: `your token`
     - Repository: `chandler-heath/pivotpoint-design-system`
     - Default Branch: `main`
     - File Path: `data/tokens.json`

You can now "pull from GitHub" (icon on bottom left) to fetch the tokens.

When done editing tokens, you should "push to GitHub" (icon button on bottom left).
