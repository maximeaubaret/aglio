# 2.0.0-beta5 - 2015-07-10
* Fix an issue with included paths when using `--server`.
* Update to [olio theme](https://github.com/danielgtaylor/aglio/blob/olio-theme/Changelog.md) 0.0.8.

# 2.0.0-beta4 - 2015-07-10
* Update to [olio theme](https://github.com/danielgtaylor/aglio/blob/olio-theme/Changelog.md) 0.0.7.

# 2.0.0-beta3 - 2015-07-09
* Documentation updates.
* Server mode now serves static files if found.
* Add ability to output compiled API Blueprint file instead of HTML.
* Update to [olio theme](https://github.com/danielgtaylor/aglio/blob/olio-theme/Changelog.md) 0.0.6.

# 2.0.0-beta2 - 2015-05-29
* Live update fixes.
* Example fixes.

# 2.0.0-beta1 - 2015-05-28
* Implement theme engine support; depend on the default olio theme.
* Switch to using drafter.js instead of protagonist directly.

# 1.18.0 - 2015-03-31
* Upgrade to [Protagonist] 0.19.0, which adds support for Node.js 0.12.x
  and iojs 1.x.
  ([#77](https://github.com/danielgtaylor/aglio/issues/77))

# 1.17.1 - 2014-12-16
* Switch to [Remarkable](https://github.com/jonschlinkert/remarkable)
  Markdown parser, which is faster and supports the new CommonMark
  specification. [GFM](https://help.github.com/articles/github-flavored-markdown/)
  is supported.
* Fix live reload no longer working with some configurations
  ([#74](https://github.com/danielgtaylor/aglio/issues/74))
* Watch all included files for live reloading.

# 1.17.0 - 2014-12-16
* New logo
* Add support for [including files]
  (https://github.com/danielgtaylor/aglio#including-files)
* Update dependencies (chokidar)

# 1.16.2 - 2014-11-18
* Update dependencies (chokidar, marked, protagonist, stylus)
* Fixes rendering description when headers are not present
  ([#66](https://github.com/danielgtaylor/aglio/pull/66))
* Fixes minor typo
  ([#67](https://github.com/danielgtaylor/aglio/pull/67))

# 1.16.1 - 2014-08-29
* Fixes template js bug related to live reloading.
  ([179ea7e](https://github.com/danielgtaylor/aglio/commit/179ea7e5bf1b37e53b2b034be11eb134a506ffcf))

# 1.16.0 - 2014-08-29
* Fix long choic lists not wrapping
  ([#35](https://github.com/danielgtaylor/aglio/pull/35))
* Fix long hostnames not wrapping
  ([#55](https://github.com/danielgtaylor/aglio/pull/55))
* Add support for live reloading the preview server
  ([#57](https://github.com/danielgtaylor/aglio/pull/57))
* Fix a bug when reading from stdin
  ([#59](https://github.com/danielgtaylor/aglio/pull/59))
* Update dependencies (coffee-script)
* Minor test fixes
