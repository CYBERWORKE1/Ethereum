In this assestment we have created a contact name token
MyToken: A Simple Token Contract
we have created public variables 
Token name as Delta
Token aabrev as DLT
Totalsupply = 0
Then we have mapped variable 
Balance Tracking: The contract uses a mapping (balances) to track the balance of each address holding tokens.
Minting: The mint function allows authorized users to create new tokens. It increases the totalSupply and the balance of the recipient address by the specified _value.
Burning: The burn function enables authorized users to destroy tokens. It ensures that the address has sufficient balance (balances[_address] >= _value) before deducting the _value from both the totalSupply and the address's balance.
Motivation behind to create this code as to have deep understaing of soidity how token is created and how values are being passed .
