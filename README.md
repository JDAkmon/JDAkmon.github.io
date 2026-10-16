# Type Dojo domain root

This companion to [JDAkmon/type-dojo](https://github.com/JDAkmon/type-dojo) serves the public landing page, AdSense ownership meta tag, and root-level `ads.txt` at **https://jdakmon.github.io/**.

The learning app remains at **https://jdakmon.github.io/type-dojo/**. This repository requests no ads. The app is in verification mode until Google approves the site and the publisher finishes consent/ad-unit setup.

GitHub Pages publishes `main` from the repository root. The files are generated with `npm run build:ad-root` in the app repository. After changing the public publisher ID or root landing template there, regenerate and copy `index.html`, `ads.txt`, and `.nojekyll` here before committing and pushing.
