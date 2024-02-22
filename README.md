# Integrate SSO Passgraf App as Your App's SSO Authentication Flow

***The system is in TEST phase, and NOT to be used for production sites or by third parties.***

### Prerequisites

- Application with OIDC (OpenID Connect) SSO Flow Login (Single Page Application)
- A domain to share and host your application

## Steps

1. **Initiate Integration**: Contact support to begin the integration process.
2. **API Instructions**: Follow the instructions in the response to obtain the relevant authentication/authorization APIs for your application.
3. **Implement APIs**: Add the API endpoints to your application as described in the support email response.
4. **Domain and Redirect URI Sharing**: Share the domain name where you intend to deploy your app, along with the authorization callback API path (redirect_uri) with support. This URI is where the user's `id_token` should be sent to access protected resources. 
   - **Example**: If your application's URL is `https://example.com` and there's a protected endpoint `/profile` that users can access after authenticating with Passgraf, then your redirect URI will be `https://example.com/profile`.
5. **Await Integration Confirmation**: Wait for a response from support to confirm integration. Once confirmed, proceed to deploy and test the flow.

You should now have your app integrated with the SSO Passgraf App, enabling the Sign-In/Up and SSO flow with Passgraf as your authorization/authentication service!

### Additional Resources

- For further assistance, reach out to support for an example app that implements the OIDC redirect flow. This can either mimic your application or serve as a reference for implementation.
