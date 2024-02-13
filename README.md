# Open banking postman collections for EU
Postman collections for Mastercard Open Banking Europe.

## Overview

The [Postman](https://www.postman.com/) collection for [Open Banking APIs](https://docs.aiia.eu) (EU).

## Collection
[Collection JSON ⤓](./openbanking-eu.postman_collection.json)

[Environment JSON ⤓](./openbanking-eu.postman_environment.json)

## Run the Collection
### Things to Know :point_down:

* A [free Aiia account](https://portal.aiia.eu/) is required to obtain your **Client ID**, **Client Secret** and **API_key**.

* Now it’s time to connect your first user by calling `api-sandbox.aiia.eu/v1/oauth/connect` with the following information:
  * `client_id`: your Client ID
  * `scope`: account information, payment capabilities and periodic access, based on the contents of [this page](https://docs.aiia.eu/#/auth/scopes/)
  * `redirect_uri`: the same URL you have given us on the Developer Portal
  * `response_type`: code

* After navigating the user to the connect URL, the user signs up with Aiia and connects their accounts.

<p align="center">
<img src="https://docs.aiia.eu/getting-started/quickstart/authentication-intro.png" width="500px"/>
</p>

### Import or Fork the Collection
1. Click here: [![Run in Postman](
https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/20782065-58762784-b8db-4d70-b37b-2b7d10a5481f?action=collection%2Ffork&collection-url=entityId%3D20782065-58762784-b8db-4d70-b37b-2b7d10a5481f%26entityType%3Dcollection%26workspaceId%3D5b96ecad-9493-4bff-b64e-ee3e9d8e485b#?env%5BAiia%20API%5D=W3sia2V5IjoiYmFzZV91cmwiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJ0ZXh0Iiwic2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjowfSx7ImtleSI6ImNsaWVudF9pZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InRleHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjF9LHsia2V5IjoiY2xpZW50X3NlY3JldCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InRleHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjJ9LHsia2V5IjoiY2xpZW50X3JlZGlyZWN0X3VyaSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InRleHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjN9LHsia2V5IjoiYWNjZXNzX3Rva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjpmYWxzZSwidHlwZSI6InRleHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjR9LHsia2V5IjoicmVmcmVzaF90b2tlbiIsInZhbHVlIjoiIiwiZW5hYmxlZCI6ZmFsc2UsInR5cGUiOiJ0ZXh0Iiwic2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4Ijo1fSx7ImtleSI6ImFjY291bnRfaWQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOmZhbHNlLCJ0eXBlIjoidGV4dCIsInNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6Nn0seyJrZXkiOiJ0cmFuc2FjdGlvbnNfcGFnaW5nX3Rva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjpmYWxzZSwidHlwZSI6InRleHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjd9LHsia2V5IjoiYWNjZXNzX3Rva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoidGV4dCIsInNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6OH0seyJrZXkiOiJyZWZyZXNoX3Rva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoidGV4dCIsInNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6OX0seyJrZXkiOiJkZXN0aW5hdGlvbl9pZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjEwfV0=) 
2. Select the Aiia environment (top right) and update `client_id`, `client_secret` and `client_redirect_uri` variables
3. Click _Send_ on individual requests, or _Run collection_
4. Explore the various folders and update the collection as you wish