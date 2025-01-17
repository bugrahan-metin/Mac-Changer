# Mac Changer

This is a simple application with which you can change the MAC address of your computer.

## **Features**
- Changes the MAC address of network connections.
- Easy to use command line interface.
- Any network interface (e.g. eth0, wlan0, etc.).


## ** Nasıl Kullanılır **

1. **Identify Your Network Interface**
   First, decide which interface you will make changes to.

2. **Run the Program:**
   ```bash
   python mac_changer.py -i "<interface>" -m "<mac_address>"


3. **for example:**
   ```bash
   python mac_changer.py -i eth0 -m 00:22:33:44:55:66

4. **Check**
   ```bash
   ifconfig

**Notes**
- This tool is for educational and personal use only. Unauthorized use may be illegal in some jurisdictions.

   
