# api.justinsweb.com

Messing around with API gateway and REST clients

## Auth is in AWS Cognito

https://cognito.justinsweb.com/login?response_type=code&client_id=(client_id)&redirect_uri=(encoded_uri)

client_id - relates to the app for the identity provider.
redirect_url - should match your redirect url from the UserPool app settings.
response_type - token (or code).
