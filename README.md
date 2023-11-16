# WSL
Install Ubuntu on WSL2

Original source of this guidance see https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-10#1-overview

You may create cross-platform applications without ever leaving Windows by installing a full Ubuntu terminal environment on your Windows computer in a matter of minutes with Windows Subsystem for Linux (WSL).
We'll walk you through setting up Ubuntu on WSL in this guide. You can use these instructions with Windows 10 or Windows 11.

**First Installation Method**
1) Type Windows PowerShell into the Windows search bar. From there, select **Run as administrator**.
2) At the command prompt type:
   wsl --install
3) And then wait for the process to complete. You will now need to restart your computer for WSL to be properly active.
4) Download the latest Ubuntu release here:
   https://www.microsoft.com/en-us/p/ubuntu/9pdxgncfsczv?rtc=1&activetab=pivot:overviewtab
5) Choose your preferred distribution and then click **Get** or just click **Install**. Ubuntu will then be installed on your computer.

**Second Installation Method**
1) A single command will install both WSL and Ubuntu simultaneously. When you first launch Windows PowerShell, simply change the initial command to:
wsl --install -d ubuntu
2) This will install both WSL and Ubuntu!

Whether you use the first or second installation method, remember to restart your computer before continuing. 
The application will either be launched directly from the store or you can search for Ubuntu in Windows's search bar after installation.
After Ubuntu has completed its initial setup, you must create a username and password (which do not have to match your Windows user credentials).
It's always a good idea to install the latest updates with the following commands (enter your password when prompted):
sudo apt update
then
sudo apt upgrade

You have installed Ubuntu on your computer. Congrats!!


