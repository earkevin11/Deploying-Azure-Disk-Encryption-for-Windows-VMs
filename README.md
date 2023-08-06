# Azure-Disk-Encryption-for-Windows-VMs-and Windows Defender

# What is Azure Disk Encryption? #236
- Azure Disk Encryption for Windows VMs helps safeguard companies data to meet your organization security and compliance requirements.
- How does it work? Azure Disk Encryption uses Bitlocker feature of Windows to encrypt the OS and Data Disks of Azure Virtual Machines, and it is integrated with Azure Key Vault, which helps in controling and managing the disk encryption keys and secrets.

# Importance of Disk Encryption
- Companies store high value sensitive data in their virtual machines and if it is not encrypted, then hackers would be able to see the information in clear text.
- Remember, Encryption ensures confidentiality. Hashing ensures integrity.
- If companies choose to use Microsoft Defender for Cloud, they will be alerted if they have Virtual Machines that are not encrypted and will provide recommendations to encrypt the Virtual Machines.
- Azure Disk Encryption is zone resilient, the same way as Virtual Machines.

# Azure Disk Encryption Supported VMs and Operating Systems
- Supported VMs
- - Generation 1 and Generation 2 VMs
- - VMs with Premium Storage

# Supported Operating Systems
- Windows client: Windows 8 and later.
- Windows Server: Windows Server 2008 R2 and later.
- Windows 10 Enterprise multi-session.

# Not supported Azure Disk Encryption
- Not available on Basic, A-Series VMs, or on virtual machines with less than 2GB of memory


# Azure Disk Encryption for Linux VMs
- Azure Disk Encryption uses the DM-Crypt feature of Linux to provide volume encryption for the OS and data disks of Azure virtual machines (VMs) and is integrated with Azure Key Vault to help you control and manage the disk encryption keys and secrets.

# How to Encrypt disks for a Azure VM?
- You need an Azure Key Vault.
- Within the Key Vault, you must enable "Azure Disk Encryption for volume encryption" in the Access Policies
- Generate a new encryption key
- From the Virtual Machine > Disk > Settings > Enable disk encryption
