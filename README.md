<h1>Configuring a Default Domain Password Policy</h1>


<h2>Description</h2>
In this lab, I learned to configure a default domain password policy. It is a policy that stipulates the required complexity (length, a mix of uppercase/lowercase letters, symbols, duration before expiration, and so on) of passwords in order to ensure security.
<br />



<h2>Environments Used </h2>

- <b>Windows Server 2016 Standard</b> 

<h2>Program walk-through:</h2>

<p align="center">
From the taskbar hit the seach icon, then type in "group edit" to navigate to "group edit policy": <br/>
<img src="https://i.postimg.cc/kgKG09MP/Screen-Shot-2022-08-25-at-9-26-55-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
From the left pane navigate to Computer Configuration > Windows Settings > Security Settings > Account Policies > Password Policy   <br/>
<img src="https://i.postimg.cc/4x2G2SVR/Screen-Shot-2022-08-25-at-9-30-39-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
<br />
Select minimum password length and in the minimum password length properties dialog box change the characters to what you wish:  <br/>
<img src="https://i.postimg.cc/BQtMc7SK/Screen-Shot-2022-08-25-at-9-35-06-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />




<br />
Go back to the left pane and right click password policy and export the list: <br/>
<img src="https://i.postimg.cc/C1qfxDSd/Screen-Shot-2022-08-25-at-9-38-35-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />




<br />
In the Export List dialog box save the file to document the change <br/>
<img src="https://i.postimg.cc/YStXgrhp/Screen-Shot-2022-08-25-at-9-41-08-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />


  








  
  
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
