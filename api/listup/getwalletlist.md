# getWalletList

Provides a **list of authorized wallets** for the user's WorldCoin ID. API to call when information about a user's authorized wallets is needed

## Request <a href="#request" id="request"></a>

**API Request Methods**

<table><thead><tr><th width="119">Method</th><th align="center">URL</th></tr></thead><tbody><tr><td>GET</td><td align="center">/user/{userId}</td></tr></tbody></table>

**Request Header**

<table><thead><tr><th width="125">Field</th><th width="106">Type</th><th width="105">Required</th><th>Description</th></tr></thead><tbody><tr><td>userId</td><td>String</td><td>required</td><td>The identifier for the user in the World Coin system</td></tr></tbody></table>

## Response <a href="#response" id="response"></a>

**Response Elements**

<table><thead><tr><th width="125">Field</th><th width="106">Type</th><th width="105">Required</th><th>Description</th></tr></thead><tbody><tr><td>code</td><td>Number</td><td>required</td><td>3-digit HTTP status code</td></tr><tr><td>walletList</td><td>String[]</td><td>required</td><td>wallet address list</td></tr></tbody></table>

{% hint style="info" %}
Refer to [Common Status Codes](../api-common-guide.md#api-response)
{% endhint %}
