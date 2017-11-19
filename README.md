# UsefulKnowledge
Useful and knowledgeable things I've picked up


# How to create Symbolic Links to Save Space 

```
robocopy /copyall /mir /xj C:\Users D:\Users 
rmdir /S /Q C:\Users 
mklink /J "C:\Users" "D:\Users"

# 'Users' can be any directory
```

