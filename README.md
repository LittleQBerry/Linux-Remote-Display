# Linux-Remote-Display
If you want to visualize some dataset in linux server and want to use the remote display, this work will help you.


Problem:
  I want to see my dataset in the server with linux system. 
  
Solution
  1. using Xmanager. However it is a paid software233333.
  2. using Mobaxterm. It is work, but slowly.
  3. using Anydesk. It is the best choice. 
  

## Install a virtual desktop
  For archlinux: [xfce] (https://wiki.archlinux.org/title/Xfce)   
  For Ubuntu: [xfce](https://itsfoss.com/install-xfce-desktop-xubuntu/)    
  ATTENTION: reboot your server    
  
## MobaXterm
  In the [Advanced SSH Setting]     
    Check "X11-fording"   
    Choose "Xfce4 desktop" in "Remote environment"    
    Connect    

## Anydesk
  1.Install anydesk. For archlinux: https://aur.archlinux.org/packages/anydesk-bin/     
  2.Get the Computer ID    
    cat /etc/anydesk/system.conf    
  3. Set the connect password. password is your password     
    echo password | sudo anydesk --set-password    
  4. Download a client in PC. Connect it.       


Over.
