<p align="center"><img src="https://i.ibb.co/hBhQ5Dw/CPU.png" width="200"></a>
<h1 align="center"><b>Game does not launch - Intel 10th Gen CPU or newer</b></h1>
<br />

## NFO:
Since the 10th Generation of Intel i-Series Processors, there is an Error in the Calculation of the OpenSSL Instructions
https://www.intel.com/content/www/us/en/developer/articles/troubleshooting/openssl-sha-crash-bug-requires-application-update.html
<br />
<br />

## Ho-To fix:
1. Press WinKey + R to open Run window, paste: ```SystemPropertiesAdvanced```
2. Press "OK"
3. Next click on "Environment Variables..."
4. In the System variables Window, press "New..."
5. Paste these Values:
* Variable name: ```OPENSSL_ia32cap```
* Variable value: ```~0x20000000```
6. Press "OK" and close the Window
7. Restart the Computer
