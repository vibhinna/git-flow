# Introduction
This section is created for testing purposes.
This section is created only for testing purposes.
The first thing a newcomer wants to know is what operations require authorization and what is possible with an API with proper credentials. Example from DNA Center and Meraki:
The XYZ Dashboard API requires access via an authenticated and authorized account. Only authorized accounts are able to submit requests to API operations. All operations must communicate over a secure HTTPS connection.
Expand on how to provide the API key, API token, or other credentials (usually in a header or as a token request). Provide clean, stepwise information for authenticating to use the API. Include screenshots if there is a dashboard to generate an API key or token.
When a user authenticates, they receive an authorization token to include in the request of each API operation. The API token must be provided on every request using the Authorization request header with a value of Bearer <api token>. For example:
