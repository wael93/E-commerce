##Full Stack Challenge

Overview
In this challenge you will build an e-commerce system which allows users to search, add items to their shopping cart, create order and checkout successfully.

Given a sample database in MySQL, you will need to implement the backend and frontend (Check out the files at: https://github.com/zandoan/turing-fullstack).

If you are strong in Node and React, please do this challenge in Node and React, since we have maximum customers who want Node+React full stack engineers, and a lot of opportunities to match you quickly for medium to long term projects, if you do exceptional work in this project.

If you are not familiar with one or both of these frameworks, please feel free to use other frameworks/languages (Angular, Vue, PHP, C#, Python, Clojure, etc.). We have fewer customers interested in full stack engineers skilled in these other technologies, but they still exist and we can match you if you do exceptional work in this project.

Any advanced techniques, tools, frameworks used in the code will also give you bonus points. Please add notes in the readme file so we can easily find and evaluate them.

Our customer companies have very high standards for software engineers, so please do your best possible work here, to impress them.


Before Your Start

Please visit the following link when you are ready to work on the project: Virtual Stand Up (https://turing.ly/postmatch/)
You will need to login and set a time for a daily check-in.
You are required to give a short report of your progress at this set time each day. Failing to do so will negatively affect your candidacy.


Core expectations
Pixel perfect (Optional): We require pixel perfect UI for fonts, colors, layouts... Please try to follow the design as much as you can. You may see different data from the APIs but it’s OK. That’s an open-ended question. We want to see your own solution for that.
UI Design:
Clean and responsive design: You can use 3rd party component libraries. Use modern structure/technology you know (SCSS, HTML5, flex) in HTML/CSS.
Functionalities: Work as expected. Precise inputs/outputs. Users can go through flows smoothly. No critical bugs.
System Design: Use the most advanced front-end architecture.
Coding: Clean code. Good coding style. Good comments. Easy to read, debug and add more stuffs.
Testing: You should add test cases for the main functions of the system.
Deployment: Host your solution online and provide the URL
Documentation: Describe the architecture, technologies you use in your documents and readme file.
Source Code: please upload your source code on Github, set it private, invite TuringCom as Collaborator, and send the link to us.




 
Overview
In this challenge you will build the front-end of an e-commerce system which allows users to search, add items to their shopping cart, create orders, and checkout successfully.

Given a database in MySQL, and the backend APIs, you will need to implement the front-end (Check out the API documents at: https://github.com/zandoan/turing-frontend).

If you are strong in React, please do this challenge in React. We have many customers who need React front end engineers, and lots of opportunities to match you quickly for medium to long term projects, if you do exceptional work in this project.

If are not familiar with React, please feel free to use other frameworks/languages (Angular, Vue, PHP, C#, Python, Ruby, etc.). We have fewer customers interested in frontend engineers skilled in these other technologies, but they still exist and we can match you if you do exceptional work in this project.

Any advanced techniques, tools, frameworks used in the code will also give you bonus points. Please add notes in the readme file so we can easily find and evaluate them.

Our customer companies have very high standards for software engineers, so please do your best possible work here to impress them.

Before Your Start
Please visit the following link when you are ready to work on the project: Virtual Stand Up
You will need to login and set a time for a daily check-in.
You are required to give a short report of your progress at this set time each day. Failing to do so will negatively affect your candidacy.
Core expectations
Pixel perfect (Optional): We require pixel perfect UI for fonts, colors, layouts... Please try to follow the design as much as you can. You may see different data from the APIs but it’s OK. That’s an open-ended question. We want to see your own solution for that.
UI Design:
Clean and responsive design: You can use 3rd party component libraries. Use modern structure/technology you know (SCSS, HTML5, flex) in HTML/CSS.
Functionalities: Work as expected. Precise inputs/outputs. Users can go through flows smoothly. No critical bugs.
System Design: Use the most advanced front-end architecture.
Coding: Clean code. Good coding style. Good comments. Easy to read, debug and add more stuffs.
Testing: You should add test cases for the main functions of the system.
Deployment: Host your solution online and provide the URL
Documentation: Describe the architecture, technologies you use in your documents and readme file.
Source Code: please upload your source code on Github, set it private, invite TuringCom as Collaborator, and send the link to us.
Feature Requirements
Users can view all items when entering the website
Items are displayed properly based on the selected department and category
Users can search items through search box
Support paging if we have too many items
Users can see item details by selecting a specific item
Users can add items to their shopping carts
Users can register/login using website custom forms, or social login libraries
Users can update personal profiles with shipping addresses and other info
Users can checkout with 3rd party payment gateways: Stripe. This requirement is mandatory, you must use our API to handle the payment.



Feature Requirements
Users can see all items when entering the website.
Items are displayed properly based on the selected department and category.
Users can search items through search box.
Support paging if we have too many items.
Users can see item details by selecting a specific item.
Users can add items to their shopping carts.
Users can register/login using website custom forms, or social login libraries.
Users can checkout with 3rd party payment gateways: Paypal or Stripe. This requirement is mandatory, you must use the related API for the payment.
Users will get confirmations over emails about their orders.
Frontend requirements
Elegant UI
You are welcome to use any 3rd party component library like Bootstrap, Material Design. Try to polish the UI as much as you can.
Component rendered smoothly
Data loaded from server side and rendered on components smoothly.
Strong frontend framework
We strongly recommend the use of modern architecture, frameworks (React most preferred, Angular, Vue are okay also) to control flow, store client data...
Advanced client-side techstack
We strongly recommend using advanced CSS/HTML/JS techniques (local storage...)
Clean code structure
Code structure/directory makes sense and can be scaled easily
Friendly error messages
Display custom error messages to users
Backend requirements
Use Turing database in Github
This is mandatory. We don’t accept your own database.
Strong backend framework
Can develop backend APIs fast and easily.
Has a good solution (ORM...) to interact with the database.
Returns proper APIs to the frontend.
Performance
APIs should be fast. No timeout or long executions.
You'll be evaluated on your caching technique.
Security
The APIs should be secured well without security holes.
Use URL rewriting to support SEO and search engine friendly URLs.
Clean code structure
Code structure/directory makes sense and can be scaled easily.
End Points
Follow the swagger documentation in this link, All endpoints, inputs, and outputs need to be exactly matched this documentation. This is your guide but please don’t use it for your front end.
Errors
Use this link to check the list of errors, you need to use these codes and messages.
Authentication
The Authentication should use a header param named 'USER-KEY' using Bearer scheme.
Your application needs to return the key preceded by the word 'Bearer' at '/customers' and '/customers/login'.
Payment
You should use our Stripe API key 'sk_test_lomdOfxbm7QDgZWvR82UhV6D' to do the charge.
You should send the 'order_id' on metadata property to Stripe.
Sample designs
Please check out the designs (https://github.com/zandoan/turing-fullstack/tree/master/designs), and some very simple mocks (https://github.com/zandoan/turing-fullstack/tree/master/screenshots). Feel free to redesign them and come up with the new designs that surprise us :)

Sample projects
Design	https://youtu.be/bjCmoRi13LI
Registration	https://youtu.be/Hl5MGUpuIbw
Payment	https://youtu.be/P_Bo02pQEz8
Once you complete, please send us the code and the link to your hosted solution.

Question
If you have any question or concern about our challenge. Please send an email to softwarejobs@turing.com or create an issue on the Github repository we have given. We already created a list of Frequently Asked Questions, feel free to check it out: FAQ