# Slack App-in-Tab extension

A Chrome + Firefox extension to open the Slack app with its multi-workspace sidebar in a simple browser tab.

1. Install the extension from [the Chrome Webstore(pending)] or [addons.mozilla.org](https://addons.mozilla.org/en-US/firefox/addon/slack-app-in-tab/)
2. Visit [app.slack.com](https://app.slack.com) and log into any of your workspaces
3. That's it, all your workspaces appear in the sidebar, just like in the Slack App

Under the hood, "_Slack App-in-Tab_" is a 10 LOCs long extension.
It changes your browser's User Agent String to the one used in Chrome OS, when you visit app.slack.com.
Slack always runs in _app mode_ on that platform. _Tada!_

Note that this app cannot adopt WebExtension Manifest v3 until [this chromium bug](https://bugs.chromium.org/p/chromium/issues/detail?id=1137396&q=manifest%20content%20security%20policy%20component%3DPlatform%3EExtensions&can=2) is fixed.

# Author

[@louisremi](https://twitter.com/louis_remi)
