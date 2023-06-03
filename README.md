---
description: >-
  Introducing PoPwallet : A protocol that allows wallets and WorldCoin IDs to
  correspond 1:1 per chain.
---

# About PoPwallet

{% hint style="danger" %}
**This is `alpha`, WorldApp login should be in**[ **staging mode**](https://simulator.worldcoin.org/)
{% endhint %}

{% hint style="warning" %}
Currently, we support **Ethereum mainnet only** (will support more chain soon**)**
{% endhint %}

## Overview

<figure><img src=".gitbook/assets/Component 2 (2).png" alt="" width="188"><figcaption><p>PoPwallet</p></figcaption></figure>

With [**worldapp**](https://worldcoin.org/) authentication, an on-chain user can "**link**" one address per chain in the **PoPwallet** to authenticate that the linked address is the only one in that chain.&#x20;

In the existing crypto ecosystem, there is an invisible war going on between **multi-accounters** and **foundations**. There are a lot of battles going on to stop sybil attacks. For example, [**Paraswap**](https://www.paraswap.io/) has effectively defended against it by using wallet tracing. ([**ref.**](https://decrypt.co/86509/paraswap-just-rewrote-the-rules-on-airdops)_)_&#x20;

<figure><img src=".gitbook/assets/스크린샷 2023-06-04 오전 4.11.49.png" alt=""><figcaption><p>Transaction map of metasleuth</p></figcaption></figure>

In response, **multi-accounters** are referring to tools like [**metasleuth**](https://metasleuth.io/) to bypass it, and even checking transaction paths to hide the origin of tokens by sending Ethereum from different **CEX**. As this battle continues, the labor and computing resource drain of increasingly complex transactions will increase. For now, the best way to prevent it is not captcha, not a bunch of web-2 authentication, but [**Worldapp**](https://worldcoin.org/).&#x20;

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption><p>Worldcoin ORB</p></figcaption></figure>

A worldapp is an **unique**, biometrically authenticated proof of personhood that can't be easily replicated.&#x20;

<figure><img src=".gitbook/assets/스크린샷 2023-06-04 오전 4.07.27.png" alt=""><figcaption><p>PoPwallet dapp</p></figcaption></figure>

**We can simplify authentication between dapps and on-chain users**. Users don't need to authenticate through the app every time they access another dapp, and the dapp only needs to verify that the address is authenticated using our API **without any transactions**. It's incredibly **simple & fast** protocol for providers and users alike.

**Users can assign an address to each chainid** permanently**.** (with a wallet connection, of course!!) This should be linked very **carefully** and in most cases **irreversibly** (unlinking it for reasons like lost mnemonics would be a huge effort).

\
_`In other words`**`, PoPwallet is anti-multi-wallet protocol!`**_

## Quick links

{% content-ref url="api/listup.md" %}
[listup.md](api/listup.md)
{% endcontent-ref %}

{% content-ref url="api/api-common-guide.md" %}
[api-common-guide.md](api/api-common-guide.md)
{% endcontent-ref %}
