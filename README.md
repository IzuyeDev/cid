# Tutorial

CID from Enrico Imanuel

## How To Use :

* Open Google Cloud Console [Click Here](https://shell.cloud.google.com) then click on Activate Cloud Shell

* After your cloud shell terminal is ready paste this :
```bash
git clone https://github.com/IzuyeDev/cid.git
```
* And then type:
```bash 
cd/cid
```
* Edit Your bot cerdential in [corefunc.h](https://github.com/IzuyeDev/cid/blob/787b88212e27a99e1cc3b6be42664c2b9e973670/corefunc.h#L21) on File Editor
```c
//Edit sesuai keinginan

#pragma once
//Set GrowID
string Growid_acc = "yourbotname";  << edit this to your bot name

//Set Password
string Password_acc = "yourpass";  << edit this to your bot password

//Customing Gmail 
string Gmail_acc = "randommail";   << wrtite a random gmail without add @gmail.com

//Setting Start akun dari nomor(Account)
int START_ACC = 1;

//Setting Start email dari (Gmail)
int START_GMAIL = +1;
```
* Save and type this on console to build:
```bash
bash build.sh
```
 * After building success, type:
```bash
chmod +x createid
```

## Start Creating Bots Acc

* Start creating by typing: 
```bash
./createid
```

* if you want to see the list of bots you have created, open File Editor and open ```acc.txt``` file.

