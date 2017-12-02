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
 
 
