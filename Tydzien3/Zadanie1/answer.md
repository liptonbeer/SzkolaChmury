# Odpowiedź

Budując swoją konwencję wzorowałem się na <https://docs.microsoft.com/en-us/azure/architecture/best-practices/resource-naming>.

| Zasób | Długość | Konwencja | Przykład |
|-------|---------|-----------|----------|
| Resource Group | 1-90 | `<service short name>`-`<environment>`-rg | ecom-prod-rg |
| Virtual Network | 2-64 | `<service short name>`-vnet | ecom-vnet |
| Subnet | 2-80 | `<context>` | web |
| Network interface | 1-80 | `<vm name>`-nic`<number>` | ecom-sql-vm01-nic01  |
| Network security group | 1-80 | `<service short name>`-`<context>`-nsg | ecom-web-nsg |
| Virtual Machine | 1-15 (Windows), 1-64 (Linux) | `<service short name>`-`<role>`-vm`<number>` | ecom-sql-vm01 |
| Managed Disk | 1-80 | `<disktype>`disk`<number>` | OSdisk01 |
| Storage account data | 3-24 | `<service short name>`data`<number>` | ecomdata01 |
| Storage account disk | 3-24 | `<vm name without hyphens>`st`<number>` | ecomsqlvm01st01 |
