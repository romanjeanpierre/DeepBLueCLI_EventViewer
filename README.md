<h1> Event Log Analysis with DeepBlueCLI</h1>

<h2>Brief Description</h2>
<p> The objective of this project is to employ the DeepBlueCLI tool for event log analysis. By eliminating the necessity for manual event log investigation, DeepBlueCLI will identify potential patterns signaling malicious activity.  .</p>

<h2>Project Walk-Through</h2>
<p> Change directory to where DeepBlue application reside</p>
<p> Input path to event log <code> .\evtx\ </code></p>
<img src="https://imgur.com/3ll2LFv.png" height="80%" width="80%" alt="Project Overview Image">
<p> Results: </p>
<p> 41 accounts password sprayed</p>
<p> User: jwrig</p>
<p> Hostname: Desktop-JR78RLP </p>
<p> MITRE ATT&CK Technique ID for password spraying </p>
<img src="https://imgur.com/B0cs7vh.png" height="80%" width="80%" alt="Project Overview Image">

<h3>Investigate new-user-security.evtx</h3>
<img src="https://imgur.com/5CJ9TI5.png" height="80%" width="80%" alt="Project Overview Image">
<p> New user created and added to administrator group, IEuser</p>

<h3> Investigate powersploit-system.evtx </h3>
<img src="https://imgur.com/APggiAk.png" height="80%" width="80%" alt="Project Overview Image">
<p> 2 files detected to be downloaded </p>

<h3> Output all logs into text file </h3>
<img src="https://imgur.com/WLRkFyI.png" height="80%" width="80%" alt="Project Overview Image">
<p> Open Sublime text and CTRL + F to find github</p>
<img src="https://imgur.com/1C66acm.png" height="80%" width="80%" alt="Project Overview Image">
<p> Mimikatz has been executed in the machine</p>

<h3> Research Mimikatz </h3>
<img src="https://imgur.com/UCxrWMl.png" height="80%" width="80%" alt="Project Overview Image">








