# TPot Honeypot — Quick README

- **Environment**
  - Host: VMware (VM running on Windows host)
  - Guest OS: `ubuntu-24.04.3-live-server-amd64.iso` installed as the VM image

- **TPot CE Installation & Setup**
  - Deployed **TPot Community Edition (TPot CE)** on the Ubuntu VM following the official TPot CE GitHub reference
  - Confirmed configuration and basic services started successfully

- **Access & Interaction**
  - Connected to the Ubuntu VM from Windows using **PuTTY (SSH)**
  - Performed live interactions and verified honeypot functionality

- **Run Details**
  - Ran the honeypot for approximately **1 hour**
  - Verified that TPot services were capturing and logging network activity

- **Artifacts & Repository**
  - Collected output (screenshots/logs/results) and uploaded them to the **`img/`** folder of this repository
  - The `img/` folder contains the captured results from the 1-hour honeypot session

- **What I Read & Understood**
  - Reviewed the **TPot CE Git reference** for setup, architecture, and components
  - Understood the data flow, included honeypot containers, and log visualization (Kibana, ELK stack, etc.)

- **Notes / Next Steps**
  - Add VM specs (RAM, vCPUs, disk size) for reproducibility
  - Include TPot CE version/commit used and any non-default config changes
  - Consider adding a short section describing each image/log in the `img/` folder
  - Optionally, document step-by-step installation commands for full reproducibility
