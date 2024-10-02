<h1>Encryption/Decryption with Bash</h1>

<h2>Description</h2>
This project addresses the protection of sensitive healthcare information, specifically focusing on safeguarding personally identifiable information (PII) and protected health information (PHI) using encryption. A Bash script was developed to encrypt files containing healthcare data, ensuring compliance with privacy regulations such as HIPAA. The script secures sensitive documents by transforming them into an unreadable format during transit, with only authorized users able to decrypt the files using a valid password.
<br /><br />
To ensure reliable security, the script enforces strong password protocols and limits login attempts to prevent unauthorized access. It also logs user activities, providing an audit trail for tracking access, a key requirement in healthcare data protection. The implementation of AES-256 encryption further fortifies the system, making healthcare information significantly less vulnerable to data breaches. This solution demonstrates the script’s effectiveness in creating a secure environment for handling ePHI in healthcare.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash</b>
- <b>GPG (for encryption)</b>
- <b>AES-256 (encryption algorithm)</b>

<h2>Environments Used </h2>

- <b>Windows 11</b>
- <b>Ubuntu Linux</b>

<h2>Program walk-through:</h2>

Due to its length, I have attached a Word file for you to review, which contains the input code. The steps and explanations are annotated with hashtags for clarity: <br/>
You can [view the Word file here](encryptdecrypt.docx).
<br />
<br />
This output demonstrates the program's ability to successfully encrypt a document and provide appropriate error messages to the user when necessary. Output:  <br/>
<img src="https://imgur.com/UKKatM3.png" height="80%" width="80%"/>
<br />
