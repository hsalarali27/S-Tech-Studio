# S-Tech Studio — Developer portfolio

Independent portfolio for Android apps and web projects. No paid hosting, backend or build process.

## Live URL (once GitHub Pages is enabled)
https://hsalarali27.github.io/S-Tech-Studio/

## GitHub Pages setup
Open https://github.com/hsalarali27/S-Tech-Studio/settings/pages → Build and deployment → Deploy from a branch → main → /(root) → Save. The site is in a project repository; URLs include /S-Tech-Studio/.

## Site pages
- Home: index.html
- Portfolio: apps/index.html and apps/<slug>/index.html
- Privacy: privacy/index.html and privacy/<slug>/index.html
- Support: support/index.html and support/<slug>/index.html
- MilGaya terms: terms/milgaya/index.html
- MilGaya deletion: delete-account/milgaya/index.html
- Shared CSS and JS in assets/
- sitemap.xml, robots.txt, .nojekyll

## Add an app
Copy an existing app's apps/<slug>/, privacy/<slug>/ and support/<slug>/ directories. Update the app directory, privacy directory, support directory, homepage if featured, footer links if necessary, and sitemap.xml. Carefully verify the exact release's SDKs, permissions, file handling, data collection and retention. Supply a monitored support email and verify any Google Play listing before linking it.

## Review notes
MilGaya: operator Salar Ali, verified public contact milgaya.support@gmail.com; content adapted from existing public/privacy.html, public/delete-account.html and public/terms.html in hsalarali27/milgaya branch build/milgaya-compatibility-v020. Image Compressor: reviewed repo hsalarali27/calculator_app branch photo-size-compress. Calcora: reviewed branch feat/calculator-foundation. Subscription App: repository/features unverified; privacy page is intentionally marked pending. Generic studio support email not yet provided. Image Compressor's proposed publisher Salar Tech differs from portfolio brand S-Tech Studio; must confirm consistency before store publication.

Do not commit secrets or upload app backend credentials to this public repository.

## Visual assets

MilGaya app icon: verbatim copy of `hsalarali27/milgaya`, branch `build/milgaya-compatibility-v020`, `branding/MilGaya-app-icon.svg`.
Image Compressor icon: verbatim copy of `hsalarali27/calculator_app`, branch `photo-size-compress`, `photo_size_compress/branding/app_icon.svg`.
The two files in `assets/illustrations/` are original conceptual UI/development illustrations and are not genuine app screenshots. Replace them with real captures only if clearly identified as such.
