# Web App Launch Handling

Author: Matt Giuca &lt;<mgiuca@chromium.org>&gt;<br>
Author: Eric Willigers &lt;<ericwilligers@chromium.org>&gt;<br>
Author: Jay Harris &lt;<harrisjay@chromium.org>&gt;<br>
Author: Raymes Khoury &lt;<raymes@chromium.org>&gt;<br>
Author: Alan Cutter &lt;<alancutter@chromium.org>&gt;<br>

Last updated: 2022-03-03

This site details a proposal to add a `launch_handler` field to the [web app manifest](https://www.w3.org/TR/appmanifest).
See [explainer](launch_handler.md).


There are two older proposals archived here:
 - [Declarative Link Capturing](declarative_link_capturing.md) which was replaced by `launch_handler`.
 - The [service worker `launch` event](sw-launch-event.md) which preceeded `launch_handler` but will likely become an extension to it in future.