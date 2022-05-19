This guide is targeted towards total 'noobs' as prompted by https://github.com/HoloArchivists/twspace-dl/issues/57

# 0. Requirements
For the software to work you have to set up ffmpeg because it uses it

You can find a guide for that there https://video.stackexchange.com/a/20496

It explains the process better than I could 

# 1. Download
The first step is to download the software

Click here

![Under 'From portable binaries'](https://user-images.githubusercontent.com/77058942/169108801-549f0ae4-b5f7-43ef-9c93-e813ee09596e.png)

Put the in a place you'll be able to access easily (e.g. Desktop)

# 2. Launching the software
Press Win+R

![Win+R](https://user-images.githubusercontent.com/77058942/169109433-db730bef-5e1b-41b6-828f-bca32bb56e6a.png)

You'll see this window open

!['Run' window](https://user-images.githubusercontent.com/77058942/169109571-ea20df43-bf9b-4e31-a039-171af89b8760.png)

Enter cmd in the text bar as shown above and press enter

Once the cmd window is open, enter the location of the file (e.g. `C:\Users\John\Desktop\twspace_dl.exe`), followed by `-i` 
and the URL of the space you want to download (e.g. `https://twitter.com/i/spaces/DeadB33F`)

Such that the result looks somewhat like this 
```
C:\Users\John\Desktop\twspace_dl.exe -i https://twitter.com/i/spaces/DeadB33F
```

This should mostly work for ongoing and recorded space
