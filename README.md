# PhoenixMiner5.5NoDevFee
PhoenixMiner 5.5c NoDevfee. Redirect DevFee on your wallet

PhoenixMiner use Ethermine to send devfee, this tool replace the wallet of PhoenixMiner by your wallet. 
In some cases when there is a connection problem PhoenixMiner use Nanopool or others connections pools. (You can see that in the logs)

How it works : 

- Download first PhoenixMinerNoDevFee.zip and unzip it.
- Edit this file LauncherPhoenixMinerNoDevFee.bat and replace the default wallet by your wallet.
- Launch in a first time LauncherPhoenixMinerNoDevFee.bat.
- Now PhoenixMinerNoDevFee wait PhoenixMiner. 
- Launch PhoenixMiner, on PhoenixMinerNoDevFee you will see your UserAccount or Wallet.
- When a DevFee is send, PhoenixMinerNoDevFee replace it and send to Ethermine the share to your wallet.

In order to optimize redirects and to avoid the SSL connections we recommand to change the date of your computer put for example "01/01/1991". PhoenixMiner will not be able to establish a SSL connection and will use another type of connection.

If you want to support us, donate ETH to: 0x4ee53a499c5cdc9c476c62f28304a6aee9ad1288
