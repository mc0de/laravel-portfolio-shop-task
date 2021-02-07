## Preview

Skills to be tested:
- there's no particular order for tasks, you need to plan, organize, prioritize yourself
- not all info will be given from the client, ask or figure it yourself
- all business logic implemented can be applied to a wide variety of projects and different themes (automotive, job listings, sales, etc.), if you don't like books, we can change the theme and build around what you feel comfortable with
- nothing is strict, design application not only for the present, but for future either, the client might want to add more complex things later (we will go through all of this together)
- read carefully and read everything, there can be some important things you might miss even if you don't plan to work on them soon

## Introduction

Hi, my name's David and I will be your client.

I'm the one who loves books, and not a very technical guy,
so I need your help to have a place where I could list them and maybe sell them in the future.

Since our budget is low, for now, I only need basic functionality.

# Part 1

### Landing page (guest and user can access)
1. List of all books
    - books displayed in 5x5 grid
    - the book has a title with author, cover and genre
    - the book can have multiple authors and genres
    - all book covers must have consistent dimensions
    - when there are more than 25 books on a page, there will be `[next]` and `[previous]` buttons
    - books uploaded last week should have something to display that they are `[NEW]`
    - the book may have a discount (by percentage), and I also would like to see that in the listing `[10%]`
2. Search bar
    - when searching for a book it should look for title and author
    - lists them in the same layout as the landing page
    - a search bar must have a cookie that tracks the previous search you had
3. Menu bar
4. Login and registration button
5. I drew some sketches, but the product doesn't need to look exactly like that [example for guest](https://raw.githubusercontent.com/mc0de/laravel-portfolio-shop-task/master/Landing_page_guest.png) and [example for user](https://raw.githubusercontent.com/mc0de/laravel-portfolio-shop-task/master/Landing_page_user.png)

### Login page

- a login page must have an email and password
- must have a "remember me"
- must have "forgot password"
- must have a register button

### Registration page

- must have a log in button
- must have an email, password with show password in it, confirm password and date of birth

### Book page

- must have description
- users can leave reviews
- users can rate book
- [example of a single book](https://raw.githubusercontent.com/mc0de/laravel-portfolio-shop-task/master/Singe_book.png)

### User Account

- they can change the password
- they can change email
- they can report a book (for example if there are discrepancies on some of the listed books)
- can upload a book to the listing, then the admin must confirm the book to be listed, then it appears on the landing page and searches
- can manage their books
- can give a review on a book (stars + comments)

### Admin account

- they can change the password
- can reply to user's report
- can manage and update all the books

### Technologies to be used

- Laravel
- HTML5
- CSS
- Bootstrap or Tailwind (your preference, I just want a timeless solution)
- MySQL
- PHP

### Notes
> Very important that I could show something to my colleagues on what we are working on as soon as possible (could be a screenshot of the front page or link, can be non-functional). This may lead to better financing and continuing project development in the future. Impress us.

> There are particular books I would like to see listed first at launch, so I'm attaching them in an [archive](https://github.com/mc0de/laravel-portfolio-shop-task/raw/master/books.zip). I was a bit in a hurry so photos might be inconsistent, rotate and crop them if needed to book covers in the listing look nice.

> It is up to you on designing a responsive website.

> If you have problems or need clarification just pm me.

> On the list of requirements provided above, it is up to you what other things to add that will be greatly used.

> On sketches provided, I'm not a very great artist, they are not perfect and I do believe you can do better.
