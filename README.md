# SpaceRenter

### App Description
A mobile app that allows **sellers** to rent out equipment they own to **buyers** in the area in order to achieve a lower price.

### App Idea Evaluation
// TODO: Evaluate app across the following categories using the App Evaluation Protocol.

- Mobile: Ease of use, location, audio/chat, camera

- Story: Allows people to rent different spaces for different activities

- Market: Any person that has equipment avaliable for rental, and any person that would like to rent equiptment or a space

- Habit: Depends on who the user is; a music producer for example, would use it a lot if they need time to make music with equipment they don't own

- Scope 
    - **V1**: Allows the user to see potential space offerings and see open time slots. Security and ID for those who are renting their things out. Seller can post listings with what equipment they have available, with basic instructions on how to use it.
    - **V2**: They should also be able to pay through the app so that we make a percentage of the payment in order to fund more progress.
    - **V3**: Waitlist/Booking schedule for renters to schedule times.

---

### User Stories
**Required Must-have Stories**

 * Log In
 * Profile, for buyer and seller
 * A stream of availible spaces to be rented
 * Buyer Interface
     * A way for the buyer to request a block of time
 * Seller Interface
     * Shows spaces the seller is currently offering


 

**Optional Nice-to-have Stories**

 * Rate the space
 * Rate the people, buyer and seller
 * A way to leave a tip
 * A watch list for the buyer
 * Users can add pictures 
 * A calendar showing availible dates
 * A way for users to see eachothers profiles
 * A wait list
     * Have the ability to check the status on the wait list

    

## 2. Screen Archetypes

 * Login
   * This is where the user signs in or registers for a new account. This can usually take the form of username / password although commonly includes third-party authentication such as facebook or twitter connect for easy access.
   * Login screens usually require the following components:

Accepting varying types of form input from user for basic login / signup
See: text fields, input fields
Validation of form inputs for invalid data (i.e bad emails, duplicate emails)
Sending requests to server to authenticate or create new user accounts
See: sending requests
Integrating third-party connection SDKs (i.e Facebook SDK)
See: parse sdk
Loading states during authentication or creation
See: progress bars
   
 * Detail
     This archetype is focused on displaying all relevant information about a single discrete item within the application. This usually is a view that is reached when a user is consuming content in a stream that they would like to view in more detail or interact with. Typically this view contains additional data not displayed on the stream as well as actions a user can perform such as editing their items, liking or commenting on other user's content.

Detail views usually require the following components:

Sending network request to retrieve additional details or media for the data item
See: sending requests
Action buttons that allow user to interact with the item
See: events
Option for user to share the content out to other apps
See: sharing
Scrollable text or media content to read about the item
See: scrollview 
 * Stream
   This archetype is focused on the primary content or data that a user consumes within the application. This is typically time-based displaying activities from other users that might be of interest. This is usually a list of discrete items which contain different data properties. The primary data is usually text or media content while secondary data includes the timestamp and the author.

Streams usually require the following components:

Sending network requests to retrieve lists of content data to display
See: sending requests
Creating a list of items based on that source data including displaying text and media
See: listview
Endless scrolling which paginates as user consumes content
See: endless scrolling
Handling cases where the user wants to view more information on a piece of content
See: events
Allowing the user to take primary actions on this content such as deleting or editing
Optimizing the display of items such that scrolling the stream is smooth
See: viewholder

 * Creation
     This archetype is focused on allowing the user to create a new item by filling in all the properties for the item using a creation flow. This typically involves presenting the user with a series of input fields and allowing them to attach media such as a photo from the camera or metadata such as their location. Usually this is broken up into discrete steps and/or a great deal of fields are optional.

Creation screens usually require the following tasks:

Input fields of various types to collect information
See: input fields
Ability to validate fields for correctness before creation
Sending network request to create new valid content item
See: sending requests
Option to capture a photo or select from photo gallery
See: camera and media
Option to capture current location of device
See: location
Option to share or include friends related to the item
See: parse sdk
    
 * Profile
   * This archetype is focused on allowing the user to view information about their own account, view their own content, and provide them account related action items. Typically, the profile contains important statistics about the user (i.e number of followers), displays recent content, and provides access to actions such as editing their profile, changing their picture, logging out, etc.

Profile screens usually require the following components:

Grid or list of recent content items for user
See: listview
Images associated with the user's identity
See: picasso
List of related users (followers, following)
Action items when on another user's account
See: events
   * ...

## 3. Navigation

**Tab Navigation** (Tab to Screen)

 * Home Feed
 * Search
 * If seller, availibility

**Flow Navigation** (Screen to Screen)

 * Login Screen
   * Create New Account
   * Log into existing
 * Stream
   * Detail
     * Seller Profile
          * Calendar
   * Search
       * Detail
       * Seller Profile
           * Calendar

 * Seller Interface
     * Creation
     * Calendar
 * Buyer Interface
     * Watchlist
 
     

### Wireframes
// TODO: Add Wireframe Images
https://www.figma.com/file/fTQDZNR2ldnABBTU9tLRqSSZ/Untitled?node-id=0%3A1
---

### App Pitch Presentation
// TODO: Add link to Pitch Presentation Deck
