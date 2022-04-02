Original App Design Project - README Template
===

# SplitBread

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
SplitBread is the easiest way to share expenses with friends and family and stop stressing about “who owes who.” User can use SplitBread to organize group bills for households, trips, and more. Our mission is to reduce the stress and awkwardness that money places on our most important relationships.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Finance
- **Mobile:** This app would be primarily developed for mobile and it would also be developed on computer lately. Functionality wouldn’t be limited to mobile devices, however mobile version could potentially have more features. 
- **Story:** Allows user to make a group where users can share their spending within a group. User can make private friendships for any splitting situation.Keep track of who should pay next, or settle up by recording cash payments or using our integrations.
- **Market:** Any individual could choose to use this app.There is no age restrictions for this app. Simply anyone could use this app for their convenience when needed.
- **Habit:** Dependending on users preferences and  social life this app could be used as often or unoften.  
- **Scope:** First of all, we would let the user to sign up and create account. User would be given options to add friends by sending email invitations or text messages. User would name a group and choose a group image

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can create an account
* User can log in
* User can add people
* Users can create a group, and invite others to join 
* User can request payment from people
* User can clarify on requested payment(Reason, description, date, etc.)
* User can verify paying requested payment
* User can verify recieved payments

**Optional Nice-to-have Stories**

* User can upload bill
* User can be notified of finalized payments
* User can see how much money they paid and received

### 2. Screen Archetypes

* Registration Screen
    * User can create a new account
* Login Screen
    * User can log in
* Home Screen
    * User can view groups and individuals 
    * User can pin regular groups and individuals(Optional)
* Detail Screen
    * User can view shared expenses (Reason, description, date, etc.)
    * User can see pending payments 
    * User can verify payment
* Notifications Screen
    * User can view when added to a group
    * User can view requested money
    * User can view when someone verifies payment
* Creation screen
    * User can create new groups
    * User can add expenses and add details
* Profile Screen
    * User can view and edit profile
    * User can view successful transactions
    * User can view total money sent and received(Optional)

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home
* Detail
* Notifications
* Creation 
* Profile


**Flow Navigation** (Screen to Screen)

* Registration Screen => Home
* Login Screen => Home
* Home Screen => Detail
* Detail Screen => None
* Creation Screen => Home (the new created shared expense will appear on the home screen)
* Profile Screen => None
* Notifications Screen => None

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
