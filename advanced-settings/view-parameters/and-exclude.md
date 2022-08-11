---
description: Same concept as &view, except does the opposite
---

# \&exclude

Viewer-Side Option! ([`&view`](view.md), [`&scene`](scene.md), [`&room`](../../general-settings/room.md))

## Aliases

* `&ex`

## Details

Any stream ID listed as a value will **NOT** be played or requested.

Example usage:

`https://vdo.ninja/?room=myroom123&exclude=stream121,sidestream321`

{% hint style="warning" %}
Excluding a stream ID will prevent even a peer connection.\
No video, audio, or chat can be had.
{% endhint %}
