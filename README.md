<h1>Meshing Parameter Optimization</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This project was one I took on when I realized we can save time and computing resources based on the definition of our meshes we are doing computation fluid dynamics on. For context, more precise parameters gives a higher definition mesh which in turn, gives us more reliable CFD results, however, this comes at the cost of time and need for stronger computers. My goal was to reduce the preciseness of the parameters up until the point we can no longer get reliable numbers. What I did to achieve my goal was to create a very large dataset of all combinations of the parameters at different, but reasonable, values. I created a design of experiments to run all my design points and used the highest definition meshes as my baseline, knowing that those would be the most accurate numbers. I then plotted all my parameters to try and find natural cutoffs as well as regression testing to find which parameters affected the output the most. This project is still in progress as I am currently taking a data analysis class that I am hoping teaches me more techniques to get even more valueble information from the data I have collected.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
