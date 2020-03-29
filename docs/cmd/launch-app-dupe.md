# Duplicate Icon - App Launch

![Screenshot](../img/launch-app-dupe.png)

## Fix

* Locate file in `::: /usr/share/applications`
* Copy file to `::: ~/.local/share/applications`
* Open file with text editor
    * Launch the app
    * Run `::: xprop WM_CLASS` in terminal & click in app window for results
        * Sample Output `::: WM_CLASS(STRING) = "google-chrome", "Google-chrome"`
    * Append `::: StartupWMClass=<result>` to file, replacing with the results from before
