# Azure-Sentinel-SIEM-

# Objective
To gain hands-on experience with SIEM technology by leveraging Azure Sentinel's capabilities for monitoring and analyzing security events by displaying attack data on a world map and correlating attacks with their physical locations and magnitudes. Additionally, to configure Azure Log Analytics Workspace for ingesting custom logs containing geographic data for enhanced threat analysis.


### Skills Learned
- Securitty Information and Event Management (SIEM) principles
- Configuring and managing Azure Sentinel
- Data ingestion and log management in Azure
- Threat Detection, Analysis and Visualization

### Tools Used
- Azure Sentinel: For monitoring and visualizing security events
- Azure Log Analytics: For ingesting and managing logs
- Custom Logs: For providing geographic data for threat analysis
- Honeypot VM

### Steps
Post screen shots here, and talk about what you did etc

Flowchart

Here is an overview how the Azure Sentinel SIEM lab works. Our unprotected VM gets exposed to the global internet, gathering the data for the Log Analytics Workspace to analyze and transfer it to the Azure Sentinel to visualize.
![how SIEM works](https://github.com/timuakhm/Azure-Sentinel-SIEM-/assets/171197854/749825bf-802d-4b69-8f7f-d739a6769349)


SIEM Logs

This is the data that is being fed to Azure Sentinel to visualize the geopgraphical data.
![SIEM logs](https://github.com/timuakhm/Azure-Sentinel-SIEM-/assets/171197854/5ff45baf-8b08-47cd-9821-3e59ad809131)


--Results--

Day 1:
![Failed RDP Map Day 1](https://github.com/timuakhm/Azure-Sentinel-SIEM-/assets/171197854/daa652e3-06ef-4e1e-a85f-fc239c37d85a)

Day 2:
![Failed rdp map day 2](https://github.com/timuakhm/Azure-Sentinel-SIEM-/assets/171197854/b2bf9eed-219e-4112-9fee-c0e2b5fb4c12)


Day 3:
![failed rdp map day 3](https://github.com/timuakhm/Azure-Sentinel-SIEM-/assets/171197854/3c30a1f1-2d79-41ba-88e2-9501f4f45ba7)


