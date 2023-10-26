<h1>RAS and NAT Install</h1>
<h2>This will allow future clients to access the internet while being in the internal network</h2>

1. Return to the 'Roles and Features' option on the home page and add the 'Remote Access' role.
<img src="https://i.imgur.com/VVE9FIJ.png" height="80%" width="80%"/>

2. Click 'Next,' and under 'Role Services,' select 'Routing.' 'DirectAccess and VPN (RAS)' will be added automatically.
<img src="https://i.imgur.com/xdfR3SG.png" height="80%" width="80%"/>

3. Continue by clicking 'Next' until you reach the installation phase. After installation is complete, press 'Close.'
<img src="https://i.imgur.com/Ekgm24d.png" height="80%" width="80%"/>

4. Now that 'Remote Access' is installed, go to 'Tools' in the upper right and click on 'Routing and Remote Access.'
<img src="https://i.imgur.com/K7JgATz.png" height="80%" width="80%"/>

5. Right-click on the Domain Controller (or whatever you named it) and choose 'Configure and enable routing access.'
<img src="https://i.imgur.com/1nvgLUV.png" height="80%" width="80%"/>

6. The wizard will open, and you'll want to configure 'Network Address Translation.'
<img src="https://i.imgur.com/FFmGanS.png" height="80%" width="80%"/>

7. Select the Network Interface that has the internet connection. Remember that we labeled both of our NICs.
   Tip: If your networks do not appear after the initial install, close the current window and retry steps 4 through 7. If that fails, restart your VM and retry steps 4 through 7.
<img src="https://i.imgur.com/K41YsQN.png" height="80%" width="80%"/>

8. Click 'Finish.'
<img src="https://i.imgur.com/MzFQDiv.png" height="80%" width="80%"/>

9. Once the configuration is complete, your Domain Controller should display a green icon. This setup is now complete."
<img src="https://i.imgur.com/vEwm7NM.png" height="80%" width="80%"/>
