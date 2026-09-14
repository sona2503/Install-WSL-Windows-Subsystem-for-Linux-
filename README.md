# Steps to Install WSL on Windows

## Requirements
- Make sure your computer/PC is running **Windows 10/11**.

## Steps:
1. Open CMD or PowerShell -> Run as administrator
2. Enter the following command:
   ```sh
   wsl --install
   ```
3. Once the Linux kernel has finished installing, enter this command to display the list of available distributions:
   ```sh
   wsl --list --online
   ```
   ![Screenshot](gambar1.png)

4. After choosing the distribution you want to use, enter this command:
   ```sh
   wsl --install -d <distro_name>
   ```
5. Set up your username and password.
6. Look for the "Ubuntu" app (or whichever distro you installed) in your Start menu.
7. Check the distro version with the following command:
   ```sh
   lsb_release -a
   ```
   ![Screenshot](gambar2.png)
