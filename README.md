# KidGrow website

Standalone static website for KidGrow by Autotech.

## Netlify

Import this GitHub repository, select branch `main`, leave the build command empty, and use `.` as the publish directory. No framework, environment variables, or package installation is needed. The configuration is in `netlify.toml`.

After the first deploy, add `kidgrow.imautotech.in` in Netlify Domain management. Add the exact DNS record Netlify supplies at the authoritative DNS provider, then verify HTTPS. Do not point the app or store listing to the custom domain until it resolves and all pages work.

Pages: `/`, `/privacy.html`, `/support.html`, `/terms.html`, `/delete-account.html`.

The existing GitHub Pages deployment remains available at https://xemb0.github.io/kidgrow-site/ while the custom domain is being connected.
