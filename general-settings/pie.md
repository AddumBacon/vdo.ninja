---
description: Support for piesocket.com
---

# \&pie

General Option! ([`&push`](../source-settings/push.md), [`&room`](room.md), [`&view`](../advanced-settings/view-parameters/view.md), [`&scene`](../advanced-settings/view-parameters/scene.md))

## Options

Example: `&pie=YourPiesocketAPIKey`

| Value      | Description                                          |
| ---------- | ---------------------------------------------------- |
| (API\_KEY) | the only parameter is your own piesocket.com API key |

## Details

Third-party handshake-server service option. If using piesocket, you can just do `&pie=APKKEY` to use that service, without deploying any code or servers yourself.

{% hint style="warning" %}
At the time of originally adding this feature, PieSocket was a free service. That has since changed (Dec 2021). VDO.Ninja is not affiliated with PieSocket and never has been. We have no recommendation on whether you should use them or not.

For a free handshake-server though, please instead consider hosting your own on Google Cloud or Amazon AWS with a free micro-server instance. The following server code is compatible with VDO.Ninja: [https://github.com/steveseguin/websocket\_server](https://github.com/steveseguin/websocket\_server)
{% endhint %}
