# Getting-Started-With-Solidity
# Final Assessment.
MetaCrafters course Second Module code Using the Solidity is provided in the Code Section.
/*
       REQUIREMENTS
    1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
    2. Your contract will have a mapping of addresses to balances (address => uint)
    3. You will have a mint function that takes two parameters: an address and a value. 
       The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
    4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
    5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.
*/

We Used the Basic Concepts of the solidity to write the code for the Tokens.
1) variables Declared State variables.
2) Mapping to the Adresses is provided by using mapping keyword which simply maps the address to the Amount or Value of the Tokens.
3) Function mint is created which recieves two arguments i.e.  Address and Amout of token or value. This function simply increments the value of total supply and also this same value is mapped by the address(Which is provided).
4) lastly the Burn function is created which is used to reduce the Token but before reducing the token it will check that there is enough token available to decrement or not.if Token are are available then it will reduce the tokens else it will do nothing the state of the variable of the value in the variables Remains Same.


For More information mail me on: abhay71052@gmail.com



