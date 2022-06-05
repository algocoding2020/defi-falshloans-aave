# defi-falshloans-aave

#Flash loans:

Flash loans allow you to borrow very large sums of token on Ethereum without
providing any collateral, if you repay the loan in the same transaction.

three most common use cases for flash loans arbitrage flash loans can magnify the profit  
of executing a successful arbitrage opportunity.
let's imagine that there is a price discrepancy in the die usdc pulls between uni swap and curve  you can trade one dive for one usdc on curve but you only need 0.99 die to buy one usdc on uni swap.
now you can try to execute the arbitrage
step 1: borrow 100,000 die from ava via flash loan
step 2: swap  100,000 die for usdc on uni swap and receive one hundred one thousand ten(101,010) usdc
step 3: swap one hundred one thousand ten(101,010) usdc for  one hundred one thousand and ten die on curve  
step 4: repay initial one hundred thousand die plus zero  point zero nine percent fee equals one hundred nine hundred (100,900)
step 5: profit one hundred ten die (110)

![image](https://user-images.githubusercontent.com/69389020/172038873-0d120863-4a41-4672-a280-bd1c89eb10f1.png)

the next use case for flash loans is a collateral swap 
let's say you have borrowed dye from compound with Eth as collateral
you can swap your collateral from Eth too for example Bat in the following way 
step 1: take a flash loan in dye to cover the amount of dye that was borrowed 
step 2: repay your compound loan with borrowed dye  
step 3: withdraw your Eth from compound
step 4: swap your Eth for Bat on Uniswap
step 5: supply Bat as collateral on compound borrow die against your Bat collateral  
step 6: repay flash loan with borrowed die plus fees
So you just swapped your collateral from Eth to bat and paid 0.09 percent of the borrowed 
amount for this 
![image](https://user-images.githubusercontent.com/69389020/172038879-7d007c36-2b16-4376-915f-d183154494db.png)

#Self-liquidation:
imagine the following scenario 
you have a loan in die on compound with Eth as collateral
The Eth price keeps going down and you are approaching the liquidation level.
you also do not want to deposit more Eth to increase your liquidation level and you also  
don't have the Die required to repay the loan.
now instead of allowing the maker DAO contract to liquidate your collateral and charge you the liquidation fee you can take the following steps
Step 1: take a flash loan for the amount of diet that you owe from Aave
Step 2: repay your Die loan and withdraw your Eth from compound
step 3: swap enough Eth to die in order to repay the flash loan plus fees that has taken from Aave, keep the rest of your Eth

![image](https://user-images.githubusercontent.com/69389020/172038888-b42e8bb7-470f-4952-b4af-c6bc949e8bbe.png)

Famous Hack is BZXHack
bzx hack where a flash loan was used to manipulate  the uni swap oracle price.


it is also possible to use them without doing  any coding projects such as collateral swap  
defi saver, furucombo make it possible 

Furucombo is a tool that allows you to construct an Ethereum transaction using a simple drag-and-drop user interface

