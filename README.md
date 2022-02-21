# Predicting-Flight-Ticket-Pricing-Using-Machine-Learning

## Table of contents
* [Introduction](#Introduction)
* [Dataset Description](#Dataset-Description)
* [Features](#Features)
* [Deployment ](#Deployment)
  * [Demo](#Demo)  
## Introduction 
Nowadays, it is difficult to predict the optimal time to buy the ticket with a minmum price since prices change dynamically due to different conditions. As a result of that, we use machine learning to fix the problem to help customers predict the optmal time to buy a ticket with minmum price.

## Dataset Description
 * The dataset is about the prices of the flights for various airlines based on some features and conditions
 * the dat is collected from [https://www.kayak.ae/](#KAYAK) which is an american travel agency for booking 

<img src = "https://i.imgur.com/cHOkO7a.png" >

## Features 
* __Out_Date, Out_Day, Out_Weekday, Out_Month, out_Year:__ The date when the journey starts from the source.
* __Out_Time:__ The time when the journey starts from the source
* __Out_Cities:__ The city at which the journey starts from the source
* __Out_Airline:__ The name of the airline when the journey travels only to the destination
* __Return_Date, Return_Day, Return_Weekday, Return_Month, Return_Year:__ The date when someone travels back to its source
* __Return_Time:__ The time when the journey travels back the source
* __Return_Cities:__ The city at which the journey travels back to the source
* __Return_Airline:__ The name of the airline when the journey travels back to the sources
* __Out_Travel_Time:__ Total duration of the flight to travel only to the destination
* __Return_Travel_Time:__ Total duration of the flight to travel back to the source
* __Out_Journey_Type:__ The type of the journey during travelling to the destination. It could be direct or connecting
* __Return_Journey_Type:__ The type of the journey during travelling back to the source. It could be direct connecting
* __Out_Stop_Cities:__ The intermediate stop cities of the journey during travelling to the destination
* __Return_Stop_Cities:__ The intermediate stop cities of the journey during travelling to the source
* __Price:__ The price of the ticket
* __timestamp:__ The date and time for webscarpping the information from the website
* __sort:__ sorting based on the quality of the flight journey


## Deployment 
We put the model into production by creating web application to predict the optimal time to book the flight price with minimum price.
### Demo 



