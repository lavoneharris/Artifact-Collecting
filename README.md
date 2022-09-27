<h1>Artifact Collecting</h1>


<h2>Description</h2> In this simple lab we will be doing some artifact collecting from my personal spam inbox both manually and automicattly from a VM environment for added safety. We will look to collect both email and file artifacts.
<br> 



<h2>What is Artifact Collecting </h2>
Artifact collecting is gathering specific information from emails or files to will further allow us investigate and take defensive measures.
 <br>

<br />

<h2>Types of Email Artifacts</h2>
1. Sending Email - Where the email actually came from (even if spoofed).<br />
2. Subject Line - Subject of the email.<br />
3. Recipent(s) Email Address - Identifies which mailboxes have received the email.<br />
4. Sender Server IP & Reverse DNS - the address of the server that has sent the email. When the IP is found we could do a reverse DNS search using MCToolbox.<br />
5. Reply-To Address -  email address that will receive any replies to the original email. Value maybe different than the sending address depending if the address was spoofed for example “support@nike.com” replies would go to that address (attacker cant access that). So, they insert a email address they can actually access for example replies go to “pureevil@outlook.com”.<br />
6. Date & Time - Date and Time email was sent.<br />
<br />
<h2>Types of File Artifacts</h2>
1.Attachment Name - File name and extension of potentially malicous file.<br />
2. SHA-256 Value - The hash value of the poetnetially malicious file. To check the repuation of the file we can use online tools like VirusTotal and Talos File Repuattion.<br />
<br />
<h2>Types of File Artifacts</h2>
1. Full Urls - Url of the HyperLink.<br />
2. Root Domain - Not totally necessary but can help to show if the site has been created for malicious acts or if it is a compromised website.<br />

<br />
