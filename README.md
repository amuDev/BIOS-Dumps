I reccomend using flashrom & CH341A to flash chips. BINs are taken from working boards, version is not logged.
Setting clock and updating to latest is highly reccomend.


Example commands:

  Flashing BIN to chip -
  
    sudo ./flashrom -p ch341a_spi -w /path/to/gitclone/brand/binfile.bin
    
  Create BIN file from chip -
  
    sudo ./flashrom -p ch341a_spi -r /path/to/gitclone/brand/binfile.bin
    
    

I am not responsible for your device, use at your own risk, although these bin files are grabbed from working boards does not mean they will work with yours!
