---
layout: home
title: Invalid carts
nav_order: 3
description: 
---

# Invalid carts
Basic plan
{: .label .label-green }

Cartinator uses Machine Learning models to identify and automatically mute invalid carts. The model used is supervised and depends on human supervision to produce desired results.

This feature is enabled by default. Use the settings page to configure the behavior of the application:

* **Suspicious carts**: Set the invalid cart probability required to flag the cart as possibly invalid. These carts won't be muted automatically, just flagged for your review.
* **Auto-muted carts**: Set the invalid cart probability required to mute the cart automatically. Once the probability exceeds this threshold, Cartinator will automatically mute the cart. Cartinator will flag these carts as auto-muted, so you can unmute them if it got it wrong.
* **Minimum carts required for auto-mute**: Set the number of the minimum volume of the carts needed to enable auto-mute functionality—the larger the number, the better the results.

The model used to calculate the probability is retrained every five minutes.