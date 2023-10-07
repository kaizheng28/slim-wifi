# slim-wifi
Schematic and layout file for the SlimWiFi prototype. Open with Altium Designer. 

The LCR values need fine-tuning but you may start with the values in the schematic. The frequency should be close to 2.4GHz using the posted values. Play around with C2, C4, and C5 to fine-tune.  
L4, C6, and C7 are reserved for impedance matching, but in our previous experiment, bypassing them yields the strongest output signal for some reason.

**Related publication:**
Zhao, Renjie, Kejia Wang, Kai Zheng, Xinyu Zhang, and Vincent Leung. "{SlimWiFi}:{Ultra-Low-Power}{IoT} Radio Architecture Enabled by Asymmetric Communication." In 20th USENIX Symposium on Networked Systems Design and Implementation (NSDI 23), pp. 1201-1219. 2023.
