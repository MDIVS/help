# Internet Issues
[home](../README.md)

Sometimes when I have internet issues, these steps are helpful:

> Note: If you are asked for an administrative login, you will need to contact your system administrator.  

1. Type win+R and press enter to open "windows run"
2. Type `cmd` and press enter to open command prompot
3. Type `ipconfig /flushdns` and press Enter.  
4. Type `ipconfig /registerdn` and press Enter.  
5. Type `ipconfig /release` and press Enter.  
6. Type `ipconfig /renew` and press Enter.  
7. Type `netsh winsock reset` and press Enter.  

Restart the computer.