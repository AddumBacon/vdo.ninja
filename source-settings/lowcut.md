---
description: Adds a low-cut filter
---

# \&lowcut

Sender-Side Option! ([`&push`](push.md))

## Aliases

* `&lc`
* `&higpass`

## Options

Example: `&lowcut=150`

| Value           | Description                                         |
| --------------- | --------------------------------------------------- |
| (integer value) | Sets the cut-off frequency in hz (default is 100hz) |

## Details

Adds a low-cut filter.

{% hint style="warning" %}
Enables the audio processing pipeline.
{% endhint %}

## Related

{% content-ref url="and-compressor.md" %}
[and-compressor.md](and-compressor.md)
{% endcontent-ref %}

{% content-ref url="and-limiter.md" %}
[and-limiter.md](and-limiter.md)
{% endcontent-ref %}

{% content-ref url="and-equalizer.md" %}
[and-equalizer.md](and-equalizer.md)
{% endcontent-ref %}
