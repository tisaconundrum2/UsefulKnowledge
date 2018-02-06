# UsefulKnowledge
Useful and knowledgeable things I've picked up


# How to create Symbolic Links to Save Space 

```
robocopy /copyall /mir /xj C:\Users D:\Users 
rmdir /S /Q C:\Users 
mklink /J "C:\Users" "D:\Users"

# 'Users' can be any directory
```

If you want SymLink an entire User profile you'll need a Live CD
<br>With the Live CD access the CMD and do the same thing as above

# Travis CI, How to encypt your deployment

```
# This should be done in Linux
travis encrypt "GITHUB PASSWORD" --add deploy.password branch_name
```

# Bitcoin

The several ways to protect your Bitcoin Keys

## Hardware

 - Trezor `$99`
 - Ledger Nano S `$65`

## Software

 - Desktop wallets `cold storage` `risk of orphaning coins if system breaks`
 - Mobile wallets `quick access` `risk of orphaning coins if system breaks`
 - Online wallets `accessed from anywhere` `risk of orphaning coins if system breaks` `trust is with the site owner`

### Some software websites

 - Copay
 - Electrum
 - Exodus
 - Jaxx
 
## Paper

 - simply a printed piece of paper that contains a cryptocurrency address `considered to be more confusing and complicated to set up`
 
# A Place to buy full Open Software
codecanyon.net

# How to decompile your APK (Android App)
1. Go to [https://ibotpeaches.github.io/Apktool/](https://ibotpeaches.github.io/Apktool/) and download the latest apktool.jar file
2. You will need to install `jdk-9.0.4_windows-x64_bin.exe` this will help with step 4
3. And install `jre-9.0.4_windows-x64_bin.exe` this will help with recompiling `apk`s
4. Open CMD and type `java -version` if everything worked, you've successfully installed java
<br>![](https://i.imgur.com/kSWBNZo.png)
5. 
