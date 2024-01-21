# santaisaja
tenaga tambahan

Get yourself a GNU/Linux machine. (Ubuntu +22.04 preferred)
Install libfuse2, nodejs and snarkjs:
sudo apt install fuse libfuse2 nodejs -y
sudo npm install -g snarkjs
Download the latest AppImage of the Owshen Wallet:
wget https://github.com/OwshenNetwork/owshen/releases/download/v0.1.3/Owshen_v0.1.3_x86_64.AppImage
Make it executable:
 chmod +x Owshen_v0.1.3_x86_64.AppImage
If this is the first time you are creating a wallet, initialize your wallet and KEEP YOUR 12-WORD MNEMONIC PHRASE IN A SAFE PLACE!
./Owshen_v0.1.3_x86_64.AppImage init
Otherwise, if you have previously participated in our airdrop and already have a wallet, re-initialize your wallet with your old 12-mnemonic phrase via this command:
./Owshen_v0.1.3_x86_64.AppImage init --mnemonic "[YOUR 12 WORD MNEMONIC-PHRASE]"
In case you have problems reinitializing your wallet, try removing the old wallet files (THIS WILL REMOVE YOUR WALLET FILE, MAKE SURE YOU HAVE WRITTEN DOWN YOUR 12-WORD MNEMONIC PHRASE SOMEWHERE!):
rm -rf ~/.owshen-wallet
rm -rf ~/.owshen-wallet-cache
And then initialize again!
Run the Owshen wallet! You should be able to see your DIVE balance in case you have successfully participated on our Bermuda airdrop!
./Owshen_v0.1.3_x86_64.AppImage wallet
