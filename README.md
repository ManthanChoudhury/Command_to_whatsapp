# Command_to_whatsapp

Script to send the CLI output of the linux command to the whatsapp contact as a message

### This script is compatible with any linux distro like RHEL7/8, Linux Mint , Ubuntu, kali , Fedora ,Debian , Centos.

## How to use this script ?

- Log in to the Whatsapp web
- Run the following command to create link with phone number and CLI output as a message.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `var=$(sh cmd.sh)`

  ![bash](https://user-images.githubusercontent.com/45136716/113188556-d2c7b900-9277-11eb-899f-a7383ab2ac92.png)

  Note: The phone number must be entered in an international format and without + sign and space. Eg. For India country code is +91. So, for India phone number must start with 91 followed by a 10-digit mobile number as 91XXXXXXXXXX.
- The variable named var contains the appropriate link to send the CLI output. We can open this link with firefox using the following command:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `firefox $var`

![whatsapp](https://user-images.githubusercontent.com/45136716/113188578-d78c6d00-9277-11eb-9faf-ccf7eda6bb15.png)

- This will open the Whatsapp web app in the Firefox browser, automatically opens the chat window for an entered phone number, and fills the input message-box with the command line output we had passed through the link.<br>


- You are all done! As a final step, you are just required to click on the send button and our CLI output is sent to the contact.

## Code:

![sscode](https://user-images.githubusercontent.com/45136716/113188591-dce9b780-9277-11eb-98dc-137f59a0f471.png)
