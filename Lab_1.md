# Week 1 Lab Report


## Installing VScode
  Installing VSCode is very easy.
  
  1. First you would go to the Visual Studio Code Website [https://code.visualstudio.com/](https://code.visualstudio.com/)
  2. Click Download, follow the instructions, and install it on your computer

  > **Note**: You can only download this operating systems for Macs, Windows, or Linux operating systems.

  Once it is installed, it should open a window just like this picture below.
![VSCode](https://user-images.githubusercontent.com/114209345/193187125-9c73a75f-40e6-48f7-8b8b-54436effcf7b.png)

## Remotely Connecting
  To connect within a school computer we will use a program called OpenSSH. This program allows you to connect your computer to other computers.
  1. Remember to install the OpenSSH client and **NOT** the server
  2. Click this this link:[Install OpenSSH](https://learn.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse?tabs=gui)
  3. Once OpenSSH is installed, go to Visual Studio Code
  4. Connect to the remote computer using VSCode's remote option. Instructions: [Connect to host](https://code.visualstudio.com/docs/remote/ssh#_connect-to-a-remote-host)
  5. Open the terminal of VSCode and after the $ sign input
      > ssh cs15lfa22XX@ieng6.ucsd.edu
      > ieng6 is the Linux servers for school
  6. There will then be a comment saying:
      > Are you sure you want to continue connecting
      > Type **Yes** and press enter
  7. Then typed in the password you have placed for your cs15lfa22XX account\
  8. Once you have seen a cluster status, you are IN
  ![Cluster status](https://user-images.githubusercontent.com/114209345/193204679-d01422c8-c47c-4fe1-8f9e-056092f8fc5c.png)
  7. Then typed in the password you have placed for your cs15lfa22XX account\
  
## Trying Some Commands


## Moving Files with scp


## Setting an SSH Key


## Optimizing Remote Running
