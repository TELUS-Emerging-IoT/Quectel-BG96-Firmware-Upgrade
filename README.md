# Quectel-BG96-Firmware-Upgrade
Instructions on how to upgrade the **BG96 module firmware** on  TELUS Sixfab RPi Shield.

`You need Windows Operating System to perform this upgrade.`

1. Download, Unzip and Install **Quectel LTE Windows USB driver** (https://iotdevkit.s3.ca-central-1.amazonaws.com/Quectel_LTE_Windows_USB_Driver_V1.0.zip)

2. Download and Unzip **Quectel QFlash Porgrammer** application (https://iotdevkit.s3.ca-central-1.amazonaws.com/QFlash_V4.8.zip)

3. Download and Unzip **BG96 Firmware** file (https://iotdevkit.s3.ca-central-1.amazonaws.com/BG96MAR02A07M1G_01.016.01.016.zip)

4. Open **Windows Device Manager**, expand the **Ports (COM & LPT)** section.

5. Connect micro USB cable to TELUS Sixfab Shield and plug the other end to the computer.

   ![alt_text](images/IMG_8400_320.jpg) ![alt_text](images/IMG_8402_320.jpg)

6. Press and hold **Power Key** button for 3 seconds.

   ![alt_text](images/IMG_8404.jpg)

7. Three new COM ports should now be listed under the Ports section of Windows Device Manager

   ![alt_text](images/COM_Ports.png)

8. Launch **QFlash_V4.8.exe** application inside the extracted QFlash_V4.8 folder. `(Note: Paths to the tool and firmware may NOT contain spaces or non-English characters!)`

      ![alt_text](images/QFlash_V48.png)

9. Set **Buadrate** to **460800**

10. Set **COM Port** to COM port number of **Quectel USB DM Port**

11. Click **Load FW Files** button. Select **acdb.mbn** file inside **BG96MAR02A07M1G_01.016.01.016\UPDATE** folder and click OK. `QFlash winsow will update with a list of files to be programmed`

      ![alt_text](images/Load_FW_Files.png)

12. Click **Start** button to upgrade the firmware.

      ![alt_text](images/FW_Upgrade_Progress.png)

13. 
