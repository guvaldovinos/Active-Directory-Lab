
<h1>Installing Windows Server & Active Directory Domain Services (AD DS) </h1>

<h2>🧠Description  </h2>
<p>This lab involved setting up Windows Server 2016 in VMware Workstation and installing Active Directory Domain Services (AD DS) to create a functional domain environment. This is the foundation for future labs involving user managerment, Group Policy, and network configuration.  </p>
<br />

## 🖥️ Environment
- **Virtualization:** VMware Workstation Pro  
- **Operating System:** Windows Server 2016 Standard (Desktop Experience)  
- **Network Mode:** NAT (Static IP assigned)  

---

## ⚙️ Steps Completed
1. Created a new VM in VMware and installed Windows Server 2016.  
2. Configured a **static IP address**.  
3. Installed **Active Directory Domain Services (AD DS)** through Server Manager.  
4. Promoted the server to a **Domain Controller**.  
5. Restarted and verified that the server successfully joined the new domain.  

---

## 🧩 Key Skills Demonstrated
- Installing and configuring Windows Server 2016  
- Setting up Active Directory Domain Services (AD DS)  
- Promoting a server to Domain Controller  
- Configuring static IP  
- Understanding basic networking in VMware  

---

## 📸 Screenshots 
1. **VMware Setup Screen**  🖥️
      
<img width="1907" height="883" alt="Media Player 10_7_2025 9_02_57 PM" src="https://github.com/user-attachments/assets/fc9646ac-2626-4b8b-81ed-1f12995823dd" />

   **Caption:** The VMware virtual machine is configured to run Windows Server 2016, confirming that the lab environment is properly set up and ready for domain configuration.  

2. **Static IP Configuration**🌐  
     <img width="1920" height="964" alt="Windows Server 2016 - VMware Workstation 10_7_2025 9_20_08 PM" src="https://github.com/user-attachments/assets/d8967727-9014-4e2d-81b0-dac0861b871c" />

    **Caption:** The network adapter’s IPv4 settings have been configured with a static IP address, subnet mask, and default gateway to ensure consistent network communication for the domain controller.
   
3. **AD DS Role Installation in Server Manager**    ⚙️ 
      <img width="1490" height="795" alt="Media Player 10_7_2025 9_31_26 PM" src="https://github.com/user-attachments/assets/0b93a91e-e6e9-4966-804d-9b6da025f0bf" />

    **Caption:** The *Active Directory Domain Services (AD DS)* role is selected in the “Add Roles and Features Wizard,” preparing the server to host domain and directory services.
   
4. **Promoting the Server to Domain Controller** 🧱 
    <img width="1920" height="852" alt="Media Player 10_7_2025 9_44_55 PM" src="https://github.com/user-attachments/assets/65ddc12f-2c8c-4136-8e90-4cc13406eb8f" />
   
   **Caption:** The server is being promoted to a domain controller, with the root domain name (`ietf.local`) specified—indicating that the domain has been created and configured.  
    
5. **Server After Reboot / Domain Login Screen** 🔑 
    <img width="1697" height="880" alt="Media Player 10_7_2025 9_47_31 PM" src="https://github.com/user-attachments/assets/2b11b765-255f-4a9a-ae00-4b8cef6b4072" />
 
   <img width="1708" height="821" alt="Media Player 10_7_2025 9_49_48 PM" src="https://github.com/user-attachments/assets/5324af25-a139-4962-8f49-978a24f9c016" />

   **Caption:** After reboot, the server successfully logs into the new domain (`IETF\Administrator`) and displays both AD DS and DNS roles in Server Manager, confirming a completed and functional domain setup.  
