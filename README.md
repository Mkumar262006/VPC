# Virtualization - Virtual Private Cloud using Azure

### Aim :

To design and implement a secure, scalable, and highly available Azure Virtual Network (VNet) infrastructure that enables seamless communication between cloud-based resources and on-premises systems, while ensuring compliance with organizational security and networking standards.

### Problem Statement :

Modern cloud applications need secure, isolated, and scalable networks for reliable communication and data protection. Without a properly configured Azure Virtual Network (VNet), resources face security risks and connectivity issues. Organizations struggle to design networks that meet performance, security, and compliance needs.

### Design Steps :

1. Sign in to the Azure Portal
	Navigate to https://portal.azure.com and log in with your Azure account credentials.
  <img width="650" alt="image" src="https://github.com/user-attachments/assets/fe21745f-2030-4f20-a2ab-d1831b891a0c" />
<br>

2. Navigate to Virtual Networks
	In the left-hand menu, click Create a resource or search for Virtual networks in the search bar.
	Select Virtual network and click Create.

  <img width="650" alt="image" src="https://github.com/user-attachments/assets/383b4ac4-1dad-49f0-ade2-2681945c6b50" />
<br>

3. Configure Basic Settings
	Subscription: Choose your Azure subscription.
	Resource Group: Select an existing resource group or create a new one .
	Name: Enter a name for the VNet .
	Region: Select the Azure region .

  <img width="650" alt="image" src="https://github.com/user-attachments/assets/43c38dff-b046-4b30-8e6e-aff530ad9311" />
<br>

4. Configure Security Settings (Optional)
	DDoS Protection: Enable Azure DDoS Protection Standard for defence against DDoS attacks.
	Firewall: Enable Azure Firewall for centralized network traffic filtering, or skip if not needed.

  <img width="650" alt="image" src="https://github.com/user-attachments/assets/a115ca4e-1747-4663-8327-b3715371ea98" />
<br>

5. Define IP Address Space
	IPv4 address space: Specify a private IP range.
	Subnet: Add at least one subnet:
                	Name: default or custom name.
        	Address range: A subset of the VNet range.

  <img width="650" alt="image" src="https://github.com/user-attachments/assets/defe6cb5-aa26-4d3a-a4a3-4953a9636bb9" />
 <br>

6. Add Tags (Optional)
	Add key-value pairs for resource organization (e.g., Environment: Production).

  <img width="650" alt="image" src="https://github.com/user-attachments/assets/bcd582d7-a5d8-4bdb-8a19-60b9b8d995d4" />
 <br>

5. Review and Create
	Review the configuration details.
	Click Create to provision the VNet. Deployment typically takes a few minutes.

  <img width="650" alt="image" src="https://github.com/user-attachments/assets/a586fcf3-d7e2-4295-a17c-638ebad616c0" />
 <br>

### Output : 

<img width="650" alt="image" src="https://github.com/user-attachments/assets/a826a838-cb23-4122-9afe-f15380c3b5d5" />
<br>

### Result : 
A secure and scalable Azure Virtual Network (VNet) was implemented, enabling isolated communication between cloud resources. Integration with on-premises infrastructure was achieved via a VPN gateway, with security enforced through Network Security Groups (NSGs). The network met performance, accessibility, and compliance standards, resulting in a production-ready environment.
