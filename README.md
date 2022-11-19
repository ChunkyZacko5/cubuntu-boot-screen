
![image](https://user-images.githubusercontent.com/111050027/202845820-6aa98cd6-58e2-4336-a4f4-31690558a11d.png)

The Cubuntu boot screen based on Xubuntu splash screen.

It is for only Plymouth.


![image](https://user-images.githubusercontent.com/111050027/202846517-3977c649-7f90-431c-8415-3336e84bd3c1.png)


![image](https://user-images.githubusercontent.com/111050027/202850288-61a08fbf-1cf8-4978-8a3f-ceaa32c5520f.png)

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

![image](https://user-images.githubusercontent.com/111050027/202847217-0c3b0b64-97cd-419a-be6a-87afd6635565.png)

Linux Mint:

  1: First, type in the terminal:
  
  `sudo apt update && sudo apt install plymouth-theme-xubuntu-logo plymouth-theme-xubuntu-text`
  
  2: Open file manager, right click and click "Open as Root".
  
  3: Click in releases, download as ZIP.
  
  4: Extract in the terminal:
  
  `unzip ~/Downloads/cubuntu-boot-screen-<version>.zip`
  
  5: In the file manager as root, copy xubuntu-logo folder after clicking Ctrl+C, go to /usr/share/plymouth/themes, click Ctrl+V to paste. (Logo)
  
  6: In the file manager as root, copy xubuntu-text folder after clicking Ctrl+C, go to /usr/share/plymouth/themes, click Ctrl+V to paste. (Text Mode)
  
  7: In the file manager as root, remove mint-logo, remove mint-logo-legacy.
  
  You are now ready. Reboot your system to take the changes!
