Logic for ATM Simulator:

1.	A separate class is defined for User to enter their name and PIN.
2.	Name and PIN are taken as attributes for User Class
3.	An object called user then calls ‘User’ class and enters the name and PIN.
4.	ATM Simulator function is defined and also a variable called Balance is created whose default value is 10,000
5.	User is prompted to enter their name and PIN
6.	 The logic is ATM Simulator function will work only if the input provided in it matches the name and PIN provided in the User Class.
7.	The above statement is checked by ‘If’ and ‘Else’ condition.
8.	If the name and PIN does not match user will get a statement as ‘You have entered Incorrect Details’.
9.	If name and PIN matches then user is prompted to select one the following options from 1. Balance 2. Withdraw 3. Deposit  4. Exit 
10.	The choices made by the user is checked by If and Elif statement

Condition On User Choice:
	If User selects 1, then the balance is directly printed
	If User selects 2 then a further condition is checked using nested If condition. 
	If the User selects Withdraw then function will check if the amount to be withdrawn is more than the balance amount.
	If the withdraw amount is more than the balance, user will get a statement as ‘Insufficient Fund’ and user has to again select the options else the program will continue.
	If User selects 3 which is Deposit, user will be asked to enter the amount to be deposited and then the deposit amount will be added with the balance.
	If user selects 4 the loop will return and user will receive a ‘Thank You’ statement.
