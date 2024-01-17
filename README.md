<h1>File Integrity Monitor</h1>


<h2>Description</h2>
The aim of this project was to create a simple file integrity monitor which monitors 3 text files for any changes by creating a baseline hash of each folder then continously monitoring the files by hashing and checking against the baseline for changes. 
<br> 



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
