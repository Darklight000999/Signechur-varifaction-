# Signing Integration

This folder is reserved for the future DSC/eSign provider integration.

Never upload private keys, DSC PINs, OTPs, Aadhaar data or provider secrets to GitHub.

A production signing workflow must:
- Obtain explicit signer consent.
- Bind consent to the exact PDF document.
- Use an authorised eSign provider or valid DSC workflow.
- Create a standards-compliant PAdES PDF signature.
- Validate the provider response and preserve verification evidence.

This folder is currently a placeholder. No legal signing is implemented yet.
