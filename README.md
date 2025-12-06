# Bark Springs Documentation

This contains the markdown files, images, and configuration for generating the Bark Springs documentation. This site is intended for guests of our comfy abode.

To access the Fern Dashboard visit dashboard.buildwithfern.com. There you can find the Fern Editor.

To use a Code Editor:

1. Install Fern and login

```bash
npm i -g fern-api
fern login
```

2. Clone this repo

3. Run the site locally

```bash
fern docs dev
```

4. Generate a preview link
```bash
fern generate --docs --preview --log-level debug
```

5. Publish to production
```bash
fern generate --docs --log-level debug
```
