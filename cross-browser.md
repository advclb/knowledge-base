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
npx browserslist
```

## Browsers need more attention

- IE11: you know it
- Edge <= 18: CSS3 support is bad
- iOS Safari: view port behaviors that is different from others
- Samsung Internet: more bugs than other chrome-based Android browsers
