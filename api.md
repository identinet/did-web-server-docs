# API



| **Functionality**     | **Method** | **Path**                                                                              | **Return Codes**                                                                                                                   |
| --------------------- | ---------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| Retrieve DID document | GET        | <p><code>/&#x3C;id>/did.json</code> or<br><code>/v1/web/&#x3C;id>/did.json</code></p> | <p><code>200</code> OK<br><code>400</code> Bad Request<br><code>404</code> Not Found<br><code>500</code> Internal Server Error</p> |
| Create DID document   | POST       | `/v1/web/<id>/did.json`                                                               | <p><code>200</code><br><code>400</code></p>                                                                                        |
| Update DID document   | PUT        | `/v1/web/<id>/did.json`                                                               | <p><code>200</code><br><code>400</code></p>                                                                                        |
| Delete DID document   | DELETE     | `/v1/web/<id>/did.json`                                                               | <p><code>200</code><br><code>400</code></p>                                                                                        |
