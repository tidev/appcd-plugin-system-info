# @appcd/plugin-system-info

Detects system information.

Report issues to [GitHub issues][2]. Official issue tracker in [JIRA][3].

## Info

The `info` service aggregates the info from the
[android](https://npmjs.org/package/appcd-plugin-android),
[genymotion](https://npmjs.org/package/appcd-plugin-genymotion),
[ios](https://npmjs.org/package/appcd-plugin-ios),
[jdk](https://npmjs.org/package/appcd-plugin-jdk),
[titanium-sdk](https://npmjs.org/package/appcd-plugin-titanium-sdk), and
[windows](https://npmjs.org/package/appcd-plugin-windows) plugins.

```js
const { response } = await appcd.call('/system-info/latest/info');
console.log(response);
```

## Legal

This project is open source under the [Apache Public License v2][1] and is developed by
[Axway, Inc](http://www.axway.com/) and the community. Please read the [`LICENSE`][1] file included
in this distribution for more information.

[1]: https://github.com/appcelerator/appcd-plugin-system-info/blob/master/LICENSE
[2]: https://github.com/appcelerator/appcd-plugin-system-info/issues
[3]: https://jira.appcelerator.org/projects/DAEMON/issues
