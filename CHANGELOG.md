# v1.5.2 (Jun 4, 2020)

 * chore: Added API version 2.x.
 * chore: Updated dependencies.

# v1.5.1 (Jan 13, 2020)

 * chore: Switched to new `appcd.apiVersion`.
   [(DAEMON-309)](https://jira.appcelerator.org/browse/DAEMON-309)
 * chore: Updated dependencies.

# v1.5.0 (Aug 15, 2019)

 * chore: Added Appc Daemon v3 to list of compatible appcd versions.
 * chore: Update dependencies.

# v1.4.0 (Jun 6, 2019)

 * chore: Switched `prepare` script to `prepack`.

# v1.3.0 (Mar 29, 2019)

 * chore: Upgraded to Gulp 4.
 * chore: Update dependencies.
 * chore: Fixed lint warnings.
 * refactor: Refactored promises to use async/await.
 * fix: Initialize the data destination before requesting data from an external plugin.
 * fix: Improved code efficiency by caching the data destination instead of computing it ever data
   event.
 * fix: No longer errors out when an external plugin cannot be reached.

# v1.2.0 (Oct 25, 2018)

 * chore: Moved to `@appcd` scope.
 * chore: Update dependencies.
 * feat: Add Daemon 2.x support.

# v1.1.0 (Apr 11, 2018)

 * feat: Added Titanium SDK info.
   [(DAEMON-217)](https://jira.appcelerator.org/browse/DAEMON-217) and
   [(DAEMON-246)](https://jira.appcelerator.org/browse/DAEMON-246)
 * fix: Removed `appcd-*` dependencies and locked down the appcd version in the `package.json`.
   [(DAEMON-208)](https://jira.appcelerator.org/browse/DAEMON-208)
 * fix: Fixed URLs in `package.json`.
 * chore: Updated dependencies.

# v1.0.0 (Dec 5, 2017)

 * Initial release.
