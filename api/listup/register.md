# register

**Register** the user's Worldcoin ID and the token ID and address of the currently linked wallet with the server. Call this API when the user wants to verify the desired wallet

## Request <a href="#request" id="request"></a>

**API Request Methods**

<table><thead><tr><th width="124">Method</th><th align="center">URL</th></tr></thead><tbody><tr><td>POST</td><td align="center">/register</td></tr></tbody></table>

**Request Header**

<table data-full-width="false"><thead><tr><th width="161">Field</th><th width="93">Type</th><th width="100">Required</th><th>Description</th></tr></thead><tbody><tr><td>userId</td><td>String</td><td>required</td><td>The identifier for the user in the World Coin system</td></tr><tr><td>tokenId</td><td>String</td><td>required</td><td>The identifier for a specific token (chain id)</td></tr><tr><td>walletAddress</td><td>String</td><td>required</td><td>The address of the wallet associated with the user</td></tr></tbody></table>

## Response <a href="#response" id="response"></a>

**Response**

<table data-full-width="false"><thead><tr><th width="132">field</th><th width="100">Type</th><th width="108">Required</th><th>Description</th></tr></thead><tbody><tr><td>code</td><td>Number</td><td>required</td><td>3-digit HTTP status code</td></tr><tr><td>body</td><td>String</td><td>required</td><td>Success / Fail</td></tr></tbody></table>



{% hint style="info" %}
Refer to [Common Status Codes](../api-common-guide.md#api-response)
{% endhint %}
