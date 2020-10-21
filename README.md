ATH9KFixup
==========

An open source kernel extension providing patches for unsupported Atheros cards.
- AR9485


#### Features
Only support for AR9485, and no boot Arg required unless for debug.

#### Boot Args List
-ath9koff/n
-ath9kdbg/n
-ath9kbeta/n

#### Installation
1. Put ATH9KInjector.kext to L/E
2. Put ATH9KFixup to C/K/O for Clover or OC/Kexts for Opencore
3. Make some changes to your config if needed
* Require Lilu.kext version 1.2.0 or latest


#### Credits
- [Apple](https://www.apple.com) for macOS  
- [vit9696](https://github.com/vit9696) for [Lilu.kext](https://github.com/vit9696/Lilu) & for patch
- [Pike R. Alpha](https://github.com/Piker-Alpha) for patch
- [lvs1974](https://applelife.ru/members/lvs1974.53809/) for original source code and idea
- [chunnann](http://www.insanelymac.com/forum/user/1977171-chunnann/) for writing the software and maintaining it
- [dickymuliafiqri](https://github.com/Dicky-MF) for change support to only AR9485
