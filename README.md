# xkb_wasd2arrows

## Intro

RightShift + w = up arrow  
RightShift + a = left arrow  
RightShift + s = down arrow  
RightShift + d = right arrow  

RightShift + q = Home  
RightShift + e = End  

RightShift + z = PageUp  
RightShift + x = PageDown  


## Usage
1. backup original files
```
cd /usr/share/X11/xkb/symbols
sudo cp pc pc.bak
sudo cp us us.bak
```

2. replace original files with new files
```
cp ./pc /usr/share/X11/xkb/symbols
cp ./us /usr/share/X11/xkb/symbols
```

3. remove current rules
```
sudo rm -rf /usr/share/X11/xkb/rules/*.xml
```

4. restart your system
```
sudo reboot
```