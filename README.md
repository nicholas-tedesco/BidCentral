# BidCentral 

[![My Skills](https://skillicons.dev/icons?i=py,postgres,js,html,css,docker)](#)

## Overview

BidCentral is a full-stack application that simulates an online auction platform. Primary user functionalities include listing items for sale, bidding on existing items, and viewing finished auctions. The app uses Python Flask as a web framework and a PostgreSQL database for persistent storage.

This project was created as part of coursework at Georgia Tech. To avoid potential honor code violations, the source code is not included in this repo. 

## Demo

### Main Menu

Following registration and successful login, the user is presented with a customized main menu depending on user details and administrative status.

<img src="/images/admin-menu.png">

### Search for Items 

Users may search for items using a series of criteria. Search results contain brief snapshots of item bid information, as well as links to each item's auction page. 

<img src="/images/search.png">

### View Item for Sale

An active auction page consists of detailed item information, bid history, and the option for users to bid on the current item. Users may also view ratings for previously completed auctions involving the same item type. Administrators have the additional ability to cancel the auction.

<img src="/images/admin-active-item.png">

### List Item

Users fill out a form to list items for sale. Some fields are required, while others are optional. 

<img src="/images/list-item.png">

<!-- ### View Finished Auctions 

Users may also view items which have already completed. Items may finish in one of three ways: 
- successful: item was purchased
- unsuccessful: bid criteria was not met at auction conclusion
- cancelled: administrator cancelled the auction

<img src="/images/finished-auctions.png">

### Rate Purchased Item -->




