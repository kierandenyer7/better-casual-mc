# Better Casual MC

A standalone website for Minecraft Java 26.2. No build, dependencies, accounts, whitelist forms, API keys, or backend. index.html contains the whole site.

## Enable friends to start the server (required)

1. In Falix, open your account Profile Settings.
2. Enable **External Server Start**. This setting applies to every server you own.
3. Have a friend test the website's Start server button while the server is offline. Falix says server owners/admins should use their console instead.
4. Friends press Start on the Falix page. They may encounter a CAPTCHA or startup queue. The website cannot skip these, and clicking its link alone does not start the server.

The configured link is https://falixnodes.net/startserver?ip=bettercasualmc.falix.gg
Friends do not need a Falix account. Actual startup depends on Falix availability and your account/server settings. The site does not claim to show live server status.

## Publish for free with GitHub Pages

1. Create a new **public** GitHub repository named `better-casual-mc`.
2. Extract this ZIP on your computer.
3. In the repository select **Add file → Upload files**. Upload `index.html` and `README.md` directly into the repository root, then commit to `main`. Upload the extracted files, not the ZIP or an enclosing folder.
4. Open **Settings → Pages**.
5. Under Source select **Deploy from a branch**, then **main** and **/(root)**. Click **Save**.
6. Wait for deployment to finish and use the site URL GitHub displays. Share that link with friends.

No changes to your existing portfolio repository are needed. This package does not change or unpublish the older ChatGPT-hosted website.

## Server whitelist

This website has no whitelist form. If the Minecraft server itself still has its whitelist enabled and you want everyone to join, run `whitelist off` in the Falix console. This lets anyone who knows the address join. Keep online-mode enabled so Minecraft accounts remain authenticated.

## Editing

Edit index.html directly on GitHub. Search for `bettercasualmc.falix.gg` to change both the displayed address and the Falix start link. Search for `26.2` to update the Minecraft version. Commits to main republish automatically.

## Preview locally

Open index.html in a browser. Copy-to-clipboard works on GitHub Pages HTTPS; local file previews may use the select-and-copy fallback.

## References

- https://kb.falixnodes.net/falix/dashboard/automation/external-start
- https://falixnodes.net/startserver
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
