# Generates EVM compatible wallet

Generates EVM compatible mnemonic phrases and their corresponding public keys, while automatically saving the private keys to a text file.

Join our Channel for More Information about Airdrop

<div align="center">
  <a href="https://t.me/airdropseeker_official" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Telegram&logo=telegram&label=&color=2CA5E0&logoColor=white&style=for-the-badge" height="25" alt="Telegram Logo" />
  </a>
</div>


## Installation & how to run?

```bash
git clone https://github.com/linuxdil/Create-EVM-Wallet.git
cd Create-EVM-Wallet
```
Install Dependency
```bash
pip install -r requirements.txt
```
Run Bot/Create Wallet
```bash
python3 create.py
```
## Example Usage

When you run the script, it will prompt you to enter the number of mnemonic phrases to generate:
```bash
Enter the number of Ethereum mnemonic phrases to generate: 5
```
The script will generate the specified number of mnemonic phrases, along with their corresponding private keys and public keys, saving them to a file named evm_keys.txt. The output in the text file will look like this:
```bash
 Mnemonic Phrase: rifle hour code output diet distance service flight broken course coach forget
 Private Key: 4fb7537e13a9cd1060a0c919d5d88bebf8de385d3e9f5f701454c2add01580c2
 Public Key/address: 0xc5c3fabDaB4F17DEdDEC757dBE9B7c0594de15A8
 --------------------------------------------------------------
 Mnemonic Phrase: narrow squeeze avocado arena cheese alarm diary slush file inmate next industry
 Private Key: 7cc0bfb0304a794fcab5530a515aa4a5c7d97614bcc4e2af645cc18ea7ad0b6d
 Public Key/address: 0x8406F4e5a7A90D41FCd99761117Ecbf078ae08aE
 --------------------------------------------------------------
...
```
# Important Notes:

• File Handling: The script saves the mnemonic phrases, private keys, and public keys to evm_keys.txt. You can change the filename in the script if desired.

• Security: Ensure proper handling of private keys and mnemonic phrases. Never expose or share them in public or unsecured environments.

• Key Management: Consider implementing secure storage mechanisms and key management solutions for real applications.

This script efficiently generates Ethereum mnemonic phrases, private keys, and public keys while automatically saving the private keys to a text file. Enjoy generating your keys!
