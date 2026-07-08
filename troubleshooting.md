
## Troubleshooting

### Unable to connect to VM

Problem:

- RDP connection failed.

Cause:

- NSG did not allow inbound RDP from my public IP.

Solution:

- Added inbound TCP 3389 rule restricted to my public IP.

---

### Unable to access Blob Container

Problem:

Received HTTP 403 Authorization Error.

Cause:

My account lacked the Storage Blob Data Owner role.

Solution:

Assigned Storage Blob Data Owner role through Azure RBAC and refreshed the portal.

---

### Azure Monitor showed no metrics

Problem:

CPU and Availability graphs displayed no data.

Cause:

The virtual machine was stopped.

Solution:

Started the VM and waited several minutes for metrics to populate.
