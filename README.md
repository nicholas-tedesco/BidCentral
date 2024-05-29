# BidCentral 

[![My Skills](https://skillicons.dev/icons?i=py,flask,postgres,js,html,css,docker&theme=light)](#)

BidCentral is a full-stack application that simulates an online auction platform. Primary user functionalities include listing items for sale, bidding on existing items, and viewing finished auctions. The app uses Python Flask as a web framework and a PostgreSQL database for persistent storage.

This project was created as part of coursework at Georgia Tech. To avoid potential honor code violations, the source code is not included in this repo. 

## Demo

### Main Menu

Following registration and successful login, the user is presented with a customized main menu depending on user details and administrative status.

<kbd><img src="/images/admin-menu.png"></kbd>

### Search for Items 

Users may search for items using a series of criteria. Search results contain brief snapshots of item bid information, as well as links to each item's auction page. 

<kbd><img src="/images/search.png"></kbd>

### View Item for Sale

An active auction page consists of detailed item information, bid history, and the option for users to bid on the current item. Users may also view ratings for previously completed auctions involving the same item type. Administrators have the additional ability to cancel the auction.

<kbd><img src="/images/active-auction-details.png"></kbd>

### List Item

Users fill out a form to list items for sale. Some fields are required, while others are optional. 

<kbd><img src="/images/list-item.png"></kbd>

### View Finished Auctions 

Users may also view items which have already completed. Items may finish in one of three ways: 
- successful: item was purchased
- unsuccessful: bid criteria was not met at auction conclusion
- cancelled: administrator cancelled the auction

<kbd><img src="/images/finished-auction-results.png"></kbd>

### View Details for Finished Auction 

After clicking an item on the finished auction results page, the user may view the item's detailed information and bid history. 

<kbd><img src="/images/finished-auction-details.png"></kbd>

