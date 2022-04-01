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
[Description of your app]

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:**
- **Mobile:**
- **Story:**
- **Market:**
- **Habit:**
- **Scope:**

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
