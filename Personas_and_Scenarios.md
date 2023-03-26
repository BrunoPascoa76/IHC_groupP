# Personas

## Persona 1 - Harrison Tucker
Age: 43  
Sex: Male  
Education: 9th grade  
Occupation: Quality Assurance Professional  
Demografic: wife, 2 children
Motivation: Wants to manage the whole family's budget colaboratively  
Experience:
* Doesn't surf the internet.
* Previously tracked budget using an excel sheet, financial knowledge mostly comes from experience.

# Scenarios:

## Scenario 1: Shopping List
Harrison wants to go shopping, so he creates a new shopping lists and adds items to the list. He then checks the shopping list at the app and, when paying, he scans the qr code to get the price. Since Harrison's app is associated with MB Way through his phone number, the transaction is automatically processed.

## Scenario 2: Buying bus ticket
Harrison is going back home from work, so catches the bus and pays the driver with money. While he's waiting, he adds the ticket cost to the app.

## Scenario 3: Adding a family member
Harrison's daughter turned 18 so his father gave her a credit card. Later that day, Harrison added her daughter's account to the app so he could track her spending.

## Scenario 4: Syncing balance
Harrison's daughter bought a ticket for a concert without telling her father. When Harrison returned went on the app to check the app, he noticed that the balance was lower than expected so he went to the transaction breakdown and saw the tickets listed on her daughter's name.

## Scenario 5: Getting a raise
Harrison finally got a raise at work, so he goes to the app and modifies his salary to the new amount, so he could keep track of that extra money.

## Scenario 6: Adding salary
Harrison's wife found a new job, so Harrison adds a new monthly transaction under her wife's name.


# Tasks
1. Adding Transactions  
  1.1. Creating Shopping list  
    1.1.1. Adding items to shopping list  
      1.1.1.1. Checking shopping list  
  1.2. Scanning QR Code  
  1.3. Setting transaction as single/monthly/yearly  
  1.4. Adding value of transaction  

2.Modifying/Removing Transactions  
  2.1 Checking transaction list  
  2.2 Selecting wanted transaction  

3. Creating users  
  3.1. Creating credit cards  
  
4. Checking balance  
  
# Requirements:
## Functional:
The app must sync check for new data periodically whenever it is connected to the internet.
The app must automatically add transactions done by QR code to the list.
The app must allow the users to add/modify/remove transactions. (core)
The app must allow users to check current transactions and whose account it is associated with. (core)
The app must allow users to check current balance. (core)
The app must allow to add transactions manually. (manually is core)
The app must allow users to set the type of transactions (single, monthly, yearly).  (core)
The app must allow administrators to add new accounts.  (core)
The app must allow administrators to add cards under a certain account. (core)  
The app must automatically add monthly/yearly transactions, if any, at the start of the month.  (core)
The app must allow users to add shopping lists.
The app must allow users to add items to the shopping list.  
The app must read QR codes to get the price of the transaction. (QR is not available due to lack of deal with MB WAY)
The app must foward the transaction request to MB WAY, if a phone number is added.  (MB WAY not available in this version, due to lack of deal)

## Non-Functional:
The app should allow users to add transactions manually or check existing transactions without using WiFi.  
The app should be able to check internet connectivity.  
The app shouldn't allow non-administrators to add/remove accounts/cards.  
The app should work on android and IOS.  
The app should have a secure connection with MB WAY.
The app should respond in less than 1s, even when dealing with large volumes of information.
The app should be available in English in order to reach a broader user base.
The app should use simple and easy to use language, in order to make it more intuitive to learn.
  
 

