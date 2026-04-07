# Lab 5 - Azure Key Vault & Secrets Management

**What id did:** Created an Azure Key Vault using the standard pricing tier. Stored a secret (database password) inside it and viewed its secret identifier url, the reference applications use to fetch secrets at runtime without storing passwords in code. Reviewed RBAC role assignments on the vault

**What i learned:** Key Vault is Azure's managed service for storing secrets, cryptographic keys, and certificates. RBAC controls who can access the vault, follwing the zero trust principle of least privilege.
key vault has two tiers: Standard (software-protected keys) and Premium (HSM-protected keys for highest security)

**Services used:** Azure Key Vault, Secrets, RBAC, IAM
