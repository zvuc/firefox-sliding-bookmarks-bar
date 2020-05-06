<img src="https://user-images.githubusercontent.com/2870726/81133027-5820eb80-8f8b-11ea-813c-f28c0543f0c0.gif" alt="firefox-sliding-bookmarks" width="480" height="272" />

# Sliding Bookmarks Bar userChrome.css tweak for Firefox (76.0+) on macOS

Makes your Firefox bookmarks bar slide out only when you hover over the navbar, making it look more clean and simple.

This tweak existed ever since 2011 in [userstyles.org](https://userstyles.org/styles/48051/firefox-sliding-bookmarks-bar-mac), with fixes and adjustments applied every time Firefox version went up and introduced breaking changes. Now it lives here.

**This is guaranteed to work on macOS only!**
You'll have to manually tweak px values if you want to make it work on your non-macOS environment.

## How to apply

Please refer to this wonderful guide at [userchrome.org](https://www.userchrome.org/how-create-userchrome-css.html) for how to set up your own `userChrome.css` file to enable customizations for the Firefox UI.

Once you have a blank (or existing) userChrome.css file in your Firefox profiles folder, copy-and-paste the code included in the `sliding-bookmarks-bar.css` file. 

As a bonus, if you want to show only icons on your bookmarks bar to make it look more compact (see the GIF image above), copy and paste the code in `compact-bookmarks.css` file in the same `userChrome.css` file as well.

## See also
[Firefox macOS native translucent Tabbar tweak](https://github.com/zvuc/firefox-macos-native-tabbar) - Replaces default black-and-white theme with a more native-looking light/dark compatible translucent tabbar.

## License
MIT License
