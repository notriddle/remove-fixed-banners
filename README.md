Removing auto-scrolling banners
===============================

A set of [uBlock Origin](https://github.com/gorhill/uBlock/) filters to conserve vertical screen real estate and remove nag boxes.

### Installation

To add these filters to your own list, go to the uBlock Origin Settings page,
then go to Custom, then check the Import box.

Add this URL to make it work:

    https://notriddle.com/remove-fixed-banners/filters.txt

### Development tips

Medium uses cookies to decide whether to show you their pop-up box or not.
They don't show you a nag box immediately on the first article, but rather wait until the *second* one.
If you want to consistently get their nag box to appear, I've been able to do it by opening a medium article in a "Private Window" (which has the affect of clearing cookies), then clicking the author's name, then clicking another article.
