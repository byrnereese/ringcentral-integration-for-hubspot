# ringcentral-integration-for-hubspot

App state: WIP.

An app to add RingCentral to hubspot, so Hubspot user can call with RingCentral by Click Hubspot call button.

It is powered by [Hubspot's calling-extensions-sdk](https://github.com/HubSpot/calling-extensions-sdk).

## Video preview

[https://youtu.be/7LjebH31-1s](https://youtu.be/7LjebH31-1s)

## Use

Just goto Hubspot App marketplace, search `RingCentral`, connect it. then when click call button in Hubspot, you could choose call with RingCentral, check the video for detail.

## Experimental Use

Goto your Hubspot page, open browser console, input:

```js
localStorage.setItem(
  "LocalSettings:Sales:CallingExtensions",
  '{"name": "RingCentral", "url": "https://qz0upjt4k5.execute-api.us-east-1.amazonaws.com/prod/app"}'
)
```

and press `enter`, then refresh the page.
