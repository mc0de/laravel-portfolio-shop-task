## Preview

Skills to be tested:
- there's no particular order for tasks, plan, organize, prioritize
- not all info will be given from client, ask or figure it yourself
- all business logic implemented can be applied to wide variety of projects and different themes (automotive, job listings, selling games etc.), if you don't like books, we can change theme and build around what you feel comfortable about
- nothing is strict, design application not only for now, but for future either, client might want to add more complex things later (we will go through all of this together)
- read carefully and read everything, there can be some important things you might miss even if you don't plan to work on them in near future

## Introduction

Hi, my name's David and I will be your client.

Im the one who loves books, and not very technical guy,
so I need your help to have a place where I could list them and maybe sell them in the future.

Since our budget is low, for now I need only basic functionality.

# Part 1

### Landing page (guest and user can access)
1. List of all books
    - books displayed in 5x5 grid
    - book has title with author and cover and genre
    - book can have multiple authors and genres
    - all book covers must be consistent size
    - when there are more than 25 books on a page, there will be `[next]` and `[previous]` buttons
    - books uploaded in last week should have something to display that they are `[NEW]`
    - book may have a discount (by percentage), and i also would like to see that in listing `[10%]`
2. Search bar
    - when searching for a book it should look for title and author
    - lists them in same layout as landing page
    - a search bar must have a cookie that tracks the previous search you had
3. Menu bar
4. Login and registration button

### Login page

- a login page must have an email and password
- must have a remember me
- must have forgot password
- must have register button

### Registration page

- must have a login button
- must have an email, password with show password in it, confirm password and date of birth

### Book page

- must have description
- users can leave reviews
- users can rate book

### User Account

- they can change password
- they can change email
- they can report a book (for example if there's discrepancies on some of the listed books)
- can upload a book to listing, admin must confirm book to be listed, then it appears in landing page and search
- can manage their books
- can give a review on a book (stars + comments)

### Admin account

- they can change password
- can reply to user's report
- can manage and update all the books

# Part 2 (TBD)

- warehouse management
- email notifications
- orders
- probably Stripe API and payment handling

### Technologies to be used
- laravel
- html5
- css
- bootstrap or tailwind (your preference, i just want timeless solution)
- mysql
- php

### Notes
> Very important that i could show something to my colleagues on what we are working as soon as possible (can bee screenshot of front page or link, can be non functional). this may lead to better financing and extending project in the future. impress us.

> there are particular books i would like to see listed first at launch, so im attaching them in an archive. i was a bit in a hurry so photos might be inconsistent, rotate and crop them if needed to covers in listing look nice.

> it is up to you on designing responsive website

> if you have problems or need clarification just pm me

> on the list of requirements provided above, it is up to you what other things to add that will be greatly used

> on scetches provided, im not very great artist, they are not perfect and I do believe you can do better
