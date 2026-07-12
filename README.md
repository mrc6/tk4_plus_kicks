# tk4_plus_kicks
A fully installed kicks ( open source replacement for CICS ) on tk4 emulator for Mainframe training   
Learn about tk4 here: https://wotho.pebble-beach.ch/tk4-/     
Learn about kicks here: https://www.kicksfortso.com/   

# How to use    
Download the file [tk4_plus_kicks.zip](https://www.dropbox.com/scl/fi/06kh4wrwx73a7r7lzlsuj/tk4_plus_kicks.zip?rlkey=8ztl1qg9v0w5va6w48i01g9mi&st=vus1and3&dl=0) and extract it into a folder.    
Start tk4, logon as HERC01 user, press F3 until go back to READY    
Exec the following command:   
**exec kickssys.v1r5m0.clist(kicks)**   
    
  ![Exec Kicks](https://github.com/mrc6/tk4_plus_kicks/blob/main/images/exec_kicks.png)     
ENTER twice    
    
  ![Kicks Logo](https://github.com/mrc6/tk4_plus_kicks/blob/main/images/kicks_logo.png)   
CLEAR() key ( in my case alt+c)   
**KEDF**   
You can try an example    
Clear() key, **INQ1**    
      
  ![Using Demo](https://github.com/mrc6/tk4_plus_kicks/blob/main/images/kicks_demo.png)  
      
  ![Demo result](https://github.com/mrc6/tk4_plus_kicks/blob/main/images/kicks_demo_result.png)    
      
To finish the session use the command **KSSF**    
    
  ![Exiting](https://github.com/mrc6/tk4_plus_kicks/blob/main/images/kicks_demo_exit.png)  

          
  By Marcob
