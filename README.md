# Witness Record — hosted site

The compiled web build of the **Expert Witness Sign-Off** app, served via GitHub Pages.

This repository contains build output only. The source lives in a separate
private repository; do not edit these files by hand — they are overwritten on
each deploy.

To publish a new version, run this in the source project:

```bash
npx expo export --platform web --output-dir dist
```

then copy the contents of `dist/` over this repository (keeping `.nojekyll` and
`CNAME`) and push.
