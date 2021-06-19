# dRegulation
> Private standards for DeFi contract construction and governance

`emergencyWithdraw`: public function which returns deposits without rewards to avoid locked funds.

Examples, SushiSwap `MasterChefV2`:

![image](https://user-images.githubusercontent.com/41117279/122651023-240f7800-d104-11eb-8955-d31927a48e23.png)

`admin key`: a role set on a contract which usually involves 'owned' functions and special access controls. 

Examples, BanklessDAO Multi-Sig (Gnosis SAFE) - 4/7 signatures that controls vesting and minting of token supply. 
