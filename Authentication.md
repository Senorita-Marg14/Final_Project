# Authentication

## Multi-Factor Authentication (MFA)
When you attempt to log into your account, you may notice that after you enter your password, it asks you to confirm your login session using your phone or another device. This might seem annoying, but it's just one way that your account is trying to keep you protected. There are three main ways that multi-factor authentication occurs. 
1. Secondary Device: As mentioned before, some digital accounts will require you to confirm your login session on another device that you're already logged into the account on. This often just requires you to click yes to confirm the login attempt
2. Codes: Other MFAs require you to have access to a phone number or email that can be used to deliver a one-time code that can be used to authenticate your login. Once you enter your username and password, a prompt to enter a code is shown and a numeric code is sent to one of your devices that you must enter to allow the login to continue.
3. Biometric: Now that many laptops, phones, and tablets have biometric scanning abilities, these may also be used for authentication. Once you enter your username and password, you may get a prompt to use your fingerprint or face to verify that it is you who's trying to log in. If you're using face ID, you don't have to smile or make a crazy face, just make sure that the camera can see your entire face to authenticate.


## Sender Policy Framework (SPF) (Email)
Sender Policy Framework helps to verify that the email that you are receiving a message from is the correct email and has not been spoofed (faked or made to look like a legitimate email address when it's not). SPF works by matching the IP addresses (A unique device name that identifies your device when it connects to the internet) to the email account being used. This process generates an approved list of IP addresses (ex. your phone, your laptop, your tablet) that are allowed to send emails from that account. If an email is sent from your account that doesn't match one of these devices, it may prompt the email to be marked as spam. The recipient's email account may also reference this list of approved IP addresses to double-check on their end that the email that they are receiving is legitimate. 



