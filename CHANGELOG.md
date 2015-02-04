##### 1.0.0 - 03 February 2015

Stable Version 1.0.0

##### 1.0.0-beta.2 - 10 January 2015

Fixed some tests.

##### 1.0.0-beta.1 - 10 January 2015

Now in beta

##### 1.0.0-alpha.6 - 05 December 2014

###### Backwards compatible bug fixes
- Fix for making copies of `options`

##### 1.0.0-alpha.5 - 05 December 2014

###### Backwards compatible bug fixes
- Updated dependencies
- Now safely making copies of the `options` passed into methods

##### 1.0.0-alpha.4 - 01 December 2014

###### Backwards compatible API changes
- Added DSHttpAdapter.getPath

###### Backwards compatible bug fixes
- #8 - Fixed handling of `forceTrailingSlash` option

##### 1.0.0-alpha.3 - 19 November 2014

###### Breaking API changes
- `queryTransform`, `serialize` and `deserialize` now take the resource definition as the first argument instead of just the resource name

##### 1.0.0-alpha.2 - 01 November 2014

###### Backwards compatible API changes
- #4 - Log failures. See also #5 and #6

##### 1.0.0-alpha.1 - 31 October 2014

###### Backwards compatible bug fixes
- #3 - _this.defaults.log() throws Illegal invocation

##### 0.4.2 - 22 October 2014

###### Backwards compatible bug fixes
- Fixed illegal invocation error

##### 0.4.1 - 30 September 2014

###### Backwards compatible API changes
- Added `forceTrailingSlash` option to `DSHttpAdapter#defaults`

###### Other
- Improved checking for the js-data dependency

##### 0.4.0 - 25 September 2014

###### Breaking API changes
- Refactored from `baseUrl` to `basePath`, as `baseUrl` doesn't make sense for all adapters, but `basePath` does

##### 0.3.0 - 21 September 2014

###### Backwards compatible API changes
- Small re-organization.

##### 0.2.0 - 21 September 2014

###### Backwards compatible API changes
- Added deserialize and serialize.

##### 0.1.0 - 17 September 2014

- Initial release