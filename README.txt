Nutriwize website, version 1.2
Created and compiled by Dr Surendran Venkataraman and Dr Angusubalakshmi Rajasivachalam. (c) 2026. All rights reserved.

Upload every file in this folder to the top level of a GitHub repository named nutriwize, then turn on GitHub Pages.
Keep the files together. Do not upload the signing key.

index.html             The application
manifest.webmanifest   Makes the site installable
sw.js                  Enables offline use. Its version number changes with each release
config.json            Holds the address of the Google Sheet forum used by the @ icon
Nutriwize.apk          The Android app offered for download on the site
icon-192.png, icon-512.png   App icons

To connect the @ forum, edit config.json so that it reads:
{ "api": "https://script.google.com/macros/s/YOUR_ID/exec" }

Installation and offline use need HTTPS. Opening index.html directly from a file does not enable them.
