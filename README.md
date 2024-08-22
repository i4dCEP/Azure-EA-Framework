**Azure Enterprise Agreemant (EA) Scaffold & Governance Framework**

🌱  Azure EA & MG Structure with defined RBAC (Super Admin Level Controls)

      - Departments / Oranisations (Spend Limits & Department Level Admin Controls)
      - Accounts (Account Level Service Admin Controls & Enable / Disable Ent. DevTest offer)
      - Subscriptions (Environment Level Admin Controls)
      
🌱  Subscription Model with defined RBAC (Subscription Admin Level Controls)

      - CORE / HUB Infra Environment (Environment Level Admin/Owner/Contributor Controls)
          > Identity, Security & Share IT Services
      - PROD Environment (Environment Level Admin /Owner/Contributor Controls)
          > Production Workloads, Cloud Native Back-up & DR Services
      - UAT /STAGING / PRE-PROD Environment (Environment Level Admin /Owner/Contributor Controls)
          > Pre-Prod /Staging Workloads, Cloud Native Back-up & Archival Services
      - DEV / TEST Environment (Environment Level Admin /Owner/Contributor Controls)
          > DevOps Workloads, Cloud Native Code Repository, Back-up & Archival Services
          
🌱  Resource Group Model with defined RBAC (Resource Group Level Admin Controls)

      - Service / Application wise Resource Groups (Owner/Contributor/Reader Level Controls)
          > IaaS / PaaS Workloads/Services, Compute, HDD/SSD Disks, Storage, Network, NIC’s, ILB/ELB’s, NSG’s, WAF, API’s, Security, Automation, etc.
