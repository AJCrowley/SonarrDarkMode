# Sonarr - Dark Mode UserCSS Script

CSS &copy; 2023 [Kris McCann](https://github.com/AJCrowley) - [krismccann@gmail.com](mailto:krismccann@gmail.com)

Some simple CSS enhancements for Sonarr to give it a night mode and add a layer of polish.

This is a work in progress, and as such, I'm still making somewhat frequent tweaks, so be sure to check in from time to time to make sure that you have the latest code version.

To use, just install a UserCSS browser extension, I use [Stylus for Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), as it allows you to define different CSS adaptions by URL, so these mods won't be applied to all servers on your localhost. To limit the mods to Sonarr (or whatever you have running on port 8989), just uncomment the line specifying the URL to watch (and matching bracket on the last line), and modify the port to match your Sonarr listening port.
```css
@-moz-document url-prefix("http://127.0.0.1:8989") {
	/* css changes live here */
}
```

There are however plenty of options for UserCSS extensions, depending upon your browser, but I've found this one to be the best for my purposes.

Enjoy!
