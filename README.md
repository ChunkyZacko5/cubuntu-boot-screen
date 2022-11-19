# Cubuntu boot/splash screen

![image](https://user-images.githubusercontent.com/111050027/202845820-6aa98cd6-58e2-4336-a4f4-31690558a11d.png)

The Cubuntu boot screen based on Xubuntu splash screen.

It is for only Plymouth.

# How to use Cubuntu boot/splash screen in Linux?

![image](https://user-images.githubusercontent.com/111050027/202846517-3977c649-7f90-431c-8415-3336e84bd3c1.png)

Ubuntu:


  1: First, type in the terminal:
  
  
  `sudo apt-get update`
  
  `sudo apt-get install plymouth-theme-xubuntu-logo plymouth-theme-xubuntu-text`
  
  
  2: Click in releases, download as ZIP.
  
  3: Extract ZIP.
  
  4: Type in the terminal:
  
  
  `cd ~/Downloads/cubuntu-boot-screen-<version>`
  
  `sudo cp xubuntu-logo /usr/share/plymouth/themes/xubuntu-logo`
  
  
  5: To remove the spinner (Ubuntu default theme), type in the terminal:
  
  
  `sudo apt-get remove plymouth-theme-spinner`
  
  6: To set the text:
  
  
  `sudo cp xubuntu-text /usr/share/plymouth/themes/xubuntu-text`
  
Now you are ready. Reboot the system to take the changes!
