## What I Learned

- Created an Azure Storage Account for cloud storage.
- Created a Blob Container named "company-files".
- Assigned the appropriate RBAC role (Storage Blob Data Owner) to access blob data.
- Verified container access after Azure propagated the new permissions.
- Uploaded a test file to validate successful storage operations.

## Why Azure Blob Storage?

Azure Blob Storage is used to store unstructured data such as:

- Images
- Documents
- Videos
- Backups
- Application logs
- Virtual machine disks

Organizations commonly use Blob Storage for scalable, durable, and cost-effective cloud storage.

## Key Takeaways

- Azure separates management permissions from data permissions.
- Storage Blob Data Owner grants access to blob data inside containers.
- RBAC permission changes may require a short propagation period before taking effect.
