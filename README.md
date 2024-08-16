# DD-windows-svr-2025-GCP
Tested and working on GCP.

Below content are for EDUCATIONAL PURPOSE and will no hold any responsibilities on any account banned.

Requirements for win svr 2025:
2core 4gib machine with 35gib storage 64bit cpu

1. Create instance in GCP with Debian11 OS (AMD/INTEL) and wait for the process
2. SSH into the debian OS and type the command below :
2.1     sudo -i
2.2     apt-get update
2.3     apt-get install -y xz-utils openssl gawk file wget -y

3. Get info for your server ip-addr , ip-mask & ip-gate you will need to use it when running the command

    Example : --ip-addr 10.148.0.1 --ip-mask 255.255.255.0 --ip-gate 10.148.0.1
   
   
4. Download the DD windows svr2025 gzip file from my google drive and host it in your own personal server to use for the installation later
   
      (  https://drive.google.com/file/d/1qQZ6Sp7xv6Jx25hzWaEGnPzSumNVXbf3/view  )

5. Make sure to download the image file url have to include the file name "WinSvr2025_Datacenter_EN.vhd.gz" else the installation will failed

6. wget --no-check-certificate -qO InstallNET.sh 'https://github.com/teddysun/across/raw/master/InstallNET.sh' && bash InstallNET.sh --ip-addr Your_Server_IP --ip-mask Your_Server_IP_Mask --ip-gate Your_Server_IP_Gate -dd 'http://Your_Server_name/WinSvr2025_Datacenter_EN.vhd.gz'

7. Wait for the installation it will take around 1 hour 10 minutes to complete the whole process.
8. Connect to your new Win Svr2025 with Remote desktop client on any computer or mobile phone.

9. Username : Administrator
10. Password: Qwerty@1@2@3

11. Note: This windows are not activated ! Please get the Genuine Key from microsoft 

12. Credits thanks to Teddysun for the wondefull InstallNET.sh script and vhd file from me. 
