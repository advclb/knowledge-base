# WeChat Mini Program

## Why Mini Program

Mini Program benefits from all good things of WeChat eco-system:

1. User authentication
2. Payment system
3. Social features
4. Huge user base

The technology stack has many advantages:

1. Truely cross platform: write once, run everywhere
2. Fast and smooth experience like native applications
3. Efficient software distribution
4. Development is easier and operation is cheaper

If your application is:

1. Made for mobile users
2. Targeting China/Chinese market
3. Content-driven
4. Simple (single purpose, no multi-tasking)

Then Mini Program can be a great choice.

## History

### WebView

WeChat has built-in WebView to preview and interact with web content without
leaving the messaging app. So any existing web application can be used in WeChat.
It is not special. Most messaging mobile applications provide WebView so users
can preview external content faster and stay in the application longer.

### JS-SDK

WeChat added extra API to the WebView, so web application can use WeChat features
through JavaScript, like get username and friends, share photos in Friend’s circle.
These APIs then become WeChat JS-SDK. An application with WeChat JS-SDK support
can make advantages of WeChat, providing smoother experience. Integration of WeChat
JS-SDK is easy and fast. Any existing web applications can become a WeChat web app,
even it is a static web page or a WordPress site. It is not necessary to create
a dedicated WeChat web app.

### Mini Program

The pain point of mobile web application is still loading speed and transition
smoothness. So WeChat made a new front-end technology stack: Mini Program. It is
light weight, platform independent, uses JavaScript, like web applications. It is
lightning fast and smooth, like native application.

## Design

[Official Document](https://developers.weixin.qq.com/miniprogram/en/design/)

[Component Preview](https://weui.io/)

### Visual Expression

Mini Program is still a part of WeChat. So it forces the style to be consist with
WeChat UI. It limits the colors, fonts and component styles you can use. Even
though we are able to create customize components, too out-standing design can
cause the rejection of Mini Program submit.

The golden rule of Mini Program is:

> Let users focus on your content and service, not the Mini Program itself.
