---
description: Rotates the camera
---

# \&rotate

Sender-Side Option! ([`&push`](../../source-settings/push.md))

## Options

| Value            | Description                                         |
| ---------------- | --------------------------------------------------- |
| (degree)         | Rotates the camera in the specified value in degree |
| (no value given) | 90 degree                                           |

## Details

Applies to the publisher's side. Rotates the camera 90-deg by default, or specify `&rotate=180` or `&rotate=270` to rotate more.

Rotates your video for the guests/OBS as well. The rotation uses CSS.

{% hint style="warning" %}
It will not work in full-screen, and the control-bar gets rotated also. Some browsers might have issues, too.
{% endhint %}

## Related

{% content-ref url="../view-parameters/and-portrait.md" %}
[and-portrait.md](../view-parameters/and-portrait.md)
{% endcontent-ref %}
