# Redline catalog

The list of plugins and themes offered by Redline's built-in store and shown on the Redline website, and the Chrome
extensions Redline recommends.

`catalog.json` is generated from a hand-picked list of projects. Each plugin points to its author's own GitHub
release, with the file size and SHA-256 that Redline checks before installing; each theme points to a fixed
commit of its author's repository. Each recommended extension is listed by its Chrome Web Store ID, and Redline
installs it from the Chrome Web Store; those marked `verified` have been tested in the current Steam client.
Nothing is re-hosted here: every download comes from the original authors.

Redline and the website read the file from:

    https://raw.githubusercontent.com/GFocacetti/redline-catalog/main/catalog.json

## For authors

If you would like your plugin, theme or extension to be added, changed or removed, please open an issue.
