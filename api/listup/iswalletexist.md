# isWalletExist

Verify that the **wallet address is authorized**. This API is requested when authentication information is required for a wallet address.

## Request <a href="#request" id="request"></a>

**API Request Methods**

<table><thead><tr><th width="115">Method</th><th align="center">URL</th></tr></thead><tbody><tr><td>GET</td><td align="center">/address/{walletAddress}</td></tr></tbody></table>

**Request Header**

<table><thead><tr><th width="135">Parameter</th><th width="92">Type</th><th width="112">Required</th><th>Description</th></tr></thead><tbody><tr><td>walletAdddress</td><td>String</td><td>required</td><td>The address of the wallet associated with the user</td></tr></tbody></table>

## Response <a href="#response" id="response"></a>

**Response Elements**

<table><thead><tr><th width="141">Field</th><th width="98">Type</th><th width="102">Required</th><th>Description</th></tr></thead><tbody><tr><td>code</td><td>Number</td><td>required</td><td>3-digit HTTP status code</td></tr><tr><td>body</td><td>json</td><td>required</td><td>Whether the wallet address is verified</td></tr></tbody></table>

{% hint style="info" %}
Refer to [Common Status Codes](../api-common-guide.md#api-response)
{% endhint %}
