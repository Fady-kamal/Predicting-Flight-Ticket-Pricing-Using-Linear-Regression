# Predicting-Flight-Ticket-Pricing-Using-Machine-Learning

## Table of contents
* [Introduction](#Introduction)
* [Dataset Description](#Dataset-Description)
* [Setup](#setup)
## Introduction 
Nowadays, it is difficult to predict the optimal time to buy the ticket with a minmum price since prices change dynamically due to different conditions. As a result of that, we use machine learning to fix the problem to help customers predict the optmal time to buy a ticket with minmum price

## Dataset Description
 * The dataset is about the prices of the flights for various airlines based on some features and conditions
 * the dat is collected from [https://www.kayak.ae/](KAYAK) which is an american travel agency for booking 

<img src = "https://i.imgur.com/cHOkO7a.png" >

## Features 
* Out_Date, Out_Day, Out_Weekday, Out_Month, out_Year: The date when the journey starts from the source.
* Out_Time: The time when the journey starts from the source
* Out_Cities: The city at which the journey starts from the source
* Out_Airline: The name of the airline when the journey travels only to the destination
* Return_Date, Return_Day, Return_Weekday, Return_Month, Return_Year: The date when someone travels back to its source
* Return_Time: The time when the journey travels back the source
* Return_Cities: The city at which the journey travels back to the source
* Return_Airline: The name of the airline when the journey travels back to the sources
* Out_Travel_Time: Total duration of the flight to travel only to the destination
* Return_Travel_Time: Total duration of the flight to travel back to the source
* Out_Journey_Type The type of the journey during travelling to the destination. It could be direct or connecting
* Return_Journey_Type: The type of the journey during travelling back to the source. It could be direct connecting
* Out_Stop_Cities: The number of intermediate stop cities of the journey during travelling to the destination
* Return_Stop_Cities: The number of intermediate stop cities of the journey during travelling to the source
* Price: The price of the ticket
* timestamp: The date and time for webscarpping the information from the website
* sort: sorting based on the quality of the flight journey
