
# Firefox Search Engine Shortcuts
A compilation of search engine shortcuts for Mozilla Firefox

## Setup

### Regular installation:

If you only want to install the extensions, you can do so by navigating to their respective product pages:
- [Etsy Search Engine Shortcut](https://addons.mozilla.org/en-US/firefox/addon/etsy-search-engine-shortcut/)
- [Google Maps Search Engine Shortcut](https://addons.mozilla.org/en-US/firefox/addon/google-maps-search-shortcut/)
- [Thesaurus.com Search Shortcut](https://addons.mozilla.org/en-US/firefox/addon/thesaurus-com-search-shortcut/)
- [YouTube Search Engine Shortcut](https://addons.mozilla.org/en-US/firefox/addon/youtube-search-engine-shortcut/)

### Debugging and development installation:

If you want to install them as a temporary add-on for debugging, you can follow these steps:
1. Open Firefox
2. Enter `about:debugging#/runtime/this-firefox` into the URL bar
3. Click "Load Temporary Add-on" (located in the upper right)
4. Open the extension's directory and select the `manifest.json` for the given extension

_Note: temporary add-ons are removed when Firefox restarts_

## Development

Custom search engines shortcuts do not use any JavaScript code. Instead, they use the [`search_provider`](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/chrome_settings_overrides) key in the extension's manifest.json. The only way to do any debugging is by making changes to the manifest, reloading it, and running the search.

## Contributing

If you'd like to contribute, whether it be an update, bug fix, or an entirely new search engine, feel free to open a pull request!
