# InspoQuotes

InspoQuotes is a basic app that lists off inspirational quotes and allows users to buy more quotes.

## Introduction

InspoQuotes is from a tutorial by Angelu Yu with the focus on working with in-app purchases, restoring purchases, and StoreKit.

## Skills used

* In-app purchases
* StoreKit

## Process and challenges

After setting up the initial tableview with the free set of quotes, all that was required to allow the purchase of more quotes was to set up a payment queue with SKPaymentQueue. All that was needed was to write an if statement of if the transaction failed or was successful. If it was successful, run the function that ran the extra quotes they payed for. If it failed, it simply ended the transaction with an error message. To add the quotes they payed for, all that was needed was to append the quotes to an array with the initial ones and reload the tableview.

To restore the users quotes if they had already paid for them required only one line of code using restoreCompletedPurchases, making writing in-app purchases fairly straightforward for this example.

The process also introduced me to sandbox testing and creating a sandbox user to use for purchasing in-app purchases and making sure they work correctly with payment and restoring purchases as well.

<img src="https://user-images.githubusercontent.com/113778995/217657417-4d7a43bb-f847-40e6-bfcb-6dfedca3b3b1.PNG" width="200">  <img src="https://user-images.githubusercontent.com/113778995/217657321-d664ffe6-5e97-42d7-b43c-e94937fa456d.PNG" width="200">  <img src="https://user-images.githubusercontent.com/113778995/217657237-aeb00eda-9a0e-4712-8197-6537d050747e.PNG" width="200">  <img src="https://user-images.githubusercontent.com/113778995/217657113-da597457-f1cd-4e83-ba55-af30dbcb6dec.PNG" width="200">


