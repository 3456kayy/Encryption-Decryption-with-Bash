<h1>Encryption/Decryption with Bash</h1>

<h2>Description</h2>
This project addresses the protection of sensitive healthcare information, specifically focusing on safeguarding personally identifiable information (PII) and protected health information (PHI) using encryption. A Bash script was developed to encrypt files containing healthcare data, ensuring compliance with privacy regulations such as HIPAA. The script secures sensitive documents by transforming them into an unreadable format during transit, with only authorized users able to decrypt the files using a valid password.

To ensure robust security, the script enforces strong password protocols and limits login attempts to prevent unauthorized access. It also logs user activities, providing an audit trail for tracking access, a key requirement in healthcare data protection. The implementation of AES-256 encryption further fortifies the system, making healthcare information significantly less vulnerable to data breaches. This solution demonstrates the script’s effectiveness in creating a secure environment for handling ePHI in healthcare.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash</b>

<h2>Environments Used </h2>

- <b>Windows 11</b>
- <b>Ubuntu Linux</b>

<h2>Program walk-through:</h2>

Due to its length, I have attached a Word file for your review, which contains the input code. The steps and explanations are annotated with hashtags for clarity: <br/>
You can [view the Word file here](encryptdecrypt.docx).
<br />
<br />
This output demonstrates the program's ability to successfully encrypt a document and provide appropriate error messages to the user when necessary. Output:  <br/>
<img src="https://imgur.com/UKKatM3.png" height="80%" width="80%"/>
<br />
<br />
The script prompts the user for their annual salary, calculates federal tax using conditional statements based on progressive tax brackets, and performs arithmetic operations using the bc command for precise calculations. Input:  <br/>
<img src="https://imgur.com/dMXLP6g.png" height="80%" width="80%"/>
<br />
<br />
The program calculates federal and state taxes, retirement, and Medicare deductions based on the user's input salary. It then subtracts the total deductions from the annual salary to determine the user's monthly take-home pay, which is displayed to the user. Output:  <br/>
<img src="https://imgur.com/wrocr1o.png" height="80%" width="80%"/>
<br />
