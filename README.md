
# Owshen Wallet

A quick and easy guide on how to install Owshen with Ubuntu

## Step by Step Guide (With Photos)

1. Boot up your Ubuntu/Powershell 
&nbsp;

![App Screenshot](https://i.imgur.com/yTotcBI.png)
&nbsp;

2. Install libfuse with this following command:

```bash
  sudo apt install libfuse2
```
![App Screenshot](https://i.imgur.com/GT0CzZI.png)
&nbsp;

3. Download the Owshen Wallet AppImage

```bash
   wget https://github.com/OwshenNetwork/owshen/releases/download/v0.1.0/Owshen_v0.1.0_x86_64.AppImage
```

&nbsp;
![App Screenshot](https://i.imgur.com/yxzG0Lc.png)
&nbsp;

3. Make the Github AppImage an executable
&nbsp;
```bash
   chmod +x Owshen_v0.1.0_x86_64.AppImage
```
&nbsp;

4. Run the executable 
&nbsp;
```bash
   ./Owshen_v0.1.0_x86_64.AppImage init
```
Note: DO NOT FORGET TO SAVE YOU MNENOMIC!!
&nbsp;

5. Open the Wallet via  http://127.0.0.1:9000
&nbsp;
```bash
   ./Owshen_v0.1.0_x86_64.AppImage wallet
```

6. Save your wallet address and submit it!
