# SOAR-EDR

## Objective
  This project objective is focused on learning how to reduce repetetive tasks while following structured process using platforms like Tines and LimaCharlie. Throughout this home lab, I've learned how to configure an automated playbook that sends alerts via email and Slack. This also involves implementation of responsive capability that allows an analyst to automatically isolate a compromised machine with a single click. This project helped me learn the logic of security orchestration that demonstrates practical SOC automation skills.

### Skills Learned
  - Making a playbook on how to isolate the machine
  - Automation & Workflow Engineering
  - Endpoint Forensic Analysis
  - Scripting & Data Parsing
  - Detection Engineering

### Tools Used
  - Vultr
  - LimaCharlie
  - Slack
  - Tines

### Steps
<p align='center'>
Playbook Diagram for SOAR-EDR-Project: <br/>
<img src="https://i.imgur.com/50w5LUM.png" alt="Elastic Badge" style="height: 480px;" /> <br/>
<br/> 
<br/>
Created a cloud server on Vultr and added Firewall: <br/>
<img src="https://i.imgur.com/XiuDOCK.png" alt="Elastic Badge" style="height: 300px;" /> <br/>
<img src="https://imgur.com/yi9BnAP.png" alt="Elastic Badge" style="height: 360px;" /> <br/>
<br/>
<br/>
Downloaded LimaCharlie to the server and confirming it is connected: <br/>
<img src="https://imgur.com/qoTp8VX.png" alt="Elastic Badge" style="height: 360px;" /> <br/>
<img src="https://imgur.com/mzi7bN2.png" alt="Elastic Badge" style="height: 360px;" /> <br/>
<br/>
<br/>
Modified existing D&R rules from credentials: <br/>
<img src="https://imgur.com/QxsFOrK.png" alt="Elastic Badge" style="height: 360px;" /> <br/>
<br/>
<br/>
Created Slack, then I proceeded to make an alert message to be sent to Slack and email and containing all the information from our diagram: <br/>
<img src="https://imgur.com/fGwZkK2.png" alt="Elastic Badge" style="height: 360px;" /> <br/>
<img src="https://imgur.com/wOuHEt9.png" alt="Elastic Badge" style="height: 360px;" /> <br/>
<br/>
<br/>
Made a "story" in Tines and a user prompt asking if they want to isolate the specific machine: <br/>
<img src="https://imgur.com/o5zIzgj.png" alt="Elastic Badge" style="height: 360px;" /> <br/>
<img src="https://imgur.com/t02tGay.png" alt="Elastic Badge" style="height: 360px;" /> <br/>
<br/>
<br/>
After choosing "Yes" on isolating the machine, these alerts are sent automatically to Slack and also isolating the machine from LimaCharlie: <br/>
<img src="https://imgur.com/qgauJ6Z.png" alt="Elastic Badge" style="height: 360px;" /> <br/>
<img src="https://imgur.com/DYfYUtf.png" alt="Elastic Badge" style="height: 360px;" /> <br/>
<img src="https://imgur.com/8NW4u5k.png" alt="Elastic Badge" style="height: 360px;" /> <br/>
<br/>
<br/>
If they chose not to isolate the device, this message will then be sent to Slack: <br/>
<img src="https://imgur.com/iRHnN15.png" alt="Elastic Badge" style="height: 360px;" /> <br/>
<br/>
<br/>
