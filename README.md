# App description

This is a bank simulator app with 3 users accounts: Kevin Johnson from GB, Scarlett Stewart from USA and Shinji Mirukami from Japan. They can transfer the money between each other, request loan from bank, close account. Each user's money is in his national currency.

# Logging in

User can log in by entering his account data into 2 text boxes following this rules:
user = user initials (kj for Kevin, ss for Scarlett, sm for Shinji)
PIN = 1111 for Kevin, 2222 for Scarlett, 3333 for Shinji
User can relog to another account when he is logged in.

# Logging out

User can log out manually by clicking "log out" button. It can also happen automatically after 3 minutes of inactivity.

# Transferring money

To transfer the money to another account user needs to pass initials of user to whom he wants to transfer the money and the amount of money that he want to pass.

# Loan from bank

User can request a loan from bank by entering an amount of money that he want to get. The loan will be accepted if he has at least one movement worth at least 10% of the loan amount. Loan is delayed by 3 seconds by using a timer.

# Closing account

User can close his account by entering his account data. After this he will be logged out and won't be able to log in again
until he reloads the page.
