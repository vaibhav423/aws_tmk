# AWS - FULL AUTO - LOGIN - SCRIPT

this script would make login faster for aws console in browser


# How to get your AWS MFA Secret

This script requires your Time-based One-Time Password (TOTP) secret key to automatically generate MFA codes. You can get this secret key when you set up a new virtual MFA device in your AWS account.

## Steps to get your MFA Secret

1.  **Log in to your AWS account** and navigate to the **IAM (Identity and Access Management)** console.
2.  In the IAM console, go to **Users** and select your user.
3.  Go to the **Security credentials** tab.
4.  In the **Multi-factor authentication (MFA)** section, click **Assign MFA device**.
5.  Choose **Authenticator app** as the MFA method and click **Next**.
6.  AWS will display a QR code. **Instead of scanning the QR code**, click on **Show secret key**.
7.  **Copy the secret key** that is displayed. This is the value you need to provide to the script.
8.  **Important**: After copying the secret key, you can proceed to scan the QR code with your authenticator app (like Google Authenticator, Authy, or Microsoft Authenticator) to complete the MFA setup in AWS. You will need to enter two consecutive MFA codes from your app to finish the process.

## Adding the Secret Key to the Script

When the script prompts you for your MFA secret for the first time, paste the key you copied from the AWS console. You can also update it later using the settings menu (the gear icon).

By following these steps, you can securely obtain your MFA secret and use it with this script for automatic logins.
