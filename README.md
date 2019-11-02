# HarSM2
HarSM Java HSM Simulator
Welcome,
HarSM is a java webbased HSM simulator that performs the standard functions of ISO 8583 DES security.

During my work in the Financial IT Sector I've often encountered situation where during development phase the developers team doesn't have access to a HSM or for practicality and maybe budget reasons often resort to try to find a software based solution for all the standard HSM functions for the ISO 8583 communication.

Added with the standard learning curve associated for inexperienced developers in Thales HSM configuration and racal communication protocol often complicates a relatively straightforward problem.

 

HarSM is a compilation of all the standard most commonly used ISO 8583 DES based security actions, at least the ones I've encountered for banks and other major financial bill payment switching institutions in Asia. It provides a webmenu and HTTP get based interface so you can use it programatically from your application via simple HTTP GET method.

 

HarSM v 0.7 has the following features

- DES/TDES(Triple DES)/2TDES key generation

- DES/TDES/2TDES key generation from components (XOR Method) similar to the thales FK command

- Basic LMK(Local Master Key) support

- Key Check Value Calculation

- DES/TDES/2TDES Encryption/Decryption with ISO 8583 ANSI ECB standard

- Key Translation ( transalate a key wrapped in one key to another key)ZMK, TAK, ZPK

- MAC Generation (ANSI CBC Standard, most commonly used)

- PINBLOCK Generation (ISO Format 0, most commonly used)

- CVV and PVV Calculation for VISA, Mastercard and AMEX

 

You can download the software from the download link, you need at least JDK 1.5 to run, I reccomend 1.6. Unzip the file and to start just type java -jar HSMp.jar

With the default settings, the webmenu is started at port 8080, while the http interface is at 9090.
