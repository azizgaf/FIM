<h1>File Integrity Monitor</h1>


<h2>Description</h2>
This is a file integrity monitor.  
<br> 
<br> Please note the user inputs are not checked and the script is susceptible to an injection attack. 


<h2>Results</h2>

<br/> First creating a hash of each file to set our baseline to compare against later:
<p align="center">
<img src="https://imgur.com/5Iafboz.gif" height="100%" width="100%"/>
<br />
</p>

<br/> Starting the file monitoring loop constantly hashing the file data and checking against baseline, and creating a message if the hash has changed:
<p align="center">
<img src="https://imgur.com/Wg5W6kq.gif" height="100%" width="100%"/>
<br />
</p>

<br/> Resetting the baseline after the files have been changed by running the script again:
<p align="center">
<img src="https://imgur.com/KbncfTv.gif" height="100%" width="100%"/>
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
