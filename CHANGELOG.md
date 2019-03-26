# v1.3.0

 * Upgraded to Gulp 4.
 * Update dependencies
 * Fixed lint warnings.
 * Refactored promises to use async/await.
 * Initialize the data destination before requesting data from an external plugin.
 * Improved code efficiency by caching the data destination instead of computing it ever data
   event.
 * No longer errors out when an external plugin cannot be reached.

# v1.2.0 (Oct 25, 2018)

 * Moved to `@appcd` scope
 * Update dependencies
 * Add Daemon 2.x support

# v1.1.0 (Apr 11, 2018)

 * Added Titanium SDK info.
   [(DAEMON-217)](https://jira.appcelerator.org/browse/DAEMON-217) and
   [(DAEMON-246)](https://jira.appcelerator.org/browse/DAEMON-246)
 * Removed `appcd-*` dependencies and locked down the appcd version in the `package.json`.
   [(DAEMON-208)](https://jira.appcelerator.org/browse/DAEMON-208)
 * Fixed URLs in `package.json`.
 * Updated npm dependencies.

# v1.0.0 (Dec 5, 2017)

 * Initial release.
