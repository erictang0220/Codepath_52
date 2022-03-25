# DocsRadar

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
An app that will look for the doctors or clinics nearby to help people look for the appropriate doctors and make doctor appointments with ease. User can rate their doctors and the ratings are accessible to all the users.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category**
    - Medical
- **Mobile: How uniquely mobile is the product experience?**
    - What makes your app more than a glorified website?
    - Try for 2 or more of these: maps, camera, location, audio, sensors, push, real-time, etc
    - Answer: With user's location, we can recommend them to the nearby doctors 
- **Story: How compelling is the story around this app once completed?**
    - How clear is the value of this app to your audience?
    - How well would your friends or peers respond to this product idea?
    - Answer: 
- **Market: How large or unique is the market for this app?**
    - What's the size and scale of your potential user base?
    - Does this app provide huge value to a niche group of people?
    - Do you have a well-defined audience of people for this app?
    - Answer: This app doesn't have a targeted group
- **Habit: How habit-forming or addictive is this app?**
    - How frequently would an average user open and use this app?
    - Does an average user just consume your app or do they create?
    - Answer: This app is not addictive as people only use it in need of medical service.
- **Scope: How well-formed is the scope for this app?**
    - How technically challenging will it be to complete this app by the end of the program?
    - Is a stripped-down version of this app still interesting to build?
    - How clearly defined is the product you want to build?
    - Answer: It will be fairly challenging to gather doctors' information

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* [ ] Users can log in and out off the app
* [ ] App will remember login even after the app closes
* [ ] Users can select the type of doctor they're looking for (dermatologist, general physician, pediatrician, etc.)
* [ ] App will display contact information of local doctors of the appropriate type (in the local area)

**Optional Nice-to-have Stories**

* [ ] Infinite scroll -- the lower you scroll, the farther away the doctors get.
* [ ] Users can rate the doctor after they've visited
* [ ] App will display the rating of the doctor
* [ ] Users can leave comments for each doctor
* [ ] App will display expanded information of each doctor when the appropriate cell is tapped

### 2. Screen Archetypes

* Login
   * Prompt user to enter username and password
   * Link to register if new user
   * Verify username and password
   * Show appropriate error message if needed (e.g. wrong password, username doesn't exist)
* Register
   * Prompt user to enter username and password
   * Confirm password
   * Verify username and password before creating new user
   * Show appropriate error message if needed (e.g. passwords don't match, username already exists)
* Stream
    * User can view a list of doctors near them
* Rate
    * Prompt user to add their rating out of 5 stars, price range for the doctor, maybe a comment - present modally.
* User Profile
    * Prompt user to enter age, sex, illness

### 3. Navigation

**Tab Navigation** (Tab to Screen)
* Home
* User Profile

**Flow Navigation** (Screen to Screen)

* Login
    * &rarr; User Profile
* Register
    * &rarr; User Profile
* Stream
    * &rarr; Rate if tap on doctor's table view cell
* Rate
    * &rarr; Stream
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
