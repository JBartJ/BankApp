# App description

This is a bank simulator app with 3 users accounts: Kevin Johnson from GB, Scarlett Stewart from USA and Shinji Mirukami from Japan. They can transfer the money between each other, request loan from bank, close account. Each user's money is in his national currency.

# App preview
![image](https://user-images.githubusercontent.com/99435285/158790493-982e9969-7ccb-4696-85f0-9d29422a52cc.png)

# Logging in

User can log in by entering his account data into 2 text boxes following this rules:
user = user initials (kj for Kevin, ss for Scarlett, sm for Shinji)
PIN = 1111 for Kevin, 2222 for Scarlett, 3333 for Shinji
User can relog to another account when he is logged in.

![image](https://user-images.githubusercontent.com/99435285/158789978-683bc89f-eae5-4461-9aa1-beb722e9e532.png)

# Logging out

User can log out manually by clicking "log out" button. It can also happen automatically after 3 minutes of inactivity.

# Transferring money

To transfer the money to another account user needs to pass initials of user to whom he wants to transfer the money and the amount of money that he want to pass. Every account uses different currency, so the value is obviously calculated to currency of receiver.

![image](https://user-images.githubusercontent.com/99435285/158790159-a458d25e-62b1-4a2e-9a15-dc922b0bb629.png)

# Loan from bank

User can request a loan from bank by entering an amount of money that he want to get. The loan will be accepted if he has at least one movement worth at least 10% of the loan amount. Loan is delayed by 3 seconds by using a timer.

![image](https://user-images.githubusercontent.com/99435285/158790258-3b6d099f-8408-4cdd-ba13-8e8c79ef63a5.png)

# Closing account

User can close his account by entering his account data. After this he will be logged out and won't be able to log in again
until he reloads the page.

![image](https://user-images.githubusercontent.com/99435285/158790314-2038b2ec-5cef-4012-a3d3-2e02b7b34dbb.png)

# Sorting movements

User can sort account's movements by values by clicking sort button.

![image](https://user-images.githubusercontent.com/99435285/158790685-7797ec93-ee9d-46f9-9b04-e054fffdbc05.png)

