# Cross Browser Testing

## Tools

- [Browserslist](https://github.com/browserslist/browserslist) is a collection of front-end development tools that help you to auto-prefix CSS vendor properties and identify compatibility issues in your code.
- [Can I use...](https://caniuse.com/) is an online tool to search HTML/CSS/JS features' browser compatibility.
- [ECMAScript 6 compatibility table](https://kangax.github.io/compat-table/es6/)
- [BrowserStack](https://www.browserstack.com/) is a tool to test many browsers and devices without testing machines and virtual machines.

## What browsers should we support?

For all future projects, if possible, drop IE of all versions and Edge <= 18. You can get rid of most compatibility issues.

For some industrial applications, only support IE 11 and Edge 17+. You need to avoid using too fancy CSS3 features, check [Can I use...](https://caniuse.com/) if not sure.

Browserslist can show you the default browser support with this command:

```
$ npx browserslist
and_chr 78
and_ff 68
and_qq 1.2
and_uc 12.12
android 76
baidu 7.12
chrome 78
chrome 77
chrome 76
chrome 49
edge 18
edge 17
firefox 70
firefox 69
firefox 68
ie 11
ie_mob 11
ios_saf 13.2
ios_saf 13.0-13.1
ios_saf 12.2-12.4
kaios 2.5
op_mini all
op_mob 46
opera 64
opera 63
safari 13
safari 12.1
safari 5.1
samsung 10.1
samsung 9.2
```

## The most troublesome browsers

- IE11: you know it
- Edge <= 18: CSS3 support is bad
- iOS Safari: its has some behaviors that is different from others
- Samsung Internet: some strange bugs
