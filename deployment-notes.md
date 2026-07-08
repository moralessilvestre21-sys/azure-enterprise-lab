
# Deployment Notes

## Deployment Order

1. Resource Group
2. Virtual Network
3. Network Security Group
4. Windows Virtual Machine
5. Microsoft Entra ID
6. RBAC
7. Storage Account
8. Azure Monitor
9. Microsoft Defender for Cloud

---

## Why this order?

Each service builds upon the previous one.

The Resource Group provides centralized management.

The Virtual Network establishes network isolation.

The NSG protects network traffic before workloads are deployed.

The VM provides a compute resource for testing.

Entra ID manages identities.

RBAC controls permissions.

Storage provides centralized cloud storage.

Azure Monitor provides visibility into resources.

Microsoft Defender for Cloud evaluates the overall security posture.
