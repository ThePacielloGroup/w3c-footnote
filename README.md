foot-note custom element
========================

In order to work from your hard drive, you need to explicitly allow your browser to access it. The method for doing so is different for each browser.

For Chrome, add the --allow-file-access-from-files command line switch to make it work. On Windows, this is accomplished by creating a shortcut to Chrome (right click a Chrome icon and select "Create shortcut", or try dragging it to your desktop), right clicking it, selecting Properties, and typing --allow-file-access-from-files after "...chrome.exe" in the Target box.

On OSX: open /Applications/Google\ Chrome.app --args --allow-file-access-from-files

For Firefox, type about:config in the URL bar. Then locate the security.fileuri.strict_origin_policy parameter and set it to false.