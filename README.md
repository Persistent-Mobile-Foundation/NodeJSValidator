Persistent Mobile Foundation
===
## NodeJSValidator
A sample application demonstrating use of the Node.js Token Validator.

### Tutorials
https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/application-development/authentication-and-security/protecting-external-resources/

This sample can be used in coordination with client samples applications described here:

- [UserLogin](https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/application-development/authentication-and-security/user-authentication/security-check/)
- [PinCodeAttempts](https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/application-development/authentication-and-security/credentials-validation/security-check/)

### Sample usage
1. Navigate to the sample's root folder and run the command: `npm install` followed by: `npm start`.  
2. Make sure to [update the confidential client](https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/application-development/authentication-and-security/protecting-external-resources/#confidential-client) and secret values in the PMF Operations Console.
3. Deploy either of the security checks: **[UserLogin](https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/application-development/authentication-and-security/user-authentication/security-check/)** or **[PinCodeAttempts](https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/application-development/authentication-and-security/credentials-validation/security-check/)**.
4. Register the matching application.
5. Map the `accessRestricted` scope to the security check.
6. Update the client application to make the `WLResourceRequest` to your Node.js resource.

### Supported Levels
Persistent Mobile Foundation: `9.x.x - 10.0.0`
