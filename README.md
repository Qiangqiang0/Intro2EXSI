# Intro2EXSI

## 1. Introduction
  1. It is a virtual machine tools.
  2. It is a __stable__ virtual machine tools.
  3. It is not free.

## 2. Install EXSI
  1. __download__ exsi.(I use version 6.7 on evaluation mode)
  2. __RUFUS__/ultroISO... to make bootable usb.
  3. __Install__ and just agree all the agreement.
  
<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/InkedInstall_sucess_LI.jpg" align="middle" height="250" width="" ></a>

  4. press __F2__ to customize your system
  

  
  4. Select __configure password__, press enter to choose, and set your passwd
  
<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/ConfigurePasswd.jpg" align="middle" height="250" width="" ></a>
  
  5. Remember your __IP__.
  
## 3.  Access EXSI by web. 

  1. You should have __another computer__ which has browser!!!

<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/access.jpg" align="middle" height="250" width="" ></a>

  2. It looks like this:
  
<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/InkedEXSI_WEB_all_LI.jpg" align="middle" height="250" width="" ></a>

  3. __Upload your ISO file__.
  
  Select datastore --> datasotrebrower --> upload iso.
  
  
<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/install_datastore.jpg" align="middle" height="250" width="" ></a>




## 3. Install for linux and win10.

    * Build a virtula machine;
<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/build_1.jpg" align="middle" height="250" width="" ></a>
  
<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/build_2.jpg" align="middle" height="250" width="" ></a>

<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/build_3.jpg" align="middle" height="250" width="" ></a>

<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/build_4.jpg" align="middle" height="250" width="" ></a>


__Choose your iso here and check the tick at connect__

<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/build_5.jpg" align="middle" height="250" width="" ></a>

<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/build_6.jpg" align="middle" height="250" width="" ></a>

<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/build_7.jpg" align="middle" height="250" width="" ></a>

   * Finished

<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/build_8.jpg" align="middle" height="250" width="" ></a>


## 4. Mac

### 1. enable ssh:(two methods)
      
* web: <a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/ssh.jpg" align="middle" height="250" width="" ></a>
        
* Host: <a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/EnableSSH.jpg" align="middle" height="250" width="" ></a>

### 2. dowload unlocker: If you are using versions of EXSI before6.5, you could download unlocker208. which you can find on github.

![unlocker300](https://github.com/Qiangqiang0/Intro2EXSI/blob/master/APP/esxi-unlocker-300.tar)

### 3. Upload yourfile to unlocker to EXSI host /vmfs/datastore1/your_unloker_folder with filezilla or scp or ...
  
  __ensure that no other unlocker installed__
  
  `chmod o+x exsi-*`
  
  `./exsi-install.sh`
  
  `reboot`

<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/unlocker.jpg" align="middle" height="250" width="" ></a>

  __Note when reboot, exsi shutdown ssh automatically__
### 4. Access EXSI:
  
  * if you recevie 503 service unavailable (failed to connect to endpoint:[n7vmacore4http16localservicespece:0x00000050d4ebd540] _servernamespace = / action = allow _port = 8309):
  
  * you should:
  
    1. open ssh in EXSI host,(Because you can not access web)
    
<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/EnableSSH.jpg" align="middle" height="250" width="" ></a>

    2. start vsphere-ui service
    service.sh start vsphere-ui
    
    
### 5. build your mac the same as linux.
  
__Choose macos__
  
<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/mac_1.jpg" align="middle" height="250" width="" ></a>
  
 __Choose  mac iso__
 
<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/mac_2.jpg" align="middle" height="250" width="" ></a>
  
### 6. finished
  
<a href="url"><img src="https://github.com/Qiangqiang0/Intro2EXSI/blob/master/Picture/mac3.jpeg" align="middle" height="250" width="" ></a>
    
    

 

  
  
  
  
