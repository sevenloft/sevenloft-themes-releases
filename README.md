# Sevenloft themes — releases

This repository holds only the release packages of the Sevenloft WordPress themes:

- `sevenloft-theme` — for ordinary sites
- `sevenloft-theme-eshop` — for WooCommerce shops

Each release has two installable ZIPs and one small JSON manifest per theme
(version, package URL, SHA-256 checksum, WordPress and PHP requirements). Sites
running the themes read the manifest of the latest release to offer updates
under **Dashboard → Updates**, and check the downloaded ZIP against its checksum
before installing it.

The source code is developed elsewhere. There is nothing to build or change here;
releases are published by Sevenloft.

## Installing

For a first install, download the ZIP for your theme from
[Releases](https://github.com/sevenloft/sevenloft-themes-releases/releases) and
upload it through **Appearance → Themes → Add New → Upload Theme**. Later versions
arrive as updates in WordPress.

The theme folder must stay named `sevenloft-theme` or `sevenloft-theme-eshop`.

## Licence

GNU General Public License v2 or later.
