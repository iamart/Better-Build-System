Better Build System
===================

Better Build System is an edited standard build system with few enhancements.

Features:
---------
  - **Doesn't show build panel on successful build.** Instead of showing build panel plugin will print "Build finished" on status bar if no errors or warnings were found during building (if compiler returns exit code 0).
  - **Doesn't show debug text on exit codes.** Doesn't show debug text if compiler return exit code other than 0. Debug text is a text sublime shows on failure, e.g. [cmd: ...], [dir: ...], [path: ...].

Commands:
---------
#### Use commands to disable specific features
```javascript
// Shows panel only if build is unsuccessful. Set to false to disable this feature.
"show_panel_on_failed_build_only": true,
// Doesn't show debug text if compiler return exit code other than 0. Set to false to disable this feature.
"show_debug_text": false,
// Standard command, works if "show_panel_on_failed_build_only" set to "false":
// Shows the Build Results panel when building. If set to false, the Build
// Results can be shown via the Tools/Build Results menu.
"show_panel_on_build": true,
```

TO DO:
------
Leave a feature on issues page if you want to see something else.

Change log:
-----------
#### *1.1.0*
Now build panel shows if compiler returns exit code other than 0. Previously, plugin displayed the panel if errors were found. This technique required "file_regex" parameter to be set up on custom .sublime-build files. *Thanks to Rafal Chlodnicki*.

License
----
[![Creative Commons License](http://i.creativecommons.org/l/by-nc-nd/3.0/88x31.png "Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License")](http://creativecommons.org/licenses/by-nc-nd/3.0/deed.en_US)

This work is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License](http://creativecommons.org/licenses/by-nc-nd/3.0/deed.en_US).

### [![Top-5ive.Net](http://top-5ive.net/images/logo.png "Top-5ive.Net")](http://top-5ive.net/)