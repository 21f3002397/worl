# worl
## DESCRIPTION:
**States whether given text is "w" or "l"**

## SETTING UP:
**git clone https://github.com/21f3002397/worl.git ~/worl**

**chmod +x ~/worl/worl.x**

**cp ~/worl/worl.x /usr/bin/worl**

## USAGE:
**worl \[options\] \[text\]**

## OPTIONS:
### **-o | --offset**

**kind of acts like a seed, changes the output of the command.**
 
**if provided multiple times, then offset adds up**
 
**Example: worl -o 45 blah blah blah**
  

### **-r |--random**

**random offset.**
 
**no effect from multiple uses**
 
**Example: worl -r hello world**
  

### **-f | --file**

**read from file.**
 
**if provided multiple times, then only reads from the last -f option**
 
**Example: worl -f index.html**
  
## 
**Any other option would be treated as normal text.**


