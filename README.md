<h1>Failed RDP to IP Geolocation</h1>

<h2> Description </h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
</b>
<br />
<br />
I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. This honey pot
is used as a way to attract hackers and the point of this project is to truly point out how vulnerable any company or smally business is.
With this project for a short period of time I'm able to  observe live attacks (RDP Brute Force) from all around the world. 
I will use a custom PowerShell script to 
look up the attackers Geolocation information and plot it on an Azure Sentinel Map using ipgeolocation.io
<br />
<br />

![API](https://github.com/Macheeeeto/AzureSentinal-Lab/assets/135657145/d8d75dc3-8667-46e1-ac40-4b5a1ff03024)

<h2>Languages Used</h2>

  <b> PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>
![Names](https://github.com/Macheeeeto/AzureSentinal-Lab/assets/135657145/b44c03b1-797d-4ab2-98e8-46e29ae8ab34)








