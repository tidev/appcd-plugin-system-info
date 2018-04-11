# appcd-plugin-system-info

Detects system information.

## Info

The `info` service aggregates the info from the
[android](https://npmjs.org/package/appcd-plugin-android),
[genymotion](https://npmjs.org/package/appcd-plugin-genymotion),
[ios](https://npmjs.org/package/appcd-plugin-ios),
[jdk](https://npmjs.org/package/appcd-plugin-jdk),
[titanium-sdk](https://npmjs.org/package/appcd-plugin-titanium-sdk), and
[windows](https://npmjs.org/package/appcd-plugin-windows) plugins.

```js
appcd.call('/system-info/latest/info', ctx => {
	console.log(ctx.response);
});
```

## Legal

This project is open source under the [Apache Public License v2][1] and is developed by
[Axway, Inc](http://www.axway.com/) and the community. Please read the [`LICENSE`][1] file included
in this distribution for more information.

[1]: https://github.com/appcelerator/appcd-plugin-system-info/blob/master/LICENSE
