# Network Security Group

## Purpose

A Network Security Group (NSG) acts as a stateful firewall in Microsoft Azure. It controls inbound and outbound traffic to Azure resources by using security rules.

## Configuration

- Name: nsg-enterprise-lab
- Resource Group: rg-enterprise-lab
- Region: East US

## Default Rules

Azure automatically creates default inbound and outbound rules to allow essential Azure networking while denying unauthorized inbound traffic.

## Security Considerations

- Follow the principle of least privilege.
- Only allow required ports.
- Restrict Remote Desktop access whenever possible.

## Skills Demonstrated

- Azure Networking
- Firewall Configuration
- Network Security
