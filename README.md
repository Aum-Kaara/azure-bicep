# azure-bicep

# Generate deployment credentials

```
{
    "clientId": "<GUID>",
    "clientSecret": "<GUID>",
    "subscriptionId": "<GUID>",
    "tenantId": "<GUID>",
    (...)
 }
```

# Configure the GitHub secrets

Select Settings > Secrets > New secret.

Paste the entire JSON output . Give the secret the name AZURE_CREDENTIALS.
