# Cubuntu boot/splash screen
The Cubuntu boot screen based on Xubuntu splash screen.
It is for only Plymouth.

# How to use Cubuntu boot/splash screen in Linux?
Ubuntu:


  1: First, type in the terminal:
  
  
  `sudo apt-get update`
  
  `sudo apt-get install plymouth-theme-xubuntu-logo plymouth-theme-xubuntu-text`
  
  
  2: Download repository as ZIP.
  
  3: Extract ZIP.
  
  4: Type in the terminal:
  
  
  `cd ~/Downloads/cubuntu-boot-screen-<version>`
  
  `sudo cp xubuntu-logo /usr/share/plymouth/themes/xubuntu-logo`
  
  
  5: To remove the spinner (Ubuntu default theme), type in the terminal:
  
  
  `sudo apt-get remove plymouth-theme-spinner`
  
  6: To set the text:
  
  
  `sudo cp xubuntu-text /usr/share/plymouth/themes/xubuntu-text`
  
Now you are ready. Reboot the system to take the changes!
