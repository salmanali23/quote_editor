In this tutorial, we will build a single-page, reactive quote editor with only a single line of custom JavaScript for the flash message animation. You can look at the finished project on the quote editor page of this website. Go ahead! Create a quote, click on it and start adding dates and items to see what we'll build.

With the quote editor, you can create, update and delete quotes. When clicking on a quote, you access the page to create, update and delete dates. On each date, you can add line items. Every time you create, update, or delete a line item, the quote total gets updated.

This project is heavily inspired by a project I had to build with React. When turbo-rails was released in December 2020, the first line of the README was: "Turbo gives you the speed of a single-page web application without having to write any JavaScript".

I wanted to see if that was true, so I read the Turbo Rails source code and rebuilt the quote editor with Turbo. I was blown away by how easy it was to work with. And the best part? No more React, no more Redux, no more Formik! Instead, I could work with the tools I love and know well: Ruby on Rails and Simple Form. Boring? Yes, but I could get the benefits from React with a tenth of the effort.



Who is this book for?
In this book, we will:

Create CRUD controllers
Create our design system
Setup authentication with the Devise gem
Learn about Turbo Drive, Turbo Frames, and Turbo Streams
If you are already familiar with about 1 - 3 and want to learn about 4, this tutorial is for you!