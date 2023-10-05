## About the Contract
This is the basic Solidity smart contract below!

## CONTRACT REPORT 
This Solidity smart contract contains various features to manage a custom token. It includes two public variables: 
1. Strings as the token's name. (nature)
2. Strings as the token's abbreviation. (water)
The contract also contain a variable uint that keeps track of the total token supply which I assigned as a zero. 
To manage user balances, there is a mapping variable named "balances" that connects addresses with their corresponding token balances.

The other most important part of this contract is to mint and burn token!!
The contract contains two primary operations, known as "mint" and "burn." 
* The "mint" function enables to increase the token balance of a set address by the set amount. 
* In Reversed , the "burn" function allows to decrease the token balance of a set address by the set number of tokens.

## COMPILER USED
 remixIDE 

## INITIATING PROGRAM 
* WE have to Create a new folder in remixIDE (Here i give a name as Solidity.sol).
* After writing a code we have to compile it with the help of side menu where we have to select "Compile and Run" option.
* Once the code has been compiled, we need to deploy the contract in order to obtain the account address.
* Copy the account address and deploy it.
* The contract has been deployed.
* To create new tokens, select the "Mint" button and input the account address where the tokens should be added. Then, enter the desired token quantity (e.g., 2000) and click "Transact" to complete the transaction.
* To check the balances, click on the "Balances" tab, paste the account address, and then select "Call" to obtain the current balance.
* To Burn the tokens, select the "Burn" button and input the account address where the tokens should be subtracted. Then, enter the desired token quantity (e.g., 500) and click "Transact" to complete the transaction.It subtract the tokens to the account.
* Again , To check the balances, click on the "Balances" tab, paste the account address, and then select "Call" to obtain the current balance.
* By doing above steps you can also get an output

## HELP OFF !!

"The project beneficial from the invaluable guidance provided, and in the presence of a highly supportive community was a Notable asset."

## AUTHORIZER
PARUL RAUT

## LICENSE
This project is licensed under the [MIT] License - see the LICENSE.md file for details
