<h1>File Integrity Monitor</h1>

 ### [YouTube Demonstration](https://youtu.be/Vn_L0xCZq7M?si=85hbWY88JREd2cCz)

<h2>Description</h2>
The File Integrity Monitor is a PowerShell script that creates a baseline of file hashes from a designated folder and then continuously monitors for any changes. If a file is added, modified, or deleted, the script immediately alerts you by comparing current file hashes with the saved baseline, helping you quickly identify any unauthorized changes.
<br />


<h2>Languages and Utilities Used</h2>

- <b>The project is implemented entirely in PowerShell.</b> 
- <b>Get-FileHash: For computing cryptographic hashes using the SHA512 algorithm.</b>
- <b>Get-ChildItem: To enumerate files within a specified directory.</b>
- <b>Start-Sleep: To create delays during continuous monitoring.</b>
- <b>Test-Path, Remove-Item, Write-Host, and Read-Host: For file operations and user interaction.</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
