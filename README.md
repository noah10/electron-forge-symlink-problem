This repository is to demonstrate a bug with electron-forge, npm modules installed from a local directory, and the vite plugin.

The forge-project directory was created with `npm init electron-app@latest forge-project -- --template=vite`.
The sayhi module was added to forge-project with `npm add ../common/sayhi` .