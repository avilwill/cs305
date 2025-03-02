# cs305
Module 8 Journal

### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Create financial service plans for customers while ensuring secure information handling, proper authorization, and secure transfers.

### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

To find vulnerabilities and have secure code... this helps establish trust with current customers and also encourages word-of-mouth marketing. Conducting dependency checks for vulnerabilities is crucial, as is ensuring proper authorization for users and employees to prevent any hacking incidents or financial complications. Additionally, it is important to identify and address false positive vulnerabilities.

### Which part of the vulnerability assessment was challenging or helpful to you?
Learning about certificates was both helpful and challenging, as it was new information to me.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
We implemented AES encryption to secure sensitive financial transactions and used hashing for password security

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities? What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
After refactoring code, I ran the system and created a new dependency check file, which is used to compare finding new or improved vulnerabilities. I used the maven dependency check tool. I think this is very helpful in determinining secure code and finding any false-positives.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
This demonstrates my ability to analyze and secure code by identifying vulnerabilities and mitigating risks. It highlights my experience using tools like Maven dependency check to detect security flaws. Additionally, it showcases my understanding of encryption, hashing, and secure coding practices, which are essential for protecting sensitive financial data.
