
# Constellation1 eSign July 2025 Release Notes

Production Release: Tuesday July 29, 2025 

**Release Summary**

*   *   Handling a special anchor tag processing error case.
    *   Pre-populating the SMS phone number in the signing ceremony based on client configuration flag.
    *   The ability to launch eSign UI on the Dashboard page.
    *   Based on a client property flag, now the Reviewer role can also view signed tags of prior signers.

**Release Details**

Bug Fixes

1.  GPES-5570

Upon prior changes to the UpdateUserByUsername API call, the returned value of the property SystemUserId wasn’t always populated. Now, it is always populated with the value of the updated record.

2.  GPES-5555

Fixed an anchor tag processing error case, where an unknown caused of an RTF document caused invalid tag coordinates to be returned that cased invalid argument error and marked the entire document to fail processing. We added a case to discard such error cases.

3.  GPES-5552

We added the SSO ability into eSign to launch the user directly on the Dashboard page, by supplying the “dashboard” as the value to the “landingPage” property in the LogMeIn call.

4.  GPES-5553

We introduced a new enterprise client-level property flag to enable the pre-population of the SMS phone number in the signing ceremony so that the signer doesn’t have to re-enter their phone number. We didn’t turn this feature on for all other clients to prevent giving them something they might not want. If this feature is desired to be turned on, please contact our support team to enable it for the requested enterprise client.

5.  GPES-5494

We introduced a new enterprise client-level property flag to allow the Reviewer to see signed tags. We didn’t turn this feature on for all other clients to prevent giving them something they might not want. If this feature is desired to be turned on, please contact our support team to enable it for the requested enterprise client.

6.  GPES-5422

A fix to downloading long file named documents. Now, the users can correctly download long file named documents.

7.  GPES-5034

A mobile CSS correction was made to the country dropdowns to properly display the list.

Was this article helpful to you?

Was this article helpful to you?