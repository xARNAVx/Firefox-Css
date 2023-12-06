Go to about:support and click the "Open Folder/Show in Finder" button for the root directory of your browser profile/s.

Download and copy the chrome folder into the profile folder.

Go to about:config and change these preferences:
For all operating systems:

    toolkit.legacyUserProfileCustomizations.stylesheets = true
    svg.context-properties.content.enabled = true
    layout.css.color-mix.enabled = true

On macOS:

    To use the Edge style context menu on macOS then set widget.macos.native-context-menus = false
