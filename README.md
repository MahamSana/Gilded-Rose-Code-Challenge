

Welcome to TechieMinions.

We help companies from startups to corporations build their products from scratch on cutting-edge technologies. Our team is working on products that are backed by ISO, IETF, Adobe, Deloitte, DoorDash, and OpenDoor cofounders.

The code challenge is to improve a buggy and unstructured code.
Your goal is to do following:
- Understand the problem/requirements of code challenge.
- Setup a private git repository for this project and email us a zip file of that repo.
- Choose any language template already available in the repo.
- Add **unit test cases** to your code (if you are not aware of unit test cases do read how to write good unit test cases).
- Refactor code.
- Remove bugs from code according to requirements below.

Evluation of your assignment will be based on following criteria:
- 40% Test cases
- 30% Code Structuring/Refactoring
- 30% Removing Bugs

# Gilded Rose Refactoring Challenge
We have recently engaged with a client, The Gilded Rose, who has hired us to update their inventory management system. The Gilded Rose is a small inn with a prime location in a prominent city ran by a friendly innkeeper named Allison. They only buy and sell only the finest goods. Unfortunately, our goods are constantly degrading in quality as they approach their sell by date.

Prior to our engagement, The Gilded Rose hired an independent developer named Leeroy to build their inventory management system. Leeroy who has moved on to new company. We will be taking over updating, supporting, and maintaining the inventory management system he built moving forward.

Our first task is to add a new feature to the inventory management system so that The Gilded Rose can start selling a new category of item.

First an introduction to our system:

All items have a sell-in value which denotes the number of days we have to sell the item

All items have a quality value which denotes how valuable the item is

At the end of each day our system lowers both values for every item

Pretty simple, right? Well this is where it gets interesting:

Once the sell by date has passed, quality degrades twice as fast

The quality of an item is never negative

"Aged Brie" actually increases in quality the older it gets

The quality of an item is never more than 50

"Sulfuras", being a legendary item, never has to be sold or decreases in quality

"Backstage passes", like aged brie, increases in quality as its sell-in value approaches; quality increases by 2 when there are 10 days or less and by 3 when there are 5 days or less but quality drops to 0 after the concert

We have recently signed a supplier of conjured items. This requires an update to our system:

"Conjured" items degrade in quality twice as fast as normal items
Feel free to make any changes to the update-quality method and add any new code as long as everything still works correctly. However, do not alter the item function as that belongs to the goblin in the corner who will insta-rage and one-shot you as he doesn't believe in shared code ownership.

Just for clarification, an item can never have its quality increase above 50, however "Sulfuras" is a legendary item and as such its quality is 80 and it never alters.
