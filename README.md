## Powershell
Introduction to the Script
This PowerShell script demonstrates how to interact with the Windows Certificate Store to request, renew, and manage SSL certificates. The script uses the Get-Certificate cmdlet to request certificates from a Certificate Authority (CA) and performs actions such as:

Credential Prompt: Uses Get-Credential to securely capture user credentials for authentication with the CA.
Requesting a Certificate: Submits a certificate request using the Get-Certificate cmdlet with a specified template, DNS names, and policy URL.
Retrieving Existing Certificates: Retrieves a specific certificate from the local machine's certificate store using its thumbprint.
Processing Certificate Requests: Retrieves and processes pending certificate requests.
Managing Certificate Store: Navigates the local certificate store and handles certificate-related operations.

