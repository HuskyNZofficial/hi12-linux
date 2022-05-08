# Install lunix on your Chuwi Hi12


#1.
    Install a linux distro the one I used was linux mint but any debian based distro should work.
    
    1.A
      Flash the linux mint iso to a usb
    1.B
      Boot the usb but pressing f7 on you chuwi on boot
    1.C
      Istall linux mint like any other computer
     
#2.
  Install the Liquorix kernal
 
    2.A You will need you phone to hotspot becase at the time of this writing the default kernal has broken wifi drivers
    
    2.B Install
        (On other os's not lunix mint you may need to install software-properties-common using this command sudo apt install software-properties-common)
    

      Debian Prerequisites:

          curl 'https://liquorix.net/add-liquorix-repo.sh' | sudo bash

      Ubuntu Prerequisites:

          sudo add-apt-repository ppa:damentz/liquorix && sudo apt-get update

      The Liquorix kernel can be installed by way of meta-packages. This will guarantee that the latest kernel is installed on every upgrade.

          sudo apt-get install linux-image-liquorix-amd64 linux-headers-liquorix-amd64
          
          Reboot
          (Pulled from there website)
          
 
 
 Done, you should have a working toch screen and all else working it is mutch faster than other os's
