OrangePi Build System
---------------------------------------

Welcome to OrangePi Build System, Good start Linux World with OrangePi!

Funny with your idear and build your owner Linux system.

#### OrangePi Build System support list:

  * OrangePi PC2
 
  * OrangePi Prima
 
  * OrangePi Win

  * OrangePi Win plus

  * OrangePi Zero

  * OrangePi Zero plus

  * OrangePi Zero plus 2

  * OrangePi PC plus

  * OrangePi Plus 2E

  * OrangePi Lite

  * OrangePi One

  * OrangePi Mini2

  * OrangePi 2

  * OrangePi Plus 2

  * OrangePi 2G-IOT

  * OrangePi i96

-----------------------------------------------------------------

#### Using OrangePi Build System

   It's easy to build owner Linux distro in OrangePi Build System, you need follow
   thoese steps:

   1. Download source code for your OrangePi Board.

      You need clone this repertory, and run build scripts to download
      source code for your OrangePi Board. such as:
      
      ```
        git clone https://github.com/OrangePiLibra/OrangePi.git
      ```
      
      This scripts is a simple entry that build different OrangePi distro,
      After finishing to download this repertory, you need change dirent into
      "OrangePi", and run build scripts:
      
      ```
        ./Build_OrangePi.sh
      ```

     Choose correct OrangePi version that you want, and scripts will download
     source code that contain kernel, uboot and build scripts.

     It will cost some time, so please wait a mintue. After this finish, you
     will get a new dirent and change your dirent into new dirent.

     If you use "OrangePi PC2/Prima/Zero plus2", please change your dirent into "OrangePiH5"

     If you use "OrangePi Win/Win plus", please change your dirent into "OrangePiA64"

     If you use "OrangePi Zero", please change your dirent into "OrangePiH2"

     If you use another board, please change your dirent into "OrangePiH3"

   2. Build owner distro OrangePi system

     Then, you only need run a scripts and you can build your owner system easily.
     Note, please don't run this scripts as root. Last, you need run scripts,
     such as:
     
     ```
       ./build.sh
     ```

------------------------------------------------------------------

### Maintain OrangePi

  We offer different repertory to maintain OrangePi, you can also push your patch
  into OrangePi build system, more detail:

  * OrangePi 2G-IOT/i96

    OrangePi 2G-IOT/i96 build on Allwinner RDA8810 Soc, the offfical maintain
    repertory as follow:

    kernel:
    
    ```
      https://github.com/OrangePiLibra/OrangePiRDA_kernel.git
    ```
    
    scripts:
    
    ```
      https://github.com/OrangePiLibra/OrangePiRDA_scripts.git
    ```

  * OrangePi PC2/Prima/Zero plus2

    OrangePi PC2/Prima/Zero plus build on Allwinner H5 Soc, the offfical maintain
    repertory as follow:

    kernel:
    
    ```
      https://github.com/OrangePiLibra/OrangePiH5_kernel.git
    ```
    
    u-boot:
    
    ```
      https://github.com/OrangePiLibra/OrangePiH5_uboot.git
    ```
    
    build scripts
    
    ```
      https://github.com/OrangePiLibra/OrangePiH5_scripts.git
    ```
    
    external binary file
    
    ```
      https://github.com/OrangePiLibra/OrangePiH5_external.git
    ```
    
    toolchain
    ```
      https://github.com/OrangePiLibra/OrangePiH5_toolchain.git
    ```

  * OrangePi Win/Win plus

    OrangePi Win/Win plus build on Allwinner A64 Soc, the offfical maintain
    repertory as follow:

    kernel:
    
    ```
      https://github.com/OrangePiLibra/OrangePiA64_kernel.git
    ```
    
    u-boot:
    
    ```
      https://github.com/OrangePiLibra/OrangePiA64_uboot.git
    ```
    
    build scripts
    
    ```
      https://github.com/OrangePiLibra/OrangePiA64_scripts.git
    ```
    
    external binary file
    ```
      https://github.com/OrangePiLibra/OrangePiA64_external.git
    ```
    
    toolchain
    ```
      https://github.com/OrangePiLibra/OrangePiA64_toolchain.git
    ```


  * OrangePi Zero

    OrangePi Zero plus build on Allwinner H2+ Soc, the offfical maintain
    repertory as follow:

    kernel:
    
    ```
      https://github.com/OrangePiLibra/OrangePiH2_kernel.git
    ```
    
    u-boot:
    
    ```
      https://github.com/OrangePiLibra/OrangePiH3_uboot.git
    ```
    
    build scripts
    
    ```
      https://github.com/OrangePiLibra/OrangePiH2_scripts.git
    ```
    
    external binary file
    
    ```
      https://github.com/OrangePiLibra/OrangePiH2_external.git
    ```
    
    toolchain
    ```
      https://github.com/OrangePiLibra/OrangePiH3_toolchain.git
    ```

  * OrangePi Plus2/Plus 2E/One/PC/2/Lite/PC Plus/Mini2

    OrangePi Plus2/Plus 2E/One/PC/2/Lite/PC Plus/Mini2 plus build on Allwinner H3 Soc,
    the offfical maintain repertory as follow:

    kernel:
    
    ```
      https://github.com/OrangePiLibra/OrangePiH3_kernel.git
    ```
    
    u-boot:
    
    ```
      https://github.com/OrangePiLibra/OrangePiH3_uboot.git
    ```
    
    build scripts
    
    ```
      https://github.com/OrangePiLibra/OrangePiH3_scripts.git
    ```
    
    external binary file
    
    ```
      https://github.com/OrangePiLibra/OrangePiH3_external.git
    ```
    
    toolchain
    
    ```
      https://github.com/OrangePiLibra/OrangePiH3_toolchain.git
    ```
