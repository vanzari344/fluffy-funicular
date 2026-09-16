# Project overview

This repository is a static website contained in `index.html`. It has no package dependencies or build step.

## Run

The **Start application** workflow serves the project on Replit's web preview with:

```sh
python3 -m http.server 5000 --bind 0.0.0.0
```

The page loads some fonts, icons, scripts, and images from external CDNs, so those resources require network access.