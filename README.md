== README

# Week 1 Assignment - *Ruby Restaurant*

**Ruby Restaurant** is a Ruby on Rails application.

Submitted by: **An Ta**

Time spent: **10** hours spent in total

URL: **http://sheltered-fortress-7134.herokuapp.com/foods**

## User Stories

The following **required** functionality is complete:

* The User must be able to go two pages: Menu, and Contact Us.
* The User can see the address and phone number on the contact us page.
* The User can see a basic google map on the Contact Us page.
* The User can navigate to a menu page with four sections: Breakfast, Lunch, Dinner, Drinks
* The user should see at least 5 food items in each section.
* Each food item should have the following fields: Name, Description, Price, Section, Image URL
* The User should be able to filter by section of Breakfast, Lunch, Dinner, or Drinks and see only the relevant items.
* The User can sort menu items by “alphabetical”, “price low to high”, and “price high to low”.
* The User should be able to get for a menu item and see results.
* Clicking on an item in the menu brings up its detail, where you see the description and a larger picture.
* The User can click “order” on a menu item to go to a “Create Order” page.
* The User is able to fill in their name, phone number, and address.
* The User is taken to a “Thank you for your order page” that lists the name of item, the total cost (delivery should cost 20,000 VND), the user’s name, the user’s address, and the time the order was created in human-readable format (for example, Tuesday, December 1, 15:25).

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

https://drive.google.com/open?id=0BwwwHC2oIXDMM2V1Wl9ibmpMZ3M

## Notes

I finished the app and realized that I forgot to add "-d postgresql" when I generated the app, so the app used sqllite and could not be deployed to Heroku. I need to manually change the Gemfile and database.yaml file to make it work, so it's done later than expected.

## License

    Copyright [2015] [An Ta]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
