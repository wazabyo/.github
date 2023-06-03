# API Common Guide

{% hint style="info" %}
**GitBook tip:** A succinct video overview is a great way to introduce folks to your product. Embed a Loom, Vimeo or YouTube video and you're good to go! We love this video from the fine folks at Loom as a perfect example of a succinct feature overview.
{% endhint %}

## API Request <a href="#api-request" id="api-request"></a>

**API Request Methods**

API only accept /???application/json???/ for calls, and parameter passing is done in the following manner.

<table><thead><tr><th width="118.33333333333331">Method</th><th width="96">Type</th><th>Description</th></tr></thead><tbody><tr><td>GET</td><td>URL</td><td>Query parameters as represented in the request URL</td></tr><tr><td>POST</td><td>BODY</td><td>Data represented as application/json in the request body</td></tr></tbody></table>

## API Response

**Common status codes**

Response status codes indicate the execution result of an API call. We only respond to the status codes below, and any response status codes that are not represented are represented in the \_code field of the Response Body.

<table><thead><tr><th width="164">Status Code</th><th>Description</th></tr></thead><tbody><tr><td>200</td><td>Successful API execution</td></tr><tr><td>400</td><td>4xx errors</td></tr><tr><td>500</td><td>5xx errors</td></tr></tbody></table>
