# Sonarr - Dark Mode Enhancements UserCSS Script

## Note: white Sonarr 4 is in beta, I have to make changes each time they release an update. For this reason, I'm pausing any further work on this until 4 is stable. If you're still running v3, you can still check out the older commits that cover v3 to add the dark mode. Since 4 comes with dark mode as standard, I'll see how it turns out before making any changes. Thanks!

CSS &copy; 2023 [Kris McCann](https://github.com/AJCrowley) - [krismccann@gmail.com](mailto:krismccann@gmail.com)

Since Sonarr 4 Beta comes with dark mode installed by default, this UserCSS script has been vastly simplified. It now uses the default colour palette for the most part, while still having the rounded edges and gradient colour coding of the previous version of the theme.

To use, just install a UserCSS browser extension, I use [Stylus for Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), as it allows you to define different CSS adaptions by URL, so these mods won't be applied to all servers on your localhost. To limit the mods to Sonarr (or whatever you have running on port 8989), just uncomment the line specifying the URL to watch (and matching bracket on the last line), and modify the port to match your Sonarr listening port.
```css
@-moz-document url-prefix("http://127.0.0.1:8989") {
	/* css changes live here */
}
```

There are however plenty of options for UserCSS extensions, depending upon your browser, but I've found this one to be the best for my purposes.

Enjoy!
