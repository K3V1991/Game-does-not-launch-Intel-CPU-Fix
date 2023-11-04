<p align="center"><img src="https://github.com/K3V1991/Game-does-not-launch-Intel-CPU-Fix/blob/main/CPU.png" width="200"></a>
<h1 align="center"><b>Game does not launch - Intel 10th Gen CPU or newer</b></h1>
<br />

<p align="center">
<a href="https://liberapay.com/K3V1991" alt="LiberaPay"><img src="https://img.shields.io/badge/Liberapay-F6C915?style=for-the-badge&logo=liberapay&logoColor=black" /></a>
<a href="https://ko-fi.com/k3v1991" alt="Ko-fi"><img src="https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white" /></a>
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HW8B98TVDLKWA" alt="PayPal"><img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" /></a>
<a href="https://github.com/K3V1991/Donate-Crypto/blob/main/README.md" alt="Crypto"><img src="https://img.shields.io/badge/Bitcoin-000?style=for-the-badge&logo=bitcoin&logoColor=white" /></a>
</p>
<hr />
<br />

## NFO:
Since the 10th Generation of Intel i-Series Processors, there is an Error in the Calculation of the OpenSSL Instructions
https://www.intel.com/content/www/us/en/developer/articles/troubleshooting/openssl-sha-crash-bug-requires-application-update.html
<br />
<br />

## Ho-To fix:
1. Press WinKey + R to open Run window, paste: ```SystemPropertiesAdvanced```
2. Press ```OK```
3. Next click on ```Environment Variables...```
4. In the System variables Window, press ```New...```
5. Paste these Values:
* Variable name: ```OPENSSL_ia32cap```
* Variable value: ```~0x20000000```
6. Press ```OK``` and close the Window
7. Restart the Computer
