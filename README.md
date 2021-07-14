# Install-Dynatrace-ActiveGate-On-Linux
Dynatrace offers two types of ActiveGate: Environment ActiveGate and Cluster ActiveGate. But this is installation Environment ActiveGate tpye.

# ActiveGate hardware and system requirements for Linux
You can see ActiveGate hardware and system requirements for Linux from this [link](https://www.dynatrace.com/support/help/shortlink/activegate-requirements-linux)  

# Install an Environment ActiveGate on Linux  

1. In Dynatrace. you can go to **Deployment status** > **ActiveGate** > **Install ActiveGate**  
    
   [![Screen-Shot-2564-07-14-at-12-48-14.png](https://i.postimg.cc/XJH52NMt/Screen-Shot-2564-07-14-at-12-48-14.png)](https://postimg.cc/HcMjngkt)  
   
2. Select **Linux** button, and then **Create token** > copy command on the target host to download the installer.  

   [![Screen-Shot-2564-07-14-at-12-57-40.png](https://i.postimg.cc/QdXV9Bys/Screen-Shot-2564-07-14-at-12-57-40.png)](https://postimg.cc/6ymBFQK1)  
  
   - What's the purpose of this ActiveGate? You can see information of [ActiveGate purpose](https://www.dynatrace.com/support/help/shortlink/sgw-types#anchor_purposes)  
   - If your ActiveGate host can't useing wget command, you can download the ActiveGate installer from **No internet access on servers**  
    
   [![Screen-Shot-2564-07-14-at-14-34-15.png](https://i.postimg.cc/m24Yby7g/Screen-Shot-2564-07-14-at-14-34-15.png)](https://postimg.cc/0rtMnmtT)  
    
3. Go to your ActiveGate host, If you can using wget command, you can run the command from step 2. And then run the installer with root rights.  
   - This command run the installer. 
      >/bin/sh Dynatrace-ActiveGate-Linux-x86-(Version...).sh

   [![Screen-Shot-2564-07-13-at-20-10-35.png](https://i.postimg.cc/9Qk55MsC/Screen-Shot-2564-07-13-at-20-10-35.png)](https://postimg.cc/Mn1r1WWF)  
   
   [![Screen-Shot-2564-07-13-at-20-51-43.png](https://i.postimg.cc/SxC7q1vR/Screen-Shot-2564-07-13-at-20-51-43.png)](https://postimg.cc/686Gfcwx)  
   
   [![Screen-Shot-2564-07-14-at-14-57-02.png](https://i.postimg.cc/9XwBJfYy/Screen-Shot-2564-07-14-at-14-57-02.png)](https://postimg.cc/CdYDKStK)
    
    
    
# Reference:  

[Install an Environment ActiveGate on Linux](https://www.dynatrace.com/support/help/shortlink/sgw-install-linux)
