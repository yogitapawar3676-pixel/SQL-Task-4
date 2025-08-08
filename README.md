# SQL-Task-4

 Hotel Management Database – MySQL

#Overview

This project is a Hotel Management System Database built in MySQL.
It stores and manages data for hotels, rooms, guests, bookings, and payments.
Additionally, it includes reporting queries to help hotel managers make better business decisions.

The database can answer questions like:

How many bookings does each hotel have?

What’s the average room price in each hotel?

How much total revenue has each hotel earned?

Which hotel is the top earner?

What’s the highest room price by room type?

How many unique guests has each hotel served?

How long do guests stay on average?


# Features

1. Data Storage

Hotel – Stores hotel names, addresses, and IDs.

Room – Stores room details (type, price, hotel association).

Guest – Stores guest details (name, contact info).

Booking – Stores booking details, check-in/check-out dates.

Payment – Stores payment amounts and related booking IDs.


2. Reports & Analysis

Total Bookings per Hotel – Count of bookings for each hotel.

Average Room Price per Hotel – Average nightly rate per hotel.

Total Revenue per Hotel – Total payment amount received per hotel.

High-Earning Hotels – Hotels with revenue above ₹50,000.

Highest Room Price by Type – Most expensive room for each type.

Unique Guests per Hotel – Number of different guests who stayed.

Average Stay Duration – Average length of stay in days.

Highest Earning Department – Department with maximum payment revenue.



#Requirements

MySQL Server (8.0 or later)

MySQL Workbench (or any SQL editor)



#How to Run the Project

1. Setup the Database

CREATE DATABASE HotelDB;
USE HotelDB;

2. Create the Tables

You will create Hotel, Room, Guest, Booking, and Payment tables with primary & foreign keys.

3. Insert Sample Data

Add example hotels, rooms, guests, bookings, and payments.

4. Run the Queries

Execute the provided SQL queries to get reports.



#Database Structure

Table Name	Description	Key Columns

Hotel	Stores hotel info	hotel_id, hotel_name
Room	Stores room details	room_id, room_type, price_per_night
Guest	Stores guest info	guest_id, guest_name
Booking	Stores booking data	booking_id, check_in, check_out
Payment	Stores payment data	payment_id, amount


