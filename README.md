Group Project - README Template
===

# APP_NAME_HERE

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Allows users to rent a room at someones house and use it as a study space.

### App Evaluation

- **Category:** Marketplace/ Hospitality
- **Mobile:** This app is primarily developed for a mobile device but has the potential to be used on a computer similar to Airbnb.
- **Story:** Allows users to rent out study rooms that are within their neighborhood.
- **Market:** Anyone is able to post their homes as a study space. In order to rent out a study room, the user must have a .edu email address to verify that they are a student. 
- **Habit:** This app would be used as often as the user requires. Finals/midterm weeks would have more activity as user would most likely need more time to study.
- **Scope:** This app would initially allow user to study, but eventually could be used as a space to hold study sessions, review sessions, or meeting spaces.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can login/sign up
* User can add/edit their payment option
* User can update their location
* Profile pages for users
* Settings (payment options add/delete)
* User can post their home as an avaiable study space
* User can view and select from availble study 

**Optional Nice-to-have Stories**

* A rating for the owner of the house and the person renting the house
* A map view of the available houses within your area


### 2. Screen Archetypes

* Login/Sign up - user logs in or signs up 
    * Upon first download of the app, the user is asked to create an account if they do not have one, or sign into their existing account 
* Room Selection Screen
    * User is able to look at all the rooms that are availbe to reserve for studying 
* Room Details Screen
    * User can see more details about the room that they are trying to reserve such as pictures and amenities
* Payment Screen
    * Allows user to pay for the room that they are trying to reserve
* Profile Screen
    * User can look at their own profile with a history of rooms they've booked 
* Settings Screen
    * Lets people update their payment methods

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Room Selection
* Profile
* Settings

**Flow Navigation** (Screen to Screen)

* Login -> account creation if no account exists
* Room Selection-> Room Details
* Room Selection-> Payment Screen
* Profile
* Settings

## Wireframes
<img src="https://i.imgur.com/B1uc1fI.jpg" width=200>
<img src="https://i.imgur.com/fRxqSlS.jpg" width=200>
<img src="https://i.imgur.com/vYQXQtO.jpg" width=200>
<img src="https://i.imgur.com/EA0VS62.jpg" width=200>
<img src="https://i.imgur.com/hASnvat.jpg" width=200>
<img src="https://i.imgur.com/56Ddwur.jpg" width=200>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
### Models
Room Listings Screen

| Property     | Type     | Description |
| --------     | -------- | -------- |
| Image        | File     | Image that user posts    |
| Rate         | String   | Price of room per hour
| Distance     | String   | Distance away from your current location
| Availability | String   | Available times for the current day


Room Details Screen

| Property | Type | Description |
| -------- | -------- | -------- |
| Image    | File     | Image that user posts     |
| Rate     | String   | Price of room per hour|
| Profile Picture| File | Image of the host|
| Host Bio | String | Brief description about host|
| Amenities | String | List of resources/tools that come with the room |
| Timings | String | List of all the available timings that the host lends out the room |


Booking Confirmation Screen

|  Property | Type | Description |
| -------- | -------- | -------- |
| Booking Confirmation     | String     | Confirms your booking     |
| Study Room Description | String | Shows location of study rooom |
| Address | String | Address of the study room |
| Time | String | The times that the room is reserved for| 
| Image | File | Image of the user |
| Name | String | Description of the user such as name and bio |
| Total Amount | String | Shows the total amount due along with a breakup of the charges |



### Networking


| CRUD | HTTP Verb | Example |
| -------- | -------- | -------- |
| Read     | GET     | Fetching avaiable study rooms for the user to view     |
| Update | PUT | Update the users credit card information |
| Delete | DELETE | Delete the users credit card information |
