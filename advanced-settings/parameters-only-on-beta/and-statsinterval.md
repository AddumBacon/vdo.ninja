---
description: >-
  Lets you change the default stats update interval from 3-seconds to something
  else
---

# \&statsinterval

Viewer-Side Option! ([`&view`](../view-parameters/view.md), [`&scene`](../view-parameters/scene.md), [`&room`](../../general-settings/room.md))

## Options

Example: `&statsinterval=1500`

| Value            | Description                     |
| ---------------- | ------------------------------- |
| (no value given) | stats update interval = 3000-ms |
| (integer value)  | stats update interval in ms     |

## Details

`&statsinterval` lets you change the default stats update interval from 3-seconds to something else. Changing it to 1-second or 10-seconds might suit your needs better when using [`&bitratecutoff`](and-bitratecutoff.md), or if you just want frequent updates. Changing the stats interval will impact the auto-keyframe fix feature, potentially breaking it, but this won't be an issue with OBS 27.2 and onwards.

## Related

{% content-ref url="and-bitratecutoff.md" %}
[and-bitratecutoff.md](and-bitratecutoff.md)
{% endcontent-ref %}

{% content-ref url="../../general-settings/and-stats.md" %}
[and-stats.md](../../general-settings/and-stats.md)
{% endcontent-ref %}
