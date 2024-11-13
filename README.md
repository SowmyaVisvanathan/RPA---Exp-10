### Name : Sowmya V
### Reg no : 212222110045
### Date : 
# Exercise 10 - Email Automation - send email

### Aim:
To send an email from a Gmail account using UiPath

### Software required:
UiPath Studio-community edition

### Procedure:


#### Configure the SMTP Mail Message Activity in UiPath
1. Open UiPath Studio and your project.
2. In the **Activities** panel, search for **Send SMTP Mail Message** and drag it into your workflow.
3. Configure the following properties:
   - **To**: Enter the recipient’s email address.
   - **Subject**: Provide the subject of the email (e.g., "RPA email automation").
   - **Body**: Write the email message (e.g., "Hello! UiPath automated email").
4. In the **Properties** panel, configure the SMTP server settings:
   - **Server**: `smtp.gmail.com`
   - **Port**: `587` (for TLS) or `465` (for SSL)
   - **Username**: Your Gmail email address
   - **Password**: Paste the App Password you generated (not your regular Gmail password)
   - **SecureConnection**: Set to **StartTLS** (for port `587`) or **SSL/TLS** (for port `465`)


### Main.xaml:

![image](https://github.com/user-attachments/assets/6f576418-4bf2-4a1c-8855-1a4de40684eb)


### Output:

![image](https://github.com/user-attachments/assets/7e7d8575-05d7-4ed3-828c-4e0b159feb4c)

![image](https://github.com/user-attachments/assets/184b64fd-4f80-40d1-a69c-4844b87f2fc6)


### Results:
Thus, email automation process is successfully executed in uipath.


