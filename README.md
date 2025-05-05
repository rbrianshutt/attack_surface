<h1>Creating and exposing a Windows 10 virtual machine to simulate attack surface</h1>

Delete Network Security Group rule for RDP <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/1.3%20delete%20nsg%20rule.png)
<br />

Create inbound port rule <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/1.3.2%20create%20inbound%20port%20rule.png)
<br />

Set inbound security rule allowing any source and any destination port<br/>
Click Add <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/1.3.3%20add%20inbound%20security%20rule.png)
<br />

Any port, source, destination is allowed purposefully to allow brute force attacks <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/1.3.4%20rule%20added.png)
<br />

Look up the public IP address  <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/1.4%20get%20public%20ip%20address.png)
<br />

Remote into the Windows virtual machines <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/1.4.2%20remote%20into%20vm.png)
<br />

Enter username and password <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/1.4.3%20username%20and%20password.png)
<br />

Go to the VM Windows Defender  <br/>
Click Windows Defender Firewall Properties<br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/1.5.1%20vm%20windows%20defender%2C%20click%20windows%20defender%20firewall%20properties.png)
<br />

Turn off the firewall on: <br/>
- <b>Domain Profile</b> 
- <b>Private Profile</b>
- <b>Public Profile/b>

Click Apply and OK <br/>


![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/1.5.2%20turn%20off%20domain%2C%20private%2C%20public.png)
<br />

Firewalls are off  <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/1.5.3%20firewalls%20are%20off.png)
<br />

Use your personal computer to test connectivity to the VM. <br/>
Ping the IP address of the VM <br/>
It pings <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/1.5.4%20use%20ping%20to%20test%20ability%20to%20connect%20to%20vm%20from%20own%20computer.png)
<br />
