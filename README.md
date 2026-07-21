# webos-vc — lightweight WebRTC video calling for webOS (TouchPad / Atlas)

A single ~5 KB HTML page that does a 1:1 video call using **getUserMedia** +
**PeerJS** (free cloud broker for signalling). Built because Jitsi Meet's SPA is
far too heavy for the 2011 TouchPad's browser (it OOM-crashes the web process).

**Usage:** open `https://herrie82.github.io/webos-vc/#<room>` on both devices with
the same `<room>`. First to open hosts; the second joins and calls the host.

The webOS Messaging app + Phone-app Video tab open this URL (in Atlas "simple"
mode) with a room derived from the conversation.
