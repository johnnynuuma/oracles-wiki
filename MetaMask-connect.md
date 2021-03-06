## Connect to Oracles network via MetaMask

### Install MetaMask plugin for Google Chrome
Install the MetaMask plugin from [Google Chrome Store](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)

_Note that this plugin is currently available only for Google Chrome v59.0.3071.115 or later._

### Connect to the Oralces Network
1. Click on the Network name next to the head of the fox in the upper left corner and select "Custom RPC" from the dropdown list

![Step1](./docs/metaMaskConnect/DefaultMM_Step1.png)

2. Enter the RPC connection url `http://testnet.oracles.org:8545` (however, if master of the ceremony explicitly provided you with another connection url you should use it).

Note: _url on the screenshot below is just an example_

![Step2](./docs/metaMaskConnect/DefaultMM_Step2.png)

3. Wait a little bit, the network name in the left upper corner should change to "Private Network" 
### Importing of keys
1. Click on the account icon in the right upper corner, and then on "Import account"

![Step3](./docs/metaMaskConnect/DefaultMM_Step3.png)

2. In "Select Type" dropdown choose "JSON file" option. Then click on "Select file" and browse your filesystem to locate the keyfile. Enter password for the keyfile and click "Import".

Note: _name of the file on the screenshot below is just an example, it will be different in your case_

![Step3](./docs/metaMaskConnect/DefaultMM_Step4.png)

3. Click on the account icon in the right upper corner again and select the newly created account (usually the newest one is the lowest one in that list, however you should check the address `0x...` field below account name).
