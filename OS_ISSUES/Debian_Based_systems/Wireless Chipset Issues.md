**Debain based wireless issues**
 1. **Qualcomm Atheros* - Some times though after installing `frimware-atheros`
    in Debia(& based systems), it is possible that either wifi or Ethernet or 
    may not work. Sometimes there is possiblity that when WiFi works ethernet 
    doesnot work and sometimes Ethernet works and WiFi doesn't work. 
    
***Solution:*  Use this [Github repository](https://github.com/ajaybhatia/Qualcomm-Atheros-QCA9377-Wifi-Linux)
 or you may get(Download) this from here  [uploads](https://gitlab.com/gorlapraveen/TheLearningDocumentationProject/raw/0cef4563fe690050a3d8a2f6018ebacec0e7f5cd/uploads/Qualcomm-Atheros-QCA9377-Wifi-Linux.zip)  (updated on 2018 Dec 11)

When you Download thorugh [uploads](https://gitlab.com/gorlapraveen/TheLearningDocumentationProject/raw/0cef4563fe690050a3d8a2f6018ebacec0e7f5cd/uploads/Qualcomm-Atheros-QCA9377-Wifi-Linux.zip), Extract it and READ `README.md` for specific installation based on Linux kernel.

2. `Wired Unmanned` in Debian systems, LAN will not be working.
  
 Solution: In `/etc/NetworkManager/NetworkManager.conf` change `managed=false` to `managed=true`.

**Optional Hint:** Use `nmtui` command to Add/Edit/Delete unnecessary Wireless Interfaces, incase of more duplicate `LAN` interfaces while in `Wired Unmanaged`