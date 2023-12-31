# Curly Spoon

## [Frontend](https://github.com/RomanKosmyna/curly-spoon-frontend)
## [Backend](https://github.com/RomanKosmyna/curly-spoon-backend)

# Images

## Mobile Screenshots

| Mobile Authorization                   | Mobile Main Page                        | Mobile Navigation                  |
|----------------------------------------|-----------------------------------------|------------------------------------|
| ![Mobile Auth window](https://github.com/RomanKosmyna/curly-spoon-images/blob/main/mobile-auth.jpg) | ![Mobile Main window](https://github.com/RomanKosmyna/curly-spoon-images/blob/main/mobile-main.png) | ![Mobile Navigation window](https://github.com/RomanKosmyna/curly-spoon-images/blob/main/mobile-nav.png) |

| Mobile Settings                        | Mobile General                          | Mobile Venue                       | Mobile Add Venue                   |
|----------------------------------------|-----------------------------------------|------------------------------------|------------------------------------|
| ![Mobile Settings window](https://github.com/RomanKosmyna/curly-spoon-images/blob/main/mobile-settings.png) | ![Mobile General window](https://github.com/RomanKosmyna/curly-spoon-images/blob/main/mobile-general.png) | ![Mobile Auth window](https://github.com/RomanKosmyna/curly-spoon-images/blob/main/mobile-venue.png) | ![Mobile Auth window](https://github.com/RomanKosmyna/curly-spoon-images/blob/main/mobile-add-venue.png) |

## Desktop Screenshots

| Desktop Auth                           | Desktop Main                            | Desktop Settings General           |
|----------------------------------------|-----------------------------------------|------------------------------------|
| ![Desktop Auth window](https://github.com/RomanKosmyna/curly-spoon-images/blob/main/desk-auth.png) | ![Desktop Main window](https://github.com/RomanKosmyna/curly-spoon-images/blob/main/desk-main.png) | ![Desktop Settings General window](https://github.com/RomanKosmyna/curly-spoon-images/blob/main/desk-settings-general.png) |

| Desktop Venues                        | Desktop Add Venue                        |
|---------------------------------------|------------------------------------------|
| ![Desktop Venues window](https://github.com/RomanKosmyna/curly-spoon-images/blob/main/desk-venues.png) | ![Desktop Add Venue window](https://github.com/RomanKosmyna/curly-spoon-images/blob/main/desk-add-venue.png) |

## Final Okten School project.

Main Technologies:
HTML5, CSS, JavaScript, TypeScript, Node.js, React, Next.js, Redux, Redux Toolkit, Nest.js, Prisma, PostgreSQL, GraphQL

API:
- GraphQL

Front-End Technologies:
- HTML5, CSS
- JavaScript, TypeScript
- React, Next.js
- Redux, Redux Toolkit, Axios

Back-End Techologies:
- Nest.js
- Prisma ORM
- Multer, Bcrypt, Swagger

Database:
- PostgreSQL

Tools:
- Postman, Eslint, Prettier

Description:
Website about different kinds of venues. 

Users are able to create, edit and delete venues. Before being published, those venues are sent to Administrator's (from now on, Admin) personal account for review.
If they pass a review, then they are getting published on a Home page.

Since project is using Next.js 13 for its client side, it exploits built in fetch for data integration from Backend , which provides an up-to-date information about all reviewed venues.

## Main Features:

 1) _From user perspective:_

    • Authentication, Authorization process
    <br/>
    • Ability to add, edit and delete venues
    <br/>
    • Ability to rate veunes
    <br/>
    • Viewing the list of establishments
    <br/>
    • Sorting (by rating, average check, publication date, in alphabetical order, proximity to the user)
    <br/>
    • Searching by name
    <br/>
    • Filtering by criteria (rating, type, range of average check, tag (specified by the establishment), features (Wi-Fi, parking, live music)
    <br/>
    • Adding an venue to favorites
    <br/>
    • Sending a message to the venue manager (basically a user that added a venue)
    <br/>
    • Logging into a personal account (with corresponding privileges)
  
  
2) _Navigation through general sections:_

    • Home (All venues)
    <br/>
    • Filtering/Search
    <br/>
    • Top (with editing capabilities) + Ability to add top categories like "Best venue for weddings, corporate events, birthdays"
    <br/>
    • News (add promotions)
 
 
3) _Personal Account (Regular User):_

    • Profile Editing
    <br/>
    • Adding Venue (after moderation by the venue administrator, the venue is included in the general list)
    <br/>
    • Editing Venue
    <br/>
    • Deleting Venue
    <br/>
    • Adding Venue News
    <br/>
    • Deleting Venue News
    <br/>
    • Favorites Tab (viewing favorites, removing from favorites)
    <br/>
    • My Comments Tab (list of venues with my comments)
    <br/>
    • My Ratings Tab (list of venues with my ratings)
    <br/>
    • View statistics of views within specified date ranges for personal venue
    <br/>
    • Messages from the venue's page (complaint or question via email)
    
4) _Personal Account (Administator) (Already has all regular user account functions):_

    • List of venues awaiting moderation
    <br/>
    • All venues
    <br/>
    • Editing all venues
    <br/>
    • Deleting any venue
    <br/>
    • Editing news in a venue 
    <br/>
    • All users
    <br/>
    • Editing a user
    <br/>
    • Deleting a user
    <br/>
    • Linking a venue to another user
    <br/>
    • Editing comments and changing venues ratings
    <br/>
    • Access to analytics on venue views
    <br/>
    • Analytics on venue views over time
    <br/>
    • Editing general textual information in the application (About the establishment, contacts...)
    <br/>
    • Editing general news
