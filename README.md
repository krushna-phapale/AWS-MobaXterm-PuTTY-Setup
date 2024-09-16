# AWS-MobaXterm-PuTTY-Setup
This repository provides installation and configuration instructions for using MobaXterm and PuTTY to connect to AWS instances. Simplify your AWS access with these step-by-step guides.

# Installation Guide: MobaXterm and PuTTY for AWS

## MobaXterm

1. **Download MobaXterm**:
   - Visit the [MobaXterm official website](https://mobaxterm.mobatek.net/download.html).
   - Download the **Home Edition** or **Professional Edition** as needed.

2. **Install MobaXterm**:
   - Run the downloaded installer.
   - Follow the installation prompts to complete the setup.

3. **Configure MobaXterm for AWS**:
   - Open MobaXterm.
   - Click on **Session** in the toolbar.
   - Select **SSH**.
   - Enter your AWS instance’s public IP address or DNS in the **Remote host** field.
   - Choose **Specify username** and enter your AWS instance’s username (e.g., `ec2-user`).
   - Click **OK** to save and connect.

## PuTTY

1. **Download PuTTY**:
   - Visit the [PuTTY official website](https://www.putty.org/).
   - Download the **PuTTY Installer**.

2. **Install PuTTY**:
   - Run the downloaded installer.
   - Follow the installation prompts to complete the setup.

3. **Configure PuTTY for AWS**:
   - Open PuTTY.
   - In the **Session** category, enter your AWS instance’s public IP address or DNS in the **Host Name (or IP address)** field.
   - In the **Connection > SSH > Auth** category, click **Browse** and select your private key file (e.g., `your-key.pem`).
   - Go back to the **Session** category and save your session settings if desired.
   - Click **Open** to connect to your AWS instance.

## Additional Notes

- Ensure that your AWS security group allows inbound SSH traffic on port 22.
- For MobaXterm, you might need to convert your PEM key to PPK format if required (using PuTTYgen).

Feel free to reach out if you have any questions or issues!

