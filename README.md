# Wetlether box — deploy config

This repo holds **only** the deploy config for the [Wetlether](https://wetlether.com) box.
There is no application source here — the box ships as a public Docker image,
`ghcr.io/wetlether/box`. `render.yaml` tells a host to run that image always-on with a
persistent disk at `/data`.

**One-click:** [Deploy to Render](https://render.com/deploy?repo=https://github.com/wetlether/box-deploy)

You'll paste your Wetlether **access code** as `WL_TOKEN` when prompted. That's it.
